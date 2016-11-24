#Spring+Quartz实现定时任务Demo
##Spring+Quartz实现Job有两种方式(第二种)


####Spring整合Quartz实现定时任务步骤很简单，大致需要经过如下几步
1. 创建任务（Job）
2. 配置JobDetail
3. 配置触发器（Trigger）
4. 配置SchedulerFactoryBean