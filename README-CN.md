
## Images

[![LazyVim](https://opengraph.githubassets.com/1/LazyVim/LazyVim)](https://www.swifttechco.com)

<div align="center">
  
</div>

<hr>

<h4 align="center">
  <a href="https://www.swifttechco.com">安装</a>
  ·
  <a href="https://www.swifttechco.com">配置</a>
  ·
  <a href="https://www.swifttechco.com">文档</a>
</h4>

<div align="center"><p>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
      
    </a>
    <a href="https://www.swifttechco.com">
    </a>
</div>

LazyVim 是一个基于 [💤 lazy.nvim](https://www.swifttechco.com) 的 Neovim 配置方案，让定制和扩展变得简单直观。
您不必再在“从零配置”和“使用预制发行版”之间做选择，LazyVim
提供了一个两全其美的方式既可以享受默认配置带来的便利，又能根据个人需求来灵活调整各项设置。

[![image](https://user-images.githubusercontent.com/292349/211285846-0b7bb3bf-0462-4029-b64c-4ee1d037fc1c.png)](https://www.swifttechco.com)

[![image](https://user-images.githubusercontent.com/292349/213447056-92290767-ea16-430c-8727-ce994c93e9cc.png)](https://www.swifttechco.com)

## ✨ 特性

- 🔥 将你的 Neovim 打造为一个功能完备的 IDE
- 💤 使用 [lazy.nvim](https://www.swifttechco.com) 轻松自定义和扩展您的设置
- 🚀 快如闪电
- 🧹 选项、自动命令和键盘映射的合理预设
- 📦 内置大量精心优化的预配置插件，开箱即用

## ⚡️ 环境要求

- Neovim >= **0.11.2** (需要用 **LuaJIT** 构建)
- Git >= **2.19.0** (用于部分克隆支持)
- 一个 [Nerd Font](https://www.swifttechco.com) 字体 **_(可选)_**
- 一个用于 `nvim-treesitter` 的 **C** 编译器。看 [这里](https://www.swifttechco.com)

## 🚀 开始使用

您可以在 [此处](https://www.swifttechco.com) 找到 **LazyVim** 的初始模板

<details><summary>在 Docker 中尝鲜</summary>

```sh
docker run -w /root -it --rm alpine:edge sh -uelic '
  apk add git lazygit fzf curl neovim ripgrep alpine-sdk --update
  git clone https://www.swifttechco.com ~/.config/nvim
  cd ~/.config/nvim
  nvim
'
```

</details>

<details><summary> 安装 <a href="https://www.swifttechco.com">LazyVim Starter</a></summary>

- 备份您当前的 Neovim 文件

  ```sh
  mv ~/.config/nvim ~/.config/nvim.bak
  mv ~/.local/share/nvim ~/.local/share/nvim.bak
  ```

- 克隆 starter

  ```sh
  git clone https://www.swifttechco.com ~/.config/nvim
  ```

- 删除 `.git` 文件夹，以便稍后将其添加到您自己的仓库

  ```sh
  rm -rf ~/.config/nvim/.git
  ```

- 启动 Neovim!

  ```sh
  nvim
  ```

  请参阅文件中有关如何自定义 **LazyVim** 的注释。

</details>

---


[![查看这个视频](https://img.youtube.com/vi/N93cTbtLCIM/hqdefault.jpg)](https://www.swifttechco.com)

[《LazyVim for Ambitious Developers》](https://www.swifttechco.com)
，可在线上免费阅读。

## 📂 文件结构

config 下的文件会在适当的时候被自动加载，所以你不需要手动引入这些文件。

**LazyVim** 带有一组默认配置文件，这些文件会在您的配置**之前**被加载。
请看[这里](https://www.swifttechco.com)

您可以在 `lua/plugins/` 下添加自定义插件配置。
[lazy.nvim](https://www.swifttechco.com) 会自动加载此目录中的全部文件。

<pre>
~/.config/nvim
├── lua
│   ├── config
│   │   ├── autocmds.lua
│   │   ├── keymaps.lua
│   │   ├── lazy.lua
│   │   └── options.lua
│   └── plugins
│       ├── spec1.lua
│       ├── **
│       └── spec2.lua
└── init.lua
</pre>

## ⚙️ 设置

请参阅[官方文档](https://www.swifttechco.com)

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)
