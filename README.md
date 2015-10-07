# awesome-php
收集整理一些常用的PHP类库, 资源以及技巧. 以便在工作中迅速的查找所需...

---

- 这个列表中的内容有来自 [awesome-php](https://github.com/ziadoz/awesome-php) 的翻译, 有来自开发者周刊以及个人的积累等.
- 一个前端组件的列表 [awesome-frontend](https://github.com/JingwenTian/awesome-frontend) 推荐

---

##学习资源
>PHP相关的有参考价值的社区,博客,网站,文章,书籍,视频等资源

- **PHP网站(PHP Websites)**

    - [PHP The Right Way](http://www.phptherightway.com/) 一个PHP实践的快速参考指导

---

##依赖管理( Dependency Management )
>用于依赖管理的包和框架

- [Composer](https://getcomposer.org/) / [Packagist](https://packagist.org/) - 一个包和依赖管理器.
- [Composer Installers](https://github.com/composer/installers) - 一个多框架Composer库安装器
- [pickle](https://github.com/FriendsOfPHP/pickle) - PHP扩展安装器
- [Melody](http://melody.sensiolabs.org/) - A tool to build one file Composer scripts.

##框架( Frameworks )
>Web开发框架

- [Symfony2](http://symfony.com/) - 由独立组件构成的框架(SP2)
- [Zend Framework 2](http://framework.zend.com/) - 同样是由独立组件构成的框架(ZF2)
- [Laravel 5](http://laravel.com/) - 简洁优雅的PHP Web开发框架(L5)
- [Aura PHP](http://auraphp.com/) - 独立组件的框架
- [Yii2](https://github.com/yiisoft/yii2/) - 用于开发大型Web应用的高性能PHP框架
- [Nette](http://nette.org/) - 同样是由独立组件构成的框架
- [PPI Framework 2](http://www.ppi.io/) - 一个交互性的框架
- [CakePHP](http://cakephp.org/) - 一个高效的应用开发框架(CP)
- [Phalcon](http://phalconphp.com/en/) - 一个作为C扩展的框架
- [Yaf](http://php.net/manual/zh/book.yaf.php) - 鸟哥的C扩展的框架

##组件( Components )

- [Aura Components](http://auraphp.com/) - 一个PHP5.4的组件包
- [Hoa Project](http://hoa-project.net/En/) - 一个PHP组件集合

##微框架( Micro Frameworks )
>微型框架和路由

- [Silex](http://silex.sensiolabs.org/) - 基于Symphony2组件的微型框架
    - [Silex Skeleton](https://github.com/fabpot/Silex-Skeleton) - 用于Silex的项目框架
    - [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - 用于Silex的Web调试工具条
- [Slim](http://www.slimframework.com/) - 另一个简单的微型框架
    - [Slim Skeleton](https://github.com/codeguy/Slim-Skeleton) - 用于Slim的框架
    - [Slim View](https://github.com/codeguy/Slim-Views) - Slim的自定义视图集
    - [Slim Middleware](https://github.com/codeguy/Slim-Middleware) - Slim的自定义中间件集合
    - [SlimMVC-Skeleton](https://github.com/JingwenTian/SlimMVC-Skeleton) - Slim基础上实现了MVC及一些组件
- [Bullet PHP](http://bulletphp.com/) - 用于构建REST APIs的微型框架
- [Lumen](http://lumen.laravel.com/) - 基于Laravel的微型框架
- [Proton](https://github.com/alexbilbie/Proton) - 一个微型PHP框架

##路由( Routers )

- [Fast Route](https://github.com/nikic/FastRoute) - 一个高效路由库
- [Route](https://github.com/thephpleague/route) - 基于Fast Route的路由库
- [Pux](https://github.com/c9s/Pux) - 另一个高效的路由库
- [Klein](https://github.com/chriso/klein.php) - 一个灵活的路由库

##模板引擎( Templating )
>模板和词法分析的库与工具

- [Twig](http://twig.sensiolabs.org/) - 一种综合的模板语言
- [Twig Cache Extension](https://github.com/asm89/twig-cache-extension) - 用于Twig的模板片段缓存库
- [Mustache](https://github.com/bobthecow/mustache.php) - PHP实现的Mustache模板语言
- [Phly Mustache](https://github.com/weierophinney/phly_mustache) - 另一个PHP实现的Mustache模板语言
- [MtHaml](https://github.com/arnaud-lb/MtHaml) - PHP实现的HAML模板语言
- [PHPTAL](http://phptal.org/) - PHP实现的TAL模板语言
- [Plates](http://platesphp.com/) - 一个原始的PHP模板库
- [Lex](https://github.com/pyrocms/lex) - 一个轻量级模板解析器

##静态站生成器( Static Site Generators )
>生成Web页面内容的预处理工具

- [Sculpin](http://sculpin.io/) - 将Markdown和Twig转换为静态HTML的工具
- [Phrozn](http://phrozn.info/) - 另一款将Textile、Markdown和Twig转为HTML的工具

##HTTP
>用于HTTP和抓取网站的库

- [Guzzle](https://github.com/guzzle/guzzle) - 一个完整的HTTP客户端
- [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个HTTP客户端
- [Requests](https://github.com/rmccue/Requests) - 一个简单的HTTP库
- [HTTPFul](https://github.com/nategood/httpful) - 一个链式HTTP客户端
- [Goutte](https://github.com/fabpot/Goutte) - 一个简单的Web抓取器
- [PHP VCR](http://php-vcr.github.io/) - 一个录制和回放HTTP请求的库

##中间件( Middlewares )
>用于构建应用的类库的中间件

## URL
>解析URL的库

- [Purl](https://github.com/jwage/purl) - 一个URL操作库
- [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - 一个本地的后缀解析器
- [Url](https://github.com/thephpleague/url) - 一个简单的URL操作库

##邮件( Email )
>用于发送和解析Email的库

- [SwiftMailer](http://swiftmailer.org/) - 一个邮件程序的解决方案
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - 另一个邮件程序的解决方案
- [Fetch](https://github.com/tedivm/Fetch) - 一个IMAP库
- [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - 一个邮件回复解析器库
- [Stampie](https://github.com/henrikbjorn/Stampie) - 关于邮件服务的库，比如SendGrid、PostMark、MailGun和Mandrill
- [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - 邮件模板中一个内联的CSS库
- [Email Validator](https://github.com/nojacko/email-validator) - 一个小巧的邮箱验证库

##文件操作( Files )

##依赖注入( Dependency Injection )

##图像( Imagery )

##测试( Testing )

##文档( Documentation )

##安全( Security )

##密码( Passwords )

##调试( Debuging )

##日期与时间( Date and Time )

##日志( Logging )

##PDF

##Office

##数据库( Database )

##非关系型数据库( NoSQL )

##队列( Queue )

##搜索( Search )

##命令行( Command Line )

##鉴权( Authentication and Authorization )

##标记( Markup )

##字符串( Strings )

##数字( Numbers )

##过滤和验证( Filtering ang Validation )

##API

##缓存( Caching )

##数据结构和存储( Data Structure and Storage )

##通知( Notifications )

##部署( Deployment )

