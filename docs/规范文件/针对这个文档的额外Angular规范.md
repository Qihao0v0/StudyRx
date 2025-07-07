# 针对这个文档的额外 Angular 规范

我们规定这个仓库的 commit 使用 Angular 规范，但单纯的 Angular 规范并不足以描述一个学习资料仓库，故我们规定针对这个文档的额外 Angular 规范：

- build：对构建系统或者外部依赖项进行了修改
- ci：对CI配置文件或脚本进行了修改
- docs：改动说明文档、非学习资料本体的内容（如README）
- feat：增加新的特征
- fix：修复 bug，修改错误、笔误、格式问题
- pref：提高性能的代码更改
- refactor：既不是修复 bug 也不是添加特征的代码重构
- style：不影响代码含义的修改，比如空格、格式化、缺失的分号等
- test：增加确实的测试或者矫正已存在的测试
- add：对学习资料添加新的资料内容、文档章节等（相当于 feat）
- update：对已有文档内容进行更新（相当于 refactor/improve）
- meta：改动配置文件（如 mkdocs.yml、.gitignore）
- style：格式调整，无实质内容变化（如空格、换行）
- move：文件或目录结构调整
- remove：删除不必要的文档或内容