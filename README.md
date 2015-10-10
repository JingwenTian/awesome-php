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

- **PHP书籍(PHP Books)**

    - [Modern PHP](http://shop.oreilly.com/product/0636920033868.do) - 作者是[PHP 之道](http://www.phptherightway.com/)的发起人和[Slim框架](http://www.slimframework.com/)的作者
        - [Modern PHP（中文版）](http://about.ac/books/modern-php/)

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

##持续集成( Continuous Integration )
>持续集成的库和应用

- [Travis CI](https://travis-ci.org/) - 一个持续集成的平台
- [SemaphoreCI](https://semaphoreapp.com/) - 一个给开源程序和私有项目的持续集成平台
- [PHPCI](http://www.phptesting.org/) - 一个PHP的开源持续集成平台
- [Sismo](http://sismo.sensiolabs.org/) - 一个持续的测试服务器库
- [Jenkins](http://jenkins-ci.org/) - PHP支持的持续集成平台
- [JoliCi](https://github.com/jolicode/JoliCi) - PHP开发的由Docker支持的持续集成客户端


##文档( Documentation )
>生成项目文档的库

- [Sami](https://github.com/fabpot/Sami) - 一个API文档生成器
- [APIGen](https://github.com/apigen/apigen) - 另一个API文档生成器
- [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - 文档生成器
- [phpDox](http://phpdox.de/) - 一个PHP项目的文档生成器（不仅仅是API文档）

##安全( Security )
>用于生成安全的随机数、加密数据、扫描漏洞的库

- [HTML Purifier](https://github.com/ezyang/htmlpurifier) - 一个标准的HTML过滤器
- [RandomLib](https://github.com/ircmaxell/RandomLib) - 生成随机数和随机字符串的库
- [True Random](https://github.com/pixeloution/true-random) - 使用www.random.org生成随机数的库
- [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - 一个PHP安全库
- [PHPSecLib](http://phpseclib.sourceforge.net/) - 一个纯的PHP安全通信库
- [TCrypto](https://github.com/timoh6/TCrypto) - 一个简单的键值加密存储库
- [PHP IDS](https://github.com/PHPIDS/PHPIDS) - 一个结构化的PHP安全层
- [PHP SSH](https://github.com/Herzult/php-ssh) - 面向对象的SSH包装库
- [IniScan](https://github.com/psecio/iniscan) - 一个扫描PHP INI文件安全的工具
- [SensioLabs Security Check](https://security.sensiolabs.org/) -  一个根据安全建议检查Composer依赖的Web工具
- [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - 用于Web应用的集成渗透测试工具

##密码( Passwords )
>处理和存储密码的库和工具

- [Password Compat](https://github.com/ircmaxell/password_compat) - 一个用于新的PHP5.5密码功能的兼容库
- [phpass](http://www.openwall.com/phpass/) - 一个便携式密码哈希框架
- [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - 一个用于生成和验证密码的库
- [Password Policy](https://github.com/ircmaxell/password-policy) - 一个PHP和JavaScript的密码规则库
- [Password Validator](https://github.com/jeremykendall/password-validator) - 验证和升级密码哈希的库
- [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - 一个基于Zxcvbn JS的PHP显示密码强度估计库
- [GenPhrase](https://github.com/timoh6/GenPhrase) - 一个生成安全随机口令的库

##代码分析( Code Analysis )
>用于分析、解析和操作代码库的工具

- [PHP Parser](https://github.com/nikic/PHP-Parser) - 一个PHP编写的PHP解析器
- [PHPPHP](https://github.com/ircmaxell/PHPPHP) - 一个PHP实现的PHP虚拟机
- [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - PHP的沙盒环境
- [Dissect](https://github.com/jakubledl/dissect) - 词法和语法分析的工具集合
- [PHP Mess Detector](http://phpmd.org/) - 一个扫描代码bug、次佳代码和未使用参数的库
- [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - 一个检测PHP、CSS和JS代码标准冲突的库
- [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - 一个检测复制和粘贴代码的库
- [PHP Analyser](https://github.com/scrutinizer-ci/php-analyzer) - 一个分析PHP代码中错误的库
- [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - 一个代码标准库
- [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - 用于分析和修改PHP源代码的库
- [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - 一个静态测量库
- [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - 一个用于重构PHP代码的命令行工具
- [UBench](https://github.com/devster/ubench) - 一个简单的小型基准测试库
- [Athletic](https://github.com/polyfractal/athletic) - 一个基于标注的基准测试库
- [Mondrian](https://github.com/Trismegiste/Mondrian) - 使用图论的代码分析工具
- [Scrutinizer](https://scrutinizer-ci.com/) - 检查PHP代码的Web工具
- [PHPLOC](https://github.com/sebastianbergmann/phploc) - 一个快速评估PHP项目大小的工具
- [PHPCheckstyle](https://github.com/jbrooksuk/phpcheckstyle) - 一个帮助遵守特定代码规则的工具
- [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - 一个创建可定制型依赖关系图表的工具
- [Code Climate](http://codeclimate.com/) - 自动化的code review

##结构( Architectural )
>有关于设计模式,编程规范以及代码组织方式的库

- [PHP Option](https://github.com/schmittjoh/php-option) - 一个PHP选项类型的库
- [Ruler](https://github.com/bobthecow/Ruler) - 一个简单的无状态的产生环境规则的引擎
- [Finite](http://yohan.giarel.li/Finite) - 一个简单的PHP有限状态机
- [Compose](https://github.com/igorw/compose) - 一个功能组合库
- [Monad PHP](https://github.com/ircmaxell/monad-php) - 一个简单Monad库
- [Patchwork](http://antecedent.github.io/patchwork/) - 一个重新定义用户的函数库
- [Galapagos](https://github.com/endel/galapagos) - 语言转换进化
- [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - 一个使用PHP实现的设计模式实例库
- [Functional PHP](https://github.com/lstrojny/functional-php) - 一个函数式编程库
- [Lib Accessor](https://github.com/phine/lib-accessor) - 一个简化访问的库
- [Iter](https://github.com/nikic/iter) - 一个使用生成器提供迭代原语的库

##调试和性能( Debugging and Profiling )
>调试代码的库和工具

- [xDebug](https://github.com/xdebug/xdebug) - 一个PHP的调试和分析工具
- [PHP Debug Bar](http://phpdebugbar.com/) - 一个调试工具条
- [PHP Console](https://github.com/Seldaek/php-console) - Web调试控制台
- [Barbushin PHP Console](https://github.com/barbushin/php-console) -  一个使用Google Chrome的Web调试控制工具
- [PHPDBG](http://phpdbg.com/) - 一个交互性的PHP调试器
- [Tracy](https://github.com/nette/tracy) - 一个简单的错误检测、日志和时间测量库
- [Z-Ray](http://www.zend.com/en/products/server/z-ray) - 一个调试和性能分析的工具
- [xHprof](https://github.com/phacility/xhprof) - Facebook开源的PHP性能评测工具
- [Blackfire.io](http://blackfire.io) - 一个低开销的代码探查器
- [Kint](https://github.com/raveren/kint) - 一个调试和性能分析的工具

##构建工具( Build Tools )
>项目构建和自动化工具

- [Go](https://github.com/herrera-io/php-go) - 一个简单的PHP构建工具
- [Bob](https://github.com/CHH/bob) - 一个简单的项目自动化工具
- [Phake](https://github.com/jaz303/phake) -  一个PHP克隆库
- [Box](https://github.com/kherge/Box) - 用来构建PHAR文件的工具
- [Phing](http://www.phing.info/) - 依据Apache Ant的PHP项目构建系统

##任务运行器( Task Runners )
>自动运行任务的库

- [Task](http://taskphp.github.io/) - 依据Grunt和Gulp的纯PHP任务运行器
- [Robo](https://github.com/Codegyre/Robo) - 面向对象的PHP任务运行器
- [Bldr](http://bldr.io/) - 构建在Symfony组件上的PHP任务运行器

##导航( Navigation )
>构建导航结构的工具

- [KnpMenu](https://github.com/KnpLabs/KnpMenu) - 一个菜单库
- [Cartographer](https://github.com/tackk/cartographer) - 一个站点地图生成库

##资源管理( Asset Management )
>用于管理、压缩和最小化网站资源的工具

- [Assetic](https://github.com/kriswallsmith/assetic) - 一个资源管理的管道库
- [Pipe](https://github.com/CHH/pipe) - 另一个资源管理的管道库
- [Munee](https://github.com/meenie/munee) - 一个资源优化库
- [JShrink](https://github.com/tedivm/JShrink) - 一个JavaScript的压缩库
- [Puli](https://github.com/webmozart/puli) - 一个检测资源绝对路径的库

##地理定位( Geolocation )
>使用经纬度编码地址的库

- [GeoCoder](http://geocoder-php.org/) - 一个地理编码库
- [GeoTools](https://github.com/php-loep/Geotools) - 一个地理工具相关的库
- [PHPGeo](https://github.com/mjaschen/phpgeo) - 一个简单的地理库
- [GeoJSON](https://github.com/jmikola/geojson) - 一个GeoJSON的实现


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

