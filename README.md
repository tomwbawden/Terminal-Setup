# Installation instructions for ZSH + Oh-my-zsh

1. Install brew (if not install already)
2. Install ZSH
	- brew install zsh zsh-completions
3. Install oh+my+zsh
	- curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
	- Set as default shell chsh -s /bin/zsh
4. Edit ~/.zshrc and change the following
	ZSH_THEME=miloshadzic
    plugins=(git colored-man colorize github jira vagrant virtualenv pip python brew osx zsh-syntax-highlighting)
5. Install Solarized color scheme and make default
	- http://ethanschoonover.com/solarized
