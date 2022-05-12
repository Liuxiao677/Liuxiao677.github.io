## 贡献指南
app 在设计的时候将法律法规和 app 本身分离开了, 只需要增加法条和修改 data.json 即可添加某部法律..
- 首先将法律法规按照 [法律法规模版](法律法规模版.md) 排版好，放入文件夹 `法律法规` 下合适的位置
- 使用脚本 `python3 scripts/update.py` （脚本会自动处理，将新增法律加入列表以及合适的位置）
- 提交更改，并提 pr

PS 如果你有发现某部法律不完整，有问题，或者需要新增某些，但又不会自己提 pr，你可以在提一个 issue，或者直接联系设置中我的邮箱，我会在下个版本修复或增加