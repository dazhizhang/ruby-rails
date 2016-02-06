准备工作：
1. 安装rbenv, 并用rbenv安装ruby, rbenv install --list可显示可安装的ruby版本, 然后运行 rbenv install 2.2.3 (已经安装好的可以跳过这步)
2. 在终端运行 rbenv versions 查看已安装的ruby版本, 然后rbenv global 2.2.3, 这时运行 ruby -v 应该显示的版本是 2.2.3, 如果不是，说明rbenv没有正确安装, 请仔细阅读rbenv在github的安装说明重新安装。
3. 使用gem安装 rspec : gem install rspec , 使用 rspec -v 查看安装是否成功

说明: 
1.作业的代码在lib文件里面, 测试代码在spec文件夹内；测试文件命名规则为: 源文件名_spec.rb
2.大多数代码文件的开始有关于作业的描述的注释, 也有没有的, 没有的, 请查看测试文件来确定要实现的功能;
3.请不要修改测试代码； 
4.在作业文件夹根目录使用rspec命令查看测试运行结果，要求是全部通过