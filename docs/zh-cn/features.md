---
hide:
  - toc
---

## 可用功能

* 支持 Linux、macOS、Windows 10 和 FreeBSD
* [在本地和远程主机上多路复用终端窗格、标签页和窗口，支持原生鼠标操作和滚动回看](multiplexing.md)
* <a href="https://github.com/tonsky/FiraCode#fira-code-monospaced-font-with-programming-ligatures">连字</a>、彩色表情符号和字体回退，支持真彩色和[动态配色方案](config/appearance.md).
* [超链接支持](hyperlinks.md)
* [可搜索的滚动回看](scrollback.md) (使用鼠标滚轮和 `Shift-PageUp` and `Shift-PageDown` 导航, Ctrl-Shift-F 激活搜索模式)
* xterm 风格的鼠标文本选择；通过 `Shift-Insert` 粘贴选中内容（支持括号粘贴模式）
* SGR 风格的鼠标报告（兼容 vim 和 tmux）TODO：检查mouse reporting的翻译
* 支持下划线、双下划线、斜体、粗体、删除线渲染（大多数其他终端模拟器不支持如此丰富的渲染属性）
* 通过[配置文件](config/files.md)进行配置，支持热重载
* 多窗口支持（快捷键: `Super-N`）
* 分屏/窗格（水平/垂直分割：`Ctrl-Shift-Alt-%` 和 `Ctrl-Shift-Alt-"`，移动焦点：`Ctrl-Shift-方向键`）
* 标签页（快捷键：`Super-T`，切换标签：`Super-Shift-[` 和 `Super-Shift-]`，跳转标签：`Super-[1-9]`）
  <video width="80%" controls src="screenshots/wezterm-tabs.mp4" loop></video>
* [支持原生标签页的 SSH 客户端](ssh.md)
* [支持连接串口进行嵌入式/Arduino 开发](serial.md)
* 通过 Unix 域套接字连接本地多路复用服务器
* 通过 SSH 或 TCP/IP 上的 TLS 连接远程多路复用器
* 兼容 iTerm2 的图像协议支持，并且内置 [imgcat 命令](imgcat.md)
* 支持 Kitty 图形协议
* Sixel 图形支持（实验性功能：从 `20200620-160318-e00b076c` 版本开始）
