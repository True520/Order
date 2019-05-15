2018年天津市大学生创新训练项目—“基于Android的无线点餐系统的设计与研究”。
研究并设计一基于Android的无线点餐系统，系统能实现顾客就餐全过程的自动化管理。对于系统功能设计：主要包括功能框架和设计模块，其中功能框架主要包括登录模块、点餐模块、结账模块和餐台管理；功能模块设计分为服务器和客户端，具体包括登录功能、用户管理、菜谱管理、系统管理。各模块之间互相依赖，形成一个完整的无线点餐系统手机（平板）客户端与服务器的交互设计系统。
具体研究内容为：
A、确立物理架构：Android系统客户端通过无线网络访问后台Web服务器，如果需要数据访问，则访问后台数据库服务器；
B、确立技术选型：Android客户端选用JAVA技术，网络通信选用Apache Http协议，而中间Web服务器采用Servlet响应可客户请求。后台数据库使用JDBC来访问数据库，Android客户端部分数据的存储则采用SQLite数据库；
C、进行系统规划和需求分析，通过数据流程图、实体属性图分析数据间的关系，设计并创建一个合理可靠的数据库；
D、实现客户端功能设计，基于Android开发平台，前端客户端功能模块大概分为锁定桌号、桌号查询、菜品查询、加菜功能、退菜功能、结算功能；
E、实现服务器端功能设计，后端服务器功能模块大概分为用户评价管理、桌号管理、菜品管理、订单管理、信息管理；
F、后端服务器采用Tomcat服务器，利用JDBC访问后台数据库，Servlet响应HttpRequest请求，并返回响应结果，在此过程中采用MVC+DAO的设计模式及分层的开发思想。
