# DotNet 資源大全中文版 

我想很多程序員應該記得GitHub 上有一個Awesome - XXX 系列的資源整理。[awesome-dotnet](https://github.com/quozd/awesome-dotnet) 是由quozd 發起和維護。內容包括：編譯器、壓縮、應用框架、應用模板、加密、數據庫、反編譯、IDE、日誌、風格指南等。

Awesome 系列雖然挺全，但基本只對收錄的資源做了極為簡要的介紹，如果有更詳細的中文介紹，對相應開發者的幫助會更大。這也是我們發起這個開源項目的初衷。

* * *

### 我們要做什麼？

- 基於awesome-dotnet 列表，我們將對其中的各個資源項進行編譯整理。此外還將從其他來源補充好資源。
- 整理後的內容，將收錄在[伯樂在線資源頻道](http://hao.importnew.com/)。可參考已整理的內容：
  - 《[Scrapy：Python的爬蟲框架](http://hao.importnew.com/python-scrapy/)》
  - 《[Flask：一個使用Python編寫的輕量級Web應用框架](http://hao.importnew.com/flask/)》

* * *

### 如何參與本項目？

<!-- 從下面的目錄來看，本項目的工作量小不了，所以非常期待能有更多程序員一起來參與。

不過加入前，有幾個小要求：

* 英文還不錯，能讀懂英文並用自己的話複述；
* 在用DotNet；

如有興趣，請加QQ：50872495。加Q 時請註明「DotNet大全」
 -->
* * *

### 如何為列表貢獻新資源？

歡迎大家為列表貢獻高質量的新資源，提交PR時請參照以下要求：

* 請確保推薦的資源自己使用過
* 提交PR時請註明推薦理由

資源列表管理收到PR請求後，會定期（每週）在微博轉發本週提交的PR列表，並在微博上面聽取使用過這些資源的意見。確認通過後，會加入資源大全。

感謝您的貢獻！

* * *

### 本項目的參與者

- 維護者：
- 貢獻者：[Erucy](http://www.importnew.com/members/Erucy)、[heavenwing](https://github.com/heavenwing)、[Podolski](https://github.com/ circler3)、[JRoger](https://github.com/Oger-Me)、[cuibty](https://github.com/cuibty)、[tangxuehua](https://github.com/tangxuehua/) 、[KingNight67](https://github.com/KingNight67)、[xiaotupansy](https://github.com/xiaotupansy)、你

注：名單不分排名，不定期補充更新

<!-- ### 獎勵計劃

雖然獎勵可能並不是你加入的主要原因，但還是有必要提一下：

* 整理超過20 個資源後，可在伯樂在線上開通打賞；
* 每整理20 個資源，有機會獲得技術書籍或各種有意思的創意、極客產品；
* [獎勵詳情](http://hao.importnew.com/rewards/) -->

* * *

（注：下面用[$] 標註的表示收費工具，但部分收費工具針對開源軟件的開發/部署/託管是免費的）

## API

* 框架
    * NancyFx：輕量、用於構建HTTP 基礎服務的非正式（low-ceremony）框架，基於.Net 及Mono 平台。[官網](https://github.com/NancyFx/Nancy)
    * ASP.NET WebAPI：快捷創建HTTP 服務的框架，可以廣泛用於多種不同的客戶端，包括瀏覽器和移動設備。[官網](http://www.asp.net/web-api/)
    * ServiceStack：架構縝密、速度飛快、令人愉悅的web 服務。[官網](https://github.com/ServiceStack/ServiceStack)
    * Nelibur：Nelibur 是一個使用純WCF 構建的基於消息的web 服務框架。Nelibur 可以便捷地創建高性能、基於消息的web 服務，使得你全面擁有WCF 的強大能力。[官網](https://github.com/Nelibur/Nelibur)
* WebAPI Contrib：幫助你提高ASP.NET Web API 能力的開源項目集合。[官網](https://github.com/WebApiContrib/WebAPIContrib)

## 應用框架（Application Frameworks）

* ASP.NET Boilerplate：現代ASP.NET MVC web 應用程序的入門，包含最佳實踐和最流行的工具。[官網](https://github.com/aspnetboilerplate/aspnetboilerplate)
* Orleans：Orleans 框架提供了直接構建分佈式、大規模計算應用的方法，無需學習和使用複雜的並行或擴展模型。[官網](https://github.com/dotnet/orleans)
* CoreFX：corefx 倉庫包含了.NET 核心功能庫的實現（被稱為“CoreFX”）。包含了System.Collections、System.IO、System.Xml 以及諸多其它組件。目前構建並運行於Windows 平台。你可以關注這個倉庫，了解在未來的幾個月內即將增加的對Linux 和Mac 的支持。[官網](https://github.com/dotnet/corefx)
* CSLA .NET：業務層開發框架[http://www.cslanet.com](http://www.cslanet.com)。[官網](https://github.com/MarimerLLC/csla)
* Mono：Mono 是ECMA CLI、C# 以及.NET 的開源實現。[官網](https://github.com/mono/mono)
* Mono-Addins：Mono.Addins 是一個通用框架，用於創建可擴展的應用程序<del><span style="color: #ff0000;">，</del>以及這些應用程序的擴展插件。[官網](https://github.com/mono/mono-addins)
* Spring.Net：Spring.NET 是一個開源的應用程序框架，可以便捷地創建企業級.NET 項目。[官網](https://github.com/spring-projects/spring-net)

## 應用模板（Application Templates）

* MVC.Template：ASP.NET MVC 5 入門項目模板。[官網](https://github.com/NonFactors/MVC.Template)
* ProjectScaffold：F# 基金會推薦的.NET 解決方案的原型——包括文件系統的搭建、用於管理依賴的Paket 以及用於自動化構建、測試的FAKE。默認情況下，構建流程也會對文檔進行編譯，並生成NuGet 程序包。[官網](https://github.com/fsprojects/ProjectScaffold)
* Side-Waffle ：包含大量有用的Web 和桌面開發模板。[Side-Waffle](https://github.com/LigerShark/side-waffle)
* Template10 ：帶有設計模式的Windows 10 模板。[Template10](https://github.com/Windows-XAML/Template10)

## 人工智能（Artificial Intelligence）

* AIMLBot（Program#）：使用C# 編寫的一個小型、快速、兼容標準、易於定制的聊天機器人，基於AIML （人工智能標記語言Artificial Intelligence Markup Language）。[官網](http://aimlbot.sourceforge.net/)
* SIML：智能綜合智能標記語言（Synthetic Intelligence Markup Language），下一代聊天機器人及數字助手語言。[官網](http://simlbot.com/)

## 程序集處理（Assembly Manipulation）

* dnSpy：dnSpy 是一個.NET 程序集編輯器、反編譯器和調試器，來自ILSpy 分支。[官網](https://github.com/0xd4d/dnSpy)
* Fody：織入（weaving）.net 程序集的可擴展工具。[官網](https://github.com/Fody/Fody)
* Mono.Cecil：Cecil 類庫用於生成和檢查ECMA CIL 程序和庫。[官網](https://github.com/jbevain/cecil)

## 資源（Assets）

* Cassette：管理.NET web 應用程序資源（腳本、css 和模板）[Cassette](https://github.com/andrewdavey/cassette)
* NodeAssets：.net 資源管理器，通過SignalR 實時更新css，也可以使用NodeJS 編譯器。[官網](https://github.com/ajorkowski/NodeAssets)
* Bundler：編譯和最小化Less、Sass、Stylus、Css、JS、CoffeeScript、LiveScript 文件。MVC集成了MVC 和ServiceStack。[官網](https://github.com/ServiceStack/Bundler)
* ClientDependency：壓縮CSS與JS，提供WebForm與MVC版本。[官網](https://github.com/Shazwazza/ClientDependency)
* SquishIt：讓你**輕鬆**合併一些css 和javascript。[官網](https://github.com/jetheredge/SquishIt)

## 認證和授權（Authentication and Authorization）

* ASP.NET Identity：用於ASP.NET 應用程序的新身份系統。[官網](https://aspnetidentity.codeplex.com/)
* DotNetOpenAuth：OpenID、OAuth 和InfoCard 協議的一個C# 實現。[官網](https://github.com/DotNetOpenAuth/DotNetOpenAuth)
* Logibit Hawk：一個F# [Hawk](https://github.com/hueniverse/hawk#usage-example) 認證庫。[官網](https://github.com/logibit/logibit.hawk/)
* IdentityModel：.NET 4.5 和MVC4、Web API 身份和訪問控制的輔助庫。[官網](https://github.com/IdentityModel)
* IdentityServer：可擴展的OAuth2 和OpenID 連接提供程序框架。[官網](https://github.com/IdentityServer)
* OAuth：超輕量級OAuth 1.0a 簽名生成庫，C# 編寫。[官網](https://github.com/danielcrenna/oauth)

## 自動構建（Build Automation）

* Psake：基於.NET 的自動化構建工具，使用PowerShell 編寫。[官網](https://github.com/psake/psake)
* FAKE：F# Make，一個跨平台自動構建系統。[官網](https://github.com/fsharp/FAKE)
* Invoke-Build：PowerShell 自動構建和測試工具，靈感來自Psake。[官網](https://github.com/nightroman/Invoke-Build)
* MSBuild：微軟構建引擎（MSBuild）是.NET 和Visual Studio 的構建平台。[官網](https://github.com/Microsoft/msbuild)
* Cake：Cake（C# Make）使用C# DSL 的跨平台自動構建系統。[官網](https://github.com/cake-build/cake)

## 緩存（Caching）

* CacheCow：ASP.NET Web API HTTP 客戶端和服務器端緩存實現。[官網](https://github.com/aliostad/CacheCow)
* Akavache：一個異步、持久化的鍵值存儲。[官網](https://github.com/akavache/Akavache)
* CacheManager：是用C#為.NET寫的緩存管理抽象層，支持多種緩存工具，可以實現層次化的緩存。[官網](http://cachemanager.michaco.net)

## CLI

* Command Line Parser：Command Line Parser 類庫為CLR 應用程序提供了一套簡潔的API，用於處理命令行參數及相關任務。[官網](https://github.com/gsscoder/commandline)
* Fluent Command Line Parser：一個簡單、強類型的.NET C# 命令行解析庫，交互方式流暢易用。[官網](https://github.com/fclp/fluent-command-line-parser)
* Power Args：PowerArgs 將命令行參數轉換為.NET 對象，便於程序使用。它還提供了大量可選的擴展，例如參數校驗、自動生成使用幫助、tab 補全等等。[官網](https://github.com/adamabdelhamed/PowerArgs)
* UnionArgParser：針對F# 應用程序的聲明式CLI 參數和XML 配置解析器。[官網](https://github.com/nessos/UnionArgParser)

## CLR

* CoreCLR：coreclr repo 包含了完整的.NET 核心運行時實現（稱為“CoreCLR”）。它包括RyuJIT、.NET GC、非託管代碼交互（native interop）等諸多組件。它目前構建和運行於Windows 平台。你可以關注這個倉庫，了解未來的幾個月內即將增加的對Linux 和Mac 的支持。[官網](https://github.com/dotnet/coreclr)

## CMS

* Composite C1：一個web 內容管理系統，著重在用戶體驗及適應性。[官網](https://compositec1.codeplex.com/)
* mojoPortal：MojoPortal 是一個可擴展、跨數據庫、移動友好的web 內容管理系統（CMS）和web 應用程序框架，使用C# ASP.NET 編寫。[官網](https://mojoportal.codeplex.com/)
* N2CMS：開源、輕量、代碼優先的CMS，可以無縫地集成到任何MVC 項目中。[官網](http://www.n2cms.com/)
* Orchard：免費、開源、專注社區的項目，目標是在ASP.NET 平台上提供應用程序和可重用組件。[官網](https://github.com/OrchardCMS/Orchard)
* Piranha CMS：Piranha 是一個有趣、快速、輕量級的.NET 框架，用於開發基於cms 附帶其它功能的web 應用程序。它基於ASP.NET MVC 和Web 頁面創建，完全兼容Visual Studio 和WebMatrix。[官網](https://github.com/PiranhaCMS/Piranha)
* Umbraco：Umbraco 是一個免費開源的內容管理系統，基於ASP.NET 平台構建。[官網](https://github.com/umbraco/Umbraco-CMS)

## 代碼分析和度量（Code Analysis and Metrics）

* CodeMaid：Visual studio 擴展，用於清理、挖掘和簡化C#、C++、F#、VB、PHP、JSON、XAML、XML、ASP、HTML、CSS、LESS、SCSS、JavaScript 和TypeScript 代碼。[官網](http://www.codemaid.net/)
* StyleCop：StyleCop 使用一組風格和一致性規則，對C# 源代碼進行分析和強制性檢查。[官網](https://stylecop.codeplex.com/)
* Gendarme：可擴展的、基於規則的工具，用於在.NET 應用程序和類庫中查找問題。[官網](https://github.com/spouliot/gendarme)
* Metrics-Net：捕獲CLR 和應用程序級別的度量值。所以你知道它的功能。[官網](https://github.com/danielcrenna/metrics-net)

## 編譯器（Compiler）

* Bridge.NET：將C# 編譯成JavaScript 的開源編譯器[http://bridge.net/](http://bridge.net/)。[官網](https://github.com/bridgedotnet/Bridge)
* ClojureCLR：從Clojure 到CLR 的轉換，是Clojure 項目的一部分。[官網](https://github.com/clojure/clojure-clr)
* F#：F# 編譯器、核心庫和工具——更安全、更快、代碼更好的函數式編程語言。[官網](https://github.com/fsharp/fsharp/)
* FunScript：F# 到JavaScript 的編譯器，可以通過TypeScript 類型提供程序使用JQuery 等JavaScript 庫。[官網](http://funscript.info/)
* JSIL：CIL 到Javascript 的編譯器[http://jsil.org/](http://jsil.org/)。[官網](https://github.com/sq/JSIL)
* Mono-basic：Visual Basic 編譯器和運行時。[官網](https://github.com/mono/mono-basic)
* Nemerle：Nemerle 是一個.NET 平台高級靜態類型編程語言。它提供函數式、面向對象式和命令式編程語言的特性。它擁有一個簡單的類似C# 的語法和強大的元編程（meta-programming）系統。[官網](http://nemerle.org) [Github](https://github.com/rsdn/nemerle)
* Netjs：.NET 到TypeScript 和JavaScript 編譯器。兼容可移植類庫。你甚至可以使用EXE 文件。[官網](https://github.com/praeclarum/Netjs)
* Roslyn：.NET 編譯平台（“Roslyn”）提供開源的C# 和Visual Basic 編譯器，包含豐富的代碼分析API。它可以使用和Visual Studio 一樣的API 來構建代碼分析工具。[官網](https://github.com/dotnet/roslyn)
* VisualFSharp：Visual F# 編譯器和工具。[官網](https://github.com/Microsoft/visualfsharp)

## 壓縮（Compression）

* SharpCompress：SharpCompress 是一個用於.NET、Mono、Silverlight、WP7 的壓縮類庫，可以解壓rar、7zip、zip、tar、bzip2 和gzip，提供單向讀取和隨機文件訪問API。支持對zip/tar/bzip2/gzip 進行寫入的實現。[官網](https://github.com/adamhathcock/sharpcompress)
* DotNetZip.Semverd：一個開源項目，提供對ZIP 文件處理的.NET 類庫和相關工具。（分支自[**已經不再維護的** DotNetZip](http://dotnetzip.codeplex.com)）[DotNetZip.Semverd](https://github.com/haf/DotNetZip.Semverd)
* SharpZipLib：一個Zip、GZip、Tar 和BZip2 的類庫，完全由C# 編寫，面向.NET 平台。[官網](http://icsharpcode.github.io/SharpZipLib/)

## 持續集成（Continuous Integration）

* TeamCity：可以直接使用的，可擴展、面向開發人員友好的構建服務器——開箱即用**。** **[$]**[官網](http://www.jetbrains.com/teamcity/)
* CruiseControl.NET：一個自動化持續集成服務器，使用.NET Framework 實現。[官網](http://www.cruisecontrolnet.org/)
* MyGet：為NuGet、NPM、Bower 和VSIX 提供持續集成、部署、宿主程序包倉庫的服務。**[[開源軟件免費](https://www.myget.org/opensource)]** **[$]**[官網](http://www.myget.org/)
* AppVeyor：.NET 持續構建和部署服務。**[$]** **[開源軟件免費]**[官網](http://www.appveyor.com/)

## 加密（Cryptography）

* BouncyCastle：和.Net 的System.Security.Cryptography 一起，在CLR 上提供加密算法的實現。[官網](https://bouncycastle.org/)
* HashLib：HashLib 包含了幾乎所有你見過的哈希算法，它幾乎支持所有東西並且非常容易使用。[官網](http://hashlib.codeplex.com/)
* libsodium-net：libsodium for .NET——一個安全加密庫。[官網](https://github.com/adamcaudill/libsodium-net)
* StreamCryptor：使用libsodium 和protobuf 對流進行加密和解密。[官網](https://github.com/bitbeans/StreamCryptor) 

## 數據庫（Database）

* BrightstarDb：BrightstarDB 是一個原生的.NET RDF 三元組數據庫（triple store）。[官網](https://github.com/BrightstarDB/BrightstarDB)
* Event Store：開源的功能性數據庫，支持使用JavaScript 進行複雜事件處理。[https://geteventstore.com](https://geteventstore.com) [官網](https://github.com/EventStore/EventStore) 
* LiteDB：一個.NET 的NoSQL 單文件文檔數據庫。[官網](https://github.com/mbdavid/LiteDB)
* RavenDB：支持linq 的.NET 文檔數據庫。[官網](https://github.com/ravendb/ravendb)

## 數據庫驅動（Database Drivers）

* MySQL Connector：完全託管的MySQL ADO.NET 數據庫提供程序、連接器。[官網](https://dev.mysql.com/downloads/connector/net/)
* Npgsql：Postgresql 的.Net 數據提供程序。[官網](https://github.com/npgsql/Npgsql)
* MongoDB：MongoDB 官方C# 驅動。[官網](https://github.com/mongodb/mongo-csharp-driver)
* ServiceStack Redis：.NET 領先的C# Redis 客戶端。[官網](https://github.com/ServiceStack/ServiceStack.Redis)
* StackExchange Redis：來自StackExchange 的通用redis 客戶端。[官網](https://github.com/StackExchange/StackExchange.Redis)
* Cassandra：DataStax 開發的Apache Cassandra .NET 驅動程序。[官網](https://github.com/datastax/csharp-driver)
* Couchbase：couchbase 官方.NET 客戶端庫，基於Enyim memcached 客戶端。[官網](https://github.com/couchbase/couchbase-net-client)
* Firebird.NET：由C# 編寫的.NET 數據提供程序，提供對Firebird API 的高性能原生實現。[官網](http://sourceforge.net/projects/firebird/)

## 反編譯（Decompilation）

* ILSpy：ILSpy 是一個開源的.NET 程序集查看器和反編譯器。[官網](http://ilspy.net/)
* JustDecompile Engine：[JustDecompile](http://www.telerik.com/products/decompiler.aspx) 反編譯引擎。[官網](https://github.com/telerik/JustDecompileEngine)
* de4dot：是一款強大的.NET程序集反混淆和脫殼工具（開源GPLv3）。[官網](https://github.com/0xd4d/de4dot)

## 部署（Deployment）

* Unfold：基於Powershell 的.net web 應用程序部署解決方案。[官網](https://github.com/thomasvm/unfold)

## DirectX

* SlimDX：為.NET 應用程序提供的DirectX 封裝。[官網](http://www.slimdx.org)
* SharpDX：SharpDX 是一個開源項目，為.Net 及所有Windows 平台提供完整的DirectX API，可以開發高性能的遊戲、2D/3D圖形渲染以及實時音頻應用程序。[官網](https://github.com/sharpdx/SharpDX)

## 分佈式計算（Distributed Computing）

* Project Orleans：Orleans 框架提供了直接構建分佈式、大規模計算應用的方法，無需學習和使用複雜的並行或擴展模型。由微軟研究院開發。[官網](https://github.com/dotnet/orleans)
* Akka.net：Akka.NET 是流行的Java/Scala 框架Akka 的.NET 版本。它由社區提供，與Typesafe（原始的Java、Scala 版本的開發商）無關。[官網](https://github.com/akkadotnet/akka.net)

## 文檔（Documentation）

* Sandcastle：Sandcastle 幫助文件生成器和NDoc 類似。[官網](http://shfb.codeplex.com/)
* SharpDox：一個c# 文檔工具。[官網](https://github.com/Geaz/sharpDox)
* Swashbuckle：向WebApi 項目無縫地添加swagger 文檔（譯者註：swagger 是一套用於生成、描述、展現RESTful 風格web 服務文檔的框架和規範）。[官網](https://github.com/domaindrivendev/Swashbuckle)
* NSwag：通過Swagger規範生成.NET、TypeScript的Web API客戶端。[官網](https://github.com/NSwag/NSwag)
* F# Formatting：F# 和C# 項目的文檔工具，文檔生成自F# 腳本文件、Markdown 文檔、內嵌XML 或Markdown評論。[官網](http://tpetricek.github.io/FSharp.Formatting/)

## 電子商務和支付（E-Commerce and Payments）

* Paypal Merchant SDK：Paypal Merchant官方.NET SDK。[官網](https://github.com/paypal/merchant-sdk-dotnet)
* NopCommerce：nopCommerce。開源的電子商務購物車（ASP.NET MVC）。[官網](https://nopcommerce.codeplex.com/)
* ServiceStack.Stripe：針對stripe.com REST API 的強類型.NET 客戶端。[官網](https://github.com/ServiceStack/Stripe)
* SmartStoreNET：免費ASP.NET MVC 電子商務購物車解決方案。[官網](https://github.com/smartstoreag/SmartStoreNET)
* Stripe.Net：Stripe.net 是針對[http://stripe.com](http://stripe.com) 完整服務的.net api。[官網](https://github.com/jaymedavis/stripe.net)
* BeYourMarket：BeYourMarket 是一個點對點的市場框架。[官網](http://beyourmarket.com) [Github](https://github.com/beyourmarket/beyourmarket)
* Virto Commerce：Virto Commerce 是第二個版本，也是唯一的開源許可下的企業級別電子商務產品。Virto Commerce 基於.NET 4.5，使用了MVC、IoC、EF、Azure、Angular JS 等其他先進技術。它可以在微軟的雲平台（Azure）、亞馬遜雲服務（AWS）和企業內部部署。[官網](https://github.com/VirtoCommerce/vc-community)

## 環境管理（Environment Management）

* DNVM：.NET SDK 管理器，一組命令行工具，用於更新和配置需要使用的運行時環境（DNX）。[官網](https://github.com/aspnet/dnvm)

## ETL

* Reactive ETL：Reactive ETL 使用.NET 反應性擴展框架（reactive extensions） 重寫了Rhino ETL。[官網](https://reactiveetl.codeplex.com/)

## 遊戲（Game）

* MonoGame：一個用來創建跨平台遊戲的強大框架。[官網](https://github.com/mono/MonoGame)
* CocosSharp：CocosSharp 是Cocos2D 和Cocos3D API 的C# 實現版本，可以在所有支持MonoGame 的平台上運行。[官網](https://github.com/mono/CocosSharp)
* Duality：Duality 是一個2D 遊戲開發框架。專注於功能的模塊化，自帶一個可視化編輯器。[官網](https://github.com/AdamsLair/duality)
* Paradox：Paradox 遊戲引擎。[官網](https://github.com/SiliconStudio/paradox)

## 地理信息系統（Gis）

* NetTopologySuite：一個在.NET 平台上實現快速、可靠的GIS 系統解決方案。[官網](https://github.com/NetTopologySuite/NetTopologySuite/)
* SharpMap：一個易於使用的地圖庫，可以用於web 和桌面應用程序。[官網](https://sharpmap.codeplex.com/)

## Git工具（Git Tools）

* Bonobo Git Server：Bonobo Git Server for Windows 是一個web 應用程序，可以安裝在你自己的IIS 上，用於管理和連接你的git 倉庫。[官網](http://bonobogitserver.com) [Github](https://github.com/jakubgarfield/Bonobo-Git-Server)
* GitExtensions：GitExtensions 包含資源管理器擴展、Visual Studio 2008/2010/2012/2013 插件和一個獨立的Git 倉庫工具。[官網](http://gitextensions.github.io/)[Github](https://github.com/gitextensions/gitextensions)
* GitLink：讓用戶可以單步調試託管在GitHub 或BitBucket 上的代碼。[官網](https://github.com/CatenaLogic/GitLink)
* GitVersion：根據你的Git 倉庫的狀態生成一個語義化版本號（Semantic Version Number）。[官網](https://github.com/Particular/GitVersion)
* LibGit2Sharp：LibGit2Sharp 帶來了libgit2 所有的功能和速度，是一個本地Git 實現，可以運行在.Net 和Mono 平台。[官網](https://github.com/libgit2/libgit2sharp)
* NGit：NGit 是JGit 移植到C# 的版本。[官網](https://github.com/mono/ngit)
* posh-git：Git 的PowerShell 環境。[官網](https://github.com/dahlbyk/posh-git)
* GitCandy：GitCandy是一個web 應用程序，可以安裝在你自己的IIS 上，用於管理和連接你的git 倉庫。[Github](https://github.com/Aimeast/GitCandy)
    
## 圖形（Graphics）

* Oxyplot：OxyPlot 是一個.NET 跨平台繪圖庫。[官網](https://github.com/oxyplot/)
* OpenTK：Open Toolkit 是一個封裝了OpenGL、OpenCL 和OpenAL 的高級底層C# 開發庫。[官網](http://www.opentk.com/)
* NGraphics：NGraphics 是一個.NET 跨平台矢量圖形渲染庫。[官網](https://github.com/praeclarum/NGraphics)

## GUI

* MahApps.Metro：用於創建Metro 風格WPF 應用的工具箱。[官網](https://github.com/MahApps/MahApps.Metro)
* Callisto：用於Windows 8 XAML 應用的控件工具箱。包含若干UI 控件，讓你更容易地創建符合Windows UI 風格規範的Windows 商店應用。[官網](https://github.com/timheuer/callisto)
* ObjectListView：ObjectListView 使用C# 封裝了.NET 的ListView 控件。它使得ListView 更加易用，並且加入了一些新特性。[官網](http://objectlistview.sourceforge.net/cs/index.html)
* DockPanelSuite：靈感來自Visual Studio 的停靠窗口（docking）類庫，用於.NET WinForm 應用。[官網](http://dockpanelsuite.com/) 
* AvalonEdit：在SharpDevelop 中使用，基於WPF 的文本編輯器組件。[官網](https://github.com/icsharpcode/AvalonEdit) 
* XWT：跨平台UI 工具箱，用於創建.NET 和Mono 桌面應用程序。[官網](https://github.com/mono/xwt)
* Gtk#：Gtk# 是Gtk+ GUI 工具箱的Mono/.NET 版本，絕大多數Mono 中的GUI 應用都基於它構建。[官網](https://github.com/mono/gtk-sharp)
* MaterialDesignInXamlToolkit：用於創建Material Design 風格WPF 應用的工具箱。[官網](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit)
* Eto.Forms：跨平台的GUI 框架，用於.NET 和Mono 下的桌面和移動應用程序。[官網](https://github.com/picoe/Eto)
* Dragablz：可拖拽、可分離（tearable，譯者註：即拖拽標籤頁成為獨立窗口）的WPF 標籤頁控件（類似Chrome）。支持佈局和主題，包含兼容MahApps 和Material Design 的主題。[官網](https://github.com/ButchersBoy/Dragablz)
* Fluent.Ribbon：Fluent Ribbon Control Suite 是一個在WPF 中實現Office 和Windows 8 風格的Ribbon 庫。[官網](https://github.com/fluentribbon/Fluent.Ribbon)

## HTML 和CSS（HTML and CSS）

* AngleSharp：支持構建完整的HTML5 DOM 和CSS3 模型。[官網](https://github.com/FlorianRappl/AngleSharp)
* CsQuery：jQuery 風格的HTML5 解析器，可與DOM 交互。[官網](https://github.com/jamietre/CsQuery)
* dotless：ruby Less CSS 庫的.NET 移植版本。[官網](https://github.com/dotless/dotless)
* ExCSS：C# 的CSS3 解析器開發庫。[官網](https://github.com/TylerBrinks/ExCSS)
* FluentBootstrap：讓ASP.NET MVC 和WebPages 更容易使用Boostrap CSS 框架。[官網](http://fluentbootstrap.com)
* HtmlAgilityPack：一個靈活的HTML 解析器，可以對DOM 進行讀寫，支持XPATH 和XSLT。[官網](http://htmlagilitypack.codeplex.com/)
* Jumony：類似HtmlAgilityPack框架，性能有改善。[官網](https://github.com/Ivony/Jumony)

## HTTP

* Http.fs：`[F#]` 中的一個函數式HTTP 客戶端。[官網](https://github.com/relentless/Http.fs)
* RestSharp：.NET 下簡單的REST 和HTTP API 協議客戶端。[官網](https://github.com/restsharp/RestSharp)
* EasyHttp：C# Http開發庫。[官網](https://github.com/hhariri/EasyHttp)
* Refit：Xamarin 和.NET 下自動生成強類型的REST 庫。[官網](https://github.com/paulcbetts/refit) 
* RestEase：類型安全且易於使用的REST API 客戶端庫，簡單可定制。大部分靈感來自Refit。[官網](https://github.com/canton7/RestEase)

## IDE

* SharpDevelop：用於.NET 編程語言的免費IDE。[官網](https://github.com/icsharpcode/SharpDevelop)
* MonoDevelop：MonoDevelop 是一個跨平台的IDE，主要面向Mono/.NET 開發者。[官網](https://github.com/mono/monodevelop)
* Visual Studio Express：用於.NET 開發的免費、輕量版本的Visual Studio。[官網](http://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx)
* Visual Studio Community：功能完整的免費IDE。[官網](http://msdn.microsoft.com/en-us/visual-studio-community-vs.aspx)
* Waf DotNetPad：簡單快速的代碼編輯器，讓開發C# 或Visual Basic 充滿樂趣。[官網](http://dotnetpad.codeplex.com) 
* Visual Studio Code：非常棒的編輯器，來自微軟，基於GitHub Atom。[官網](https://code.visualstudio.com/)
* Rider：跨平台.Net IDE。[官網](https://www.jetbrains.com/rider/)

## 圖像處理（Image Processing）

* ImageResizer：在圖片URL 後面增加命令，在幾毫秒內獲取修改後的版本，支持實時的對圖片進行縮放、編輯。[官網](http://imageresizing.net/)
* ImageProcessor：開源.NET 庫，用於實時處理圖片。[官網](http://imageprocessor.org/)
* DynamicImage：高性能開源圖片處理庫，用於ASP.NET。[官網](http://dynamicimage.apphb.com/)
* MetadataExtractor：從圖片中提取Exif、IPTC、XMP、ICC 等其它元數據信息。[官網](https://github.com/drewnoakes/metadata-extractor-dotnet)
* Emgu CV：OpenCV 的.NET 跨平台封裝。[官網](http://www.emgu.com/wiki/index.php/Main_Page)

## 安裝工具（Install Tools）

* Wix Toolset：強大的工具集，用於創建你自己的Windows 安裝程序。[官網](http://wixtoolset.org/)
* Squirrel：Squirrel 即是一套工具也是一個類庫，可以無安全管理Windows 桌面程序的安裝和更新。[官網](https://github.com/squirrel/squirrel.windows)

## 國際化（Internationalization）

* i18n：ASP.NET MVC 智能國際化工具。[官網](https://github.com/turquoiseowl/i18n)

## 互操作（Interoperability）

* CefSharp：Chromium Embedded Framework 的.NET 支持（WPF 和WinForm）。[官網](https://github.com/cefsharp/CefSharp)
* CppSharp：在C# 中平滑使用C++ API 的工具。[官網](https://github.com/mono/CppSharp)
* Sharpen：Sharpen 是db4o 編寫的Eclipse 插件，可以讓你把Java 項目轉換為C#。[官網](https://github.com/mono/sharpen)
* CXXI：C++ 互操作框架。[官網](https://github.com/mono/cxxi)

## IoC

* Castle Windsor：Castle Windsor 是一個用於.NET 和Silverlight 的成熟的控制反轉（IoC） 容器。[官網](https://github.com/castleproject/Windsor)
* Unity：輕量級、可擴展的依賴注入容器，支持構造函數、屬性和方法調用注入。[官網](https://unity.codeplex.com/)
* Autofac：令人著迷的.NET IoC 容器。[官網](https://github.com/autofac/Autofac)
* Ninject：.net 依賴注入的忍者。[官網](https://github.com/ninject/ninject)
* StructureMap：.Net 最早的IoC/ID 容器。[官網](https://structuremap.github.io/)
* Spring.Net：Spring.NET 是一個開源應用程序框架，可以便捷地創建企業級.NET 應用。[官網](https://github.com/spring-projects/spring-net)
* LightInject：一個超輕量級IoC 容器。[官網](https://github.com/seesharper/LightInject) 
* TinyIoC：單文件、簡單、跨平台的IoC 容器。[官網](https://github.com/grumpydev/TinyIoC)

## 日誌（Logging）

* Essential Diagnostics：為內置System.Diagnostics 命名空間擴展功能，提供更靈活的日誌功能。[官網](http://essentialdiagnostics.codeplex.com/)
* NLog：先進的.NET 和Silverlight 日誌工具。[官網](https://github.com/nlog/NLog/)
* ELMAH：ELMAH 官方網站。[官網](https://code.google.com/p/elmah/)
* Elmah MVC：MVC 版Elmah。[官網](https://github.com/alexanderbeletsky/elmah-mvc)
* Logary：Logary 是一個mono 和.Net 平台下高性能、多目標的日誌、度量、追踪和健康檢查庫。支持多目標，為微服務構建。[官網](http://logary.github.io/)
* Log4Net：Apache log4net 工具庫能夠幫助程序員向多種不同的目標輸出日誌語句。[官網](https://logging.apache.org/log4net/)
* Serilog：一個NoSQL 時代下簡單直接的日誌庫。將多個優秀的傳統結構化分析日誌功能合併到一個易於使用的程序集中。[官網](https://github.com/serilog/serilog)
* StackExchange.Exceptional：Stack Exchange 網絡使用的錯誤處理程序。[官網](https://github.com/NickCraver/StackExchange.Exceptional)
* Semantic Logging Application Block (SLAB)：為內置System.Diagnostics.Tracing 命名空間（EventSource類）擴展功能，支持將日誌記錄到多個容器中，包括Azure 表存儲、數據庫、文件（JSON、XML、文本文件）。通過ETW 支持進程內和進程外的日誌記錄，支持Rx 進行實時的事件過濾和聚合。[官網](http://slab.codeplex.com/)
* Exceptionless：一個免費開源分佈式系統的日誌收集框架，它可以應用在基於ASP.NET，ASP.NET Core，Web Api，Web Forms，WPF，Console，MVC 等技術棧的應用程序中，並且提供了Rest接口可以應用在Javascript，Node.js 中。[官網](http://exceptionless.com/) [Github](https://github.com/exceptionless/Exceptionless)

## 機器學習和數據科學（Machine Learning and Data Science）

* Accord.NET：機器學習框架，包含了音頻和圖像處理的庫（計算機視覺、計算機聽覺、信號處理和統計）。[官網](http://accord-framework.net/)
* Accord.NET Extensions：高級圖像處理和計算機視覺算法擴展。[官網](https://github.com/dajuric/accord-net-extensions)
* AForge.NET：為計算機視覺和人工智能領域的開發者和研究人員提供的框架（包括圖像處理、神經網絡、遺傳算法、機器學習、機器人科學）。[官網](http://www.aforgenet.com/)
* Deedle：處理探索性數據的數據幀和時序庫，支持C# 和F#。[官網](http://bluemountaincapital.github.io/Deedle/)
* FsLab：數據科學和機器學習庫的集合，支持F# 和.NET。[官網](http://www.fslab.org)
* numl：包含最流行的監督學習和無監督學習算法，盡量減少創建預測模型時的衝突。[官網](https://github.com/sethjuarez/numl) 
* R Provider：將R 語言包和函數封裝為類型安全的類型提供程序供F# 調用。[官網](http://bluemountaincapital.github.io/FSharpRProvider/) 
* F# Data：F# 類型提供程序，訪問XML、JSON、CSV 和HTML 文件（基於樣例文檔），以及WorldBank 數據。[官網](http://fsharp.github.io/FSharp.Data/)

## Markdown 處理（Markdown Processors）

* MarkdownSharp：C# 實現的開源Markdown 處理器，在Stack Overflow 中使用。[官網](https://code.google.com/p/markdownsharp/)
* F# Formatting：用於生成F# 和C# 項目文檔的工具。該工具庫的核心組件中包含了可擴展的Markdown 解析器。[官網](http://tpetricek.github.io/FSharp.Formatting/)
* CommonMark.NET：CommonMark 規範的C# 實現，用於將Markdown 文檔轉換為HTML。為最佳性能和可移植性進行了優化。[官網](https://github.com/Knagis/CommonMark.NET)

## 郵件（Mail）

* FluentEmail：System.Net.Mail 的一個流式（Fluent）封裝，支持razor 模板引擎。[官網](https://github.com/lukencode/FluentEmail)
* MailKit：完整的跨平台的郵件協議棧，包括IMAP、POP3、SMTP，支持驗證等特性。基於MimeKit 構建。[官網](https://github.com/jstedfast/MailKit)
* MimeKit：跨平台.NET MIME 創建和解析庫，支持S/MIME、PGP、TNEF 和Unix mbox spools。[官網](https://github.com/jstedfast/MimeKit)
* PreMailer.Net：一個C# 開發庫，將你的樣式表嵌入到內置的style 屬性中，最大限度支持郵件客戶端。[官網](https://github.com/milkshakesoftware/PreMailer.Net)

## 數學（Mathematics）

* MathNet：Math.NET 是一個開源項目，旨在創建和維護涵蓋基礎數學在內的工具集，面向高級和日常需要使用此類功能的.Net 開發人員。[官網](http://www.mathdotnet.com/)

## 多媒體（Media）

* TagLib#：TagLib#（即taglib-sharp）是一個讀寫媒體文件元數據的庫，支持視頻、音頻和照片格式。[官網](https://github.com/mono/taglib-sharp)

## 度量（Metrics）

* C# StatsD Client：Etsy StatsD 服務器的C# 客戶端。[官網](https://github.com/goncalopereira/statsd-csharp-client)
* App Metrics：開源跨平台.NET 報表度量開發庫。[官網](https://app-metrics.io/)、[GitHub](https://github.com/AppMetrics/AppMetrics)

## 微框架（Micro Framework）

* .NET Micro Framework Interpreter：Microsoft® .NE​​T Micro Framework（NETMF）是一個在Visual Studio 中提供為小型設備上編寫嵌入式應用的框架。[官網](https://github.com/NETMF/netmf-interpreter)

## 雜項（Misc）

* .NET Fiddle：在瀏覽器中編寫、編譯並運行C# 代碼。相當於C# 版本的JSFiddle。[官網](https://dotnetfiddle.net/)
* AzureCrawler：從Angular、Ember、Durandal 或任何JavaScript 應用中獲取HTML 快照。[官網](https://github.com/yagopv/AzureCrawler)
* BitSharp：C# 比特幣節點。[官網](https://github.com/pmlyon/BitSharp)
* CSScript：CS-Script 是一個基於CLR 的腳本系統，使用C# 作為編程語言。CS-Script 目前針對微軟的CLR 實現（.NET 2.0/3.0/3.5/4.0/4.5）並完整支持Mono。附帶很多附加特性，比如腳本宿主。[官網](http://www.csscript.net/)
* CsvHelper：幫助讀寫CSV 文件的開發庫。[官網](https://github.com/JoshClose/CsvHelper)
* FluentValidation：一個小型的.NET 校驗庫，使用流式接口和lambda 表達式構建校驗規則。[官網](https://github.com/JeremySkinner/FluentValidation)
* Humanizer：Humanizer 能夠在.NET 平台上滿足所有針對字符串、枚舉、日期、時間、時間範圍、數字等類型數據的操作和顯示要求。[官網](https://github.com/MehdiK/Humanizer)
* LINQPad：一個C#/VB/F# 的便簽本，能夠立即執行任何表達式、語句塊或程序，帶有富文本顯示等有用的特性。同樣可以讓你使用LINQ 進行交互性數據庫查詢。[$]（譯者註：也有免費許可，但是功能受限）。[官網](http://www.linqpad.net)
* Polly：快捷便利的異常處理策略，例如重試、始終重試、等待並重試或斷路（Circuit Break）等行為。（.NET 3.5、4.0、4.5、PCL、Xamarin）[官網](https://github.com/michael-wolfenden/Polly)
* Rant：Rant 程序文本生成DSL（領域特定語言）。[官網](http://berkin.me/rant) [Github](https://github.com/TheBerkin/Rant)
* ScriptCS：使用文本編輯器、nuget 和強大的Roslyn 來編寫C# 應用！[官網](https://github.com/scriptcs/scriptcs)
* EntityFramework-Plus：Entity Framework 擴展，提供工具類、Bulk 操作、批處理/批量更新、查詢緩存/過濾器/Future、審計等功能。[官網](http://entityframework-plus.net/)、[GitHub](https://github.com/zzzprojects/EntityFramework-Plus)

## MVVM

* Caliburn.Micro：小型但功能強大的框架，可以用來給所有XAML 平台創建應用。它對MV* 模式的強大支持可以讓你快速構建你的解決方案，與此同時不必犧牲代碼質量和可測試能力。[官網](https://github.com/Caliburn-Micro/Caliburn.Micro) 
* [MVVM Light Toolkit](http://hao.importnew.com/mvvm-light-toolkit/)：該工具箱主要是用來加速創建和開發MVVM 應用，適用於WPF、Silverlight、Windows Store（RT）和Windows Phone 平台。[官網](https://mvvmlight.codeplex.com/)
* Catel：Catel 是一個應用開發平台，主要著眼在MVVM（WPF、Silverlight、Windows Phone 及WinRT）以及MVC（ASP.NET MVC）。Catel 的核心部分包含IoC 容器、模型、校驗、備忘錄模式（memento）、消息中介（message mediator）、參數檢查等。[官網](https://catel.codeplex.com/)
* UpdateControls：Update Controls 不需要你實現INotifyPropertyChanged 接口或聲明一個DependencyProperty。可以將控件直接關聯到CLR 屬性，這使得它完美貼合MVVM 模式。[官網](http://updatecontrols.net/cs/)
* ReactiveUI：一個.NET 下的MVVM 框架，集成了反應性擴展框架（Rx），允許開發者使用WPF、Windows Store Apps、WP8 或Xamarin 創建優雅的、可測試的應用。[官網](https://github.com/reactiveui/reactiveui/)
* Okra App Framework：一個以app 為中心的Windows 8.1 MVVM 框架，融合依賴注入，包含一套完整的Visual Studio MVVM 模板。[官網](http://okraframework.github.io)
* WPF Application Framework (WAF)：一個輕量級的框架，能夠幫助你創建結構優雅的WPF 應用。支持你使用分層架構和MVVM 模式。[官網](http://waf.codeplex.com)
* MVVMCross：跨平台mvvm 移動開發框架，針對WP7 和WP8 的WPF/Silverlight、Android 的Mono、iOS 的MonoTouch 以及WPA8.1/Windows 8.1 商店應用的Windows Universal 項目。它使用可移植類庫（PCL）來支持可維護的跨平台C# 原生應用。[官網](https://github.com/MvvmCross/MvvmCross)
* Stylet：最小化MVVM 框架（參考Caliburn Micro），包含了良好的文檔、高覆蓋率的測試以及自帶的IoC 容器。[官網](https://github.com/canton7/stylet/)
* Gemini：類似Visual Studio Shell 的IDE 框架。基於WPF、AvalonDock 和Caliburn Micro 構建。[官網](https://github.com/tgjones/gemini)

## Office

* ClosedXML：ClosedXML 能夠讓開發人員更便捷地創建Excel 2007、2010 文件。[官網](https://closedxml.codeplex.com/)
* [NPOI](http://hao.importnew.com/npoi/)：該項目是.NET 版本的POI 項目，原始的Java 版本位於[http://poi.apache.org/](http:/ /poi.apache.org/) 。[官網](http://npoi.codeplex.com/)
* [EPPlus](http://hao.importnew.com/epplus/)：EPPlus 是一個.net 類庫，用於讀寫Open Office Xml 格式的Excel 2007、2010 文件（xlsx）。[官網](http://epplus.codeplex.com/)
* Open XML SDK：Open XML SDK 是一個開源庫，用於處理Open XML 文檔（包括DOCX、XLSX 和PPTX）。[官網](https://github.com/officedev/open-xml-sdk)

## ORM

* Entity Framework：對象關係映射器（ORM）框架，讓.NET 開發人員使用領域特定的對象來處理關係型數據。[官網](https://github.com/aspnet/EntityFramework)
* BL Toolkit：.NET 平台的業務邏輯工具箱。[官網](https://github.com/igor-tkachev/bltoolkit)
* Dapper：一個超小型、快捷輕便的ORM 框架。[官網](https://github.com/StackExchange/dapper-dot-net)
* Dapper Extensions：小型類庫，對Dapper 的功能進行補充，為你的簡單傳統CLR 對象提供基礎的CRUD（Get、Insert、Update、Delete） 操作。[官網](https://github.com/tmsmith/Dapper-Extensions)
* NHibernate：NHibernate 對象關係映射器（移植自Java 平台的Hibernate）。[官網](https://github.com/nhibernate)
* Fluent NHibernate：便捷、無需使用XML、編譯安全、自動化、基於約定命名的NHibernate 映射庫。[官網](https://github.com/jagregory/fluent-nhibernate)
* FluentMigrator：.net 下的便捷的遷移框架。[官網](https://github.com/schambers/fluentmigrator)
* ServiceStack.OrmLite：輕量、簡單、快速、基於命名約定的POCO ORM。[官網](https://github.com/ServiceStack/ServiceStack.OrmLite)
* Massive：小型、令人愉悅的數據訪問工具，始終關愛你直到永遠。[官網](https://github.com/robconery/massive)
* LINQ to DB：最快的LINQ 數據庫訪問庫，簡單、輕量、快速、類型安全，在你的對象（POCO）和數據庫之間搭建橋樑。[官網](https://github.com/linq2db/linq2db)
* SqlSugar：NET 4.+ & .NET CORE 高性能輕量級ORM框架，眾多.NET框架中最容易使用的數據庫訪問技術。[官網](http://www.codeisbug.com) [gi​​thub](https://github.com/sunkaixuan/SqlSugar)
## 包管理（Package Management）

* NuGet：.NET 包管理器。[官網](https://www.nuget.org/)
* MyGet：為NuGet、NPM、Bower 和VSIX 提供程序包倉庫宿主，同樣提供CI 服務。**[開源軟件免費](https://www.myget.org/opensource)** **[$]** [官網](http://www.myget.org/)
* Paket：.NET 的一個包依賴管理器，支持NuGet 包和GitHub 倉庫。[官網](http://fsprojects.github.io/Paket/) [Github](https://github.com/fsprojects/Paket)

## PDF

* ITextSharp：iText 是一個PDF庫，用於創建、修改、檢查和維護Portable Document Format（PDF）格式的文檔**[$]** **開源軟件免費** [官網](https://github .com/itext/itextsharp)

## Profiler

* MiniProfiler：一個簡單但有效的小型profiler，用於ASP.NET 網站。[官網](https://github.com/MiniProfiler/dotnet)
* Glimpse：開源web 診斷平台。[官網](https://github.com/glimpse/glimpse)

## 推送通知（Push Notifications）

* PushSharp：服務器端的推送通知類庫，支持iOS、OSX、Android、Chrome、Windows Phone、Windows 8、Backberry 和Amazon 設備。[官網](https://github.com/Redth/PushSharp)

## 隊列（Queue）

* NServiceBus：.NET 平台下最流行的服務總線。[官網](https://github.com/Particular/NServiceBus)
* RabbitMQ.NET：AMQP 客戶端的C# 實現，通過WCF 綁定到已有的AMQP 服務。[官網](http://hg.rabbitmq.com/rabbitmq-dotnet-client/)
* [NetMQ](http://hao.importnew.com/netmq/)：NetMQ 是ZeroMQ 純C# 移植版本。[官網](https://github.com/zeromq/netmq)
* MassTransit：MassTransit 是一個精簡服務總線（lean service bus）的實現，使用.NET Framework 來構建松耦合應用程序。[官網](https://github.com/MassTransit/MassTransit)
* Rebus：Rebus 是一個.NET 平台的精簡服務總線和NServiceBus、MassTransit類似，只不過更加精簡。[官網](https://github.com/rebus-org/Rebus)
* EasyNetQ：易於使用的RabbitMQ .NET API。[官網](https://github.com/mikehadlow/EasyNetQ)
* Warewolf ESB：易於使用的服務總線和微服務平台，可以在一個可視化IDE 中便捷的創建應用和服務。[官網](https://github.com/Warewolf-ESB/Warewolf-ESB)
* CAP：用於處理分佈式事務的.Net 標准開發庫。支持EventBus，輕量級、高效且易於使用。[官網](https://github.com/dotnetcore/CAP)

## 響應式編程（Reactive Programming）

* Rx.NET：Reactive Extensions （Rx）庫使用觀察者序列（observable sequences）和LINQ 風格的查詢操作，來進行異步和基於事件的程序開發。[官網](https://github.com/Reactive-Extensions/Rx.NET)
* Dynamic Data：用於集合的響應​​式編程框架。[官網](https://github.com/RolandPheasant/DynamicData)

## 計劃調度（Scheduling）

* [QuartzNet](http://hao.importnew.com/quartz-net/)：Quartz 是.NET 平台的企業級調度器。[官網](https://github.com/quartznet/quartznet)
* Hangfire：在ASP.NET 應用中，超簡單地實現自主引導（fire-and-forget）、延遲和周期重複任務。高級版需要收費。[官網](https://github.com/HangfireIO/Hangfire)
* Hangfire.Redis.StackExchange：Hangfire的redis擴展庫，基於StackExchange.Redis的開源實現。[官網](https://github.com/marcoCasamento/Hangfire.Redis.StackExchange)
* Azure WebJobs：Azure WebJobs 是Azure中App Services一個附屬服務，為Azure中運行的Web App提供後台運行環境（支持多種語言編寫Job），有.NET的SDK[開源](https://github. com/Azure/azure-webjobs-sdk)，並且可以直接添加擴展[也開源](https://github.com/Azure/azure-webjobs-sdk-extensions)。[官網](https://azure.microsoft.com/en-us/documentation/articles/app-service-webjobs-readme/)

## SDK 和API 客戶端（SDK and API Clients）

* AWS SDK：AWS SDK for .NET 讓.NET 開發者可以便捷地操作Amazon Web Services。[官網](https://github.com/aws/aws-sdk-net)
* Azure PowerShell：一組PowerShell 命令行，讓開發者和管理員開發、部署和管理Microsoft Azure 應用。[官網](https://github.com/Azure/azure-powershell)
* Octokit.NET：.NET 平台下的GitHub API 客戶端庫。[官網](https://github.com/octokit/octokit.net)
* DropNet：Dropbox API 客戶端開發庫。[官網](https://github.com/DropNet/DropNet)

## 搜索（Search）

* Elasticsearch .NET：Elasticsearch.Net & NEST。[官網](https://github.com/elasticsearch/elasticsearch-net)
* PlainElastic.Net：ElasticSearch 的一個簡單的.Net 客戶端。[官網](https://github.com/Yegoroff/PlainElastic.Net)
* SolrNet：.Net 平台下的Solr 客戶端。[官網](https://github.com/mausch/SolrNet)
* Lucene.net：Lucene.Net 是Lucene 搜索引擎庫的移植，使用C# 編寫，面向.NET 環境的用戶。[官網](http://lucenenet.apache.org/)

## 序列化（Serialization）

* Protobuf.NET：Protocol buffers 是Google 使用的二進制序列化格式，在Google 數據通訊中大量使用。[官網](https://github.com/mgravell/protobuf-net)
* [Json.NET](http://hao.importnew.com/json-net/)：.NET 平台下流行的、高性能JSON 框架。[官網](https://github.com/JamesNK/Newtonsoft.Json)
* ServiceStack.Text：在servicestack.net 中使用的JSON、JSV、CSV 文本序列化器。[官網](https://github.com/ServiceStack/ServiceStack.Text)
* Msgpack-Cli：MessagePack 的CLI 實現。[官網](https://github.com/msgpack/msgpack-cli)
* Jil：.NET 平台下快速的JSON 序列化器，基於Sigil （在StackOverflow 中使用）。[官網](https://github.com/kevin-montrose/Jil)
* ProtoBuf：根據.proto 規範，為protocol buffer 序列化內容生成C# 代碼。[官網](https://github.com/hultqvist/ProtoBuf)
* F# Data：F# 類型提供程序，訪問XML、JSON、CSV 和HTML 文件（基於樣例文檔），以及訪問WorldBank 數據。[官網](http://fsharp.github.io/FSharp.Data/)
* Bond：跨平台框架，用於處理系統化（schematized）數據。支持跨平台的序列化、反序列化，以及強大的通用機制來高效處理數據。[官網](https://github.com/Microsoft/bond)

## 狀態機（State machines）

* Stateless：直接使用.NET 代碼創建一個狀態機和輕量的基於狀態機的工作流。[官網](https://github.com/nblumhardt/stateless)
* Automatonymous：.Net 平台的狀態機庫，允許你編寫流式API風格的狀態機。[官網](https://github.com/MassTransit/Automatonymous)

## 靜態網站生成（Static Site Generators）

* Pretzel：.NET 平台下的網站生成工具（包含後續的一些功能）。[官網](https://github.com/Code52/pretzel)
* Sandra.Snow：.NET 平台的靜態網站生成工具，借鑒Jekyll。[官網](https://github.com/Sandra/Sandra.Snow)
* Wyam：簡單易用、高度模塊化、擁有強大配置能力的靜態網站生成工具。[官網](http://wyam.io)

## 風格指南（Style Guide）

* C# Style Guide：StackOverflow 上的C#風格指南Q & A。[官網](http://stackoverflow.com/questions/4678178/style-guide-for-c)
* C# Coding Conventions：MSDN 官方的C# 代碼約定。[官網](http://msdn.microsoft.com/en-us/library/vstudio/ff926074.aspx)

## 模板引擎（Template Engine）

* RazorEngine：基於微軟Razor 解析器引擎的開源模板引擎。[官網](https://github.com/Antaris/RazorEngine)
* Nustache：無邏輯模板的開源庫。[官網](https://github.com/jdiamond/Nustache) 
* DotLiquid：Ruby Liquid 模板語言的C# 移植版本。[官網](https://github.com/dotliquid/dotliquid)

## 測試（Testing）

* AutoFixture：AutoFixture 是一個用於.NET 的開源框架，用於簡化單元測試中的設置（Arrange）階段。[官網](https://github.com/AutoFixture/AutoFixture)
* FakeItEasy：.NET 平台的一個簡單的mocking 庫。[官網](https://github.com/FakeItEasy/FakeItEasy)
* Fluent Assertions：一組.NET 擴展方法，可以讓你更自然地指定TDD 或BDD 風格測試的期望值。[官網](https://github.com/dennisdoomen/fluentassertions)
* Fuchu：F# 的單元測試庫，通過tests-as-values 機制讓你更容易創建領域特定語言（DSL）。[官網](https://github.com/mausch/Fuchu)
* Machine.Specifications：Machine.Specifications （MSpec）是一個上下文、規範框架，忽略了語言本身的干擾，簡化了測試。[官網](https://github.com/machine/machine.specifications)
* Moq：.NET 平台下最流行和友好的mocking 框架。[官網](https://github.com/Moq/moq4)
* NBuilder：快速創建測試對象。[官網](https://github.com/garethdown44/nbuilder)
* NSubstitute：一個友好的.NET mocking 框架。[官網](http://nsubstitute.github.io/)
* NUnit：[官網](https://github.com/nunit/nunit-framework)
* Rhino Mocks：.NET 平台的動態Mocking 框架。[官網](https://github.com/ayende/rhino-mocks)
* Shouldly：Shouldly 是一個斷言（assertion）框架，主要功能是在斷言失敗時，給出簡單明了並且友好的錯誤信息。[官網](https://github.com/shouldly/shouldly)
* SpecFlow：將業務需求綁定到.Net 代碼。[官網](https://github.com/techtalk/SpecFlow/)
* xUnit：xUnit.net 是一個.NET 平台下免費、開源、專注社區的單元測試框架。[官網](https://github.com/xunit/xunit)
* BenchmarkDotNet：功能強大的基礎測試.NET 開發庫。[官網](http://benchmarkdotnet.org/)、[GitHub](https://github.com/dotnet/BenchmarkDotNet)

## 交易（Trading）

* Lean：Lean 引擎是一個開源的，完全由C# 託管代碼編寫的交易算法引擎，用於桌面和雲端。[官網](https://lean.quantconnect.com) [Github](https://github.com/QuantConnect/Lean)
* StockSharp：交易和算法交易（algorithmic trading）的開源平台（用於股票市場、外匯市場、比特幣和期權交易）。[官網](https://github.com/StockSharp/StockSharp)

## Visual Studio 插件（Visual Studio Plugins）

* Web Essentials：Web Essentials 為Visual Stduio 擴展了大量的特性，提供了web 開發人員盼望多年的功能。[官網](https://github.com/madskristensen/WebEssentials2013)
* VsVIM：Visual Studio 中的VIM。[官網](https://github.com/jaredpar/VsVim)
* Nuget Package Manager：NuGet 是微軟開發平台（包括.NET）的包管理器。[官網](http://visualstudiogallery.msdn.microsoft.com/27077b70-9dad-4c64-adcf-c7cf6bc9970c)
* SideWaffle：Visual Studio 2012、2013 中的一組項目模板集合，讓web 開發人員更加輕鬆。[官網](https://github.com/ligershark/side-waffle)
* Resharper：Visual Studio 開發人員生產力工具**[$]** [官網](http://www.jetbrains.com/resharper/)
* Refactoring Essentials：開源C# 和VB.NET 重構擴展，包括代碼最佳實踐分析器。[官網](http://vsrefactoringessentials.com/)
* CodeContracts：.NET CodeContracts 工具源代碼。[官網](https://github.com/Microsoft/CodeContracts)
* Git Diff Margin：在Visual Studio 滾動條區域實時顯示當前文件在Git 上的差異。[官網](https://github.com/laurentkempe/GitDiffMargin)
* Productivity Power Tools：一組Visual Studio 專業版（及更高版本）的擴展，用於提高開發人員的生產力。[官網](https://visualstudiogallery.msdn.microsoft.com/d0d33361-18e2-46c0-8ff2-4adea1e34fef)

## Web 框架（Web Frameworks）

* ASP.NET MVC：ASP.NET 是一個免費的web 框架，用於創建優秀的web 站點和應用程序。[官網](https://aspnetwebstack.codeplex.com/)
* FubuMVC：.NET 平台下前端控制器（front-controller）風格的MVC 框架。[官網](https://github.com/DarthFubuMVC/fubumvc)
* NancyFx：在.Net 和Mono 平台上創建HTTP 服務的一個輕量級、非正式的框架。[官網](https://github.com/NancyFx/Nancy)
* IISNode：在IIS 中宿主NodeJS 應用程序。[官網](https://github.com/tjanczuk/iisnode)
* Suave.IO：一個框架/庫/web 服務器，當你看到你使用優美的F# 編寫的代碼提前完成了你的項目時，它的存在會讓你喜極而泣。（一個用F# 編寫Web 應用的框架和服務器端）[官網](http://suave.io/)

## Web 服務器（Web Servers）

* EmbedIO：基於Mono 編寫的跨平台的Web 服務器。[官網](https://github.com/unosquare/embedio)
* XSP：Mono 中的ASP.NET 宿主服務器。該模塊包含了Apache 模塊、FastCGI 模塊，可以用於掛載到其它web 服務器或是作為一個測試用的獨立服務器存在（類似微軟的Cassini 項目）。[官網](https://github.com/mono/xsp)
* Jexus：強勁、堅固、免費、易用的Linux ASP.NET服務器。[官網](http://www.jexus.org/)

## WebSocket

* [SignalR](http://hao.importnew.com/signalr/)：ASP.NET 庫，開發者可以通過它在web 應用程序中非常簡單地實現實時功能。[官網](https://github.com/SignalR/SignalR)
* Fleck：Fleck 是一個C# 實現的WebSocket 服務器。分支自Nugget 項目。[官網](https://github.com/statianzo/Fleck)
* Websocket-Sharp：WebSocket 協議的C# 實現，包含客戶端和服務器端。[官網](https://github.com/sta/websocket-sharp)
* XSockets：提供了一組工具，可以在微軟.NET 等平台上構建一個實時應用程序。[官網](http://xsockets.net/)
* WebSocket4NET：.NET 2.0+、Xamarin、Mono、Silverlight、Windows Phone 以及WinRT 下的WebSocket 客戶端。[官網](https://websocket4net.codeplex.com)
* [SuperSocket](http://hao.importnew.com/supersocket/)：一個輕量級, 跨平台而且可擴展的.Net/Mono Socket 服務器程序框架。[官網](http://www.supersocket.net/)

## Windows 服務（Windows Services）

* TopShelf：一​​個簡單的服務宿主框架，使用.NET 構建Windows 服務。[官網](https://github.com/Topshelf/Topshelf)

## 通訊框架（Communication Frameworks）

* DotNetty：一個快速開發高性能、高可靠性的非阻塞的事件驅動網絡應用框架。[官網](https://github.com/Azure/DotNetty)
* Helios：一套高性能的Socket通信中間件。[官網](https://github.com/helios-io/helios)
* enode： 一個用來開發DDD、CQRS、EDA 以及事件驅動應用程序的框架。[官網](https://github.com/tangxuehua/enode)

## 其他列表（Other Lists）

* [.NET-libraries-that-make-your-life-easier](https://github.com/tallesl/.NET-libraries-that-make-your-life-easier)：開源的.NET 庫，讓你的生活更加輕鬆、
* [awesome-LINQ](https://github.com/aloisdg/awesome-linq)：一組精心挑選的超棒的LINQ 類庫、工具等。

<h3 id="websites">知名網站</h3>
*值得關注的DotNet 技術站點。*

<h4>中文站點</h4>

待補充

<h4>英文站點</h4>

* channel9：第9頻道是一個微軟的社區網站，誕生於2004年4月1日。[官網](https://channel9.msdn.com/)
* .NET Blog：一個專門用於.Net 技術交流的博客網站。[官網](https://blogs.msdn.microsoft.com/dotnet/)

<h3 id="weibo-weixin">微信公眾號</h3>
* 「DotNet」：專注.NET 相關內容，包括：.NET 和C# 開發心得、工具資源和相關動態。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c79isfj20460460tr.jpg" width=150 height=150>
