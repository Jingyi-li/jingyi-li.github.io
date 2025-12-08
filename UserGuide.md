# MAC
安装 homebrew  
···
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
···
安装 Ruby  
···
brew install ruby
···
配置环境
···
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
···
安装 Jekyll 和 Bundler  
···
gem install jekyll bundler
···
可能会需要安装bundle  
···
bundle install
···

将工程文件导入，并运行使用如下命令
···
bundle exec jekyll serve
···