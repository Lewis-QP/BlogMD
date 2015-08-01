使用Sublime text 2 编辑Markdown<br>
==================
##一. 安装
1. 下载<a href="www.baidu.com">Sublime Text 2</a>,安装

##二. 安装Package Control
1. 按Ctrl + ` 打开console
2. 粘贴代码到console并回车
3. 重启Sublime Text 2
<pre><code>import urllib2,os;
pf='Package Control.sublime-package';
ipp=sublime.installed_packages_path();
os.makedirs(ipp)
if not os.path.exists(ipp) 
else None;open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read())
</code></pre>

##三、安装Markdown Preview
1. 按Ctrl + Shift + P
2. 输入pci 后回车(Package Control: Install Package)
3. 稍等... ^_^
4. 输入Markdown Preview回车

##四、编辑
1. 按Ctrl + N 新建一个文档
2. 按Ctrl + Shift + P
3. 使用Markdown语法编辑文档
4. 语法高亮，输入ssm 后回车(Set Syntax: Markdown)

##五、在浏览器预览Markdown文档
1. 按Ctrl + Shift + P
2. 输入mp 后回车(Markdown Preview: current file in browser)
3. 此时就可以在浏览器里看到刚才编辑的文档了