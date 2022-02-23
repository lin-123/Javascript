# 贡献指南

## 操作步骤

1. `sh script.sh update` 更新 upstream 代码到本地， 会把本地 README.md 变成 README.cn.md
2. 对比 README.md 更新翻译内容
3. `sh script.sh store` 恢复文件： README.md -> README.upstream.md;  README.cn.md -> README.md


## idea

- 有个干净的分支，跟踪线上的更新
- 根据更新来翻译对应内容

创建一个 follow 分支， 用于跟踪 upstream

1. git branch master 用于跟踪upstream
2. git diff master upstream/master README.md  对比文件差异
3. 修改 cn 分支下 README.md
