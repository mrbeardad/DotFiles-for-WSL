# The Best IDE Strategy for Myself

<!-- vim-markdown-toc GFM -->

- [The Best IDE Strategy for Myself](#the-best-ide-strategy-for-myself)
  - [Windows](#windows)
  - [WSL](#wsl)
  - [VSCode](#vscode)
  - [Others](#others)
  - [C++](#c)

<!-- vim-markdown-toc -->

## Windows

1. 下载并安装[MyASUS 华硕管家](https://www.microsoft.com/zh-cn/p/myasus/9n7r5s6b0zzh?activetab=pivot:overviewtab)，自动安装驱动
2. 下载并安装[Google Chrome 浏览器](https://www.google.cn/chrome/)
3. 登录 Google Chrome 账户，自动同步 Chrome 配置并手动同步 TampMonkey 配置
4. 下载并安装[Bandizip 压缩包工具](https://www.bandizip.com/)
5. 下载常用软件

   - [QQ 输入法](http://qq.pinyin.cn/)
   - [TIM 聊天通讯](https://tim.qq.com)
   - [WeChat 微信](https://pc.weixin.qq.com/?lang=zh_CN)
   - [百度网盘](https://pan.baidu.com/downloads)
   - [Listen1 音乐](https://www.zhyong.cn/posts/64cd/)
   - [Office 办公套件](https://www.office.com/)
   - [CHFS 局域网 Http 服务器](http://iscute.cn/chfs)
   - [PowerToys 工具集](https://github.com/microsoft/PowerToys/releases)
   - [Listary 搜索工具](https://www.listarypro.com/download)
       <details>
           <summary><b>...</b></summary>

     ```txt
     产  品：Listary授权信息
     姓  名：准女婿
     邮  箱：welcome5201311@163.com
     注册码：
     DR6QRNJBSYB344AJ7NJA3EKZC9B2PMWV
     KF2HP9CAQSJMBZCJXM8KSH4H3XYPAKNS
     WRR6ZBJ3HQPPZGF8FL88VQSNZ27EAW8S
     AAV6TVFGLQZTHGJCAEMAKG74573ZTDDG
     8NMLXAMZVJ6546QZLE7VTYZRNFKMHUBB
     JNWC2T2FR3EKVUDA2JEL85RDHLVFBC4Q
     复制代码


     复制代码
     姓  名：准女婿
     邮  箱：welcome5201311@163.com
     注册码：
     AQUTK8NRYKGREDZMS68GPG9NPDYSYJJK
     FGQ2ZL8B6Z3STGXEST27EAS67F77HR6M
     CW7Y6YA85T75AQUX7W3CYBNJLCJE7GY9
     WA3HSDTA8YLT2FPF8YMXWWWFLT4NQK4F
     C3LUGRGZR5R29CYAUPZ4XUEXDLGFZNGV
     JNWC2T2FR3EKULSBLMG9NLPJWRW29WYH
     复制代码


     复制代码
     姓  名：准女婿
     邮  箱：welcome5201311@znx_52pojie.com
     注册码：
     JRWX9QN8GJYF9J3S27KYKY2F7UGCW9QD
     VUHQL8ZBERXM9KMY8UM8P23QKYDXHTCW
     VHD2WNSSP8CV755UFGALVG34XYEENR76
     YSKTDDH29DEVTYD9V5TV8HLMRVGEUVC5
     XKE62QZA7YH97CBBA5V7V53MC6XC89N6
     4YA4DWA2TZ4VU8VT8S3R89W6HBKG3J42
     ```

       </details>

6. <details>
    <summary><b>系统设置</b></summary>

   - Acount
     - Your info: 登录账户
     - Your info: 登录账户
     - Sync your srttings: 同步配置
   - System
     - Display: 夜间暖色
     - Clipboard: 启用剪切板
     - About: 更改主机名
   - Devices
     - Bluetooth & other devices: 关闭蓝牙
     - Touchpad: 设置触摸板手势
     - Typing
       - Advanced Keyboard Settings
         - Input Language hot keys: 设置系统输入法热键
   - Personalization
     - Theme
       - Background: 设置桌面壁纸
       - Colors: 设置主题颜色
       - Mouse Cursor: 设置[鼠标主题](https://zhutix.com/tag/cursors/)
     - Fonts: 设置字体
       1. 安装[noMeiryoUI 字体设置](https://github.com/Tatsu-syo/noMeiryoUI/releases)
       2. 安装[MacType 字体渲染](https://github.com/snowie2000/mactype/releases)
       3. 安装[NerdCodePro 字体](fonts/)
     - Start: 设置开始界面
       1. 开启所有选项
       2. 排版磁条
     - Taskbar: 设置任务栏界面
       1. 安装[TranslucentTB 透明任务栏](https://www.microsoft.com/zh-cn/p/translucenttb/9pf4kz2vn4w9?activetab=pivot:overviewtab)
       2. 安装[XMeters 资源监测器](https://entropy6.com/xmeters/)
       3. 居中任务栏图标
       4. 隐藏桌面图标
   - Apps
     - Apps & features: 卸载多余软件
     - Startup: 管理开机自启软件
   - Time & Language: 自动同步时间与时区，并显示农历
   - Region: 设置所在地区与日期时间显示格式
   - Language: 设置系统显示语言为英语，并下载中文包
     - Administrative language settings
       - Change system locale: 选择中文语系并取消勾选 Beta 设置
   - Ease of Access
     - Mouse pointer: 更改鼠标大小

  </details>

[**Windows 使用手册**](windows.md)

## WSL

1. 安装[Windows Terminal](https://www.microsoft.com/zh-cn/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab)
2. 安装 wt 配置[settings.json](WindowsTerminal/settings.json)
3. 将[WindowsTerminalQuakeModeStartup.bat](WindowsTerminal/WindowsTerminalQuakeModeStartup.bat)复制到`%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`
4. 安装[Ubuntu WSL](https://www.microsoft.com/zh-cn/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab)
5. 启用 WSL2：控制面板》程序》开关 Windows 特性》开启"Virtual Machine Platform"与"Windows Subsystem for Linux"
6. 限制 WSL2 内存使用，`%USERPROFILE%\.wslconfig`

   ```ini
   [wsl2]
   memory=4GB
   swap=0
   ```

7. 设置 WSL2 为默认并初始化 Ubuntu20.04

   ```sh
   # in powershell
   wsl --list --all -v
   wsl --set-version Ubuntu20.04 2
   wsl --set-default Ubuntu20.04
   wsl # 进入wsl
   ```

8. 配置 Ubuntu20.04 WSL

   ```sh
   # in wsl
   mkdir ~/.local
   git clone https://github.com/mrbeardad/My-IDE .local/My-IDE
   cd .local/My-IDE && ./init.ubuntu20.04.wsl.sh
   ```

> WSL2 访问 Windows 宿主机的代理软件，需要：
>
> 1. 添加防火墙规则，允许宿主机某端口可被访问
> 2. 设置代理软件可接受局域网代理请求
> 3. Windows IP 由/etc/resolv.conf 可知

[**wsl 使用手册**](wsl.md)

## VSCode

1. 下载并安装[VSCode](https://code.visualstudio.com/download)，登录账户并同步配置。

2. 下载并安装[git](https://git-scm.com/downloads)

3. 下载并安装[neovim](https://github.com/neovim/neovim/releases/)，然后安装配置[vscode-neovim](vscode/vscode-neovim/)到`%USERPROFILE%\AppData\Local\vscode-neovim`，最后记得配置 vscode 中`nvim.exe`安装路径，且配置 init.vim 路径为`%USERPROFILE%\AppData\Local\vscode-neovim\init.vim`

[**vscode 使用手册**](vscode.md)

## Others

- 下载并安装[SwitchHosts](https://github.com/oldj/SwitchHosts/releases)

- 下载并安装[Postman](https://www.postman.com/downloads/)

- 下载并安装[Navicat](## "太TM贵了")

- 下载并安装[ARDM](https://github.com/qishibo/AnotherRedisDesktopManager/releases)

## C++

1. 编写 CMakeLists.txt 文件 (Test&Prof&Doc)

```cmake
cmake_minimum_required(VERSION 3.12)
project(ProjectName VERSION 0.1 DESCRIPTION "Project description")

if(CMAKE_BUILD_TYPE STREQUAL "Debug")
  if(CMAKE_CXX_COMPILER_ID MATCHES "Clang")
    add_compile_options(-fstandalone-debug)
  elseif(CMAKE_CXX_COMPILER_ID MATCHES "GNU")
    add_compile_options(-g3)
  endif()
endif()
include_directories(${CMAKE_CURRENT_SOURCE_DIR} ${CMAKE_CURRENT_BINARY_DIR})

find_package(Doxygen)
if(DOXYGEN_FOUND)
  set(DOXYGEN_EXCLUDE_PATTERNS */build/* */third_party/* */test/*)
  set(DOXYGEN_USE_MDFILE_AS_MAINPAGE README.md)
  set(DOXYGEN_HTML_OUTPUT ${CMAKE_BINARY_DIR}/doc)
  set(DOXYGEN_REFERENCED_BY_RELATION YES)
  set(DOXYGEN_REFERENCES_RELATION YES)
  set(DOXYGEN_CALL_GRAPH YES)
  set(DOXYGEN_CALLER_GRAPH YES)
  set(DOXYGEN_DOT_IMAGE_FORMAT png:cairo:cairo)
  set(DOXYGEN_UML_LOOK YES)
  set(DOXYGEN_EXTRACT_ALL YES)
  set(DOXYGEN_EXTRACT_STATIC YES)
  set(DOXYGEN_EXTRACT_PRIVATE YES)
  set(DOXYGEN_SOURCE_BROWSER YES)
  set(DOXYGEN_STRIP_CODE_COMMENTS NO)
  set(DOXYGEN_SORT_MEMBER_DOCS NO)
  doxygen_add_docs(doc ${PROJECT_SOURCE_DIR} ALL)
endif()
```

2. cmake 配置构建目录并导出 compile_commands.json

```sh
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=TRUE -DCMAKE_BUILD_TYPE:STRING=Debug -DCMAKE_C_COMPILER:FILEPATH=/usr/bin/clang -DCMAKE_CXX_COMPILER:FILEPATH=/usr/bin/clang++ -S/path/to/source_dir -B/path/to/build_dir
```

3. 编写.clangd (Lsp)

```yaml
# command-line-args: --enable-config --clang-tidy --function-arg-placeholders=0
CompileFlags:
  Add: [-Wall, -Wextra]
  CompilationDatabase: build
Diagnostics:
  UnusedIncludes: Strict
Completion:
  AllScopes: yes
InlayHints:
  Enabled: Yes
  DeducedTypes: Yes
  ParameterNames: No
Hover:
  ShowAKA: yes
```

4. 编写.clang-tidy (Lint)

```yaml
Checks: "-*,bugprone-*,cert-dcl21-cpp,cert-dcl50-cpp,cert-env33-c,cert-err34-c,cert-err52-cpp,cert-err60-cpp,cert-flp30-c,cert-msc50-cpp,cert-msc51-cpp,cppcoreguidelines-*,-cppcoreguidelines-macro-usage,-cppcoreguidelines-pro-type-reinterpret-cast,-cppcoreguidelines-pro-type-union-access,-cppcoreguidelines-pro-bounds-pointer-arithmetic,-cppcoreguidelines-pro-type-vararg,google-build-using-namespace,google-explicit-constructor,google-global-names-in-headers,google-readability-casting,google-runtime-int,google-runtime-operator,hicpp-*,-hicpp-vararg,misc-*,modernize-*,performance-*,readability-*,-readability-named-parameter,-readability-implicit-bool-conversion"
CheckOptions:
  - key: bugprone-argument-comment.StrictMode
    value: 1
  - key: bugprone-exception-escape.FunctionsThatShouldNotThrow
    value: WinMain,SDL_main
  - key: misc-non-private-member-variables-in-classes.IgnoreClassesWithAllMemberVariablesBeingPublic
    value: 1
FormatStyle: "file"
```

```cpp
// NOLINTNEXTLINE: Suppress warning in nextline
```

5. 编写.clang-format (Format)

```yaml
BasedOnStyle: Chromium
IndentWidth: 4
ColumnLimit: 100
BreakBeforeBinaryOperators: All
BreakBeforeTernaryOperators: true
AlignConsecutiveMacros: AcrossEmptyLines
SeparateDefinitionBlocks: Always
```

```cpp
// clang-format off
// do not format next line
```

6. 编写.vscode/.launch.json (Debug)

```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "lldb",
      "request": "launch",
      "name": "Debug Test",
      "program": "${workspaceFolder}/build/test_bin",
      "args": [],
      "env": {},
      "cwd": "${workspaceFolder}"
    }
  ]
}
```
