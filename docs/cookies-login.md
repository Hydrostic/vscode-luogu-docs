---
title: cookies 登录
sidebar_position: 2
---
请按以下提示操作或直接使用该功能：

- Windows：

  - 打开 Windows 命令提示符，依次键入：
    ```bat
    cd %HOMEPATH%
    mkdir .luogu REM 若已存在则忽略
    cd .luogu
    <您要使用的编辑器（如 notepad ）> luogu.json REM 键入 1
    <您要使用的编辑器（如 notepad ）> uid.json   REM 键入您的洛谷 uid
    <您要使用的编辑器（如 notepad ）> CsrfToken.json REM 键入您的 client_id
    ```
  - 在浏览器中登录你的洛谷账号，依次按图中操作查看您的 client_id：
   ![](./img/cl1.png)
   ![](./img/cl2.png)
- Linux：

  - 基本同 Windows，不同的是第一步为 `cd ~`。

- MacOS:
  - 基本同 Linux


![cookies登录.gif](./img/cl3.gif)