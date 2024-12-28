| 参数                         | 解释                                                              | 补充说明                                                                                                                 |
| :--                          | :--                                                               | :--                                                                                                                      |
| version                      | 版本号                                                            |                                                                                                                          |
| name                         | 主题名称，可使用中文                                              | 网页设计工具处会随机生成                                                                                                 |
| isDark                       | 分类：浅色主题或深色主题                                          |                                                                                                                          |
| backgroundColor              | 开启“按键边框border”后的键盘背景配色                            | 会被剪贴板、设置等界面复用，设置透明值后会导致部分app下显示背后内容                                                      |
| barColor                     | 无“按键边框border”下的候选工具栏配色                            |
| keyboardColor                | 无“按键边框border”下主键盘区的背景配色                          | 适当设置透明值，过高会导致部分app下显示背后内容                                                                                  |
| keyBackgroundColor           | 开启“按键边框border” 后的字母键背景配色                         | 设置界面按钮背景配色复用此值；九宫数字键背景配色复用此值；文本编辑界面方向键背景配色复用此值                             |
| keyTextColor                 | 字母键上的文本配色                                                | 有、无边框情况下均复用此值；空格键上文本配色复用此值；剪贴板条目、设置界面文本配色复用此值                               |
| altKeyBackgroundColor        | Shift键、数字切换键、逗号键、句号键、删除键、语言切换键的背景配色 | 仅在开启“按键边框border”之后有效；九宫数字界面的加减乘除键复用此值；文本编辑区全选、复制、粘贴、删除键背景配色复用此值 |
| altKeyTextColor              | Shift键、数字切换键、逗号键、句号键、删除键、语言切换键的文本配色 | 无边框下复用，同时复用于字母键上的数字及符号处                                                                           |
| accentKeyBackgroundColor     | 回车键背景配色                                              |                                                                                                                          |
| accentKeyTextColor           | 回车键文本配色                                              |                                                                                                                          |
| keyPressHighlightColor       | 按键水波纹效果的配色                                              | 一般不做修改，设置后的某些手机上的显示动画会比较慢                                                                       |
| keyShadowColor               | 开启“按键边框border”情况下各键的底部阴影配色                    | 建设适当增加透明值                                                                                                       |
| popupBackgroundColor         | 点击字母键时弹出效果的背景配色                                    | 复用：长按字母键弹出符号候选时背景配色                                                                               ；建议适当设置透明值，避免与背后内容重叠   |
| popupTextColor               | 点击字母键时弹出效果的文本配色                                    | 复用：长按字母键弹出符号候选时文本配色                                                                                   |
| spaceBarColor                | 无“按键边框border” 时的空格键配色                               |                                                                                                                          |
| dividerColor                 | 候选词分割线配色                                                  | 无“按键边框border” 时“文本编辑”界面复用此值                                                                         ；建议适当设置透明值 |
| clipboardEntryColor          | 剪贴板条目背景配色                                                |                                                                                                                          |
| genericActiveBackgroundColor | 长按字母键弹出符号选择时，被选中符号的背景配色                    |                                                                                                                          |
| genericActiveForegroundColor | 长按字母键弹出符号选择时，被选中符号的符号配色                    |                                                                                                                          |
| backgroundImage              | 仅在有背景图片时有此值                                            | 加入背景图时，会增加两个指向图片路径的路径参数                                                                           |

