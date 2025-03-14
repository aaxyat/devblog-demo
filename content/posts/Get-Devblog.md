+++
title = 'Get Devblog'
date = 2025-03-14T20:41:06Z
author = "Ayush Bhattarai"
summary = 'This details how you can install Devblog theme on your Hugo site.'
tags = ['devblog', 'theme', 'installation']
draft = false
+++

## 🚀 Let's Get Started with DevBlog!

### 🌟 Starting Fresh? No Problem! (Beginner's Guide)

Ready to embark on your blogging journey? Let's do this step by step:

1. 🛠️ **First Things First: Install Hugo**
    - 🍎 *macOS Users:* `brew install hugo`
    - 🪟 *Windows Folks:* `choco install hugo-extended`
    - 🌐 *Everyone else:* Check out the [Hugo Installation Guide](https://gohugo.io/installation/)

2. 🎯 **Create Your Shiny New Hugo Site**
    ```bash
    hugo new site my-blog
    cd my-blog
    ```

3. 📦 **Time for Git Magic**
    ```bash
    git init
    ```

### 💡 Method 1: Git Submodule Style (For the Git-savvy)
```bash
# Jump to your Hugo site
cd your-hugo-site

# Git init (if you haven't already)
git init

# Add our awesome theme
git submodule add https://github.com/aaxyat/hugo-devblog.git themes/devblog
```

### 🎁 Method 2: Keep It Simple

1. 📥 Grab our latest release
2. 📂 Drop it in your themes folder
3. ✨ Name it `devblog` and you're set!

### 🚀 Fire Up Your Hugo Site

```bash
hugo server -D
```

### 🎉 Congratulations! 🎉

You've successfully installed the Devblog theme on your Hugo site! 🚀

Ready to customize it? Dive into the [Devblog Documentation](https://github.com/aaxyat/hugo-devblog/blob/main/wiki.md)

Happy blogging! 🎉
 
 