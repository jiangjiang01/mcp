# MCP 服务器学习笔记

本项目用于记录 Model Context Protocol (MCP) 服务器的学习和使用笔记。

## 目录结构

```
.
├── README.md                 # 项目说明文档
├── docs/                     # 文档目录
│   ├── templates/           # 笔记模板
│   └── examples/            # 示例笔记
├── notes/                    # 学习笔记目录
│   ├── servers/             # 各个服务器的笔记
│   │   ├── filesystem/      # 文件系统服务器笔记
│   │   ├── git/            # Git 服务器笔记
│   │   └── ...             # 其他服务器笔记
│   └── concepts/            # MCP 概念和基础知识
├── examples/                 # 示例代码和测试
│   └── servers/             # 各个服务器的示例代码
└── results/                  # 运行结果和输出
    └── servers/             # 各个服务器的运行结果
```

## 使用说明

1. 每个服务器的笔记都放在 `notes/servers/` 目录下对应的子目录中
2. 笔记可以使用 Markdown 格式编写，也可以保存为 HTML 格式
3. 示例代码放在 `examples/servers/` 目录下
4. 运行结果和输出保存在 `results/servers/` 目录下

## 学习资源

- [MCP 官方文档](https://modelcontextprotocol.io)
- [MCP GitHub 仓库](https://github.com/modelcontextprotocol/servers) 