### 一个自己托付的项目，基于用户的推荐

### 目前依靠的数据集为movielens

### 目前思路为：
1. 对 movie-genres 矩阵进行 tf-idf 处理，得到 movie 的 genres 表达数值矩阵
2. 根据user-movie 及 movie-genres 得到 user 的 genres 表达数值矩阵
3. 暂未考虑到
