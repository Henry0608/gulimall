后台启动流程：
1、启动nacos：startup.cmd -m standalone
2、查看阿里云连接状态 阿里云地址：47.121.199.203 数据库地址
3、启动程序 
    renren-fast 主程序模块
    gulimall-gateway 网关模块
    gulimall-product 商品模块
    gulimall-third-party 阿里云上传模块
    gulimall-member 会员系统
    gulimall-coupon 优惠券积分模块
    gulimall-ware 库存系统模块
4、启动前台 npm run dev