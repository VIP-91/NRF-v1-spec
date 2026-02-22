<div align="center">

  <h1>NRF-v1-spec: NetEase Rental Functions specification</h1>

  <h3>Standard · Simple · Easy to maintain</h3>

  <p>
    <img src="https://img.shields.io/badge/mcfunction-1.12.2-00ADD8?logo=gnubash&logoColor=white" alt="mcfunction">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
    <br>
    <a href="https://caolvchong.club"><img src="https://img.shields.io/badge/Website-caolvchong.club-blue?style=flat&logo=google-chrome&logoColor=white" alt="Website"></a>
  </p>

 [中文](README.zh.md) | **English**
</div>

---

🔧 NRF-v1-spec is a specification for NetEase Rental Functions, make mcfunctions easier to use. It is designed for NetEase's 1.12.2 version server.

⚡️ The specification aims to make mcfunctions easier to maintain and extend, while also specifying the positions of some specific instructions, which facilitates quick location and modification. It also facilitates integration with specific obfuscators for obfuscation.

Warning: Since the specification is still in development, some content may be inaccurate.
   
## 1 Naming Convention
> [!CAUTION]
> **🚨 Important Declaration**
>
> - **Do not use non-English characters to name function files:** Using non-English characters or special characters to name function files may cause **unable to import** the archive problem, and the NetEase launcher will directly report an error. **Folder names also cannot contain non-English characters.**
> - **Do not use non-English characters to name integral versions:** It is not recommended to use non-English characters to name integral versions, as it may cause some unknown problems.
> - **Strictly follow the correct archive format:** Make sure that each file is placed in the correct position.