<!--
SPDX-FileCopyrightText: Night Theme Switcher Contributors
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Releasing

Release checklist:

- Bump version number in [`meson.build`](./meson.build)
- Add entry in [`CHANGELOG.md`](./CHANGELOG.md)

To make a release, create a new tag. The CI will automatically add release notes from the changelog.
