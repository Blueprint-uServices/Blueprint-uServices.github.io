---
title: goproc
target: https://github.com/Blueprint-uServices/blueprint/tree/main/plugins/goproc
date: 2024-01-10
description: Package goproc provides \`goproc.Process\`, a node that represents a runnable Golang process. It can contain any number of other golang.Node IRNodes. When it's compiled, the goproc.Process will generate a go module with a runnable main method that instantiates and initializes the contained go nodes. To achieve this, the golang.Process also collects module dependencies from its contained nodes.The \`GenerateArtifacts\` method generates the main method based on the process's contained nodes.
---
