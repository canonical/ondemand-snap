# Contributing to `ondemand-snap`

Do you want to contribute to the `ondemand-snap` repository? You've come to the right place then!
__Here is how you can get involved.__

Before you start working on your contribution, please familiarize yourself with the [Charmed
HPC project's contributing guide]. After you've gone through the main contributing guide,
you can use this guide for specific information on contributing to the `ondemand-snap` repository.

Have any questions? Feel free to ask them in the [Ubuntu High-Performance Computing Matrix chat]
or in the [High-Performance Computing category on the Ubuntu Discourse].

[Charmed HPC project's contributing guide]: https://github.com/canonical/hpc-team/blob/main/CONTRIBUTING.md
[Ubuntu High-Performance Computing Matrix chat]: https://matrix.to/#/#hpc:ubuntu.com
[High-Performance Computing category on the Ubuntu Discourse]: https://discourse.ubuntu.com/c/project/hpc/151

## Hacking on `ondemand-snap`

### Before opening a pull request on the `ondemand-snap` repository

Ensure that your changes pass all the existing tests, and that you have added tests
for any new features you're introducing in this changeset.

## License information

By contributing to `ondemand-snap`, you agree to license your contribution under
the Apache License 2.0 license.

### Adding a new file to `ondemand-snap`

If you add a new source code file to the repository, add the following license header
as a comment to the top of the file with the copyright owner set to the organization
you are contributing on behalf of and the current year set as the copyright year.

```text
Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### Updating an existing file in `ondemand-snap`

If you are making changes to an existing file, and the copyright year is not the current year,
update the year range to include the current year. For example, if a file's copyright year is:

```text
Copyright 2023 Canonical Ltd.
```

and you make changes to that file in 2025, update the copyright year in the file to:

```text
Copyright 2023-2025 Canonical Ltd.
```
