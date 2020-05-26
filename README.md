场景背景：
“好饿”公司提供在线订餐配送服务。具体业务数据表模型如图。

功能需求：
1. 对于顾客，实现顾客（customer）在线基于餐厅（restaurant）的菜单（menu_dish），在线下单；对于未接单的订单，可以修改
2. 对于顾客，实现顾客（customer）查询自己下单，并能够查看订单详情（订单状态，总价 ，点菜集合）
3. 对于店家，实现店家查询订单，并接单。

技术要求：
1. 基于spring boot，orm使用jpa(mybatis)
2. db可选（mysql，h2，mongdb），数据可自行构造
3. 实现功能需求的REST API
加分项：
4. 合理的使用设计模式实现功能
5. Domain Model实现
6. REST API标准实现
