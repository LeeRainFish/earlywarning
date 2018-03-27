# earlywarning
### 本学期的课程设计，目标是做一个工业预警系统，目前仍在开发过程中，不定时更新，回头会带上朋友写的前端页面。
本课程设计用到的框架基本为  
#### springboot+shiro+springdatajpa+redis+websocket。

老师给的需求如下  

假设工厂里有一些仪器，每个仪器具有一个数值，数值超过一定阈值代表存在异常，需要及时通知检修人员。本系统应实现对仪器的监控，功能如下：  
（1）采用程序模拟一批仪器，按照一定策略产生数值；  
（2）用户能查看仪器的信息；  
（3）用户可以针对每个仪器设置一个告警阈值；  
（4）系统能判断仪器的数值是否超过阈值，并自动向用户发送邮件。  
