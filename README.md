# thread-pool
thread-pool
调用方式：
1、实现接口WorkInfer中的生产者方法和消费者方法
2、PoolUtil.buildPool(Pool.K_SEND_BILL, 5, (WorkInfer<BillSend>) billSendService).setResidence(true);
