<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/PicGo/202303121108782.png">
  <img alt="NebulaGraph Data Intelligence Suite(ngdi)" src="https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/PicGo/202303121108782.png">
</picture>
<p align="center">
    <br> 中文 | <a href="README_en_US.md">English</a>
</p>
<p align="center">
    <em>ChatGPT meets Siri - Experience the power of chatgpt-3.5-turbo</em>
  <br>
    <em>体验语音驱动的人工智能问答，基于chatgpt-3.5-turbo</em>
</p>

<p align="center">
<a href="LICENSE" target="_blank">
    <img alt="MIT License" src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" />
</a>

<!-- iOS Badge -->
<img alt="iOS" src="https://img.shields.io/badge/iOS-14--16-orange" />
  
<!-- iPadOS Badge -->
<img alt="iPadOS" src="https://img.shields.io/badge/iPadOS-14--16-brightgreen" />

<!-- watchOS Badge -->
<img alt="watchOS" src="https://img.shields.io/badge/watchOS-7--9-blue" />


<a href="https://github.com/yetone/openai-translator/releases" target="_blank">
<img alt="macOS" src="https://img.shields.io/badge/-macOS-black?style=flat-square&logo=apple&logoColor=white" />
</a>
</p>

# ChatGPT Siri Pro 快捷指令

## 目录

-   [下载获取快捷指令](#下载获取快捷指令)
-   [使用说明](#使用说明)
    -   [安装准备](#安装准备)
        -   [安装快捷指令](#安装快捷指令)
        -   [填入你的 APIKEY](#填入你的-APIKEY)
        -   [体验版免费使用](#体验版免费使用)
    -   [开始使用](#开始使用)
        -   [启动对话](#启动对话)
        -   [自定义唤醒词](#自定义唤醒词)
        -   [设置轻敲唤醒](#设置轻敲唤醒)
        -   [设置抬腕唤醒](#设置抬腕唤醒)
-   [进阶玩法：](#进阶玩法)
    -   [Prompt 设定](#Prompt-设定)
    -   [交互对话设定](#交互对话设定)
    -   [重新开始和退出指令](#重新开始和退出指令)
-   [更新路径：](#更新路径)

🎁这是一款将chatGPT 集成到 Siri 的项目，采用快捷指令编写，支持国内直连，支持直接体验或者用APIKEY 使用，已更新 gpt-3.5-turbo，支持连续对话功能。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230307/79f697a3b2a18.png)

本快捷指令主要支持 **iPhone**  和  **iPad ​**，还支持在 Apple Watch 和 macOS（暂未测试） 中使用，支持抬手唤醒和轻敲手机背面唤醒。

# 下载获取快捷指令

💻下载地址：

1. 实时更新：[https://askgptai.com/siripro](https://askgptai.com/siripro)
2. iCloud链接：[https://www.icloud.com/shortcuts/2e9f11a8a876488fab105ddaff08ba39](https://www.icloud.com/shortcuts/2e9f11a8a876488fab105ddaff08ba39)

👆更新时间：2023.03.12 10:42


# 使用说明

😊该快捷指令支持开箱即用，填写APIKEY 后使用官方API接口，支持连续对话（依然受最多4096 token限制，约2000字左右），没有填写KEY 则使用国内第三方API。

具体使用教程如下：

## 安装准备

### **安装快捷指令**

点开上方提供的的下载链接，或**[点击此处](https://askgptai.com/siripro)**获取快捷指令，在 iOS 设备上安装本快捷指令。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/45c9781b98fe2.png)

### **填入你的 APIKEY**

删除快捷指令中的要求填入APIKEY的文本框内容，粘贴你的 APIKEY，获得支持连续对话的完全体。⚠请注意，填入APIKEY 后不要直接用你自己的 iCloud链接分享快捷指令，这会**导致你的 APIKEY 泄露**！！

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/7b6127825440f.png)

如果你有 OpenAI 账号但还没有APIKEY，可以前往官网下图位置生成你的 APIKEY：[https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230308/33272423dd5c9.png)

如果你没有OpenAI 账号，也可以免费体验无连续对话的版本，或者尝试搜索自行注册账号，目前新账号附赠 5 美元体验余额，支持约125万字的对话。

如果只是想体验 chatGPT连续对话，也可以前往：[https://askgptai.com/](https://askgptai.com/)


### **体验版免费使用**

如果没有填入 APIKEY，也可以直接使用，但暂不支持连续对话功能。第三方接口可能不够稳定，如果没有获取到答案会返回下列内容：

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/101a1c6f62d32.jpg)

## 开始使用

### **启动对话**

对着 iPhone/iPad/watch/Mac 说：**Hey Siri，展开智子**，即可与 chatGPT 开始对话，图片是接入前和接入后 Siri 对于同一个问题的回答。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/6e51cc8ffcaa7.jpg)

如果觉得第一次的回答还不够，可以继续追问 Siri，如下图为追问后的结果：

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/f7293c87414c2.jpg)

### **自定义唤醒词**

如果觉得 【**展开智子**】 这个名字不够得劲儿，可以自定义唤醒词，直接修改该快捷指令的标题即可，如：召唤二狗子，iOS 16 设备点击快捷指令顶部的标题-重新命名 修改名称，iOS 15 及更低版本的设备点击标题即可弹出对话框修改名称。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/9dd5ce36acdb7.png)

### **设置轻敲唤醒**

iPhone 8 及后续设备支持轻敲手机背面，唤醒特定的快捷指令，按照图片提示进入 **【设置】-【辅助功能】-【触控】-【轻点背面】**，将【**轻点两下**】设置为本快捷指令【**展开质子**】，轻敲手机背面即可唤起文字输入，使用 iPhone键盘的听写也能快速语音输入。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/c8669f0af6236.jpg)

### **设置抬腕唤醒**

在 【**Watch**】 应用 - 【**Siri**】 中打开【**抬腕对话**】功能，抬手直接说【**展开智子**】即可快速与 chatGPT 对话。（该功能通常是默认开启的）

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/34f136db11aca.jpg)

# 进阶玩法：

### **Prompt 设定**

本快捷指令支持简单的 **prompt 设定**，通过设定可以获得更专业精确的回答，初始设定是作为个人智能助理，如果需要调整设定，可以在快捷指令中修改 prompt 文本中的内容

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/770fa260e05b1.png)

### **交互对话**设定

本快捷指令支持 **对话交互设定**，调节后像首次启动和继续提问时，回答和询问能更连贯，例如需要Siri 每次询问之后都带上“**喵~**”，只需在指令的词典中修改右侧文字即可。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/ce2658e9076f9.jpg)

### **重新开始和退出指令**

本快捷指令默认设置为 重新开始 和 没有了，当对话中包含对应文字时，快捷指令会自动相应，你也可以修改指令达到自定义控制的效果，如将 没有了 改为：跪安吧，那么快捷指令会在听到 跪安吧 之后自动退出对话。

![](https://picloud-1302482767.cos.ap-nanjing.myqcloud.com/20230309/c09042b0c9352.jpg)
