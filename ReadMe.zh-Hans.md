# ASP.NET Core开发者指南

##  软件与环境

#### 资源下载地址
 (ftp://124.71.238.108:20001): 打开我的电脑在地址栏里输入或者用ie打开
#### 软件与教程
- ##### **Teams** 
  
  - 下载  
      [微软官方下载地址](https://www.microsoft.com/zh-cn/microsoft-teams/group-chat-software/)  

- ##### **Visual Studio**
  
  - 下载  
      [微软官方下载地址](https://visualstudio.microsoft.com/zh-hans/)：官网上免费下载最新社区版  
      资源库： /常用工具 有VS2021  
  - 学习  
      [VS快捷键](https://blog.csdn.net/kangjielearning/article/details/106432189?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164940711316780274158310%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164940711316780274158310&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-106432189.142^v7^pc_search_result_control_group,157^v4^new_style&utm_term=vs%E5%BF%AB%E6%8D%B7%E9%94%AE&spm=1018.2226.3001.4187)  
      [VS快捷键（包含记忆的口诀和演示）](https://blog.csdn.net/weixin_41424481/article/details/109049926?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164940711316780274158310%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164940711316780274158310&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-2-109049926.142^v7^pc_search_result_control_group,157^v4^new_style&utm_term=vs%E5%BF%AB%E6%8D%B7%E9%94%AE&spm=1018.2226.3001.4187)
- ##### **Git**
  
  - 下载  
      资源库 /常用工具/tools 版本：Git-2.20.1-64-bit  
  - 学习  
    [在线学习Git命令](https://learngitbranching.js.org/?locale=zh_CN)  
    [参考教程](https://www.liaoxuefeng.com/wiki/896043488029600)

- ##### **GitExtensions**

  - 下载  
    资源库 /常用工具/tools 版本：GitExtensions246SetupComplete

- ##### **PostgreSQL**
  
  - 下载  
      数据库装在服务器上 
  - 学习   
      [菜鸟教程](https://www.runoob.com/postgresql/postgresql-tutorial.html)：pgsql基本语法

- ##### **pgAdmin**
  
  - 下载  
      资源库 /国产化相关/数据库/PostgreSQL/Windows pgadmin4-6.7-x64

## 2.开发

#### 1.学习先决条件

  - #####  **Markdown**  
     [Markdown语法学习](https://www.jianshu.com/p/191d1e21f7ed): Markdown基本语法  
     [马克飞象](https://maxiang.io/)：可以预览的在线编辑Markdown网站 
   - #####  **C#**
        (https://www.pluralsight.com/paths/csharp) 原作者推荐的国外学习C#网站，可以访问网站，但是看视频要vpn，英文原生无字幕。
        (https://docs.microsoft.com/zh-cn/dotnet/csharp/tour-of-csharp/) 微软官方C#文档
        (https://www.runoob.com/csharp/csharp-tutorial.html) C# 菜鸟教程，数据全但是解释的很简单
   - [.NET 6]
        (https://devblogs.microsoft.com/dotnet/announcing-net-6) 微软官方.net6文档
   - [Entity Framework]
        (https://www.pluralsight.com/search?q=entity%20framework%20core) 原作者推荐的国外EF框架学习网站，同C#第一个
        (https://docs.microsoft.com/zh-cn/ef/core/get-started/overview/first-app?tabs=netcore-cli) 微软官方EF框架文档
        (https://www.cnblogs.com/wyy1234/p/9650759.html) 中文博客翻译自(http://www.entityframeworktutorial.net/)
   - [Dapper]
        (https://github.com/StackExchange/Dapper) Dapper是一款轻量级ORM工具，链接是github上学习Dapper的一个仓库
   - [NHibernate]
        (https://github.com/nhibernate/nhibernate-core)NHibernate是一个面向.NET环境的对象/关系数据库映射工具，链接是github上学习NHibernate的一个仓库
   - [ASP.NET Core]
        (https://www.pluralsight.com/search?q=asp.net%20core) 原作者推荐的国外学习ASP.NET Core学习网站，同C#第一个
 
   - SQL 基础知识

2. 通用开发技能

   - 学习GIT 并且在 GitHub 中创建与分享项目
   - 掌握 HTTP(S) 协议与请求方法 (GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - 不要害怕使用 Google，[Google搜索技巧](http://www.powersearchingwithgoogle.com)
   - 学习 [dotnet CLI](https://docs.microsoft.com/zh-cn/dotnet/core/tools/)
   - 阅读一些关于算法和数据结构的书籍

3. ASP.NET Core 基础

   - [MVC](https://docs.microsoft.com/zh-cn/aspnet/core/mvc/overview?view=aspnetcore-6.0)
   - [REST](https://docs.microsoft.com/zh-cn/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio)
   - [Razor Pages](https://docs.microsoft.com/zh-cn/aspnet/core/razor-pages/?view=aspnetcore-6.0&tabs=visual-studio)
   - [Razor Components](https://docs.microsoft.com/zh-cn/aspnet/core/blazor/components/?view=aspnetcore-6.0)
   - [Middlewares](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/middleware/?view=aspnetcore-6.0)
   - [Filters & Attributes](https://docs.microsoft.com/zh-cn/aspnet/core/mvc/controllers/filters?view=aspnetcore-6.0)
   - [Application Settings & Configurations](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/configuration/?view=aspnetcore-6.0)
   - [Authentication](https://docs.microsoft.com/zh-cn/aspnet/core/security/authentication/?view=aspnetcore-6.0)
   - [Authorization](https://docs.microsoft.com/zh-cn/aspnet/core/security/authorization/introduction?view=aspnetcore-6.0)
   - [IdentityServer](https://identityserver4.readthedocs.io/en/latest)
   - [Auth0](https://auth0.com/docs)
   - [OIDC](https://openid.net/connect)

4. SOLID

    - [单一责任原则 (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [开放封闭原则 (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [里氏替换原则 (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [接口分离原则 (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [依赖倒置原则 (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

5. 依赖注入

   1. DI 容器
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/dependency-injection)
      - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
      - [Ninject](http://www.ninject.org)
      - [Castle Windsor](https://github.com/castleproject/Windsor)
	  - [Simple Injector](https://github.com/simpleinjector/SimpleInjector)
   2. [生命周期](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/dependency-injection#service-lifetimes)
   3. [Scrutor](https://github.com/khellang/Scrutor)

6. 数据库

   1. 关系型
      1. [SQL Server](https://www.microsoft.com/zh-cn/sql-server/sql-server-2019)
      2. [PostgreSQL](https://www.postgresql.org)
      3. [MariaDB](https://mariadb.org)
      4. [MySQL](https://www.mysql.com)
   2. 云数据库
      - [CosmosDB](https://docs.microsoft.com/zh-cn/azure/cosmos-db/)
      - [DynamoDB](https://aws.amazon.com/cn/dynamodb/)
   3. 搜索引擎
      - [ElasticSearch](https://www.elastic.co)
      - [Solr](http://lucene.apache.org/solr)
      - [Sphinx](http://sphinxsearch.com)
   4. NoSQL
      - [Redis](https://redis.io)
      - [MongoDB](https://docs.microsoft.com/zh-cn/aspnet/core/tutorials/first-mongo-app)
      - [Apache Cassandra](http://cassandra.apache.org)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org)

7. 缓存

   1. [内存缓存](https://docs.microsoft.com/zh-cn/aspnet/core/performance/caching/memory)
   2. [分布式缓存](https://docs.microsoft.com/zh-cn/aspnet/core/performance/caching/distributed)
      1. [Redis](https://redis.io/)
         1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
         2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
      2. [Memcached](https://memcached.org)
   3. Entity Framework 二级缓存
      1. [EFSecondLevelCache.Core](https://github.com/VahidN/EFSecondLevelCache.Core)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)

8. 日志

   1. 日志框架
      - [Serilog](https://github.com/serilog/serilog)
      - [NLog](https://github.com/NLog/NLog)
   2. 日志管理系统
      - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)
      
9. API客户端和通信

    1. REST
       - [OData](https://devblogs.microsoft.com/odata/experimenting-with-odata-in-asp-net-core-3-1)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. [gRPC](https://docs.microsoft.com/zh-cn/aspnet/core/grpc)
    3. GraphQL
       - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

10. 实时通信

   - [SignalR](https://docs.microsoft.com/zh-cn/aspnet/core/signalr/introduction)
   - [WebSockets](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/websockets)
   
11. 对象映射

   - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
   - [Mapster](https://github.com/MapsterMapper/Mapster)
   - [ExpressMapper](http://expressmapper.org/)
   - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   
12. 任务调度

   - [Background Service](https://docs.microsoft.com/zh-cn/aspnet/core/fundamentals/host/hosted-services)
   - [HangFire](https://github.com/HangfireIO/Hangfire)
   - [Quartz](https://github.com/quartznet/quartznet)
   - [Coravel](https://github.com/jamesmh/coravel)  
    
13. 测试

    1. 单元测试
       1. 框架
          - [xUnit](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-mstest)
       2. 模拟
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. 断言
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. 集成测试
       - [WebApplicationFactory](https://docs.microsoft.com/zh-cn/aspnet/core/test/integration-tests)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    3. 行为测试
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    4. 端到端测试
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

14. 微服务

    1. 消息总线
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/zh-cn/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. 消息队列
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
       - [CAP](https://github.com/dotnetcore/CAP)
    3. API 网关
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
    4. 容器化
       - [Docker](https://www.docker.com)
    5. 服务编排
       - [Kubernetes](https://kubernetes.io)
       - [Docker Swarm](https://docs.docker.com/engine/swarm)
    6. 反向代理
       - [YARP](https://github.com/microsoft/reverse-proxy)
    7. 其他
       - [Orleans](https://github.com/dotnet/orleans)
       - [Steeltoe](https://steeltoe.io)
       - [Dapr](https://github.com/dapr/dapr)
       - [Tye](https://github.com/dotnet/tye)

15. 持续集成与部署
    - [Github Actions](https://github.com/features/actions)
    - [Azure Pipelines](https://azure.microsoft.com/zh-cn/services/devops/pipelines/)
    - [Travis CI](https://travis-ci.org)
    - [Jenkins](https://www.jenkins.io)
    - [Circle CI](https://circleci.com)
    - [TeamCity](https://www.jetbrains.com/teamcity)

16. 设计模式

    - [CQRS](https://docs.microsoft.com/zh-cn/azure/architecture/patterns/cqrs)
    - [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
    - [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
    - [Builder](https://www.dofactory.com/net/builder-design-pattern)
    - [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
    - [Facade](https://www.dofactory.com/net/facade-design-pattern)

17. 客户端库
    - [Blazor](https://docs.microsoft.com/zh-cn/aspnet/core/blazor/)

18. 模板引擎

   - [Razor](https://docs.microsoft.com/zh-cn/aspnet/core/mvc/views/razor)
   - [DotLiquid](https://github.com/dotliquid/dotliquid)
   - [Scriban](https://github.com/lunet-io/scriban)
   - [Fluid](https://github.com/sebastienros/fluid)

19. 进一步了解的类库

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)    
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)

