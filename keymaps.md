好的，这是根据你提供的 `wezterm.lua` 配置文件，准确且真实地转化成的 Markdown 格式键位说明书。

---

# WezTerm 键位说明书

| 功能                                   | macOS 快捷键                    | Windows/Linux 快捷键             |
| :------------------------------------- | :------------------------------ | :------------------------------- |
| **通用**                               |                                 |                                  |
| 激活复制模式                           | `F1`                            | `F1`                             |
| 激活命令面板                           | `F2`                            | `F2`                             |
| 显示启动器                             | `F3`                            | `F3`                             |
| 显示启动器 (模糊搜索标签页)            | `F4`                            | `F4`                             |
| 显示启动器 (模糊搜索工作区)            | `F5`                            | `F5`                             |
| 切换全屏                               | `F11`                           | `F11`                            |
| 显示调试悬浮窗                         | `F12`                           | `F12`                            |
| 搜索                                   | `Cmd + f`                       | `Alt + f`                        |
| 快速选择并打开 URL                     | `Cmd + Ctrl + u`                | `Alt + Ctrl + u`                 |
| **光标移动**                           |                                 |                                  |
| 发送 `Ctrl+w` (通常用于向后删除一个词) | `Cmd + w`                       | `Alt + w`                        |
| 向左移动一个词                         | `Cmd + ←`                       | `Alt + b` (*注意：此处非方向键*) |
| 向右移动一个词                         | `Cmd + →`                       | `Alt + f` (*注意：此处非方向键*) |
| 删除至行首 (发送 `Ctrl+U`)             | `Cmd + Backspace`               | `Alt + Backspace`                |
| 移动至行首 (发送 `Home` 键序列)        | `Option + ←`                    | `Alt + ←`                        |
| 移动至行尾 (发送 `End` 键序列)         | `Option + →`                    | `Alt + →`                        |
| **复制/粘贴**                          |                                 |                                  |
| 复制到剪贴板                           | `Ctrl + Shift + c` 或 `Cmd + c` | `Ctrl + Shift + c` 或 `Alt + c`  |
| 从剪贴板粘贴                           | `Ctrl + Shift + v` 或 `Cmd + v` | `Ctrl + Shift + v` 或 `Alt + v`  |
| **标签页**                             |                                 |                                  |
| 新建标签页 (默认)                      | `Cmd + t`                       | `Alt + t`                        |
| 新建标签页 (WSL: ubuntu-fish)          | `Cmd + Ctrl + t`                | `Alt + Ctrl + t`                 |
| 关闭当前标签页                         | `Cmd + Ctrl + w`                | `Alt + Ctrl + w`                 |
| 切换到上一个标签页                     | `Cmd + [`                       | `Alt + [`                        |
| 切换到下一个标签页                     | `Cmd + ]`                       | `Alt + ]`                        |
| 移动标签页到上一个位置                 | `Cmd + Ctrl + [`                | `Alt + Ctrl + [`                 |
| 移动标签页到下一个位置                 | `Cmd + Ctrl + ]`                | `Alt + Ctrl + ]`                 |
| 手动更新标签页标题                     | `Cmd + 0`                       | `Alt + 0`                        |
| 重置标签页标题                         | `Cmd + Ctrl + 0`                | `Alt + Ctrl + 0`                 |
| 切换显示/隐藏标签栏                    | `Cmd + 9`                       | `Alt + 9`                        |
| **窗口**                               |                                 |                                  |
| 新建窗口                               | `Cmd + n`                       | `Alt + n`                        |
| 缩小窗口                               | `Cmd + -`                       | `Alt + -`                        |
| 放大窗口                               | `Cmd + =`                       | `Alt + =`                        |
| 最大化窗口                             | `Cmd + Ctrl + Enter`            | `Alt + Ctrl + Enter`             |
| **背景**                               |                                 |                                  |
| 随机切换背景                           | `Cmd + /`                       | `Alt + /`                        |
| 循环到上一个背景                       | `Cmd + ,`                       | `Alt + ,`                        |
| 循环到下一个背景                       | `Cmd + .`                       | `Alt + .`                        |
| 列表选择背景                           | `Cmd + Ctrl + /`                | `Alt + Ctrl + /`                 |
| 切换背景模糊/聚焦                      | `Cmd + b`                       | `Alt + b`                        |
| **窗格**                               |                                 |                                  |
| 垂直拆分窗格 (左右)                    | `Cmd + \`                       | `Alt + \`                        |
| 水平拆分窗格 (上下)                    | `Cmd + Ctrl + \`                | `Alt + Ctrl + \`                 |
| 最大化/还原窗格                        | `Cmd + Enter`                   | `Alt + Enter`                    |
| 激活上边窗格                           | `Cmd + Ctrl + k`                | `Alt + Ctrl + k`                 |
| 激活下边窗格                           | `Cmd + Ctrl + j`                | `Alt + Ctrl + j`                 |
| 激活左边窗格                           | `Cmd + Ctrl + h`                | `Alt + Ctrl + h`                 |
| 激活右边窗格                           | `Cmd + Ctrl + l`                | `Alt + Ctrl + l`                 |
| 切换窗格 (数字选择)                    | `Cmd + Ctrl + p`                | `Alt + Ctrl + p`                 |
| **滚动**                               |                                 |                                  |
| 向上滚动 5 行                          | `Cmd + u`                       | `Alt + u`                        |
| 向下滚动 5 行                          | `Cmd + d`                       | `Alt + d`                        |
| 向上翻页                               | `PageUp`                        | `PageUp`                         |
| 向下翻页                               | `PageDown`                      | `PageDown`                       |
| **Key Table (前缀键)**                 |                                 |                                  |
| 激活字体缩放模式                       | `Cmd + Ctrl + ;` 然后 `f`       | `Alt + Ctrl + ;` 然后 `f`        |
| 字体放大 (模式中)                      | `k`                             | `k`                              |
| 字体缩小 (模式中)                      | `j`                             | `j`                              |
| 重置字体 (模式中)                      | `r`                             | `r`                              |
| 激活窗格调整模式                       | `Cmd + Ctrl + ;` 然后 `p`       | `Alt + Ctrl + ;` 然后 `p`        |
| 向上调整窗格 (模式中)                  | `k`                             | `k`                              |
| 向下调整窗格 (模式中)                  | `j`                             | `j`                              |
| 向左调整窗格 (模式中)                  | `h`                             | `h`                              |
| 向右调整窗格 (模式中)                  | `l`                             | `l`                              |
| 退出 Key Table 模式                    | `Escape` 或 `q`                 | `Escape` 或 `q`                  |
| **鼠标绑定**                           |                                 |                                  |
| 打开鼠标光标下的链接                   | `Ctrl + 左键单击`               | `Ctrl + 左键单击`                |

---

_**请注意：**_

* `Cmd` 指的是 macOS 上的 Command 键 (`⌘`)。
* `Option` 指的是 macOS 上的 Option 键 (`⌥`)。
* `Alt` 指的是 Windows/Linux 上的 Alt 键。
* `Ctrl` 指的是 macOS 上的 Control 键 (`⌃`) 和 Windows/Linux 上的 Ctrl 键。
* 此列表是根据你提供的配置文件精确生成的。由于你的配置禁用了默认键位 (`disable_default_key_bindings = true`)，所以只有这里列出的键位是有效的。
* 在 Windows/Linux 上，`Alt + ←` 和 `Alt + →` 的行为被配置文件中的最后一条规则覆盖，最终效果是发送 `Home` 和 `End` 键的转义序列，而不是移动一个词。