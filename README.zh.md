<div align="center">

  <h1>NRF-v1-spec: 网易租赁服函数规范</h1>

  <h3>标准 · 简单 · 易维护</h3>

  <p>
    <img src="https://img.shields.io/badge/mcfunction-1.12.2-00ADD8?logo=gnubash&logoColor=white" alt="mcfunction">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
    <br>
    <a href="https://caolvchong.club"><img src="https://img.shields.io/badge/Website-caolvchong.club-blue?style=flat&logo=google-chrome&logoColor=white" alt="Website"></a>
  </p>

 **中文** | [English](README.md)
</div>

---

🔧 NRF-v1-spec 是一个为 网易租赁服函数 设计的规范,旨在使 mcfunction 更易于使用.它适用于网易定制的1.12.2版本服务器

⚡️ 该规范旨在让函数便于维护与可拓展,同时规定了一些特定指令的位置,方便做到快速定位与修改,同时方便接入特定混淆器进行混淆

注意：由于时效性强,部分内容可能不准确.

## 1 命名规范
> [!警告]
> **🚨 重要声明**
>
> - **禁止使用非英文字符给函数文件命名:** 使用非英文等特殊字符命名可能会导致 **无法导入** 存档的问题,网易启动器会直接报错 **文件夹也不行**
> - **禁止使用非英文字符命名积分版:** 不推荐使用非英文字符命名积分版,可能会导致一些未知问题.
> - **严格遵守正确存档格式:** 确保你的每个文件都放在了它应该在的位置.