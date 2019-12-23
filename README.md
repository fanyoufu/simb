## 功能

制作一个简单的，能把本地的 markdown 文件生成静态博客的系统

## 目录结构

- course
  你的文章目录。其下的每一个文件夹表示一个分类。
  .md 文件的格式：`01_中文名字_YYYYMMDD.md`
  其中：
  - 01 表示文章编号
  - YYYYMMDD 表示最后修改日期
  - 中文名字表示这篇文章的中文名字，它会出现在文章列表中
- server
nodejs代码

- dist
渲染成功的静态页面

### 命令
#### gulp 
在根目录下运行 gulp 命令，自动监听 md 文件夹下的所有.md 文件的变化，并自动生成.html 文件。自动监听less 文件的变化并自动生成css。

#### npm run
列出所有可以执行的脚本。


### 注意
如果给package.json中的对象中的最后一个属性值添加"," 则会报错。  
