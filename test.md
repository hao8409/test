- ### 与客户相关
	- VD01 建立客户 Create customer
	  VD02 更改客户 Change customer  
	  VD03 显示客户 Display customer  
	  VK11 创建条件 Create Condition  
	  VK12 修改条件 Change Condition  
	  VK13 显示条件 Display Condition  
	  VA21 创建报价 Create Quotation  
	  VA22 更改报价 Change Quotation  
	  VA23 显示报价 Display Quotation  
	  VA01 创建销售订单 Create Sales Order  
	  VA02 修改销售订单 Change Sales Order  
	  VA03 显示销售订单 Display Sales Order  
	  VA05 销售订单清单 List of Sales Orders  
- ### 发货单维护和查询
	- VL01N 创建交货 Create Delivery
	  VL02N 更改交货 Change Delivery  
	  VL03N 显示交货 Display Delivery  
	  VL06O 查询销售订单 Query Sales Order  
	  VLSP 拆分发货单 Split Sales Order  
	  VL22 拆分发货单 Split Delivery  
	  VL09 取消发货过账 Cancel Goods Issue for Delivery Note  
	  VL10D STO发货单创建 Extended Mult. Processing Deliveries  
	  VKM5 对因信用控制冻结的发货单解冻 Block Delivery  
- ### 运单维护
	- VT01N 创建发运 Create shipment
	  VT02N 更改发运 Change shipment  
	  VT03N 显示发运 Display shipment  
	  MB5T 显示在途库存 Stock view  
- ### 发票创建
	- VF01 创建出具发票凭证 Create Billing Document
	  VF02 更改出具发票凭证 Change Billing Document  
	  VF03 显示出具发票凭证 Display Billing Document  
	  VF04 处理出具发票到期清单 Process Billing Due List  
	  VF11 取消出具发票凭证 Cancel Billing Document  
- ### SAP MM(物料管理)常用事务代码T-Code
	- MM01 - 创建物料主数据
	  XK01 - 创建供应商主数据  
	  ME11 - 创建采购信息记录  
	  ME01 - 维护货源清单  
	  ME51N- 创建采购申请  
	  ME5A - 显示采购申请清单  
	  ME55 - 批准采购申请（批准组：YH）  
	  ME57 – 分配并处理采购申请  
	  MB21 - 预留  
	  MB24 - 显示预留清单  
	  ME21N- 创建采购订单  
	  ME28 - ^^批准采购订单^^（批准组：YS）  
	- ME9F - 采购订单发送确认
	  ME2L - 查询供应商的采购凭证  
	  ME31 - 创建采购协议  
	  MD03 - 手动MRP  
	  MD04 - 库存需求清单（MD05 - MRP清单）  
	  MRKO - 寄售结算  
	  MELB - 采购申请列表（需求跟踪号）  
	  ME41 - 创建询价单  
	  ME47 - 维护报价  
	  ME49 - 价格比较清单  
	  MI31 - 建立库存盘点凭证  
	  MI21 - 打印盘点凭证  
	  MI22 - 显示实际盘点凭证内容  
	  MI24 - 显示实际盘点凭证清单  
	  MI03 - 显示实际盘点清单  
	  MI04 - 根据盘点凭证输入库存计数  
	  MI20 - 库存差异清单  
	  MI07 - 库存差额总览记帐  
	  MI02 - 更改盘点凭证  
	  MB03 - 显示物料凭证  
	  ME2O - 查询供应商货源库存  
	  MB03 - 显示物料凭证  
	  MMBE - 库存总览  
	  MB5L - 查询库存价值余额清单  
	  MCBR - 库存批次分析  
	  MB5B - 查询每一天的库存  
	  MB58 - 查询客户代保管库存  
	  MB25 - 查询预留和发货情况MB51  
	  MB5S - 查询采购订单的收货和发票差异  
	  MB51 - 物料凭证查询（可以按移动类型查询）  
	  ME2L - 确认采购单  
- ### ABAP开发
	- SE80 进入开发
		- package是传输的重要组成部分
		- 释放传输请求号后, 才能进行传输(发布)
	- DWDM ABAP开发文档
	- ^^SE09^^ 查看请求
	- ^^SE38^^ 释放请求
	- ^^migo^^ 查看物料异动
	- ==se37== 查看功能模组
	- ^^se93^^ 根据tcode查程序
- ### 其他
	- 显示tcode: 其他-设定-显示技术名称
	- SE16N: 删除ZDBNAME1表数据
	- SM30: 查看维护表
	- STMS: 传送请求
	- #### 查看表
		- SE11 - ABAP字典(查看表)
		- MASS - 存储了主要业务对象相关的表
