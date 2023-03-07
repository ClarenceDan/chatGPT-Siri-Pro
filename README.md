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

![](https://secure2.wostatic.cn/static/8DHgTP1jzajzJovu5HRHfH/image.png?auth_key=1678184972-vbSxgxm6LWq8HeHT6VYk7B-0-271e091475b8137f658a3b6511780e10)

本快捷指令主要支持 **iPhone**  和  **iPad ​**，还支持在 Apple Watch 和 macOS（暂未测试） 中使用，支持抬手唤醒和轻敲手机背面唤醒。

# 下载获取快捷指令

💻下载地址：

1. 实时更新：[https://askgptai.com/siripro](https://askgptai.com/siripro)
2. iCloud链接：[https://www.icloud.com/shortcuts/2ea99a13958f4a3f8a20c5ff94512981](https://www.icloud.com/shortcuts/2ea99a13958f4a3f8a20c5ff94512981)

# 使用说明

😊该快捷指令支持开箱即用，填写APIKEY 后使用官方API接口，支持连续对话（依然受最多4096 token限制，约2000字左右），没有填写KEY 则使用国内第三方API。

具体使用教程如下：

## 安装准备

### **安装快捷指令**

点开上方提供的的下载链接，或**[点击此处](https://askgptai.com/siripro)**获取快捷指令，在 iOS 设备上安装本快捷指令。

![](https://secure2.wostatic.cn/static/cPm3BRkwFDMm5V2HBqWftX/image.png?auth_key=1678184972-9CS9LqdWkYduFNqFFFn8eq-0-c0a37f15b638aeb6a7137148c57400cc)

### **填入你的 APIKEY**

删除快捷指令中的要求填入APIKEY的文本框内容，粘贴你的 APIKEY，获得支持连续对话的完全体。⚠请注意，填入APIKEY 后不要直接用你自己的 iCloud链接分享快捷指令，这会**导致你的 APIKEY 泄露**！！

![](https://secure2.wostatic.cn/static/2goTMvRvpQ5w6Z8hfubS3Y/image.png?auth_key=1678184972-fBFiDvXXdujj9C1un67zY7-0-b348366a49079c718ee4d16c9ae009b0)

如果你有 OpenAI 账号但还没有APIKEY，可以前往官网下图位置生成你的 APIKEY：[https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)

![](https://secure2.wostatic.cn/static/p9wCPFnpSD1C4FN9bPs8YG/image.png?auth_key=1678184972-fEmRLoe5SKfNFqviwtNGpT-0-a95e51fbdb7da6bb47da5052790d4950)

如果你没有OpenAI 账号，也可以免费体验无连续对话的版本，或者尝试搜索自行注册账号，目前新账号附赠 5 美元体验余额，支持约125万字的对话。

如果只是想体验 chatGPT连续对话，也可以前往：[https://askgptai.com/](https://askgptai.com/)


### **体验版免费使用**

如果没有填入 APIKEY，也可以直接使用，但暂不支持连续对话功能。第三方接口可能不够稳定，如果没有获取到答案会返回下列内容：

![](https://secure2.wostatic.cn/static/tgndpBbzEFJV376hP9VA48/6f476e7af6f9701f8754b22cb461afb.jpg?auth_key=1678184972-8DwUw2JuFkzNoenupk6kv-0-071b7d0cd3a768e8e04ee190eb3a1dc8)

## 开始使用

### **启动对话**

对着 iPhone/iPad/watch/Mac 说：**Hey Siri，展开智子**，即可与 chatGPT 开始对话，图片是接入前和接入后 Siri 对于同一个问题的回答。

![](https://secure2.wostatic.cn/static/k6N6xyP9FDCeZiEGwgoMqJ/705663e1c9176e4fca0b9056fcadb21.jpg?auth_key=1678184972-kvkdnKHiKxzZAQAc69XnsA-0-0f02263d35df5e383d608b514b753e8b)

如果觉得第一次的回答还不够，可以继续追问 Siri，如下图为追问后的结果：

![](https://secure2.wostatic.cn/static/mEzrfb933bcmMXLXxBwR8H/afaef5bd416526d474598643bee6dfa.jpg?auth_key=1678184972-rz3v4mWFCi8nvzjMoVd8d1-0-440fbc6724462b5102cdb43167cfcb4e)

### **自定义唤醒词**

如果觉得 【**展开智子**】 这个名字不够得劲儿，可以自定义唤醒词，直接修改该快捷指令的标题即可，如：召唤二狗子，iOS 16 设备点击快捷指令顶部的标题-重新命名 修改名称，iOS 15 及更低版本的设备点击标题即可弹出对话框修改名称。

![](https://secure2.wostatic.cn/static/u3uVfdngdvsK5mAvFzVD2U/image.png?auth_key=1678184972-aBSWo5h9nMiPPoDd5Db4QS-0-fb403b79bcce6e4994fdf51886d1ac3e)

### **设置轻敲唤醒**

iPhone 8 及后续设备支持轻敲手机背面，唤醒特定的快捷指令，按照图片提示进入 **【设置】-【辅助功能】-【触控】-【轻点背面】**，将【**轻点两下**】设置为本快捷指令【**展开质子**】，轻敲手机背面即可唤起文字输入，使用 iPhone键盘的听写也能快速语音输入。

![](https://secure2.wostatic.cn/static/ahKgKRAFmRk38vNquUhycf/c288b5ecb223e95dd186e2c8ebb68ef.jpg?auth_key=1678184972-og12q4bgz8yFGCA7jRAAES-0-8c48b5db8957da64d65f7ad4fd7cfc10)

### **设置抬腕唤醒**

在 【**Watch**】 应用 - 【**Siri**】 中打开【**抬腕对话**】功能，抬手直接说【**展开智子**】即可快速与 chatGPT 对话。（该功能通常是默认开启的）

![](https://secure2.wostatic.cn/static/kXwPYvfGbQ6zgof4cNzo7E/a65bc8ef1f852dbeca879b033e8903f.jpg?auth_key=1678184972-mWJ6iuZJXTPCk1tSnyVbx7-0-f782269a1afe3094dcc25f196b98fcc2)

# 进阶玩法：

### **Prompt 设定**

本快捷指令支持简单的 **prompt 设定**，通过设定可以获得更专业精确的回答，初始设定是作为个人智能助理，如果需要调整设定，可以在快捷指令中修改 prompt 文本中的内容

![](https://secure2.wostatic.cn/static/kJF11sNE5nt5x3viMYsKuu/image.png?auth_key=1678184972-nn7aqhtzDF3KvLyfinksbK-0-ae4e63dc17b5218ad4f3e507c83a67a4)

### **交互对话**设定

本快捷指令支持 **对话交互设定**，调节后像首次启动和继续提问时，回答和询问能更连贯，例如需要Siri 每次询问之后都带上“**喵~**”，只需在指令的词典中修改右侧文字即可。

![](https://secure2.wostatic.cn/static/8EwyEB4RGNuBbZAuvssWau/faa100933f44aaebd821753e409a831.jpg?auth_key=1678184972-nJ6Xdeiy9skQYqFHwEGsE2-0-1147f82874a35bba943828cca26fb2b2)

### **重新开始和退出指令**

本快捷指令默认设置为 重新开始 和 没有了，当对话中包含对应文字时，快捷指令会自动相应，你也可以修改指令达到自定义控制的效果，如将 没有了 改为：跪安吧，那么快捷指令会在听到 跪安吧 之后自动退出对话。

![](https://secure2.wostatic.cn/static/9fFKA8aqx2TVaR2xfxkn16/cfe23807baa05e8a464a4df11e06165.jpg?auth_key=1678184972-99tugcZStgg3xw1LjK6r8x-0-0218d703e89fa9e6fd3f62b508bd0f3a)

# 更新路径：

1. 当前连续对话需要将每轮对话全部传回到 chatGPT，受到最大token 数限制（4096个英文或2000字左右中文），后续考虑用 prompt enginering 优化，使最大对话轮次得以提高。
2. 当前对话不支持保存对话内容，后续考虑增加保存对话内容的版本。
3. 当前体验接口在 iOS 16 上的中文回复内容是乱码，正在测试解决该问题
4. 还在想，如果你有很好的想法或需求，可以在 Github 上提交 issue，我们也正在制作收集表格，收集大家的反馈，制作更高效的AI快捷指令，一起享受 AI 的春天吧！
