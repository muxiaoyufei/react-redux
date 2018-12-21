# react-redux
react数据管理工具redux的使用

# 数据流是什么？为什么要用数据流
 -- 数据流是我们的行为与响应的抽象
 -- 使用数据流帮助我们明确了行为对应的响应
# react与数据流的关系
  -- react 是纯 V 层框架，需要数据流进行支撑
# 主流数据流框架、我们为什么使用redux
  -- Flux/reFlux/Redux
  -- redux优势  简单/单一状态树
# 单向数据流 redux概述
  https://github.com/muxiaoyufei/react-redux/blob/master/src/images/3f1d26d73827d9068e22ae5be46e2d1.png
  
# redux 相关内容
  -- action 是行为的抽象，是普通js对象，一般由方法生成，必须有一个type
  -- reducer 是响应的抽象，是纯方法,传入旧状态和action,返回新状态
  -- store action作用于store,reducer根据store响应，store是唯一的，store包括了完整的state，state完全可预测
    