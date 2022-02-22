# 贡献指南

## 操作步骤

1. `sh script.sh update` 更新 upstream 代码到本地， 会把本地 README.md 变成 README.cn.md
2. 对比 README.md 更新翻译内容
3. `sh script.sh store` 恢复文件： README.md -> README.upstream.md;  README.cn.md -> README.md
