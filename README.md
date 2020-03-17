* 用于获取当前疫情信息及所在省份的疫情人数情况。数据来自丁香园 [API](https://lab.isaaclin.cn/nCoV/zh)。
* 源码：https://github.com/BlankerL/DXY-COVID-19-Crawler

### 交互示例
1、
- 用户：疫情新闻
- 贾维斯：2020-03-17 新闻：1. 3 月 12 日国家卫健委确诊补订遗漏 12 例确诊病例（非 12 日新增），暂无具体省份信息。 2. 浙江省 12 例外省治愈暂无具体省份信息。
2、
- 用户：疫情情况
- 贾维斯：截止2020-03-17 18:42:10,陕西省累计确诊人数246例,治愈人数236例
### 配置
# 查询新冠肺炎疫情
Covid:
  enable: true
  province: '陕西省'  # 省份
