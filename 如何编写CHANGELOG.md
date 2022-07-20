1. 格式

   ```markdown
   ## 1.0.1 (2022-07-22)
   - Added: xxxx
   - Changed: xxxx
   
   ## 1.0.0 (2022-07-21)
   - Added: xxxx
   - Changed: xxxx
   ```

2. 内容分类标识

   - Added: 添加的新功能
   - Changed: 功能变更
   - Deprecated: 不建议使用，未来会删掉
   - Removed: 删除了什么功能
   - Fixed: 修复的bug

3. 发布相关

   我们用-alpha表示此版本还没有发布。如果没有加-alpha表示此版本已发布。

   (1) 当提交代码时，更新日志中有没有-alpha结尾的版本，在最前面加一个新版本，例如

   ```markdown
   ## 1.0.2-alpha (2022-07-23)
   - Added: xxxx
   ```

   (2) 当提交代码时，更新日志中有-alpha结尾的版本，则在此版本的日志中追加即可。例如

   ```markdown
   ## 1.0.2-alpha (2022-07-24)
   - Added: xxxx
   - Changed: xxxx
   ```

   (3) 发布版本时，去掉要发布版本的-alpha标识。例如：

   ```markdown
   ## 1.0.2 (2022-07-25)
   - Added: xxxx
   - Changed: xxxx
   ```
