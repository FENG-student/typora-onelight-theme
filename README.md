<h1 align='center'>OneLight Theme For Typora</h1>

<p align="center">
    简体中文
    |
    <a href="https://github.com/caolib/typora-onelight-theme/blob/onelight/docs/README_en.md">English</a>
</p>


![总下载量](https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=grey&color=blue)
[![最新发行版](https://img.shields.io/github/v/release/caolib/typora-onelight-theme?labelColor=grey&color=red)](https://github.com/caolib/typora-onelight-theme/releases)
[![上次提交日期](https://img.shields.io/github/last-commit/caolib/typora-onelight-theme?labelColor=grey&color=blue)](https://github.com/caolib/typora-onelight-theme/activity)
[![网站部署状态](https://api.netlify.com/api/v1/badges/6ca72e1b-7dc6-4d51-8542-e07bf9ad0a88/deploy-status)](https://typora-theme.netlify.app)
[![css压缩打包状态](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml/badge.svg)](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml)
![Issues](https://img.shields.io/github/issues/caolib/typora-onelight-theme)

<details><summary><kbd>历史版本</summary></kbd>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.4.2/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.4.1/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.4.0/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.3.0/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.4/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.3/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.0/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.4/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.3/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.2/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.1/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.1.0/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.6/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.5/total"/></br>
</details>

---

## **1.概览**


> [!tip]
> **这里有两篇文章使用one-light主题，可点击查看主题详细效果展示**
>
> - **[onelight](https://bin-sites.pages.dev/onelight)**
> - **[计算机网络](https://bin-sites.pages.dev/net/计算机网络)**

---

![image-20250108140354139](https://s2.loli.net/2025/01/08/fNQF1ZCOgGydEUL.png)

![image-20250108140529374](https://s2.loli.net/2025/01/08/aMkKwdmVuTCtW4G.png)

![image-20250119102419998](https://s2.loli.net/2025/01/19/4jotBCzeDdlAwfF.png)

<details><summary><kbd>展开查看更多截图</summary></kbd>
  <img src="https://s2.loli.net/2025/01/08/Ir1mgZCto4YS6lj.png"></br>
  <img src="https://s2.loli.net/2025/03/04/YzmsQOAFJ2UkpC7.png"></br>
  <img src="https://s2.loli.net/2025/01/08/cAgBOqFoCMYE8S6.png"></br>
	一体化菜单界面
  <img src="https://s2.loli.net/2025/01/08/QF2UA9zPOW5X6ji.png"></br>
</details>

---

## 2.如何使用

### 2.1 下载文件（推荐）

> [!important]
>
> - 下载 [主题文件压缩包](https://github.com/caolib/typora-onelight-theme/releases)
>- 在typora中选择 文件 → 偏好设置 → 外观 → 打开主题文件夹
> - 将下载的压缩包解压，将**css文件**和**文件夹**粘贴到typora的主题文件夹中
> - 重启Typora然后在菜单栏切换主题，大功告成

### 2.2 克隆

> [!caution]
>
> **如果你想克隆本仓库，为了避免克隆到其他分支，请使用下面这条命令,这样只会克隆主分支**
>
> ```shell
> git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
> ```

---

## **3.关于字体**

在`onelight.css`文件开头设置了默认字体，可以自行修改，字体文件在[fonts](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/fonts)文件夹下
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

---

## **4.关于背景图片**

> [!important]
>
> 背景图片在`onelight/img`文件夹下，默认是`bg.gif`，可以自行替换,你也可以在css文件中搜索关键字 `gif` 找到对应代码进行替换，最好使用透明背景的图片
>
> ```css
> content {
>      background-color: transparent;
>      //可以替换此处的图片，不想显示可以将这段整个注释掉
>      background-image: url('./onelight/img/bg.gif');
>      background-position: 100% 100%;
>      background-repeat: no-repeat;
>      background-size: 100px auto; // 调整图片显示大小
>      transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
> ```
>
> <img src="https://s2.loli.net/2024/12/15/Fn6LcrKWC2dlp1J.gif" alt="recording" style="zoom: 50%;" />

---

## 5.其他

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="喜欢" />✅ 一体化模式下主题效果更佳

❓ 有问题可以在 [Issues](https://github.com/caolib/typora-onelight-theme/issues) 提问

⭐ 如果喜欢主题的话，请给我一个star，谢谢！

📄 [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs) 文件夹中有示例文章的markdown文件

🖼️ [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img) 文件夹中有主题的背景图片，你可以替换成你喜欢的任何图片，如果不需要可以直接删除



