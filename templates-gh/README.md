<!--
 Copyright (C) 2024 Innovate for Vegas Foundation
 
 This file is part of doc-agile-for-volunteers.
 
 doc-agile-for-volunteers is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 doc-agile-for-volunteers is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
 along with doc-agile-for-volunteers.  If not, see <https://www.gnu.org/licenses/>.
-->

# GitHub Issue and Pull Request Templates

In order to make issues and pull requests structured (with similar information as needed per issue and pull request type) and consistent for newcomers to projects and for those more experienced.

Each subdirectory is intended to be moved to the .github directory within a given initiative component project repository. Subdirectories are named according to the component type.

## Changes to these templates

Obviously templates can change as needed per component project repository. It may be that a generally-applicable change becomes apparent, in which case please consider making these changes available to this repository content, if they can be made suitable general for use across other component project into the future.

## Collaborative Development

These templates for GitHub were iterated upon in their initial form as part of the [Project-ACT Tessellation Initiative](https://github.com/Project-ACT/ov-tessellation).

## GitHub Labels

GitHub Labels are used throughout the issue and discussion form template structure with defaults according to component project repository type, issue type, and so on. A consistent label name, description, and color scheme through all Initiative Component Projects is advisable.

The GitHub command line tool, gh, is one convenient way to configure labels for each component project repository.

Please visit [gh homepage](https://gli.github.com/) to obtain and install the GitHub command line tool, and visit the manual page for [gh for labels](https://cli.github.com/manual/gh_label) for details.

You may find the yq tool. found via [yq repository](https://github.com/mikefarah/yq), to be generally useful for some automated handling of YAML files. It is based heavily on the jq tool, which is useful for automated handling of JSON files.

An example using the command line tool to configure all labels used in the templates in this structure follows. Note that label mutations are not, as of this writing, enabled for token authenticated access, you may need to authenticate your use of gh using a browser-based login, see [gh auth](https://cli.github.com/manual/auth) for more information:

```sh
yq '.use.[] | "gh create -f \"\(.name)\" --description \"\(.description)\" --color \(.color)"' labels.yml
```

The output of this yq command may be saved to a file and executed by your shell or executed as part of some other process.

The labels below are a part of a default label set on creating a GitHub repository and will not be used for Agile for Volunteers repositories. You may remove them, or use them for your own purposes. The gh cli took may be used to remove them, or they can be removed manually using the GitHub web user interface, or left as is.

Example using the gh cli tool

```sh
gh label delete documentation --yes
gh label delete enhancement --yes
gh label delete question --yes
```

Or by generating the appropriate lines using yq

```sh
yq '.remove[] | "gh label delete \(.name) --yes" ' labels.yml
```

Color selections are arbitrary for groups but similar within groups (Plan items, Task items, etc), however it may be useful,
convenient, more intuitive to use a consistent color scheme across all Initiatives within an organization or cohort.
