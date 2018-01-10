安装
====

### 备份

        mv ~/.vim ~/.vim.orig
        mv ~/.vimrc ~/.vimrc.orig

### 安装依赖程序包
        
        yaourt -S ack ctags                  # ArchLinux
        apt-get install ack-grep ctags       # Ubuntu
        yum install ack ctags                # CentOS
        brew install ack ctags               # OS X

### 配置文件

        git clone git://github.com/tgyday/dot-vimrc.git ~/.vim
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


