###李龑，男，24岁

* Mobile: 18676651554
* Home: 0755-25709093
* Email: eyeplum@gmail.com
* [Github](https://github.com/eyeplum)   [Twitter](https://twitter.com/eyeplum)   [Google+](https://plus.google.com/103284151248378359229/)   [Weibo](http://weibo.com/eyeplum)


###履历


#####1.［创业公司］［社交 iOS App］校友圈 xiaoyouq.com
---
* 2012.06.01 - 2012.11.01
* 负责校友圈iPad端的开发与部分交互设计
* 团队因为资金原因解散
* __项目经验__
	* __校友圈iPad__
		* [__App Store 已上架__](https://itunes.apple.com/app/xiao-you-quan-zui-zhuan-ye/id555303974?ls=1&mt=8)
		* 5个月的时间共上架了 1.0，1.1，1.2 三个版本
		* 1.0 版实现了 iPad App 与服务器端的基本对接
		* 1.1 版新增了新闻资讯模块和活动聚会模块
		* 1.2 版针对 1.0 和 1.1 的用户列表模块和新闻资讯模块进行了性能优化
			* 用户列表模块中，为了让 iPad 1 代也能流畅运行，效仿 twitter iOS 客户端，直接通过 drawRect 绘制控件，取得了良好的效果
			* 新闻资讯模块通过启用 CATiledLayer 并优化内存使用提高了渲染速度，减少了因内存不足导致的崩溃
		* __涉及的第三方工具、库（主要）：__
			* Cocoapods，管理 Objective-C 第三方库
			* JSONKit，解析 json 数据
			* AFNetworking，通过 AFHTTPClient 处理 App 运行过程中的所有网络请求，通过扩展 UIImageView 异步加载图片
			* SVPullToRefresh，下拉刷新，修改了部分代码以符合项目需要
			* FMDB，解析城市列表、行业列表等 App Bundle 内的 sqlite 数据库资源
			* Nimbus，利用 NIPagingScrollView 在一个页面中展示用户列表，每页 16 个用户
			* DTCoreText，解析服务器返回的新闻 html，通过 DTCoreText 渲染为 AttributedTextView，继承了 DTAttributedTextContentView 以支持文章分栏显示
			* Objective-C-HMTL-Parser，解析服务器返回的新闻 html 内的图片 URL 及说明文字
			* RubyMotion，Ruby iOS 开发环境，可以将 Ruby 代码编译为 Native iOS App，可与 Objective-C 共同使用，籍此可在 iOS 开发时利用许多 Ruby 特性，例如语法更简洁、默认枚举器、RubyGems 等，最初主要是为了配合服务器开发（Ruby on Rails）而使用
			* routable，第三方 RubyGem，提供了一个全局的 NavigationController，方便了复杂情况下的 View 导航
			* bubble-wrap，第三方 RubyGem，提供了一些 iOS API 的 Ruby 写法
			* sugarcube，第三方 RubyGem，提供了一些 iOS API 的 Ruby 写法
	
	
	* __[开源] 基于 iOS UIView 动画的校友圈营销短片__
		* 视频：[优酷](http://v.youku.com/v_show/id_XNDY5MTA0NDA4.html)
		* 源代码：[Github](https://github.com/smartweb/Soulmate)
		* 这是一个用一周时间写的小项目，目的是传播校友圈 xiaoyouq.com
		* 短片的所有动画均由 iOS UIView 动画实现
		* 声音经过后期匹配，字幕也是后期加上的（Apple Final Cut Pro X）
		* __该项目被 RubyMotion 官方 twitter 转载__
		* ![RubyMotion_Retweet](https://raw.github.com/eyeplum/EYEResume/master/img/rubymotion_retweet.png "Rubymotion Retweet")


#####2. 个人项目
---
* __［效率 iOS App］摄影计算__
	* [__App Store 已上架__](https://itunes.apple.com/app/photocalculator/id517131450?ls=1&mt=8)
	* 这是一个帮助摄影师计算摄影参数的 App
	* 被 creativebloq.com 评为 [The 20 best iPhone apps for designers](http://www.creativebloq.com/design-tools/20-useful-iphone-apps-designers-812522?page=1)
* __［教育 iOS App］漢字ちは__
	* [__App Store 已上架__](https://itunes.apple.com/app/kanjichiwa/id575833563?ls=1&mt=8)
	* 这是一个通过联系日文假名与汉字的相似之处来记忆日文假名的 App
	* 技术 Tag：UICollectionView，侘び寂び设计风格
	* ![漢字ちは](https://raw.github.com/eyeplum/EYEResume/master/img/kanjichiwa.png "漢字ちは 截图")
* __［生活 iOS App］放哪了__
	* App Store 审核中
	* 这是一个通过拍摄家中杂物，帮助你记住这些杂物的位置的 App
	* 技术 Tag：CoreData
	* ![放哪了](https://raw.github.com/eyeplum/EYEResume/master/img/放哪了.png "放哪了 截图")
* __［游戏辅助 iOS App］Diamlo（进行中）__
	* 进行中
	* 这是一个读取 Blizzard Diablo 3 [官方 API](http://blizzard.github.com/d3-api-docs/) 的游戏辅助 App
	* 技术 Tag：AFNetworking，CoreData，拟物化设计风格
	* ![Diamlo](https://raw.github.com/eyeplum/EYEResume/master/img/diamlo.jpg "Diamlo 截图")

#####3.其他工作经验
---
* __左氏文化传播有限公司，深圳总部，摄影部副主管__
	* 2011.09 - 2012.03
	* 负责统筹公司的摄影业务，下属摄影师 5 名
	* 负责部分纪实摄影、公关摄影的拍摄任务
	* 纪实摄影成果被收录进了[《再见城中村》摄影展](http://www.douban.com/event/17319068/)
* __佳兆业集团控股有限公司，深圳总部，公共关系部，助理品牌主任__
	* 2010.07 - 2011.08
	* 负责统筹集团的品牌管理工作，下属 13 个分公司的品牌专员
	* 负责集团地产业务产品线的 VI 标准化设计，完成了 2 条产品线的 VI 设计
	* 建立了佳兆业集团影像资料库，并参与了 2 个季度的维护和考核

#####4. 教育经历
---
* __华南理工大学，大学本科__
	* 2006.09 - 2010.07
	* 新闻与传播学院，传播学专业
	* 主要学习方向：互联网用户社群研究、平面设计
	* 写论文时结识了统计学垂直社区“统计之都”，后为其设计了 [logo](http://cos.name/)
* __Ruby 编程语言，自学__
	* 为了能达到校友圈iPad开发所需的 Ruby 能力而自学
	* 学习了基本的语法后在项目中不断更新相关的知识
	* 如今已经可以熟练使用
* __Python 编程语言，自学__
	* 面向对象编程思想入门
* __Scheme 编程语言，自学__
	* 函数式编程思想入门
* __交互设计，自学__
	* 设计心理学、About Face 等教程
	* 学习了基本的以用户体验为中心的思想
	* 可使用 Axure 进行原型设计
