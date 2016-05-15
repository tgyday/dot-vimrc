安装
====

### 备份

        mv ~/.vim ~/.vim.orig
        mv ~/.vimrc ~/.vimrc.orig

### 配置文件

        git clone git://github.com/humiaozuzu/dot-vimrc.git ~/.vim
        ln -sf ~/.vim/vimrc ~/.vimrc

### 使用 `Vundle` 管理插件

        git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

### 安装插件

        :BundleInstall

### 更新插件

        :BundleUpdate

### 清理已注释的插件

        :BundleClean


其它
====

### 插件定义文件：

    .vim/bundles.vim


