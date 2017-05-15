# 本文介绍: 应用语言环境的判断

>使用 `app.getLocale()` 接收返回语言环境值

Electron 通过 Chromium的 `l10n_util` 库获取应用的语言环境。

以下是语言列表:

|  语言代码 | 语言名称 |
|---------------|---------------|
| af | 南非荷兰语 |
| am | 阿姆哈拉语 |
| ar | 阿拉伯语 |
| az | 阿塞拜疆 |
| be | 白俄罗斯 |
| bg | 保加利亚语 |
| bh | 比哈里 |
| bn | 孟加拉语 |
| br | 布列塔尼 |
| bs | 波斯尼亚语 |
| ca | 加泰罗尼亚语 |
| co | 科西嘉 |
| cs | 捷克语 |
| cy | 威尔士语 |
| da | 丹麦语 |
| de | 德语 |
| de-AT | 德语(奥地利) |
| de-CH | 德语(瑞士) |
| de-DE | 德国(德国) |
| el | 希腊语 |
| en | 英文 |
| en-AU | 英语(澳大利亚) |
| en-CA | 英语(加拿大) |
| en-GB | 英语(英国) |
| en-NZ | 英语(新西兰) |
| en-US | 英文(US) |
| en-ZA | 英语(南非) |
| eo | 世界语 |
| es | 西班牙语 |
| es-419 | 西班牙语(拉丁美洲) |
| et | 爱沙尼亚语 |
| eu | 巴斯克语 |
| fa | 波斯语 |
| fi | 芬兰语 |
| fil | 菲律宾 |
| fo | 法罗语 |
| fr | 法语 |
| fr-CA | 法语(加拿大) |
| fr-CH | 法语(瑞士) |
| fr-FR | 法语(法国) |
| fy | 弗里斯兰语 |
| ga | 爱尔兰 |
| gd | 苏格兰盖尔语 |
| gl | 加利西亚 |
| gn | 瓜拉尼 |
| gu | 古吉拉特语 |
| ha | 豪萨 |
| haw | 夏威夷语 |
| he | 希伯来语 |
| hi | 印度语 |
| hr | 克罗地亚语 |
| hu | 匈牙利语 |
| hy | 亚美尼亚 |
| ia | 国际语 |
| id | 印尼语 |
| is | 冰岛语
| it | 意大利语 |
| it-CH | 意大利语(瑞士) |
| it-IT | 意大利(意大利) |
| ja | 日语 |
| jw | 爪哇 |
| ka | 格鲁吉亚语 |
| kk | 哈萨克斯坦
| km | 柬埔寨 |
| kn | 加纳达 |
| ko | 韩语 |
| ku | 库尔德语 |
| ky | 吉尔吉斯斯坦 |
| la | 拉丁语 |
| ln | Lingala |
| lo | Laothian |
| lt | 立陶宛语 |
| lv | 拉脱维亚语
| mk | 马其顿 |
| ml | 马拉雅拉姆
| mn | 蒙古语 |
| mo | 摩尔多瓦人 |
| mr | 马拉地 |
| ms | 马来西亚 |
| mt | 马耳他语 |
| nb | 挪威语(Bokmal) |
| ne | 尼泊尔语
| nl | 荷兰语 |
| nn | 挪威语(Nynorsk) |
| no | 挪威语 |
| oc | 奥克西唐
| om | Oromo |
| or | Oriya |
| pa | 旁遮普语
| pl | 波兰语 |
| ps | Pashto |
| pt | 葡萄牙语 |
| pt-BR | 葡萄牙语(巴西) |
| pt-PT | 葡萄牙语(葡萄牙) |
| qu | 盖丘亚 |
| rm | 罗曼什 |
| ro | 罗马尼亚语 |
| ru | 俄语 |
| sd | 信德 |
| sh | 塞尔维亚-克罗地亚语 |
| si | 僧伽罗语 |
| sk | 斯洛伐克语 |
| sl | 斯洛文尼亚语 |
| sn | Shona |
| so | 索马里 |
| sq | 阿尔巴尼亚语 |
| sr | 塞尔维亚语 |
| st | Sesotho |
| su | Sundㄧese |
| sv | 瑞典语 |
| sw | 斯瓦希里语
| ta | 泰米尔语
| te | 泰卢固语 |
| tg | 塔吉克斯坦
| th | 泰语 |
| ti | Tigrinya |
| tk | 土库曼斯坦
| to | 汤加 |
| tr | 土耳其语 |
| tt | 鞑靼 |
| tw | Twi |
| ug | 维吾尔族 |
| uk | 乌克兰语 |
| ur | 乌尔都语 |
| uz | 乌兹别克语 |
| vi | 越南语 |
| xh | Xhosa |
| i | 意第绪语 |
| yo | 约鲁巴 |
| zh | 中文 |
| zh-CN | 中文(简体) |
| zh-TW | 中文(繁体) |
| zu | 祖鲁 |