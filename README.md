### composer util
```
- composer.json 修改
"repositories": [
    {
      "type": "composer",
      "url": "https://mirrors.aliyun.com/composer/"
    },
    {
      "packagist": false
    },
    {
      "type": "git",
      "url": "git@github.com:thisisxiong/composerUtil.git"
    }
  ],
  
 - 使用 
 composer require xiong/say:dev-master
```
