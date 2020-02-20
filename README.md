# 金融大数据量化分析-2020春

课程共15讲，初步教学计划如下：

## 1. 量化交易体系的开启姿势
* 教学内容: 
    -量化交易概述：起源、发展和交易体系，简单认识交易中的参与者；
    -本课程的整体安排和教学要求
* 学习引导: 
    - 熟悉notebook；
    - 熟悉GitHub
* 作业: 
    - 《黑箱》读书笔记，要求简要论述自己读书后对量化交易系统的理解；2周后交

## 2. 打造稳定交易体系的基础
* 教学内容: 
    - 一个交易策略长什么样
    - 量化策略的六大要素
    - 多因子模型介绍
    - 怎样利用行为金融学扩展量化策略的逻辑来源
* 学习引导: 
    - 参考书目： 《行为金融学》
* 课堂教学计划：

  第一部分：打雪仗模型
  45分钟
  - 交易体系的关键要素
  - 不同风险偏好下的选择
  - 注意事项

  第二部分：行为金融学
  45分钟
  - 回顾EMH
  - 在市场里需要掌握聪明的程度
  - 套利限制和投资者行为

  第三部分：多因子模型
  45分钟
  - 经典派系
  - 单因子检验
  - 怎样享受多因子的好处  

## 3. 创建自己的交易策略
* 教学内容: 
    - 趋势型策略的开发
    - 策略的细节处理和策略检验
* 学习引导: 
    - 参考书目： 《海龟交易法则》
* 课堂教学计划：

  第一部分：趋势跟随
  45分钟
  - 因子回顾
  - 海龟交易法则
  - 应对复杂情况

  第二部分：均值回复
  45分钟
  - 均值回复现象和与趋势的关系
  - 反转型策略的基本框架
  - 更复杂的均值回复策略

  第三部分：在实战中如何构建和检验策略
  45分钟
  - 下次课程的策略报告要求

* 作业: 
    - 分组开发一个交易策略，可先行结组准备，路演安排在第六次课或以后；
    - 演示文稿需要包含：
      - 策略逻辑概述
      - 策略重要参数的选择依据
      - 策略回测结果及分析
      - 优化思路


## 4. 量化交易的技术基础（1）
* 教学内容: 
    - 量化交易相关的Python编程基础
    - 在聚宽上开发一个轻量级的量化策略
    - 理解基本的策略评价指标
    - 介绍Notebook任务：计算年化收益、最大回撤
* 学习引导：
    - Python环境准备
    - 理解和熟悉notebook环境并动手完成实际任务；
    - 注册第三方平台账号（聚宽或一创聚宽）并体验策略回测过程
* 课堂教学计划：

  基础知识部分：
  - 交易基础知识
  - 策略评价指标

  Python部分：
  - 环境安装
  - 常用的数据结构：
	  如何表示价格时间序列（series, dataframe）
	  如何进行价格的计算，例如计算均线、计算指数滑动平均、计算两个序列的差、价格的引用等，（包含rolling、shift）
  - 基本语法、库函数（重点介绍Pandas和TALib）
  - Notebook部分，简单讲解代码和分布运行的操作过程

  聚宽上的轻量级量化策略：
  以双均线策略为例，讲解聚宽上一个策略的开发和回测过程。标的物分成3种：
  - 一只单独的股票
  - 多只股票构成的一个股票池
  - 一只ETF


## 5. 量化交易的技术基础（2）
* 教学内容: 
    - 其他第三方平台介绍；
    - 一个轻量级的量化策略；
    - Notebook任务：计算夏普比率、分解Alpha和Beta
* 学习引导
    - 理解投资组合的alpha来源
    - 理解计算后验alpha和beta的原理
* 课堂教学计划：

  第一部分：进一步完善轻量级量化策略
  - 引入完整的股票池机制
  - 择时信号采用更小的颗粒度
  - 股票池择时框架是万能的吗
  需要倪助教测试聚宽代码

  第二部分：介绍一个第三方量化交易工具--TB
  课前要求：安装TB旗舰版
  - 介绍TB的基本功能和语法
  - 用海龟交易法实例演示TB的工作流程
  需要池助教检查大家的TB安装情况

  第三部分：投资组合的后验Alpha分解
  - 何为Alpha
  - 怎样分解beta和alpha
  - 实战中怎样看待后验分解的结果
