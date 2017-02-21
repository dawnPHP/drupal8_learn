# chapter2

## atom编辑器相关链接：
 - https://atom.io/packages/markdown-preview
 - https://segmentfault.com/q/1010000004170163/a-1020000004181709
 - https://www.zhihu.com/question/22867204

## 用户手册目录
 - https://www.drupal.org/docs/user_guide/en/index.html

## 2.5 计划内容结构
https://www.drupal.org/docs/user_guide/en/planning-structure.html

目标：
计划站点内容结构，包括内容类型与子类型，每页包含的内容。

步骤：
1. 大脑风暴一下你的网站包含的内容。
2. 确定每一段内容最适合的实体类型。你要考虑内容放在哪、怎么用。比如，农村市场站点中，你想在侧栏展示时间、地点。对于该内容，用户自定义块就行了。
3. 每个内容实体内部，确定怎么分实体亚类更有意义。
4. 对于每个实体亚类，确定所需字段。比如供应商内容实体可能包含如下字段：供应商名字、网址url、图片和描述。
5. 决定需要哪些实体列表，这将是整个页面或者页面的小区域。
6. 每个实体亚类的字段，确定需要的数据类型（比如文本、格式化文本、日期、图片等等），以及允许的值类型。大多数字段是单值得，但是菜谱的作料字段就需要带有多个值。
7. 考虑哪个字段最适合做为实体分类。
8. 考虑哪个字段需要引用其他内容实体。


## 2.6 编辑工作流

### 什么是编辑工作流

  编辑工作流就是过程处理机构遵循的创建、预览、编辑、发布内容。

  按照组织的大小和流程，不容角色的很多人可能都是过程中的一部分。比如，内容创建者收集信息、写内容；编辑预览、编辑、修改内容，一旦满意就发布内容。

站点中，内容类型需一个发布、未发布的flag来记录工作流状态，可以在内容条目保存时设置。

 - 发布的内容所有访问者可见。
 - 未发布的内容只有被授权者可见。