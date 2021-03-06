[ >>> English Version](README.md)

# QCefWidget

`QCefWidget`项目提供一个Widget来显示网页，并可以与网页进行深度交互.

相对于直接使用CEF库，`QCefWidget`保留了扩展性的同时极大的简化了使用流程，方便集成到您的应用中.

相对于直接使用Qt提供的QWebEngineView，`QCefWidget`更加灵活，可以很方便的切换CEF版本.

支持：

✅ 易于使用，仅需几行代码就可以机集成到项目中;

✅ 同时支持CEF OSR和非OSR模式;

✅ 在不规则窗体中显示背景透明的网页;

✅ Javascript与Qt交互;

✅ OpenGL图形加速;

✅ 第三方输入法;

✅ 在Debug/Release模式下完美退出程序，无任何CEF断言;

✅ 独立的CEF渲染进程和插件进程;

✅ 支持Adobe Flash, 没有任何警告，如"Control-click to run Adobe Flash Player".

✅ 支持像Electron那样，通过设置CSS属性来支持无边框窗体的拖拽.

✅ 自动适应系统DPI的改变.

---
# 快速开始
将QCefWidget作为一个普通的QWidget使用即可:

```c++
QCefWidget pCefWidget = new QCefWidget();
pCefWidget->navigateToUrl("https://www.google.com");
```

更多的属性设置, 请参考 [QCefWidget.h](./SDK/msvc2017_x86_shared/include/QCefWidget.h).

---

# Demo

Demo目录中是QCefWidget的示例程序. 

可以通过`RunDemo.exe`来启动。

---

# 截图
![screenshot1 on windows](Screenshot/screenshot1.png)
![screenshot2 on windows](Screenshot/screenshot2.png)

---

`Email: winsoft666#outlook.com`
