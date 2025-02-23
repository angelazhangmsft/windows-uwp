---
title: Windows UI Library (WinUI)
description: WinUI Libraries for Windows app development. 
ms.topic: article
ms.date: 06/24/2021
keywords: windows 10, uwp, toolkit sdk, winui, Windows UI Library
---

# Windows UI Library (WinUI)

![WinUI logo](../images/logo-winui.png)

The Windows UI Library (WinUI) is a native user experience (UX) framework for both Windows desktop and UWP applications.

By incorporating the [Fluent Design System](https://www.microsoft.com/design/fluent/#/) into all experiences, controls, and styles, WinUI provides consistent, intuitive, and accessible experiences using the latest user interface (UI) patterns.

With support for both desktop and UWP apps, you can build with WinUI from the ground up, or gradually migrate your existing MFC, WinForms, or WPF apps using familiar languages such as C++, C#, Visual Basic, and Javascript (via [React Native for Windows](https://microsoft.github.io/react-native-windows/)).

> [!Important]
> There are two versions of WinUI: **WinUI 2.x** and **WinUI 3**.

## Windows UI 2.x Library

WinUI 2.x can be used in UWP applications and incorporated into new or existing desktop applications using [XAML Islands](../desktop/modernize/xaml-islands.md).

> [!NOTE]
> WinUI 2.6 is the latest WinUI 2.x release. See the [WinUI 2.7 milestone](https://github.com/microsoft/microsoft-ui-xaml/milestone/12) for a list of work planned in the next release.

The WinUI 2.x Library is closely coupled with the [Windows 10 SDK](https://developer.microsoft.com/windows/downloads/windows-10-sdk/) and provides official native Windows UI controls and other UI elements for UWP apps.

By maintaining down-level compatibility with earlier versions of Windows 10, WinUI 2.x controls work even if users don't have the latest OS.

![WinUI 2.x platform support](../images/platforms-winui2.png)

**For installation instructions see [Getting started with the Windows UI Library](winui2/getting-started.md).**

### Related links for WinUI 2.x

- [WinUI 2.x Library overview](winui2/index.md)
- [API docs](/windows/winui/api/)
- [Source code](https://aka.ms/winui)
- [XAML Controls Gallery app](https://www.microsoft.com/p/xaml-controls-gallery/9msvh128x2zt)

## Windows UI 3 Library 

WinUI 3 is the next version of WinUI, a native Windows 10 UI platform completely decoupled from the [Windows 10 SDK](https://developer.microsoft.com/windows/downloads/windows-10-sdk/).

> [!Important]
> WinUI 3 - Windows App SDK 0.8 is the latest stable, supported version of WinUI 3. With this version of WinUI 3, you can create production apps and publish them to the Microsoft Store.
>
> Please use the [WinUI GitHub repo](https://github.com/microsoft/microsoft-ui-xaml) to provide feedback and log suggestions and issues.

By completely decoupling XAML, composition, and input APIs from the [Windows 10 SDK](https://developer.microsoft.com/windows/downloads/windows-10-sdk/), the scope of WinUI 3 includes the full Windows 10 native UI platform.

WinUI 3 is a component of [the Windows App SDK](../windows-app-sdk/index.md), which provides a unified set of APIs and tools that can be used in a consistent way by any desktop app on a broad set of target Windows 10 OS versions. As a component of the Windows App SDK, WinUI 3 ships as a part of the Windows App SDK package - see [Windows UI Library 3 - Project Reunion 0.5](winui3/index.md) for more information.

WinUI 3 is the path forward for all Windows apps—you can use it as the UI layer on your native UWP or Win32 app, or you can gradually modernize your desktop app, piece by piece, with [XAML Islands](../desktop/modernize/xaml-islands.md).

All new XAML features will eventually ship as part of WinUI. The existing UWP XAML APIs that ship as part of the OS will no longer receive new feature updates. However, they will continue to receive security updates and critical fixes according to the Windows 10 support lifecycle.

Please note that the Universal Windows Platform contains more than just the XAML framework. Features such as application and security models, media pipeline, Xbox and Windows 10 shell integration, and compatibility with a broad variety of devices will continue to be developed and supported.

> [!NOTE]
> The Windows App SDK was previously called **Project Reunion**, which was a temporary code name. Some assets such as the VSIX extension and NuGet packages still use the code name, but these files will be renamed in a future release. Most of the documentation now uses the name **Windows App SDK** except when referring to a specific release or asset that still uses the previous code name.

![WinUI 3 platform support](../images/platforms-winui3.png)

### Related links for WinUI 3

- [Stable release channel](../windows-app-sdk/stable-channel.md)
- [WinUI 3 Controls Gallery sample app](https://github.com/microsoft/Xaml-Controls-Gallery/tree/winui3)

## WinUI resources

**Github**: WinUI is an open-source project hosted on Github. Use the [WinUI repo](https://github.com/microsoft/microsoft-ui-xaml), to file feature requests or bugs, interact with the WinUI team, and view the team's plans for WinUI 3 and beyond on their [roadmap](https://github.com/microsoft/microsoft-ui-xaml/blob/master/docs/roadmap.md).

**Website**: The [WinUI website](https://aka.ms/winui) has product comparisons, explains the various advantages of WinUI, and provides ways to stay engaged with the product and the product team.