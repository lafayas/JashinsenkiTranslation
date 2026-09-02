将此 android-cache 文件夹整体上传到仓库 lafayas/JashinsenkiTranslation 的 main 分支根目录。
助手会读取：
https://raw.githubusercontent.com/lafayas/JashinsenkiTranslation/main/android-cache/index.json

每次官方游戏更新后，请用 tools/build_pack.ps1 生成新版本缓存包，并将新的 index.json 与 packs/*.zip 一起提交。终端用户无需选择 ZIP；他们只需打开助手并点击“一键从 GitHub 下载并导入汉化”。
