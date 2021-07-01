# [cVim快捷键](https://www.cnblogs.com/gongchixin/articles/7347471.html)

　　

# 键绑定

| 运动               |                                                              | 映射名称                              |
| ------------------ | ------------------------------------------------------------ | ------------------------------------- |
| `j`， `s`          | 向下滚动                                                     | 下滚                                  |
| `k`， `w`          | 向上滑动                                                     | 向上滑动                              |
| `h`                | 向左滚动                                                     | scrollLeft                            |
| `l`                | 向右滚动                                                     | scrollRight                           |
| `d`                | 滚动一半页面                                                 | scrollPageDown                        |
| 未映射             | 滚动全页下来                                                 | scrollFullPageDown                    |
| `u`， `e`          | 滚动一半页面                                                 | scrollPageUp                          |
| 未映射             | 滚动全页面                                                   | scrollFullPageUp                      |
| `gg`               | 滚动到页面顶部                                               | 滚动到顶部                            |
| `G`                | 滚动到页面的底部                                             | scrollToBottom                        |
| `0`                | 滚动到页面的左边                                             | scrollToLeft                          |
| `$`                | 滚动到页面的右侧                                             | scrollToRight                         |
| `#`                | 将滚动焦点重置为主页面                                       | resetScrollFocus                      |
| `gi`               | 转到第一个输入框                                             | goToInput                             |
| `gI`               | 转到最后一个聚焦的输入框 `gi`                                | goToLastInput                         |
| `zz`               | 中心页到当前搜索匹配（中）                                   | centerMatchH                          |
| `zt`               | 中心页到当前搜索匹配（上）                                   | centerMatchT                          |
| `zb`               | 中心页面到当前搜索匹配（底部）                               | centerMatchB                          |
| **链接提示**       |                                                              |                                       |
| `f`                | 打开当前选项卡中的链接                                       | createHint                            |
| `F`                | 在新标签页中打开链接                                         | createTabbedHint                      |
| 未映射             | 在新标签页中打开链接（活动）                                 | createActiveTabbedHint                |
| `W`                | 在新窗口中打开链接                                           | createHintWindow                      |
| `A`                | 重复最后提示命令                                             | openLastHint                          |
| `q`                | 触发悬停事件（mouseover + mouseenter）                       | createHoverHint                       |
| `Q`                | 触发不起眼的事件（mouseout + mouseleave）                    | createUnhoverHint                     |
| `mf`               | 打开多个链接                                                 | createMultiHint                       |
| 未映射             | 使用外部编辑器编辑文本                                       | createEditHint                        |
| 未映射             | 调用带有链接的代码块作为第一个参数                           | createScriptHint（`<FUNCTION_NAME>`） |
| 未映射             | 在新标签页中打开图像                                         | fullImageHint                         |
| `mr`               | 反向图像搜索多个链接                                         | multiReverseImage                     |
| `my`               | y多个链接（打开与P的链接列表）                               | multiYankUrl                          |
| `gy`               | 从链接复制URL到剪贴板                                        | yankUrl                               |
| `gr`               | 反向图像搜索（谷歌图像）                                     | reverseImage                          |
| `;`                | 改变链接提示的重点                                           |                                       |
| **QuickMarks**     |                                                              |                                       |
| `M<*>`             | 创建quickmark <*>                                            | addQuickMark                          |
| `go<*>`            | 在当前标签中打开quickmark <*>                                | openQuickMark                         |
| `gn<*>`            | 在新标签页中打开quickmark <*>                                | openQuickMarkTabbed                   |
| `gw<*>`            | 在新窗口中打开quickmark <*>                                  | openQuickMarkWindowed                 |
| **杂**             |                                                              |                                       |
| `a`                | 别名为“：tabnew google”                                      | ：tabnew google                       |
| `.`                | 重复最后一个命令                                             | repeatCommand                         |
| `:`                | 打开命令栏                                                   | openCommandBar                        |
| `/`                | 打开搜索栏                                                   | openSearchBar                         |
| `?`                | 打开搜索栏（反向搜索）                                       | openSearchBarReverse                  |
| 未映射             | 打开链接搜索栏（与按下相同`/?`）                             | openLinkSearchBar                     |
| `I`                | 搜索浏览器历史记录                                           | ：历史                                |
| `<N>g%`            | 在页面上滚动<N>百分比                                        | percentScroll                         |
| `<N>`未映射        | 将`<N>`密钥传递到当前页面                                    | 口令的                                |
| `zr`               | 重新启动Google Chrome                                        | ：铬：//重新启动<CR>                  |
| `i`                | 进入插入模式（退出退出）                                     | 插入模式                              |
| `r`                | 重新加载当前选项卡                                           | reloadTab                             |
| `gR`               | 重新加载当前选项卡+本地缓存                                  | reloadTabUncached                     |
| `;<*>`             | 创建标记<*>                                                  | 设置标记                              |
| `''`               | 转到最后滚动位置                                             | lastScrollPosition                    |
| `<C-o>`            | 转到上一个滚动位置                                           | previousScrollPosition                |
| `<C-i>`            | 转到下一个滚动位置                                           | nextScrollPosition                    |
| `'<*>`             | 去标记<*>                                                    | goToMark                              |
| `cm`               | 静音/取消静音选项卡                                          | muteTab                               |
| 没有               | 重新加载所有选项卡                                           | reloadAllTabs                         |
| `cr`               | 重新加载所有选项卡，但当前                                   | reloadAllButCurrent                   |
| `zi`               | 缩放页面                                                     | zoomPageIn                            |
| `zo`               | 缩小页面                                                     | zoomPageOut                           |
| `z0`               | 缩放页面到原始大小                                           | zoomOrig                              |
| `z<Enter>`         | 切换图像缩放（与仅在图像页面上单击图像相同）                 | toggleImageZoom                       |
| `gd`               | 别名：chrome：//下载<CR>                                     | ：铬：//下载<CR>                      |
| `ge`               | 别名：chrome：// extensions <CR>                             | ：铬：//扩展<CR>                      |
| `yy`               | 将当前页面的URL复制到剪贴板                                  | yankDocumentUrl                       |
| `yY`               | 将当前帧的URL复制到剪贴板                                    | yankRootUrl                           |
| `ya`               | 复制当前窗口中的URL                                          | yankWindowUrls                        |
| `yh`               | 从查找模式复制当前匹配的文本（如果有）                       | yankHighlight                         |
| `b`                | 搜寻书签                                                     | ：书签                                |
| `p`                | 打开剪贴板选择                                               | openPaste                             |
| `P`                | 在新标签页中打开剪贴板选择                                   | openPasteTab                          |
| `gj`               | 隐藏下载架                                                   | hideDownloadsShelf                    |
| `gf`               | 循环通过iframe                                               | nextFrame                             |
| `gF`               | 去根框架                                                     | rootFrame                             |
| `gq`               | 停止加载当前选项卡                                           | cancelWebRequest                      |
| `gQ`               | 停止加载所有标签                                             | cancelAllWebRequests                  |
| `gu`               | 在URL中上传一条路径                                          | goUpUrl                               |
| `gU`               | 转到基本URL                                                  | goToRootUrl                           |
| `gs`               | 转到当前网址的view-source：//页面                            | ：viewsource！                        |
| `<C-b>`            | 创建或切换当前网址的书签                                     | createBookmark                        |
| 未映射             | 关闭所有浏览器窗口                                           | quitChrome                            |
| `g-`               | 减去URL路径中的第一个数字（例如`www.example.com/5`=> `www.example.com/4`） | decrementURLPath                      |
| `g+`               | 增加URL路径中的第一个数字                                    | incrementURLPath                      |
| **标签导航**       |                                                              |                                       |
| `gt`，`K`，`R`     | 导航到下一个选项卡                                           | nextTab                               |
| `gT`，`J`，`E`     | 导航到上一个选项卡                                           | previousTab                           |
| `g0`， `g$`        | 转到第一个/最后一个选项卡                                    | firstTab，lastTab                     |
| `<C-S-h>`， `gh`   | 在新标签页中打开当前标签的历史记录中的最后一个URL            | openLastLinkInTab                     |
| `<C-S-l>`， `gl`   | 在新标签页中打开当前选项卡的历史记录中的下一个URL            | openNextLinkInTab                     |
| `x`                | 关闭当前选项卡                                               | closeTab                              |
| `gxT`              | 关闭当前选项卡左侧的选项卡                                   | closeTabLeft                          |
| `gxt`              | 关闭当前选项卡右侧的选项卡                                   | closeTabRight                         |
| `gx0`              | 关闭当前选项卡左侧的所有选项卡                               | closeTabsToLeft                       |
| `gx$`              | 关闭当前选项卡右侧的所有选项卡                               | closeTabsToRight                      |
| `X`                | 打开最后关闭的标签页                                         | lastClosedTab                         |
| `t`                | ：执行tabnew                                                 | ：执行tabnew                          |
| `T`                | ：tabnew <CURRENT URL>                                       | ：tabnew @％                          |
| `O`                | ：打开<CURRENT URL>                                          | ：open @％                            |
| `<N>%`             | 切换到选项卡<N>                                              | goToTab                               |
| `H`， `S`          | 回去                                                         | 回去                                  |
| `L`， `D`          | 前进                                                         | 前进                                  |
| `B`                | 搜索另一个活动选项卡                                         | ：缓冲                                |
| `<`                | 向左移动当前标签                                             | moveTabLeft                           |
| `>`                | 向右移动当前标签                                             | moveTabRight                          |
| `]]`               | 点击页面上的“下一个”链接（见上面的nextmatchpattern）         | nextMatchPattern                      |
| `[[`               | 点击页面上的“返回”链接（参见上面的上一个模式）               | previousMatchPattern                  |
| `gp`               | 引导/取消固定当前选项卡                                      | pinTab                                |
| `<C-6>`            | 在最后使用的标签之间切换焦点                                 | lastUsedTab                           |
| **查找模式**       |                                                              |                                       |
| `n`                | 下一个搜索结果                                               | nextSearchResult                      |
| `N`                | 以前的搜索结果                                               | previousSearchResult                  |
| `v`                | 进入视觉/插入模式（突出显示当前搜索/选择）                   | toggleVisualMode                      |
| `V`                | 从插入模式/当前突出显示的搜索进入视线模式                    | toggleVisualLineMode                  |
| 未映射             | 清除搜索模式突出显示                                         | clearSearchHighlight                  |
| **视觉/插入模式**  |                                                              |                                       |
| `<Esc>`            | 将视觉模式退出插入模式/退出插入模式到正常模式                |                                       |
| `v`                | 在视觉/插入模式之间切换                                      |                                       |
| `h`，`j`，`k`，`l` | 移动插入位置/扩展视觉选择                                    |                                       |
| `y`                | 配合当前的选择                                               |                                       |
| `n`                | 选择下一个搜索结果                                           |                                       |
| `N`                | 选择先前的搜索结果                                           |                                       |
| `p`                | 打开当前选项卡中的突出显示                                   |                                       |
| `P`                | 在新标签中打开突出显示的文本                                 |                                       |
| **文本框**         |                                                              |                                       |
| `<C-i>`            | 将光标移动到行的开头                                         | beginningOfLine                       |
| `<C-e>`            | 将光标移动到行尾                                             | 行结束                                |
| `<C-u>`            | 删除到行的开头                                               | deleteToBeginning                     |
| `<C-o>`            | 删除到行尾                                                   | deleteToEnd                           |
| `<C-y>`            | 删除一个字                                                   | deleteWord                            |
| `<C-p>`            | 删除一个字                                                   | deleteForwardWord                     |
| 未映射             | 删除一个字符                                                 | deleteChar                            |
| 未映射             | 删除一个字符                                                 | deleteForwardChar                     |
| `<C-h>`            | 将光标移回一个字                                             | backwardWord                          |
| `<C-l>`            | 将光标向前移动一个字                                         | forwardWord                           |
| `<C-f>`            | 将光标向前移动一个字母                                       | forwardChar                           |
| `<C-b>`            | 将光标移回一个字母                                           | backwardChar                          |
| `<C-j>`            | 将光标向前移动一行                                           | forwardLine                           |
| `<C-k>`            | 将光标移回一行                                               | backwardLine                          |
| 未映射             | 选择输入文本（相当于`<C-a>`）                                | 全选                                  |
| 未映射             | 在终端中使用Vim进行编辑（需要运行该工作的[cvim_server.py](https://github.com/1995eaton/chromium-vim/blob/master/cvim_server.py)脚本以及该脚本中的VIM_COMMAND集） | editWithVim                           |

# 命令模式

| 命令                               | 描述                                                         |
| ---------------------------------- | ------------------------------------------------------------ |
| ：tabnew（自动填充）               | 打开一个新的标签与打字/完成的搜索                            |
| ：新（自动完成）                   | 用打字/完成搜索打开一个新窗口                                |
| ：打开（自动填充）                 | 打开输入/完成的URL / Google搜索                              |
| ：历史（自动填充）                 | 搜索浏览器历史记录                                           |
| ：书签（自动填充）                 | 搜寻书签                                                     |
| ：bookmarks / <folder>（自动填充） | 按文件夹浏览书签/从文件夹中打开所有书签                      |
| ：set（autocomplete）              | 暂时更改cVim设置                                             |
| ：chrome：//（autocomplete）       | 打开一个chrome：// URL                                       |
| ：tabhistory（自动填充）           | 浏览当前选项卡的不同历史状态                                 |
| ：命令 `<NAME>` `<ACTION>`         | 别名：`<NAME>`to：`<ACTION>`                                 |
| ：放弃                             | 关闭当前选项卡                                               |
| ：qall                             | 关闭当前窗口                                                 |
| ：恢复（自动完成）                 | 恢复以前关闭的标签（仅限较新版本的Chrome）                   |
| ：tabattach（自动填充）            | 将当前选项卡移动到另一个打开的窗口                           |
| ：tabdetach                        | 将当前选项卡移动到新窗口                                     |
| ：文件（自动填充）                 | 打开本地文件                                                 |
| ：来源（自动填充）                 | 将cVimrc文件加载到内存中（如果`localconfig`以前设置了该设置，这将覆盖选项页面中的设置 |
| ：重复                             | 复制当前选项卡                                               |
| ：设置                             | 打开设置页面                                                 |
| ：nohlsearch                       | 清除上次搜索中突出显示的文字                                 |
| ：执行                             | 执行一个键序列（对于映射有用），例如“map j：execute 2j <CR>”） |
| ：buffer（自动完成）               | 更改为不同的选项卡                                           |
| ：mksession                        | 从活动窗口中的当前选项卡创建一个新的会话                     |
| ：delsession（自动填充）           | 删除已保存的会话                                             |
| ：会话（自动填充）                 | 在新窗口中从保存的会话中打开选项卡                           |
| ：脚本                             | 在当前页面上运行JavaScript                                   |
| ：togglepin                        | 切换当前选项卡的引脚状态                                     |
| ：pintab                           | 固定当前选项卡                                               |
| ：unpintab                         | 取消固定当前选项卡                                           |


chrome 快捷键
## Windows 和 Linux版本的chrome

### 标签页和窗口快捷键

| 操作                                       | 快捷键                            |
| :----------------------------------------- | :-------------------------------- |
| 打开新窗口                                 | Ctrl + n                          |
| 在隐身模式下打开新窗口                     | Ctrl + Shift + n                  |
| 打开新的标签页，并跳转到该标签页           | Ctrl + t                          |
| 重新打开最后关闭的标签页，并跳转到该标签页 | Ctrl + Shift + t                  |
| 跳转到下一个打开的标签页                   | Ctrl + Tab 或 Ctrl + PgDn         |
| 跳转到上一个打开的标签页                   | Ctrl + Shift + Tab 或 Ctrl + PgUp |
| 跳转到特定标签页                           | Ctrl + 1 到 Ctrl + 8              |
| 跳转到最后一个标签页                       | Ctrl + 9                          |
| 在当前标签页中打开主页                     | Alt + Home                        |
| 关闭当前标签页                             | Ctrl + w 或 Ctrl + F4             |
| 关闭所有打开的标签页和浏览器               | Ctrl + Shift + w                  |
| 最小化当前窗口                             | Alt + 空格键 + n                  |
| 最大化当前窗口                             | Alt + 空格键 + x                  |
| 退出 Google Chrome                         | Ctrl + Shift + q 或 Alt + F4      |

### chrome 功能快捷键

| 操作                                                 | 快捷键                  |
| :--------------------------------------------------- | :---------------------- |
| 打开"菜单"                                           | Alt + f、Alt + e 或 F10 |
| 显示或隐藏书签栏                                     | Ctrl + Shift + b        |
| 打开书签管理器                                       | Ctrl + Shift + o        |
| 在新标签页中打开"历史记录"页                         | Ctrl + h                |
| 在新标签页中打开"下载内容"页                         | Ctrl + j                |
| 打开 Chrome 任务管理器                               | Shift + Esc             |
| 将焦点放置在 Chrome 工具栏中的第一项上               | Shift + Alt + t         |
| 在地址栏、书签栏（若显示）和页面内容之间向前切换焦点 | F6                      |
| 在地址栏、书签栏（若显示）和页面内容之间向后切换焦点 | Shift + F6              |
| 打开查找栏搜索当前网页                               | Ctrl + f 或 F3          |
| 跳转到与查找栏中搜索字词相匹配的下一条内容           | Ctrl + g                |
| 跳转到与查找栏中搜索字词相匹配的上一条内容           | Ctrl + Shift + g        |
| 打开"开发者工具"                                     | Ctrl + Shift + j 或 F12 |
| 打开"清除浏览数据"选项                               | Ctrl + Shift + Delete   |
| 在新标签页中打开 Chrome 帮助中心                     | F1                      |
| 使用其他帐户登录或进入隐身模式                       | Ctrl + Shift + m        |
| 打开反馈表单                                         | Ctrl + Shift + i        |

### 地址栏快捷键

| 操作                                                    | 快捷键                           |
| :------------------------------------------------------ | :------------------------------- |
| 使用默认搜索引擎进行搜索                                | 输入搜索字词并按 Enter 键        |
| 使用其他搜索引擎进行搜索                                | 输入搜索引擎名称并按 Tab 键      |
| 为网站名称添加 www. 和 .com，并在当前标签页中打开该网站 | 输入网站名称并按 Ctrl + Enter 键 |
| 为网站名称添加 www. 和 .com，并在新标签页中打开该网站   | 输入网站名称并按 Alt + Enter 键  |
| 跳转到地址栏                                            | Ctrl + l、Alt + d 或 F6          |
| 从页面中的任意位置搜索                                  | Ctrl + k 或 Ctrl + e             |

### 网页快捷键

| 操作                                           | 快捷键                         |
| :--------------------------------------------- | :----------------------------- |
| 打开选项以打印当前网页                         | Ctrl + p                       |
| 打开选项以保存当前网页                         | Ctrl + s                       |
| 重新加载当前网页                               | F5 或 Ctrl + r                 |
| 重新加载当前网页（忽略缓存的内容）             | Shift + F5 或 Ctrl + Shift + r |
| 停止加载网页                                   | Esc                            |
| 浏览下一个可点击项                             | Tab                            |
| 浏览上一个可点击项                             | Shift + Tab                    |
| 使用 Chrome 打开计算机中的文件                 | 按住 Ctrl + o 键并选择文件     |
| 显示当前网页的 HTML 源代码（不可修改）         | Ctrl + u                       |
| 将当前网页保存为书签                           | Ctrl + d                       |
| 将所有打开的标签页以书签的形式保存在新文件夹中 | Ctrl + Shift + d               |
| 开启或关闭全屏模式                             | F11                            |
| 放大网页上的所有内容                           | Ctrl 和 +                      |
| 缩小网页上的所有内容                           | Ctrl 和 -                      |
| 将网页上的所有内容恢复到默认大小               | Ctrl + 0                       |
| 向下滚动网页，一次一个屏幕                     | 空格键或 PgDn                  |
| 向上滚动网页，一次一个屏幕                     | Shift + 空格键或 PgUp          |
| 转到网页顶部                                   | 首页                           |
| 转到网页底部                                   | 末尾                           |
| 在网页上水平滚动                               | 按住 Shift 键并滚动鼠标滚轮    |
| 将光标移到文本字段中的上一个字词前面           | Ctrl + 向左箭头键              |
| 将光标移到文本字段中的上一个字词后面           | Ctrl + 向右箭头键              |
| 删除文本字段中的上一个字词                     | Ctrl + Backspace               |
| 将焦点移到通知上                               | Alt + n                        |
| 在通知中允许                                   | Alt + Shift + a                |
| 在通知中拒绝                                   | Alt + Shift + d                |
| 在当前标签页中打开主页                         | Alt + Home                     |

### 网页快捷键

| 操作                                   | 快捷键                                                       |
| :------------------------------------- | :----------------------------------------------------------- |
| 在当前标签页中打开链接（仅限鼠标）     | 将链接拖到标签页中                                           |
| 在新的后台标签页中打开链接             | 按住 Ctrl 键的同时点击链接                                   |
| 打开链接，并跳转到该链接               | 按住 Ctrl + Shift 键的同时点击链接                           |
| 打开链接，并跳转到该链接（仅使用鼠标） | 将链接拖到标签栏的空白区域                                   |
| 在新窗口中打开链接                     | 按住 Shift 键的同时点击链接                                  |
| 在新窗口中打开标签页（仅使用鼠标）     | 将标签页拖出标签栏                                           |
| 将标签页移至当前窗口（仅限鼠标）       | 将标签页拖到现有窗口中                                       |
| 将标签页移回其原始位置                 | 拖动标签页的同时按 Esc                                       |
| 将当前网页保存为书签                   | 将相应网址拖动到书签栏中                                     |
| 下载链接目标                           | 按住 Alt 键的同时点击链接                                    |
| 显示浏览记录                           | 右键点击"后退"箭头 返回 或"前进"箭头 下一个，或者点击并按住"后退"箭头 返回 或"前进"箭头 下一个 |
| 最大化或最小化窗口                     | 双击标签栏的空白区域                                         |
| 放大网页上的所有内容                   | 按住 Ctrl 键的同时向上滚动鼠标滚轮                           |
| 缩小网页上的所有内容                   | 按住 Ctrl 键的同时向下滚动鼠标滚轮                           |
