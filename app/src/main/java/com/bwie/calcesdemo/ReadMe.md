1.模块化:
每个module都是一个library不能独立运行
2.组件化:
每个module都是一个组件（application）可以独立运行->模块化测试;
按照业务拆分->商城；用户；社区；资讯 
3.模块化与组件化的区别;
模块化不能独立运行组件化可以独立运行
4.Calces配置组件化:
  自动化构建module-.组合不同应用程序
5.Calces如何使用:
  官网地址:https://github.com/Tangpj/calces-gradle-plugin
  a.添加calces插件：
  plugins {
    id "calces.modules" version "1.0.11"
  }
  b.修改module 下gradle文件插件
  c,项目下的gradle文件中配置项目中的组件
  
    