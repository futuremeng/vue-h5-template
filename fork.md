本项目fork自https://github.com/sunniejs/vue-h5-template，当https://github.com/sunniejs/vue-h5-template更新时，通过以下步骤获取更新
1. 查看是否添加了更新源
   ```
   git remote -v
   ```
2. 添加更新源，本项目fork自https://github.com/sunniejs/vue-h5-template
   ```
   git remote add upstream https://github.com/sunniejs/vue-h5-template
   ```
3. 从源更新
   ```
   git fetch upstream
   ```
4. 合并源的分支
   ```
   git merge upstream/vue-h5-template
   ```