* 作业: 
    - notebook实验报告：要求简要说明收益序列指标评价及后验alpha、beta分解的实验结果和问题讨论, 2周后交


## 6. 分组策略开发演示及点评
* 教学内容: 
    - 分组演示自己的量化策略，重点说明策略要素和策略评价结果，对后续策略优化的思路
* 学习引导:
    - 各小组课前一定要上传策略路演报告
* 作业:
    - 到目前为止总共有3次作业，课程记分方式为3次作业中选择成绩最好的2次计入平时成绩。

## 7. 再战Alpha
* 教学内容: 
    - 更多经典策略介绍
    - 实战因素和关键问题的解决
    - 如何进行刻意练习 - 主观交易与量化交易的关系

## 8. 策略诊断及挑战性课题
* 教学内容: 
    - 如何进行有效的量化策略诊断
    - 挑战性课题 - 看看专业机构都在怎么玩
      - 怎样用少量非成分股去拟合一个宽基指数
      - 在A股市场怎样做空一个行业
* 作业:
    - 选课同学可以选做挑战性课题，作为期末加分项
    - 挑战性课题的报告要求汪老师会单独告知，对挑战性课题感兴趣的同学可以联系助教刘为为。

## 9. 期权
* 教学内容: 
    - 期权的基本概念
    - 期权交易的基本原理和典型策略；
    - 期权实战案例 - 基于pVIX的跨式策略和单边策略

## 10. 上市公司如何操纵财务报表
* 教学内容: 
    - 基本面分析的基本原理
    - 为什么要操纵财务报表
    - 如何识别财务操纵的蛛丝马迹

## 11. 爬虫与vn.py
* 教学内容: 
    - 为什么要爬取数据
    - 爬虫的基本原理和技术实现
    - VN.PY为何物
    - 典型的VN.PY技术框架及应用
    - 基于VN.PY的CTP交易小工具的实现
* 学习引导:
    - 以赛代练，基于本课程启动“第五届清华大学iCenter量化策略邀请赛”
* 作业:
    - 预告期末大作业要求

## 12. 深入讨论技术指标与信号系统
* 教学内容: 
    - 技术指标的物理意义
    - 技术指标到信号系统
    - 信号系统开发的坑
    - 如何评测信号性能

## 13. 专题报告或机构走访调研实践
* 教学内容: 
    - 《人工智能在量化交易中的应用》
    - 《配对交易》

## 14. 量化策略的体系化研发
* 教学内容: 
    - 回顾与小结：量化交易的优势和盲区
    - 量化交易策略体系化研发方法论
    - 实战量化交易的误区
    - 谈谈高频交易

## 15. 期末策略路演
* 教学内容: 
    - 以个人为单位的策略制作和报告路演

## 参考书目：
        - 《打开量化投资的黑箱》 
            - Inside the Black'Box:A Simple Guide to Quantitative and High-Frequency Trading 
            - 作者：里什纳兰 (Rishi K.Narang) 
            - 出版社: 机械工业出版社; 第1版 (2016年5月1日)
        - 《主动投资组合管理:创造高收益并控制风险的量化投资方法》 
            - Active Portfolio Management: A Quantitative Approach for Providing Superior Returns and Controlling Risk (2th Edition) 
            - 作者：理查德 C.格林诺德 (Richard C.Grinol, 雷诺德 N.卡恩 (Ronald N.Kahn), 李腾 (译者) 
            - 出版社: 机械工业出版社; 第1版 (2014年9月1日)
        - 《算法交易:制胜策略与原理》 
            - Algorithmic Trading: Winning Strategies and Their Rationale 
            - 作者：欧内斯特陈 (Ernest P.Chan) 
            - 出版社: 机械工业出版社; 
            - 第1版 (2017年1月1日)
