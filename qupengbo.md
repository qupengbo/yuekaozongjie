717 项目流程总结

    1.页面分类
        首页{
            1、首页
                运用swiper封装轮播图实现图片轮播效果
                配置router路由实现一级页面跳转
        }
        分类列表页面
            左右布局排版
        搜索页
            input绑定onClick事件跳转search页面创建div储存历史搜索内容
        购物车
            通过点击每个商品的icon图标 获取商品的id 通过id把数据存到stort中 展示到购物车页面
        我的{
            登录{
                前端通过发送用户名 密码 后台 后台数据库开始查找数据 查找到登录成功 查找失败跳转注册页面
            }
            注册 {
                前端收集用户名 密码 发送给后台 储存的数据库
            }
        }
    common 组件封装
        
        弹出框
                
        轮播图 封装swiper组件 下载第三方插件 
           
        通用商品模块 商品数据存在redux stort中按需加载调用
        
        购物车商品模块

        订单信息模块
    
    技术应用

    React React-redux redux React-router redux-sage

    自适应

    fetch 封装

    node搭建静态服务器 模拟后台接口

    搭建不同环境的脚手架

