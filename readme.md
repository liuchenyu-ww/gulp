#### 全局安装

```
npm install -g gulp
```

#### 本地安装
```
npm install --save-dev gulp
```

ps:要全局安装完再本地安装，这样的做法是为了版本的灵活性


```
// 最基本目录

├── gulpfile.js
├── node_modules
│ └── gulp
└── package.json


// gulpfile.js
// 默认任务名为default,如果是其他名字在执行的时候要指定名字

var gulp = require('gulp');

gulp.task('default', function () {
  console.log(1)
})
```


#### 运行

```
// 默认任务名
$ gulp

// 指定任务名
$ gulp 任务名
```

#### API

gulp.task()

gulp.src()

gulp.dest()

gulp.watch()