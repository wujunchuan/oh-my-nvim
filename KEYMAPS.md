# Neovim 快捷键说明 (Keymaps)

当前配置的 Leader 键为：`空格` (Space)

## 1. 窗口管理 (Window Management)
| 快捷键 | 功能描述 |
| :--- | :--- |
| `Ctrl + h` | 跳转到左侧窗口 |
| `Ctrl + j` | 跳转到下方窗口 |
| `Ctrl + k` | 跳转到上方窗口 |
| `Ctrl + l` | 跳转到右侧窗口 |
| `Ctrl + Alt + h` | 向左调整窗口大小 |
| `Ctrl + Alt + j` | 向下调整窗口大小 |
| `Ctrl + Alt + k` | 向上调整窗口大小 |
| `Ctrl + Alt + l` | 向右调整窗口大小 |

## 2. 文件与导航 (Navigation & Files)
| 快捷键 | 功能描述 | 插件 |
| :--- | :--- | :--- |
| `F9` | 打开/关闭文件浏览器 | Neo-tree |
| `F7` | 打开/关闭代码大纲 | Aerial |
| `空格 + ff` | 查找文件 | Telescope |
| `空格 + bb` | 查找已打开的 Buffer | Telescope |
| `空格 + tt` | 选择 Buffer 标签 | Bufferline |
| `空格 + ss` | 切换会话 | Session Manager |

## 3. 文本搜索 (Search)
| 快捷键 | 功能描述 | 插件 |
| :--- | :--- | :--- |
| `空格 + gg` | 全局搜索字符串 | Telescope (Live Grep) |
| `空格 + cc` | 搜索当前光标下的词 | Telescope |

## 4. LSP 代码功能 (LSP Actions)
| 快捷键 | 功能描述 |
| :--- | :--- |
| `gd` | 跳转到定义 (Definition) |
| `gr` | 跳转到引用 (References) |
| `gD` | 跳转到声明 (Declaration) |
| `gi` | 跳转到实现 (Implementation) |
| `空格 + re` | 重命名符号 (Rename) |
| `空格 + vv` | 格式化代码 (Format) |

## 5. Git 相关 (Git)
| 快捷键 | 功能描述 | 插件 |
| :--- | :--- | :--- |
| `F8` | 浮窗查看 Git 状态 | Neo-tree |
| `空格 + df` | 打开 Git Diff 视图 | Diffview |
| `空格 + dc` | 关闭 Git Diff 视图 | Diffview |

## 6. 终端 (Terminal)
| 快捷键 | 功能描述 | 插件 |
| :--- | :--- | :--- |
| `Alt + u` | 在浮窗中打开终端 | Toggleterm |
| `Alt + b` | 在底部打开终端 | Toggleterm |
