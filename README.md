# clashbox-go：OHOS 专用 Go 编译器

本仓派生自 [wefuture/golang_go 的 feature/tlsgd_mode_support 分支](https://gitee.com/wefuture/golang_go/tree/feature/tlsgd_mode_support)，用于 OHOS TLS GD 构建，保留本工程的 bootstrap 修正。普通官方 Go 发行版不能直接替代这里所需的专用编译器。

编译器准备及工程验证步骤见 [clashbox-meta](https://github.com/Ghroth6/clashbox-meta)（私有，需权限）；标准工作空间中的协调仓位于 `../../meta`。自动化协作入口见 [AGENTS.md](AGENTS.md)。本仓存在不代表应用或原生核心已经通过构建。

## 上游原始说明

以下为 Go 上游介绍，其通用下载安装流程不等同于本工程的 OHOS 编译器准备流程。

# The Go Programming Language

Go is an open source programming language that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](https://golang.org/doc/gopher/fiveyears.jpg)
*Gopher image by [Renee French][rf], licensed under [Creative Commons 4.0 Attribution license][cc4-by].*

Our canonical Git repository is located at https://go.googlesource.com/go.
There is a mirror of the repository at https://github.com/golang/go.

Unless otherwise noted, the Go source files are distributed under the
BSD-style license found in the LICENSE file.

### Download and Install

#### Binary Distributions

Official binary distributions are available at https://go.dev/dl/.

After downloading a binary release, visit https://go.dev/doc/install
for installation instructions.

#### Install From Source

If a binary distribution is not available for your combination of
operating system and architecture, visit
https://go.dev/doc/install/source
for source installation instructions.

### Contributing

Go is the work of thousands of contributors. We appreciate your help!

To contribute, please read the contribution guidelines at https://go.dev/doc/contribute.

Note that the Go project uses the issue tracker for bug reports and
proposals only. See https://go.dev/wiki/Questions for a list of
places to ask questions about the Go language.

[rf]: https://reneefrench.blogspot.com/
[cc4-by]: https://creativecommons.org/licenses/by/4.0/
