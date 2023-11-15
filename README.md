# oh_my_zsh_with_emoji
基于oh-my-zsh中ys主题魔改的一个有趣的命令提示符主题，预览如下：
每次敲击回车时都会随机显示一个不同的emoji

<img src="https://github.com/SVMawww/oh_my_zsh_with_emoji/assets/81839065/479a6e51-f0fa-4075-a6b7-a1fafada18a3" width=755 />

### 使用方法：
- [安装好oh-my-zsh](https://ohmyz.sh/#install)
- 将仓库中 **ys_emoji.zsh-theme** 文件拷贝到 **~/.oh-my-zsh/themes** 目录中
- 更改 ~/.zshrc 文件中的 ZSH_THEME变量为  `ZSH_THEME="ys_emoji"`
- 执行`source ~/.zshrc`

### 自定义显示emoji

可以在ys_emoji.zsh-theme文件中的第49行找到`emojis`变量，将你喜欢的符号放到列表里即可自定义显示。可以显示emoji是因为他在UTF-8字符集中哦~
