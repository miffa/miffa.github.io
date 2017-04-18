个人简历
--------

基本信息:

  姓名       杨茂林        学历     本科
  ---------- ------------- -------- ----------------------
  联系电话   1591   Email:   yangmaolin83@163.com

专业技能:

1.  六年linux/C++开发经验，熟练掌握C++编程；两年linux/golang开发经验；

2.  熟练掌握Linux网络编程；熟悉TCP/IP协议栈、UDP、http等常用网络协议；熟练使用网络工具分析和定位网络问题

3.  熟练掌握多线程编程；具有丰富的高并发多线程编程经验

4.  熟悉linux操作系统，熟练使用shell脚本进行数据处理，文件处理。

5.  具有高并发大数据消息处理经验，具有分布式系统开发经验，具备架构大型软件的能力

6.  熟悉mysql数据库操作，熟练使用sql对数据进行处理.

7.  熟练和熟练使用zookeeper、kafka、elsticsearch分布式系统

8.  具备独立思考,自主解决问题的能力;具备团队合作协调能力.

有一定的项目管理经验；项目跟踪，风险把控，任务分配，项目规划

工作经历:

  -----------------------------------------------
  时间                工作地点   工作职位
                                 
                                 学历
                                 
                                 英语水平
  ------------------- ---------- ----------------
  2007.12---2012.10   东信北邮   研发工程师

  2012.11---2013.08   宜搜科技   软件工程师

  2013.08---2015.06   搜狐视频   高级软件工程师

  2015.06---2017.03   猎豹移动   高级软件工程师
  -----------------------------------------------

项目开发经验:

1\. 即时通讯系统

项目简述:
支撑liveme直播项目，自主研发的im系统；主要包括发送房间消息、群消息、私信；提供可靠的消息到达机制；

个人职责：系统架构设计、核心方案流程制定、核心代码编写

主要工作业绩：设计出分布式高可用、高扩展、高性能的服务架构；设计编写高效流量控制算法、权重优先级缓存数据结构；可靠的机制保证了不丢消息，提高了消息的到达率；系统采用分布式rpc架构，可以随时对服务进行调整；构建长链接服务，使用内存池对长链接iobuffer进行内存分配优化

2\. 群组服务

项目简述：liveme直播项目转向社交方向，因此立项设计开发了群组关系系统，主要是组织和保存群组关系

个人职责：设计协议、设计和架构系统，带领团队进行研发

主要工作业绩：架构采用http接入层和业务层分离，良好的协议设计可以对逻辑层进行无缝升级；不影响客户端；项目进度把控，如期完成上线；协调客户端与后端服务开发测试；制定对系统的优化方案，降低处理延时；

项目管理：协调、罗列开发计划、任务分配、进度把控

3\. 项目名称: 分布式存储系统

项目简述：现有的redis实例不足以支撑线上的大数据，为此引入了开源项目codis，并对其进行二次开发和优化

个人职责：熟悉源码、搭建系统、修复bug、优化系统（对象池）

主要工作业绩：实现支持磁盘落地存储的类redis系统主从同步；redis大key问题：阻塞删除、阻塞迁移；单key事物

4\. 项目名称: 搜狐影音p2p服务器

项目简述:
p2p服务器主要是利用点对点下载思想，减少用户对cdn视频资源请求，以减少昂贵的带宽资源消耗，本质上该系统是一个分布式的大数据查询系统。主要包括register服务，dispatch分发服务，track服务，统计推送服务。

个人职责：对系统进行研发和优化

主要工作业绩：研发优化p2p后台服务；优化p2p日志系统，优化p2p的分布式数据一致性，优化分发服务的资源调配；优化推送流量控制。

目前p2p系统的分享率达到90%。

5\. 56宝宝app推送系统

项目简述:
56宝宝app消息推送和消息转发服务。实现对app的一些通知进行广播；对app进行点对点消息透传。

个人职责：架构设计推送&消息转发系统，带领开发人员编码和测试

主要工作业绩：完成了推送系统的架构设计和编码工作。推送系统可以灵活的横向扩展；目前单台机器可以保守支持50w并发用户。

6\. 项目名称: 搜狐影音直播平台

项目简述:大型节目直播平台。对视频流进行切片和分发到资源站；利用点播的p2p经验设计出了直播的p2p服务平台

个人职责：设计开发rtmp直播流切片机，设计和开发rtmp数据流的接收和切片分发系统；指导设计和实现直播track系统

主要工作业绩：。

目前平台设计目标支持最高在线人数200w，并可以横向扩展；目前在在直播中国好歌曲，大概用户有1w多，数据量不是很大，节约带宽大概85%。

7\. 项目名称: LBS商家数据分类器

项目简述:
LBS采用商家数据采集自第三方平台。数据整合融合时需要对商家数据进行分类入库。商家分类器的主要功能就是完成对采集到的商家数据进行机器监督式学习分类。

个人职责：调研常用的数据分类方法；设计和开发分类器框架；设计开发具体的分类算法，目前采用到的分类方法有白名单分类、贝叶斯分类方法、决策树分类。

主要工作业绩：独立设计分类器的调度框架，
带领实习生一名进行编码测试，调试，优化。

目前分类器效果为准确率93%，召回率90%。

8\. 项目名称: LBS测试工具-网页解析服务器

项目简述:
商家数据存储在磁盘大文件中，索引信息放在数据库，网页解析服务需要根据用户提供的商家编号从数据库和大文件找到相应的网页信息，解析完成发送给客户呈现。

个人职责：设计和开发网页解析服务器，制定客户端和服务通信协议，通信方式采用socket通信。服务器采用epoll
模型，客户端请求处理采用线程池处理。

主要工作业绩：全权设计和开发解析服务，以及客户端C++客户端和python客户端。

9\. 项目名称: 垃圾短信骚扰电话监控平台

项目简述:骚扰电话垃圾短信监控平台基于移动电话短信信令数据挖掘的数据分析平台。平台数据分析流程：分析数据源话单文件，对数据进行筛选归类，按照设定用户行为规则进行数据分析和筛选，选取用客感兴趣的用户数据，即用户疑似号码。每天处理峰值话单记录数量1.2亿每天，筛选疑似号码1万左右，
确认准确率在20%。

个人职责：项目管理；根据功能实现方案，进行编码调试和测试；对系统进行业务逻辑优化和性能优化。

主要工作业绩：挖掘分析指标，增强用户行为判断准确率；修改关键字模糊匹配算法，增强匹配功能；优化系统处理能力；增加关键字权重判断，提高关键字疑似读匹配灵活度。

教育背景:

  时间                毕业院校       学历   专业
  ------------------- -------------- ------ ------------------
  2003.09---2007.07   长春师范大学   本科   计算机科学与技术

自我评价：

本人忠实诚信,讲原则，说到做到，决不推卸责任；有自制力，做事情始终坚持有始有终，从不半途而废；肯学习,有问题不逃避,愿意虚心向他人学习；自信但不自负,不以自我为中心；愿意以谦虚态度赞扬接纳优越者,权威者；会用100%的热情和精力投入到工作中；平易近人。为人诚恳,性格开朗,积极进取,适应力强、勤奋好学、脚踏实地，有较强的团队精神,工作积极进取,态度认真。

如果有机会加入贵公司，一定竭尽所能，为公司做出更好的软件，创造出更好的业绩。

感谢您阅览我的简历，期待有幸与您共事！

