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
>关于文件处理和MIME类型检查

- [Gaufrette](https://github.com/KnpLabs/Gaufrette) - 一个文件流的抽象层
- [Flysystem](https://github.com/FrenkyNet/Flysystem) - 另一个文件流的抽象层
- [Canal](https://github.com/dflydev/dflydev-canal) - 一个检查互联网媒体类型的库
- [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - 一个解析Apache MIME类型的库
- [Ferret](https://github.com/versionable/Ferret) - 一个MIME检测库
- [Hoa Mime](https://github.com/hoaproject/Mime) - 另一个MIME检测库
- [Lurker](https://github.com/henrikbjorn/Lurker) - 一个资源跟踪库
- [PHP File Locator](https://github.com/herrera-io/php-file-locator) - 一个在大型项目中定位文件的库
- [PHP FFmpeg](https://github.com/alchemy-fr/PHP-FFmpeg/) - 一个用于FFmpeg视频包装的库
- [CSV](https://github.com/thephpleague/csv) - 一个CSV数据操作库

##流( Stream )
>处理流的库

- [Streamer](https://github.com/fzaninotto/Streamer) - 一个简单的面向对象流包装库

##依赖注入( Dependency Injection )
>实现依赖注入设计模式的库

- [Pimple](http://pimple.sensiolabs.org/) - 一个小的依赖注入容器
- [Auryn](https://github.com/rdlowrey/Auryn) - 另一个小的依赖注入容器
- [Container](https://github.com/thephpleague/container) - 另一个灵活的依赖注入容器
- [PHP DI](http://php-di.org/) - 一个使用标注实现的依赖注入
- [Acclimate](https://github.com/symfony/DependencyInjection) - 依赖注入容器和服务定位器的通用接口
- [Symfony DI](https://github.com/symfony/DependencyInjection) - 一个的依赖注入组件(SF2)

##图像( Imagery )
>处理图像的库

- [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - 一个图像处理库
- [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - 另一个图像处理库
- [Intervention Image](https://github.com/Intervention/image) - 同样还是一个图像处理库
- [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - 一个提取GIF动画帧信息的库
- [GIF Creator](https://github.com/Sybio/GifCreator) - 从多幅图片中创建GIF动画的库
- [Image With Text](https://github.com/nmcteam/image-with-text) - 在图像中嵌入文本的库
- [Color Extractor](https://github.com/php-loep/color-extractor) - 从图像中提取颜色的库
- [Glide](https://github.com/thephpleague/glide) - 一个按需的图片处理库
- [Image Optimizer](https://github.com/psliwa/image-optimizer) - 一个优化图片的库

##测试( Testing )
>测试代码库和生成测试数据的库

- [PHPUnit](https://github.com/sebastianbergmann/phpunit) - 一个单元测试框架
- [DBUnit](https://github.com/sebastianbergmann/dbunit) - PHPUnit的代码测试库
- [ParaTest](https://github.com/brianium/paratest) - PHPUnit的并行测试库
- [PHPSpec](https://github.com/phpspec/phpspec) - 根据规范的单元测试库
- [Codeception](https://github.com/Codeception/Codeception) - 一个全栈测试框架
- [AspectMock](https://github.com/Codeception/AspectMock) - PHPUnit/Codeception的模拟框架
- [Atoum](https://github.com/atoum/atoum) - 一个简单的测试库
- [Mockery](https://github.com/padraic/mockery) - 一个用于测试的模拟对象库
- [Phake](https://github.com/mlively/Phake) - 另一个用于测试的模拟对象库
- [Prophecy](https://github.com/phpspec/prophecy) - 一个强大的模拟框架
- [Faker](https://github.com/fzaninotto/Faker) - 一个伪数据生成库
- [Samsui](https://github.com/mauris/samsui) - 另一个伪数据生成库
- [Alice](https://github.com/nelmio/alice) - 用于生成复杂数据的库
- [Behat](http://behat.org/) - 一个行为驱动开发（BDD）的测试框架
- [Pho](https://github.com/danielstjules/pho) - 另一个行为驱动开发的测试框架
- [Mink](http://mink.behat.org/) - Web验收测试
- [HTTP Mock](https://github.com/InterNations/http-mock) - 一个在单元测试中模拟HTTP请求的库
- [VFS Stream](https://github.com/mikey179/vfsStream) - 一个用于测试的虚拟文件系统流包装
- [VFS](https://github.com/adlawson/vfs.php) - 另一个用于测试的虚拟文件系统
- [Locust](http://locust.io/) - 一个Python开发的现代负载测试库
- [Peridot](https://github.com/peridot-php/peridot) - 一个事件驱动的测试框架

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

