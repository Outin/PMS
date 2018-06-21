# 欢迎使用 PMS 底仓数据系统 ！
## 概述
PMS 是为结构化资产管理业务开发的一套底仓数据监控系统。
### 基本逻辑
> * 构建并维护产品目录
> * 各项目按日期导入估值表
> * 运行统计运算功能
### 请注意
> ST股票的统计以底仓记录中的股票简称为依据，而其他统计维度中的股票简称均以外部数据文件为准。
> * 非股票资产=资产净值-股票总市值
> * 风险敞口=优先级本金-非股票资产
> * 敞口覆盖率=股票总市值/风险敞口\*100%

### 基础数据
> 系统仅从估值表中提取数据：
> * 口径日期
> * 单位净值
> * 股票总市值
> * 资产净值
> * 股票类资产底仓数据

### 致谢
    中国民生银行总行金融市场风险管理部
