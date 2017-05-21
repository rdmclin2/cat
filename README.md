![](http://ww2.sinaimg.cn/large/006tNc79gy1fft77nr24kj31hc0m8791.jpg)

## 安装

```bash
$ hexo init Blog
$ cd Blog
$ npm install
$ npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
$ git clone git@github.com:rdmclin2/hexo-theme-cat.git
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `cat`:

```yaml
theme: cat

// 在归档页面显示所有文章
// 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
cd themes/cat
git pull
```

## License

MIT
