# awesome-php
收集整理一些常用的PHP类库, 资源以及技巧. 以便在工作中迅速的查找所需...

---

- 这个列表中的内容有来自 [awesome-php](https://github.com/ziadoz/awesome-php) 的翻译, 有来自开发者周刊以及个人的积累等.
- 一个前端组件的列表 [awesome-frontend](https://github.com/JingwenTian/awesome-frontend) 推荐

---

## 学习资源
>PHP相关的有参考价值的社区,博客,网站,文章,书籍,视频等资源

- **PHP网站(PHP Websites)**

    - [PHP The Right Way](http://www.phptherightway.com/) - 一个PHP实践的快速参考指导
    - [PHP Best Practices](https://phpbestpractices.org/) - 一个PHP最佳实践
    - [Clean Code PHP](https://github.com/jupeter/clean-code-php) - 一个PHP 编码标准
    - [PHP Weekly News](http://www.phpweekly.com/archive.html) - 一个PHP 周刊
    - [Securing PHP](http://securingphp.com/) - 有关PHP安全相关
    - [PHP FIG](http://www.php-fig.org/) - PHP框架交互小组
        - [PSR 中文翻译](https://psr.phphub.org)
    - [PHP School](http://www.phpschool.io/) - 一个开源的PHP学习资源
    - [PHPTrends](http://phptrends.com/) - 一些快速发展的PHP类库检索
    - [PHP 开发者实践](https://ryancao.gitbooks.io/php-developer-prepares/content/)
    
- **其他网站(Other Websites)**

    - [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - 一个开源软件安全社区
    - [WebSec IO](https://websec.io/) - 一个web 安全社区
    - [Semantic Versioning](http://semver.org/lang/zh-CN/) - 语义化版本
    - [Atlassian Git Tutorials](https://www.atlassian.com/git/) - 一系列的Git教程
    - [Servers for Hackers ](https://serversforhackers.com/) - 有关服务器运维相关
    - [be-a-professional-programmer](https://github.com/stanzhai/be-a-professional-programmer) - 成为专业程序员路上用到的各种优秀资料、神器及框架

- **PHP书籍(PHP Books)**

    - [Modern PHP](http://shop.oreilly.com/product/0636920033868.do) - 作者是[PHP 之道](http://www.phptherightway.com/)的发起人和[Slim框架](http://www.slimframework.com/)的作者
        - [Modern PHP（中文版）](http://about.ac/books/modern-php/)
    - [PHP Pandas](http://daylerees.com/php-pandas/) 
    - [ppts_for_php2017](https://github.com/devlinkcn/ppts_for_php2017) - 2017 第三届PHP全球开发者大会PPT/Keynote

- **其他书籍(Other Books)**

    - [The Linux Command Line](http://linuxcommand.org/) - Linux 命令行教程

---

## 依赖管理( Dependency Management )
>用于依赖管理的包和框架

- [Composer](https://getcomposer.org/) / [Packagist](https://packagist.org/) - 一个包和依赖管理器.
- [Composer Installers](https://github.com/composer/installers) - 一个多框架Composer库安装器
- [pickle](https://github.com/FriendsOfPHP/pickle) - PHP扩展安装器
- [Melody](http://melody.sensiolabs.org/) - A tool to build one file Composer scripts.

## 框架( Frameworks )
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
    - [swoole-yaf](https://github.com/LinkedDestiny/swoole-yaf) - 基于 Swoole 及 Yaf 的开发框架
    - [yaf](https://github.com/qieangel2013/yaf) - 另一个基于 Swoole 及 Yaf 的开发框架
- [SwooleDistributed](https://github.com/tmtbe/SwooleDistributed) - swoole 分布式全栈框架
- [Zan PHP Framework](https://github.com/youzan/zan) - 有赞开源的 PHP 框架
- [php-msf](https://github.com/pinguo/php-msf) - Camera360开源的微服务框架
- [Biny](https://github.com/Tencent/Biny) - Biny是一款高性能的超轻量级PHP框架
- [Swoft Framework](https://github.com/swoft-cloud/swoft/) - 基于Swoole原生协程，新时代PHP高性能协程框架

## 组件( Components )

- [Aura Components](http://auraphp.com/) - 一个PHP5.4的组件包
- [Hoa Project](http://hoa-project.net/En/) - 一个PHP组件集合

## 配置( Configuration )
>加载配置文件的类库和扩展

- [Yaconf](https://github.com/laruence/yaconf) - 一个高性能的配置管理扩展
- [config](https://github.com/hassankhan/config) - 一个轻量级的配置加载器, 支持 PHP, INI, XML, JSON, YAML files
- [Zend-config](https://github.com/zendframework/zend-config)
- [phpdotenv](https://github.com/vlucas/phpdotenv) - 读取.env中全局的最高优先级变量

## 微框架( Micro Frameworks )
>微型框架和路由

- [Silex](http://silex.sensiolabs.org/) - 基于Symphony2组件的微型框架
    - [Silex Skeleton](https://github.com/fabpot/Silex-Skeleton) - 用于Silex的项目框架
    - [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - 用于Silex的Web调试工具条
- [Slim](http://www.slimframework.com/) - 另一个简单的微型框架
    - [awesome-slim](https://github.com/xssc/awesome-slim)
    - [Slim Skeleton](https://github.com/codeguy/Slim-Skeleton) - 用于Slim的框架
    - [Slim View](https://github.com/codeguy/Slim-Views) - Slim的自定义视图集
    - [Slim Middleware](https://github.com/codeguy/Slim-Middleware) - Slim的自定义中间件集合
    - [slim-skeleton](https://github.com/JingwenTian/slim-skeleton) - Slim基础上实现了MVC及一些组件
    - [slim-boilerplate](https://github.com/damianopetrungaro/slim-boilerplate)
- [Bullet PHP](http://bulletphp.com/) - 用于构建REST APIs的微型框架
- [Lumen](http://lumen.laravel.com/) - 基于Laravel的微型框架
- [Proton](https://github.com/alexbilbie/Proton) - 一个微型PHP框架
- [blink](https://github.com/bixuehujin/blink) - 一个为构建 “long running” 服务而生的 Web 微型高性能框架

## 路由( Routers )

- [Fast Route](https://github.com/nikic/FastRoute) - 一个高效路由库
- [Route](https://github.com/thephpleague/route) - 基于Fast Route的路由库
- [Pux](https://github.com/c9s/Pux) - 另一个高效的路由库
- [Klein](https://github.com/chriso/klein.php) - 一个灵活的路由库
- [Macaw](https://github.com/NoahBuscher/Macaw) - 一个简单的 PHP 路由器，超级精简、快速而且很性感。

## 模板引擎( Templating )
>模板和词法分析的库与工具

- [Twig](http://twig.sensiolabs.org/) - 一种综合的模板语言
- [Twig Cache Extension](https://github.com/asm89/twig-cache-extension) - 用于Twig的模板片段缓存库
- [Mustache](https://github.com/bobthecow/mustache.php) - PHP实现的Mustache模板语言
- [Phly Mustache](https://github.com/weierophinney/phly_mustache) - 另一个PHP实现的Mustache模板语言
- [MtHaml](https://github.com/arnaud-lb/MtHaml) - PHP实现的HAML模板语言
- [PHPTAL](http://phptal.org/) - PHP实现的TAL模板语言
- [Plates](http://platesphp.com/) - 一个原始的PHP模板库
- [Lex](https://github.com/pyrocms/lex) - 一个轻量级模板解析器
- [Aura.View](https://github.com/auraphp/Aura.View) - Provides TemplateView and TwoStepView

## 静态站生成器( Static Site Generators )
>生成Web页面内容的预处理工具

- [Sculpin](http://sculpin.io/) - 将Markdown和Twig转换为静态HTML的工具
- [Phrozn](http://phrozn.info/) - 另一款ithub将Textile、Markdown和Twig转为HTML的工具
- [Spress](http://spress.yosymfony.com/) 
- [Couscous](http://couscous.io/) - 将Markdown 文档转换成 HTML 发布到Github Page 的工具

## HTTP
>用于HTTP和抓取网站的库

- [Guzzle](https://github.com/guzzle/guzzle) - 一个完整的HTTP客户端
- [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个HTTP客户端
- [Requests](https://github.com/rmccue/Requests) - 一个简单的HTTP库
- [HTTPFul](https://github.com/nategood/httpful) - 一个链式HTTP客户端
- [Goutte](https://github.com/fabpot/Goutte) - 一个简单的Web抓取器
- [PHP VCR](http://php-vcr.github.io/) - 一个录制和回放HTTP请求的库
- [php-curl-class](https://github.com/php-curl-class/php-curl-class) - PHP的Curl类
- [Beanbun](https://github.com/kiddyuchina/Beanbun) - 多进程网络爬虫框架

## SOAP

- [soap-client](https://github.com/phpro/soap-client) - A general purpose SOAP client for PHP
- [soap-client](https://github.com/goetas-webservices/soap-client) - PHP implementation of SOAP 1.1 and 1.2 client specifications
- [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - Simple utility and class library for generating php classes from a wsdl file.

## 中间件( Middlewares )
>用于构建应用的类库的中间件

## URL
>解析URL的库

- [Purl](https://github.com/jwage/purl) - 一个URL操作库
- [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - 一个本地的后缀解析器
- [Uri](https://github.com/thephpleague/uri) - 一个简单的URL操作库

## 邮件( Email )
>用于发送和解析Email的库

- [SwiftMailer](http://swiftmailer.org/) - 一个邮件程序的解决方案
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - 另一个邮件程序的解决方案
- [Nette Mail](https://github.com/nette/mail) - 一个简单优雅的邮件发送模块
- [Fetch](https://github.com/tedivm/Fetch) - 一个IMAP库
- [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - 一个邮件回复解析器库
- [Stampie](https://github.com/henrikbjorn/Stampie) - 关于邮件服务的库，比如SendGrid、PostMark、MailGun和Mandrill
- [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - 邮件模板中一个内联的CSS库
- [Email Validator](https://github.com/nojacko/email-validator) - 一个小巧的邮箱验证库

## 文件操作( Files )
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

## 流( Stream )
>处理流的库

- [Streamer](https://github.com/fzaninotto/Streamer) - 一个简单的面向对象流包装库

## 依赖注入( Dependency Injection )
>实现依赖注入设计模式的库

- [Pimple](http://pimple.sensiolabs.org/) - 一个小的依赖注入容器
- [container-interop](https://github.com/container-interop) - Containers interoperability
- [Auryn](https://github.com/rdlowrey/Auryn) - 另一个小的依赖注入容器
- [Container](https://github.com/thephpleague/container) - 另一个灵活的依赖注入容器
- [PHP DI](http://php-di.org/) - 一个使用标注实现的依赖注入
- [Acclimate](https://github.com/symfony/DependencyInjection) - 依赖注入容器和服务定位器的通用接口
- [Symfony DI](https://github.com/symfony/DependencyInjection) - 一个的依赖注入组件(SF2)
- [Twittee](https://github.com/fabpot/twittee)
- [simple di container](https://github.com/laracasts/simple-di-container)
- [Ding](https://github.com/marcelog/Ding)
- [di](https://github.com/yiisoft/di) - Yii DI container and injector

## 图像( Imagery )
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
- [PHPThumb](https://github.com/masterexploder/PHPThumb) - 缩略图处理库
- [phpqrcode](https://github.com/t0k4rt/phpqrcode) - 二维码生成库
- [QrCode](https://github.com/endroid/QrCode) - 另一个二维码生成库
- [pel](https://github.com/lsolesen/pel) - PHP Exif 库
- [php-exif](https://github.com/PHPExif/php-exif) - PHP Exif信息读取库
- [Captcha](https://github.com/Gregwar/Captcha) - 图形验证码


## 测试( Testing )
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
- [SimpleTest](https://github.com/simpletest/simpletest) - Unit Testing for PHP

## 持续集成( Continuous Integration )
>持续集成的库和应用

- [Travis CI](https://travis-ci.org/) - 一个持续集成的平台
- [SemaphoreCI](https://semaphoreapp.com/) - 一个给开源程序和私有项目的持续集成平台
- [PHPCI](http://www.phptesting.org/) - 一个PHP的开源持续集成平台
- [Sismo](http://sismo.sensiolabs.org/) - 一个持续的测试服务器库
- [Jenkins](http://jenkins-ci.org/) - PHP支持的持续集成平台
- [JoliCi](https://github.com/jolicode/JoliCi) - PHP开发的由Docker支持的持续集成客户端


## 文档( Documentation )
>生成项目文档的库

- [Sami](https://github.com/fabpot/Sami) - 一个API文档生成器
- [APIGen](https://github.com/apigen/apigen) - 另一个API文档生成器
- [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - 文档生成器
- [phpDox](http://phpdox.de/) - 一个PHP项目的文档生成器（不仅仅是API文档）
- [swagger-php](https://github.com/zircote/swagger-php) - A php swagger annotation and parsing library 

## 安全( Security )
>用于生成安全的随机数、加密数据、扫描漏洞, 令牌的库

- [HTML Purifier](https://github.com/ezyang/htmlpurifier) - 一个标准的HTML过滤器
- [RandomLib](https://github.com/ircmaxell/RandomLib) - 生成随机数和随机字符串的库
- [True Random](https://github.com/pixeloution/true-random) - 使用www.random.org生成随机数的库
- [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - 一个PHP安全库
- [PHPSecLib](https://github.com/phpseclib/phpseclib) - 一个纯的PHP安全通信库
- [TCrypto](https://github.com/timoh6/TCrypto) - 一个简单的键值加密存储库
- [PHP IDS](https://github.com/PHPIDS/PHPIDS) - 一个结构化的PHP安全层
- [PHP SSH](https://github.com/Herzult/php-ssh) - 面向对象的SSH包装库
- [IniScan](https://github.com/psecio/iniscan) - 一个扫描PHP INI文件安全的工具
- [SensioLabs Security Check](https://security.sensiolabs.org/) -  一个根据安全建议检查Composer依赖的Web工具
- [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - 用于Web应用的集成渗透测试工具
- [php-ratelimiter](https://github.com/akirk/php-ratelimiter) 
- [xxtea-php](https://github.com/xxtea/xxtea-php) - XXTEA encryption algorithm library for PHP.

## 密码( Passwords )
>处理和存储密码的库和工具

- [Password Compat](https://github.com/ircmaxell/password_compat) - 一个用于新的PHP5.5密码功能的兼容库
- [phpass](http://www.openwall.com/phpass/) - 一个便携式密码哈希框架
- [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - 一个用于生成和验证密码的库
- [Password Policy](https://github.com/ircmaxell/password-policy) - 一个PHP和JavaScript的密码规则库
- [Password Validator](https://github.com/jeremykendall/password-validator) - 验证和升级密码哈希的库
- [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - 一个基于Zxcvbn JS的PHP显示密码强度估计库
- [GenPhrase](https://github.com/timoh6/GenPhrase) - 一个生成安全随机口令的库

## 代码分析( Code Analysis )
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
- [php-semver-checker](https://github.com/tomzx/php-semver-checker) - 一个版本对比的命令行工具
- [UBench](https://github.com/devster/ubench) - 一个简单的小型基准测试库
- [Athletic](https://github.com/polyfractal/athletic) - 一个基于标注的基准测试库
- [Mondrian](https://github.com/Trismegiste/Mondrian) - 使用图论的代码分析工具
- [Scrutinizer](https://scrutinizer-ci.com/) - 检查PHP代码的Web工具
- [PHPLOC](https://github.com/sebastianbergmann/phploc) - 一个快速评估PHP项目大小的工具
- [PHPCheckstyle](https://github.com/jbrooksuk/phpcheckstyle) - 一个帮助遵守特定代码规则的工具
- [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - 一个创建可定制型依赖关系图表的工具
- [Code Climate](http://codeclimate.com/) - 自动化的code review
- [PHP Error](https://github.com/JosephLenton/PHP-Error) - 用于转换标准的 PHP 错误信息，主要用于开发过程中的调试

## 结构( Architectural )
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

## 调试和性能( Debugging and Profiling )
>调试代码的库和工具

- [xDebug](https://github.com/xdebug/xdebug) - 一个PHP的调试和分析工具
- [whoops](https://github.com/filp/whoops)
- [PHP Debug Bar](http://phpdebugbar.com/) - 一个调试工具条
- [PHP Console](https://github.com/Seldaek/php-console) - Web调试控制台
- [Barbushin PHP Console](https://github.com/barbushin/php-console) -  一个使用Google Chrome的Web调试控制工具
- [PHPDBG](http://phpdbg.com/) - 一个交互性的PHP调试器
- [Tracy](https://github.com/nette/tracy) - 一个简单的错误检测、日志和时间测量库
- [Z-Ray](http://www.zend.com/en/products/server/z-ray) - 一个调试和性能分析的工具
- [xHprof](https://github.com/phacility/xhprof) - Facebook开源的PHP性能评测工具
    - [xhprof](https://github.com/longxinH/xhprof) - 基于官方版本fork的社区版本(支持PHP7)
    - [xhprof.io](https://github.com/EvaEngine/xhprof.io) - 实现保存xhprof数据以及展示数据的UI
    - [xhgui](https://github.com/perftools/xhgui) - 另一个保存xhprof数据以及展示数据的UI
- [Blackfire.io](http://blackfire.io) - 一个低开销的代码探查器
- [Kint](https://github.com/raveren/kint) - 一个调试和性能分析的工具
- [phptrace](https://github.com/Qihoo360/phptrace) - 360开源的PHP执行跟踪工具
- [php-apm](https://github.com/patrickallaert/php-apm) - Application performance management for PHP application
- [BooBoo](https://github.com/thephpleague/booboo) - 集中异常捕获


## 构建工具( Build Tools )
>项目构建和自动化工具

- [Go](https://github.com/herrera-io/php-go) - 一个简单的PHP构建工具
- [Bob](https://github.com/CHH/bob) - 一个简单的项目自动化工具
- [Phake](https://github.com/jaz303/phake) -  一个PHP克隆库
- [Box](https://github.com/kherge/Box) - 用来构建PHAR文件的工具
- [Phing](http://www.phing.info/) - 依据Apache Ant的PHP项目构建系统

## 任务运行器( Task Runners )
>自动运行任务的库

- [Task](http://taskphp.github.io/) - 依据Grunt和Gulp的纯PHP任务运行器
- [Robo](https://github.com/Codegyre/Robo) - 面向对象的PHP任务运行器
- [Bldr](http://bldr.io/) - 构建在Symfony组件上的PHP任务运行器

## 导航( Navigation )
>构建导航结构的工具

- [KnpMenu](https://github.com/KnpLabs/KnpMenu) - 一个菜单库
- [Cartographer](https://github.com/tackk/cartographer) - 一个站点地图生成库

## 资源管理( Asset Management )
>用于管理、压缩和最小化网站资源的工具

- [Assetic](https://github.com/kriswallsmith/assetic) - 一个资源管理的管道库
- [Pipe](https://github.com/CHH/pipe) - 另一个资源管理的管道库
- [Munee](https://github.com/meenie/munee) - 一个资源优化库
- [JShrink](https://github.com/tedivm/JShrink) - 一个JavaScript的压缩库
- [Puli](https://github.com/webmozart/puli) - 一个检测资源绝对路径的库

## 地理定位( Geolocation )
>使用经纬度编码地址的库

- [GeoCoder](http://geocoder-php.org/) - 一个地理编码库
- [GeoTools](https://github.com/php-loep/Geotools) - 一个地理工具相关的库
- [PHPGeo](https://github.com/mjaschen/phpgeo) - 一个简单的地理库
- [GeoJSON](https://github.com/jmikola/geojson) - 一个GeoJSON的实现

## 日期与时间( Date and Time )
>处理日期和时间的库

- [Carbon](https://github.com/briannesbitt/Carbon) - 一个简单的日期时间API扩展
- [ExpressiveDate](https://github.com/jasonlewis/expressive-date) - 另一个日期时间API扩展
- [CalendR](http://yohan.giarel.li/CalendR) - 一个日历管理的库
- [date](https://github.com/jenssegers/date) - 一个多语言的日期库
- [moment.php](https://github.com/fightbulc/moment.php)

## 事件( Event )
>事件驱动或非阻塞事件循环实现的库

- [React](https://github.com/reactphp/react) - 一个事件驱动的非阻塞I/O库
- [Rx.PHP](https://github.com/asm89/Rx.PHP) - 一个反应扩展库
- [phpsocket.io](https://github.com/walkor/phpsocket.io)
- [Ratchet](https://github.com/cboden/Ratchet) - 一个Web套接字库
- [Hoa WebSocket](https://github.com/hoaproject/Websocket) - 另一个Web套接字库
- [Elephant.io](https://github.com/Wisembly/Elephant.io) - 另一个Web套接字库
- [Hoa EventSource](https://github.com/hoaproject/Eventsource) - 一个事件源库
- [Evenement](https://github.com/igorw/evenement) - 一个事件调度库
- [Event](https://github.com/thephpleague/event) - Event package for your app and/or domain.
- [Cake Event](https://github.com/cakephp/event) - 一个事件调度类库
- [Broadway](https://github.com/qandidate-labs/broadway) - 一个事件源和CQRS库

## 日志( Logging )
>用于生成和处理日志文件的库

- [Monolog](https://github.com/Seldaek/monolog) - 一个综合的日志类库
- [KLogger](https://github.com/katzgrau/KLogger) - 一个易于使用的PSR-3日志类
- [Analog](https://github.com/jbroadway/analog) - 一个机遇闭包的微型日志包
- [SeasLog](https://github.com/neeke/seaslog) - 一个高效的日志扩展

## 电子商务( E-commerce )
>用于支付和构建在线电子商务商店的库和应用

- [OmniPay](https://github.com/thephpleague/omnipay) - 一个多网关支付处理的框架

    - [omnipay-paypal](https://github.com/thephpleague/omnipay-paypal) - PayPal 支付
    - [omnipay-wechatpay](https://github.com/lokielse/omnipay-wechatpay) - 微信支付
    - [omnipay-unionpay](https://github.com/lokielse/omnipay-unionpay) - 银联支付
    - [omnipay-alipay](https://github.com/lokielse/omnipay-alipay) - 支付宝支付
    - [omnipay-pingpp](https://github.com/phoenixg/omnipay-pingpp) - ping++聚合支付
    
- [Payum](https://github.com/payum/payum) - 一个用于支付的抽象库
- [Sylius](http://www.sylius.org/) - 一个开源的电子商务解决方案
- [Thelia](http://thelia.net/v2/) - 另一个开源的电子商务解决方案
- [Money](https://github.com/mathiasverraes/money) -  PHP实现的Fowler金钱模式
- [Sebastian Money](https://github.com/sebastianbergmann/money) - 一个处理货币价值的库
- [Swap](https://github.com/florianv/swap) - 一个汇率库

## PDF
>处理PDF文件的库和软件

- [Snappy](https://github.com/KnpLabs/snappy) - 一个PDF和图像的生成库
- [WKHTMLToPDF](https://github.com/antialize/wkhtmltopdf) - 一个将HTML转换为PDF的工具
- [PHPPdf](https://github.com/psliwa/PHPPdf) - 一个将XML转化为PDF和图片的库

## Office
>Office套装的各种文档的处理库

- [PHPWord](https://github.com/PHPOffice/PHPWord) - 处理Word文档的库
- [PHPExcel](https://github.com/PHPOffice/PHPExcel) - 处理Excel文档的库
- [PHPPowerPoint](https://github.com/PHPOffice/PHPPowerPoint) - 处理PPT幻灯片的库
- [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - 操作Excel文档的库
- [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - 建议使用最新的PHPOffice维护的Excel 文档处理库

## 数据库( Database )
>使用对象关系映射（ORM）或数据映射技术的数据库交互库

- [Doctrine](http://www.doctrine-project.org/) - 一个完整的DBAL和ORM
- [Doctrine Extensions](https://github.com/l3pp4rd/DoctrineExtensions) - 一个Doctrine行为的扩展集合
- [Propel](http://www.propelorm.org/) - 一个快速的ORM，迁移和查询库
- [Eloquent](https://github.com/illuminate/database) - Laravel 5 ORM(L5)
- [LazyRecord](https://github.com/c9s/LazyRecord) - 一个快速的ORM
- [Baum](https://github.com/etrepat/baum) - 一个Eloquent的嵌套集合
- [Spot2](https://github.com/vlucas/spot2) - MySQL的ORM映射器
- [RedBean](http://redbeanphp.com/) - 一个轻量级、易配置的ORM
- [Pomm](https://github.com/chanmix51/Pomm) - 用于PostgreSQL的一个对象模型管理器
- [ProxyManager](https://github.com/Ocramius/ProxyManager) - 用于数据映射生成代理对象的工具集合
- [Cake ORM](https://github.com/cakephp/orm) - 对象关系映射器, 实现了使用数据映射模式(CP)
- [Medoo](http://medoo.in/) - 一个轻量级的加速开发的ORM
- [Aura SQL](https://github.com/auraphp/Aura.Sql) - SQL database access through PDO.

## 迁移( Migrations )
>用于管理数据库模式和迁移的库

- [PHPMig](https://github.com/davedevelopment/phpmig) - 一个迁移管理库
- [Phinx](https://github.com/robmorgan/phinx) - 一个数据库迁移管理库
- [Migrations](https://github.com/icomefromthenet/Migrations) - 另一个迁移管理库
- [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - 用于Doctrine的迁移库

## 非关系型数据库( NoSQL )
>处理NoSQL后端的库

- MongoDB
    - [mongo-php-library](https://github.com/mongodb/mongo-php-library) - MongoDB 官方PHP库
    - [MongoQB](https://github.com/alexbilbie/MongoQB) - 一个MongoDB的查询构建库
    - [Monga](https://github.com/thephpleague/monga) - 一个MongoDB的抽象库
    - [mongodm](https://github.com/purekid/mongodm) - MongoDB ORM
    - [php-mongo](https://github.com/sokil/php-mongo) - PHP ODM for MongoDB
    - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb)
- Redis
    - [Predis](https://github.com/nrk/predis) - 一个功能完全的Redis库
    - [codis](https://github.com/CodisLabs/codis) - Codis 是一个分布式 Redis 解决方案
    - [twemproxy](https://github.com/twitter/twemproxy) - 是twtter开源的一个redis和memcache代理服务器
    - [pika](https://github.com/Qihoo360/pika) - Pika是一个可持久化的大容量redis存储服务

## 队列( Queue )
>处理事件和任务队列的库

- [enqueue-dev](https://github.com/php-enqueue/enqueue-dev) - Message queue packages for PHP, Symfony, Laravel, Magento
    - [enqueue/rdkafka](https://github.com/php-enqueue/rdkafka)
    - [enqueue/enqueue](https://github.com/php-enqueue/enqueue)
    - [enqueue/pheanstalk](https://github.com/php-enqueue/pheanstalk)
    - [enqueue/redis](https://github.com/php-enqueue/redis)

**队列服务框架**

- [Kafka](https://github.com/apache/kafka) - 高吞吐量的分布式发布订阅消息系统
- [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server) - 使用 erlang 编写的 AMQP (高级消息队列协议) 的服务实现
- [RocketMQ](https://github.com/apache/rocketmq/)
- [ActiveMQ](https://github.com/apache/activemq/)
- [Qpid](https://github.com/apache/qpid)
- [Disque](https://github.com/antirez/disque) - 分布式内存队列
- [beanstalkd](https://github.com/kr/beanstalkd) - 一个高性能、轻量级的消息队列中间件

**队列相关类库**

- [Pheanstalk](https://github.com/pda/pheanstalk) - 一个Beanstalkd客户端库
- [PHP AMQP](https://github.com/videlalvaro/php-amqplib) - 一个纯PHP AMQP库
- [Thumper](https://github.com/videlalvaro/Thumper) - 一个RabbitMQ模式库
- [Bernard](https://github.com/bernardphp/bernard) - 一个多后端的抽象库
- [php-resque](https://github.com/chrisboulton/php-resque) - 基于redis的消息队列
- [php-amqplib](https://github.com/php-amqplib/php-amqplib) - 一个RabbitMQ客户端库
- [kafka-php](https://github.com/weiboad/kafka-php) - 一个kafka客户端库(Composer)
- [php-rdkafka](https://github.com/arnaud-lb/php-rdkafka) - 一个kafka客户端库(PECL)

## 搜索( Search )
>在数据中建立索引和执行查询相关的库和软件

- [ElasticSearch PHP](https://github.com/elasticsearch/elasticsearch-php) - 用于 [ElasticSearch](http://www.elasticsearch.org/) 的官方客户端库.
- [Elastica](https://github.com/ruflin/Elastica) - 另一个ElasticSearch的客户端库
- [Solarium](http://www.solarium-project.org/) - [Solr](http://lucene.apache.org/solr/) 的客户端库 .
- [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - [Sphinx](http://sphinxsearch.com/) 搜索引擎的查询库  


## 命令行( Command Line )
>构建命令行工具的库

- [symfony/console](https://github.com/symfony/console) - Symfony命令行工作组件
- [Boris](https://github.com/d11wtq/boris) - 一个微型的PHP REPL
- [PsySH](https://github.com/bobthecow/psysh) - 另一个PHP REPL
- [Pecan](https://github.com/mcrumm/pecan) - 一个事件驱动，非阻塞的shell
- [GetOpt](https://github.com/ulrichsg/getopt-php) - 一个命令行选择解析器
- [OptParse](https://github.com/CHH/optparse) - 另一个命令行选择解析器
- [Commando](https://github.com/nategood/commando) - 一个简单的命令行选择解析器
- [GetOptionKit](https://github.com/c9s/php-GetOptionKit) - 同样还是一个命令行选择解析器
- [Cron Expression](https://github.com/mtdowling/cron-expression) -计算cron运行日期的库
- [ShellWrap](https://github.com/MrRio/shellwrap) - 一个简单的命令行包装库
- [Hoa Console](https://github.com/hoaproject/Console) - 另一个命令行库
- [Shunt](https://github.com/php-loep/shunt) -一个在多台远程机器上并行运行的命令行库
- [Cilex](https://github.com/Cilex/Cilex) - 构建命令行工具的小型框架
- [CLImate](https://github.com/thephpleague/climate) - 构建命令行工具的框架(可以输出颜色和特殊格式)
- [Webmozart Console](github.com/webmozart/console)
- [Silly](https://github.com/mnapoli/silly) - Silly CLI micro-framework based on Symfony Console

## 定时任务( Crontab )
>定时任务管理 crontab在 PHP 中的相关封装

- [Dispatcher](https://github.com/Indatus/dispatcher) - 基于Laravel的定时任务管理
- [swoole-crontab](https://github.com/osgochina/swoole-crontab) - 基于swoole的定时器程序，支持秒级处理
- [jobby](https://github.com/jobbyphp/jobby) -  一个 PHP 的定时任务管理器
- [cronlingo](https://github.com/ajbdev/cronlingo) - Express crontabs as human friendly phrases


## 身份验证( Authentication and Authorization )
>实现身份验证模式的库

- [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - 一个身份验证和授权的框架
- [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - 一个用于社交网络身份验证的库
- [Opauth](https://github.com/opauth/opauth) - 提供了 OAuth 认证的支持,提供统一标准的访问方法
- [OAuth2 Server](http://oauth2.thephpleague.com/) - 一个OAuth2身份验证服务器、资源服务器和客户端库
- [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - 一个OAuth2服务器实现
- [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - 另一个OAuth库
- [TwitterOAuth](https://github.com/ruudk/twitteroauth) - 一个Twitter OAuth库
- [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - 一个经过完全测试的Twitter SDK
- [Hawk](https://github.com/dflydev/dflydev-hawk) - 一个Hawk HTTP身份验证库
- [HybridAuth](https://github.com/hybridauth/hybridauth) - 一个开源的社交登录库
- [Lock](https://github.com/BeatSwitch/lock) - 一个 Access Control Lists (ACL) 系统库.
- [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - 一个 OAuth 1.0 客户端库.
- [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - 一个 OAuth 2.0 客户端库.
- [Sentry](http://github.com/cartalyst/sentry) - 认证和授权系统
- [EvaOAuth](https://github.com/AlloVince/EvaOAuth) - 统一接口的 OAuth 登录 PHP 类库
- [JSON Web Token](http://jwt.io/)- JSON网络令牌库
    - [php-jwt](https://github.com/firebase/php-jwt) 
    - [jwt](https://github.com/lcobucci/jwt)
    - [jose](https://github.com/namshi/jose) - JSON签名和加密的库
    - [slim-jwt-auth](https://github.com/tuupola/slim-jwt-auth)
    - [jwt-auth](https://github.com/tymondesigns/jwt-auth)

## 标记( Markup )
>处理标记的库

- [Decoda](http://milesj.me/code/php/decoda) - 一个轻量级的标记解析库
- [PHP Markdown](https://github.com/michelf/php-markdown) - Markdown解析器
- [CommonMark PHP](https://github.com/thephpleague/commonmark) - 一个支持 [CommonMark spec](http://spec.commonmark.org/) 的Markdown解析器.
- [Parsedown](https://github.com/erusev/parsedown) - 一个Markdown解析器
- [Ciconia](https://github.com/kzykhys/Ciconia) - 一个支持Github风格的Markdown解析器
- [Cebe Markdown](https://github.com/cebe/markdown) - 一个快速、可扩展的Markdown解析器
- [HTML5 PHP](https://github.com/Masterminds/html5-php) - 一个HTML5解析和序列化的库
- [Emoji](https://github.com/heyupdate/Emoji) - 一个简单的处理emoji的类库
- [php-emoji](https://github.com/iamcal/php-emoji) - 一个emoji表情转换库

## 字符串( Strings )
>解析和操纵字符串的库

- [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
- [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - 一个将ANSI转换为HTML5的库
- [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - 处理UTF-8格式字符串的便携库
- [Hoa String](https://github.com/hoaproject/String) - 另一个UTF-8格式的字符串库
- [Stringy](https://github.com/danielstjules/Stringy) - 一个多字节支持的字符串操纵库
- [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - 一个处理和转换颜色的库
- [UUID](https://github.com/ramsey/uuid) - 生成UUIDs的库
- [Slugify](https://github.com/cocur/slugify) - 一个将字符串转换为slug格式的库
- [Urlify](https://github.com/jbroadway/urlify) - 一个Django URLify.js的PHP端口
- [Text](https://github.com/kzykhys/Text) - 一个文本处理库
- [SQL Formatter](https://github.com/jdorn/sql-formatter/) - 一个用于格式化SQL语句的库
- [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - 一个解析UA(User Agent)字符串的库
- [Device Detector](https://github.com/piwik/device-detector) - 另一个解析UA(User Agent)字符串的库
- [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - 一个轻量级的检测移动设备的库(包括桌面设备)
- [Browser](https://github.com/cbschuld/Browser.php) - 检测关于用户的浏览器环境
- [colors.php](https://github.com/kevinlebrun/colors.php) - An easy way to add colors in your CLI scripts.

## 数字( Numbers )
>处理数字的库

- [Numbers PHP](https://github.com/powder96/numbers.php) - 一个处理数字的库
- [Math](https://github.com/moontoast/math) - 处理较大数字的库
- [ByteUnits](https://github.com/gabrielelana/byte-units) -  一个在二进制和测量系统中解析、格式化和转换字节单位的库
- [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - 一个测量单位间转换的库
- [PHP Conversion](https://github.com/Crisu83/php-conversion) -  另一个测量单位间转换的库
- [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) -  PHP实现的Google电话号码处理系统库
- [hashids.php](https://github.com/ivanakimov/hashids.php) - 用来把整数生成唯一字符串（比如：通过加密解密id来隐藏真实id)
- [Particle](https://github.com/sschiau/Particle) - PHP ID Generator | Implementation of Twitter Snowflake ID Generator

## 过滤和验证( Filtering ang Validation )
>用于过滤和验证数据的库

- [Filterus](https://github.com/ircmaxell/filterus) -  一个简单的PHP过滤库
- [Respect Validation](https://github.com/Respect/Validation) - 一个简单的验证库
- [Valitron](https://github.com/vlucas/valitron) - 另一个数据验证库
- [Cake Validation](https://github.com/cakephp/validation) - 另一个数据验证库 
- [Illuminate validation package](https://github.com/illuminate/validation) - Laravel的验证库
- [php-readability](https://github.com/feelinglucky/php-readability) - 内容分析算法
- [Upload](https://github.com/codeguy/Upload) - 一个处理文件上传和验证的库
- [DMS Filter](https://github.com/rdohms/DMS-Filter) - 一个基于标注的过滤库
- [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - 支持YAML、JSON和XML的一个模式验证库
- [ISO-codes](https://github.com/ronanguilloux/IsoCodes) -  验证不同ISO和ZIP编码的库
- [aura/filter](https://github.com/auraphp/Aura.Filter) - Aura 数据验证组件
- [symfony/validator](https://github.com/symfony/validator) - Symfony 数据验证组件

## REST和API

>用于开发restful APIs的库和Web框架

- [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - 一个使用Zend Framework2构建的API构建器
- [Hateoas](https://github.com/willdurand/Hateoas) - 一个HATEOAS REST的web服务库
- [HAL](https://github.com/blongden/hal) -  一个超文本应用语言（HAL）构建库
- [Negotiation](https://github.com/willdurand/Negotiation) - 一个内容协商库
- [Drest](https://github.com/leedavis81/drest) -一个将Doctrine实体展现为REST资源结点的库
- [Restler](https://github.com/Luracast/Restler) - 一个将PHP方法展现为RESTful web API的轻量级框架
- [fractal](https://github.com/thephpleague/fractal) - [最佳实践]数据返回的统一化处理
- [api-problem](https://github.com/Crell/ApiProblem) - A simple implementation of the api-problem specification
- [graphql-php](https://github.com/webonyx/graphql-php) - 应用层查询语言库
- [GraphQL](https://github.com/Youshido/GraphQL) - 另一个应用层查询语言库

## 缓存( Caching )
>缓存数据的库

- [Alternative PHP Cache (APC)](http://www.php.net/manual/en/book.apc.php) - PHP的开源操作码缓存
- [Doctrine Cache](https://github.com/doctrine/cache) - 一个缓存库.
- [Zend Cache](https://github.com/zendframework/zend-cache) - 另一个缓存库
- [Cake Cache](https://github.com/cakephp/cache) - 一个用于缓存的库
- [Stash](https://github.com/tedivm/Stash) - 另一个缓存库
- [CacheTool](https://github.com/gordalina/cachetool) - 一个清除APC/opcode缓存的命令行工具
- [PhpFastCache](https://github.com/khoaofgod/phpfastcache) - PHP 缓存库 

## 数据结构和存储( Data Structure and Storage )
>实现数据结构和存储技术的库

- [Illuminate\Support\Collection](https://docs.golaravel.com/docs/5.1/collections/) - Laravel提供的流畅、便利的封装来操控数组数据的集合库
- [Collections](https://github.com/tightenco/collect) - 一个从Laravel拆离出的集合库
- [Ardent](https://github.com/morrisonlevi/Ardent) - 一个数据结构库
- [Cake Collection](https://github.com/cakephp/collection) - 一个简单的集合库
- [Collections](https://github.com/italolelis/collections) - 一个集合抽象库
- [Fractal](https://github.com/php-loep/fractal) -  一个将复杂数据结构转换为JSON输出的库
- [PHP Collections](https://github.com/schmittjoh/php-collection) - 一个简单的集合库
- [Serializer](https://github.com/schmittjoh/serializer) - 用于序列化和反序列化数据的库
- [Zend Serializer](https://github.com/zendframework/zend-serializer) - 另一个用于序列化和反序列化数据的库
- [PHP Object Storage](https://github.com/herrera-io/php-object-storage) - 一个用于对象存储的库
- [Totem](http://github.com/Wisembly/Totem) - 一个管理和创建数据修改集的库
- [PINQ](https://github.com/TimeToogo/Pinq) - PHP实时Linq库
- [JsonMapper](https://github.com/netresearch/jsonmapper) - 一个将内嵌JSON结构映射到PHP类上的库

## 通知( Notifications )
>关于通知的库

- [Nod](https://github.com/filp/nod) - 一个通知库
- [Notificato](https://github.com/wrep/notificato) - 一个处理推送消息的库
- [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - 设备推送通知的独立库
- [Notificator](https://github.com/namshi/notificator) - 一个轻量级通知库

## 部署( Deployment )
>用于项目部署的库

- [Pomander](https://github.com/tamagokun/pomander) -  一个PHP应用的部署工具
- [Rocketeer](https://github.com/Anahkiasen/rocketeer) -  PHP的快速和简单部署器
- [Envoy](https://github.com/laravel/envoy) - 使用PHP运行SSH任务的工具
- [Plum](https://github.com/aerialls/Plum) - 一个部署库
- [Deployer](https://github.com/deployphp/deployer) - 一个部署工具
- [walle-web](https://github.com/meolu/walle-web) - 一个开源的web代码发布管理系统

## 国际化和本地化(Internationalisation and Localisation)
>用于国际化(I18n)和本地化(L10n)的库

* [Aura Intl](https://github.com/auraphp/Aura.Intl)
* [Cake I18n](https://github.com/cakephp/i18n) - 翻译和本地化消息
* [symfony/translation](https://github.com/symfony/translation)
* [illuminate/translation](https://github.com/illuminate/translation)
* [Gettext](https://github.com/oscarotero/Gettext) - PHP library to collect and manipulate gettext (.po, .mo, .php, .json, etc)
* [zend/i18n](http://zendframework.github.io/zend-i18n/translation/)

## 第三方API( Third Party APIs )
>访问第三方API的库

- [mailgun-php](https://github.com/mailgun/mailgun-php) - Mailgun's Official SDK for PHP
- [wechat](https://github.com/overtrue/wechat) - 让微信开发更简单
- [Qiniu/sdk](https://github.com/qiniu/php-sdk) - Qiniu Resource Storage SDK for PHP
- [Qiniu/qshell](https://github.com/qiniu/qshell) - qshell是利用七牛文档上公开的API实现的一个方便开发者测试和使用七牛API服务的命令行工具。
- [Wafer](https://github.com/tencentyun/wafer) - 快速构建具备弹性能力的微信小程序
- [GeoIP2-php](https://github.com/maxmind/GeoIP2-php) - MaxMind GeoIP2 地理位置服务
- [pingpp-php](https://github.com/PingPlusPlus/pingpp-php) - ping++聚合支付SDK

## 扩展( Extensions )
>帮助构建PHP扩展的库

- [Zephir](https://github.com/phalcon/zephir) - 用于开发PHP扩展的一种在PHP和C++间的编译语言
- [PHP CPP](http://www.php-cpp.com/) - 一个用于开发PHP扩展的C++库
- [PHP-X](https://github.com/swoole/PHP-X) - C++ wrapper for Zend API

## PHP 安装(PHP Installation)
>帮助安装和管理PHP

- [HomeBrew](http://brew.sh/) - 一个OSX的包管理工具
- [HomeBrew PHP ](https://github.com/Homebrew/homebrew-php) - HomeBrew中PHP的安装包
- [PHP OSX ](http://php-osx.liip.ch/) - 一个OSX中的PHP安装器
- [PHP Brew ](https://github.com/phpbrew/phpbrew) - 一个PHP版本管理工具和安装器
- [PHP Env](https://github.com/CHH/phpenv) - 另一个PHP版本工具
- [PHP Switch ](https://github.com/jubianchi/phpswitch) - 另一个PHP版本工具
- [PHP Build ](https://github.com/php-build/php-build) - 另一个PHP版本工具
- [VirtPHP ](http://virtphp.org/) - 一个创建和管理分离的PHP环境的工具


## 开发环境(Development Environment)
>创建沙箱开发环境的软件和工具

- [Vagrant](https://www.vagrantup.com/) - 一个轻便的创建开发环境的工具
- [Ansible ](https://www.ansible.com/) - 一个简单的业务流程框架
- [Puppet](https://puppetlabs.com/) - 服务器自动化框架和应用
- [PuPHPet](https://puphpet.com/) - 一个用于构建PHP开发虚拟机工具
- [Protobox](http://getprotobox.com/) - 另一个用于构建PHP开发虚拟机工具
- [Phansible](http://phansible.com/) - 另一个用于构建PHP开发虚拟机工具
- [centstead](https://github.com/jason-chang/centstead) - Laravel local development environment base on vagrant  and homestead
- [Laravel Homestead](https://github.com/laravel/homestead)

## 虚拟机(Virtual Machines)
>替代的PHP虚拟机

- [HHVM ](https://github.com/facebook/hhvm) - Facebook 开源的PHP虚拟机
- [HippyVM](http://hippyvm.com/) - 另一个PHP虚拟机

## 开发工具(Integrated Development Environment)
>支持PHP的IDE

- [Netbeans](https://netbeans.org/)
- [Eclipse for PHP Developers ](https://www.eclipse.org/downloads/)
- [PhpStorm ](http://www.jetbrains.com/phpstorm/)

## Web 应用程序(Web Applications)
>基于Web的应用程序和工具

- [3V4L](https://3v4l.org/) - Online PHP shell
- [DBV](http://dbv.vizuina.com/) - 数据库版本控制应用程序
- [PHP Queue](https://github.com/CoderKungfu/php-queue) - 管理队列的后端程序
- [MailCatcher](https://github.com/sj26/mailcatcher) - 一个接受和查看邮件的程序
- [Cachet](https://github.com/cachethq/cachet) - 一个开源的网站状态展示系统(如: status.github.com )
- [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - Redis 管理工具
- [phpPgAdmin ](https://github.com/phppgadmin/phppgadmin) - PostgreSQL管理工具
- [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - MySQL管理工具
- [rockmongo](https://github.com/iwind/rockmongo) - MongoDB管理工具
- [Grav](https://github.com/getgrav/grav) - Powerful Flat-File CMS
- [Piwik](https://github.com/piwik/piwik) - 网页统计
- [YOURLS](https://github.com/YOURLS/YOURLS) - 短网址生成系统
- [Nextcloud server](https://github.com/nextcloud/server) - 开源私有云系统(a safe home for all your data)

## 基础设施(Infrastructure)
>提供PHP应用程序和服务的基础设施

- [appserver.io](http://appserver.io/) - 基于PHP的多线程应用程序服务器
- [php-pm](https://github.com/php-pm/php-pm) - 进程管理器,增压器和PHP应用程序的负载平衡器

## 数据库中间件( DB Proxy )
> 用于读写分离、分库分表等

- [kingshard](https://github.com/flike/kingshard) - 金山开源的数据库中间件
- [heisenberg](https://github.com/brucexx/heisenberg) - 百度开源的数据库中间件
- [Oceanus](https://github.com/58code/Oceanus) - 58同城开源的数据库中间件
- [Atlas](https://github.com/Qihoo360/Atlas) - 360开源数据库中间件
- [DBProxy](https://github.com/Meituan-Dianping/DBProxy) - 美团点评基于Atlas的数据库中间件
- [Mycat](http://www.mycat.org.cn/index.html)
- [TiDB](https://github.com/pingcap/tidb) - 分布式数据库
- [mysql-proxy](https://github.com/swoole/mysql-proxy) - Swoole开源的数据库中间件

## RPC框架
> 远程过程调用框架

- [thrift](https://github.com/apache/thrift) - Apache Thrift
- [grpc](https://github.com/grpc/grpc) - Google的开源框架
- [protobuf](https://github.com/allegro/php-protobuf)
- [Dubbo](https://github.com/alibaba/dubbo) - 阿里巴巴开源的RPC框架
- [Motan](https://github.com/weibocom/motan) - 微博轻量级RPC框架
- [Dubbox](https://github.com/dangdangdotcom/dubbox) - 当当网维护的dubbox
- [sofa-pbrpc](https://github.com/baidu/sofa-pbrpc) - 百度开源的sofa-pbrpc
- [yar](https://github.com/laruence/yar)
- Hprose - 高性能跨语言RPC
    - [hprose-php](https://github.com/hprose/hprose-php)
    - [hprose-swoole](https://github.com/hprose/hprose-swoole)
- 其他
    - [Dora-RPC](https://github.com/xcl3721/Dora-RPC)
    - [workerman-JsonRpc](https://github.com/walkor/workerman-jsonrpc/)

## 异步网络通信框架( Asynchronous Event Driven Framework )

- [Swoole](http://www.swoole.com/)
- [Workerman](https://github.com/walkor/Workerman)
- [Gearman](http://gearman.info/) - 任务分发系统
- [phpdaemon](https://github.com/kakserpom/phpdaemon)
- [ReactPHP](https://github.com/reactphp/react)
- [Amp](https://github.com/amphp/amp) - A non-blocking concurrency framework for PHP applications. 
- [async](https://github.com/spatie/async) - Easily run code asynchronously

## 规则引擎( Rules Engine )

- [Hoa\Ruler](https://github.com/hoaproject/Ruler) - Hoa项目的规则引擎
- [Ruler](https://github.com/bobthecow/Ruler) - 简单的无状态的规则引擎
- [Rules](https://github.com/tonera/Rules) - PHP简易规则引擎

## 其他( Miscellaneous )
>不属于以上分类的有用的类库和工具

- [pinyin](https://github.com/overtrue/pinyin) - 汉字转拼音的库
- [Pinyin](https://github.com/jifei/Pinyin) - 汉字转拼音的库
- [class.upload.php](https://github.com/verot/class.upload.php) - 文件上传处理类
- [php-paginator](https://github.com/jasongrimes/php-paginator) - 分页处理类
- [Underscore.php](https://github.com/brianhaveri/Underscore.php) - Underscore.js的PHP实现
- [Flexihash](https://github.com/pda/flexihash) - 一致性hash库
- [Eden](https://github.com/Openovate/eden) - 一个PHP快速开发类库,它包含很多组件用来自动加载、事件驱动、文档系统、缓存、模板、国际化、数据库、web服务、支付网关、装载和云服务技术。
- [html-parser](https://github.com/bupt1987/html-parser) - html解析工具
- [PHPCrawl](http://phpcrawl.cuab.de/) - PHP的爬虫框架
- [Tig](https://github.com/jonas/tig) - 命令行下的 Git 浏览器
- [copywriting-correct](https://github.com/ricoa/copywriting-correct) - 中英文文案排版纠正器
- [PHP-ML](https://github.com/php-ai/php-ml) - PHP 机器学习库
- [BotMan](https://github.com/botman/botman) - 聊天机器人库



