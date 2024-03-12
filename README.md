# wu-js-utils(函数库)

## 概述

在开发中，我们经常会将一些常用的代码块、功能块进行封装，为的是更好的复用。那么，被抽离出来独立完成功能，通过 API 或配置项和其他部分交互，便形成了插件(工具函数)。
下面这些是我在工作中积累的一些常用的前端开源工具函数，需要读者根据自己的实际业务需求进行 install 安装,根据业务需求选用，涵盖率 80%以上，欢迎留言交流和补充。^\_^

另外，不要重复造轮子，把精力放在业务逻辑上！

## Install(安装)

npm install wu-js-utils --save

## Usage(使用)

    1、防抖节流

    2、深拷贝

## 如何使用
``` language
import { deepCopy } from 'wu-js-utils';
```
``` language
const obj = {
  a: 1,
  b: '2'
};
const text = deepCopy(obj);
```
## 欢迎大家提 PR 扩充函数库，为开源社区贡献自己一份力
git仓库连接：https://github.com/Wukingbow/js-common-utils

提 Pr 步骤  
1、src 底下创建自己模块函数的文件夹  
2、函数模块包含 markdow 说明，有自己测试用例（必须）  
3、根部 index.js 导出函数  
4、packjson keywords 里写自己函数关键字  
5、npm test 跑测试用例  
6、不要修改 packjson 版本号，版本号为线上最新用户使用版本  
7、Pull requests 测试用例过后，静等作者合代码  
8、代码合并后，作者会及时发布在 npm 上，更新修复版本

## 我的博客

https://wukingbow.github.io

## License
