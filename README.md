# Lianjia_House_Info
链家二手房信息、交易记录爬虫，部分数据分析

## 采用Notebook形式，便于学习使用

## 链家爬虫
1. 爬取整个城市的小区基本信息，包括（小区名称、城市、行政区域、片区、参考均价、建筑年代、总栋数、总户数、开发商、物业费、物业公司、建筑类型、地址）
2. 爬取整个城市的小区的二手房交易记录，包括（小区名称、户型、建筑面积、成交价、挂牌价、单价、成交周期、成交日期、朝向、装修、电梯、楼层、建筑类型、区域、片区、季度、成交月份）
3. **支持的城市列表: 北京、广州、深圳、成都、南京、合肥、杭州等（目前除了上海，绝大部分链家的网站都支持）**
4. 附有于2017.04.07获取的成都的数据（二手房交易记录更新延迟15天，为2017.03.23），仅供参考研究。
5. **提示**：现在链家具有反爬虫检测，因此需要购买代理获取多个ip等方式来绕过，从而爬取完整的数据。本项目代码并未涵盖此部分内容。

## 数据分析
附有简单的数据分析，涵盖pandas的一些基本操作。

## 声明
本项目仅作研究学习使用，请勿用于商业目的。

## 支持我 & 想要更多的数据
觉得我的项目有帮助的，可以通过微信打赏。
![](http://ww2.sinaimg.cn/large/0060lm7Tgy1fehp0in5uxj30b20adta7.jpg)
想要更多的数据，或者需要帮助的，联系 QQ: 751073876