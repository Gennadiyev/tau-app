# Tau App
A fanmade Android application that can make your stay in Tau Station much easier on mobile devices.

## Disclaimer

This App has nothing to do with Makes Dreams Happen, and has not *yet* gained any support from Makes Dreams Happen.

`https://taustation.space/`, Tau Station and all related resources have their copyrights in Makes Dreams Happe.

This App does not modifies the general page layout.

## Why Tau-App

- Designed for Tau Station gameplay.

- Simplifies PC's UI and put it on mobile screens.

- (Alpha) Support for Userscripts.

- Rich links to external resources.

- TauManager support for **[TAU]** members.

## About Codes

**This project is mainly written in Lua plus a bit Java. The main Lua codes are at `/source/config.table`, and Java is used to write libraries in `/source/lib`.**

The codes are written mainly under a highly-packaged **Lua** template (which is a private project). The template controls most layouts, transitions, and handles basic webview commands. The template also serves as the way to build the `.apk`.

Despite the template's private attribute, the `config.table` contains all the codes that propelled the Tau Station App. The template makes the file unified, so that every bit of code can be edited within one file.

There are some packaged functions using Chinese, because the developer is a Chinese. Some references are listed here:

- 网页链接

A string that stores the last loaded URL.

- 退出程序()

Exits the program.

- 对话框()

Allows an `AlertDialog` and its attributes be edited and displayed. Attributes include `setTitle()`, `setPositiveButton`, etc.

- 弹出消息()

The purplish `print()`.

- 进入子页面()

Goes to a sub-page of the App.

- 加载网页()

Loads a URL onto current screen.
