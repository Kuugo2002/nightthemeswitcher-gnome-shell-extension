<!--
SPDX-FileCopyrightText: Night Theme Switcher Contributors
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# 发布流程

发布检查清单：

- 在 [`meson.build`](./meson.build) 中更新版本号
- 在 [`CHANGELOG.md`](./CHANGELOG.md) 中添加条目

要创建发布，请创建一个新标签。CI 将自动从变更日志中添加发布说明。
