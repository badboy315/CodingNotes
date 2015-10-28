## sublime 3 私有设置

### Preferences -> Settings -> User

```
"always_show_minimap_viewport": true,
"draw_minimap_border": true, # 让 minimap 里的当前位置更显眼点.
"highlight_line": true, # ST 里我经常找不到光标在哪儿, 这个开启后可以高亮当前行
"highlight_modified_tabs": true, # 修改了而尚未保存的 tab, 会用橘黄色显示
"show_encoding": true, # 显示文件编码
"show_full_path": true, # 标题栏上显示完整路径, 有时候不小心开错了文件, 这样能帮你早点发现.
"show_line_endings": true,
"open_files_in_new_window": false, #  在 Finder 里打开文件时, 不会新开窗口了.
```

### package setting

> Shift + Command + P 调出 Command Palette，输入 pci（模糊匹配），找到 Package Control: Install Package，回车;

- Monokai Extended & Markdown Extended # 安装完成后选择皮肤 `Preferences —— Color Scheme —— Mononkai Extended`
- SideBarFolders
- OmniMarkupPreviewer # 实现 markdown 实时预览 快捷键操作 `command+alt+o`
- [SublimeTmpl](https://github.com/kairyou/SublimeTmpl) #快速生成文件模板
	+ control + alt + h html
	+ control + alt + j javascript
	+ control + alt + c css
	+ control + alt + p php
	+ control + alt + r ruby
	+ control + alt + shift + p python


### 快捷键

Ctrl+Shift+P：打开命令面板
Ctrl+P：搜索项目中的文件
Ctrl+G：跳转到第几行
Ctrl+W：关闭当前打开文件
Ctrl+Shift+W：关闭所有打开文件
Ctrl+Shift+V：粘贴并格式化
Ctrl+D：选择单词，重复可增加选择下一个相同的单词
Ctrl+L：选择行，重复可依次增加选择下一行
Ctrl+Shift+L：选择多行
Ctrl+Shift+Enter：在当前行前插入新行
Ctrl+X：删除当前行
Ctrl+M：跳转到对应括号
Ctrl+U：软撤销，撤销光标位置
Ctrl+J：选择标签内容
Ctrl+F：查找内容
Ctrl+Shift+F：查找并替换
Ctrl+H：替换
Ctrl+R：前往 method
Ctrl+N：新建窗口
Ctrl+K+B：开关侧栏
Ctrl+Shift+M：选中当前括号内容，重复可选着括号本身
Ctrl+F2：设置/删除标记
Ctrl+/：注释当前行
Ctrl+Shift+/：当前位置插入注释
Ctrl+Alt+/：块注释，并Focus到首行，写注释说明用的
Ctrl+Shift+A：选择当前标签前后，修改标签用的
F11：全屏
Shift+F11：全屏免打扰模式，只编辑当前文件
Alt+F3：选择所有相同的词
Alt+.：闭合标签
Alt+Shift+数字：分屏显示
Alt+数字：切换打开第N个文件
Shift+右键拖动：光标多不，用来更改或插入列内容
Ctrl+依次左键点击或选取，可需要编辑的多个位置
Ctrl+Shift+上下键：替换行

### 参考

- [那些年我使用过的 Sublime Text 3 插件](http://bubkoo.com/2014/01/04/sublime-text-3-plugins/)
- [如何优雅地使用Sublime Text3](http://www.jianshu.com/p/3cb5c6f2421c)
