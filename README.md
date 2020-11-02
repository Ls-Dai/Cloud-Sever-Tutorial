# 云服务器使用说明
<br>

## 1. 云服务器概况
<br>

### 1.1 云服务器配置、计费
<br>

#### 1.1.1 算力说明

和A534实验室本地服务器所持显卡算力比较，云服务器提供的配置可以概括如下：

|    显卡    | 算力（TFLOPS）| 显存（G） | 相对速度 |
| ---------- | ---------- | ---------- | ---------- |
| Titan XP（A534） |  10.97 | 12 | 1 |
| G4 （RTX2080） |  13.45 | 11 | 1.226 |
| Tesla T4 |  8.141 | 16 | 0.742 |
| Tesla P40 |  11.76 | 24 | 1.072 |
| Tesla P100 |  9.526 | 16 | 0.868 |
<br>
我们主要使用RTX2080的显卡助力计算，系统选择Ubuntu。
![system select picture](src/img/system_choice.png)
<br>
<br>


#### 1.1.2 计费说明

计费内容包含三项：开机计算，存储和传输带宽
<br>
下表中，虚拟金币和人民币兑换比例为：1：0.92

|    项目    | 单位数量单位时间价格|
| ---------- | ---------- |
| 1块RTX2080显卡配上8核i5 CPU |  5.84金币 / 小时 |
| 存储空间 | 最低80G，需要 0.02金币 / 小时。超过80G的部分增加量需为 50G 的倍数，每增加50G需要 0.015金币/小时，四舍五入保留两位小数 |
| 传输带宽（按带宽计费） | 5M及以下时为每小时 0.03金币 / M，多出5M的部分需要增加每小时 0.135金币 / M |
| 传输带宽（按流量计费） | d |


* 举例说明，180G，10M 带宽需要付费 (0.02 + 2 * 0.015) + (0.03 * 5 + 0.135 * 5) = 0.83 金币 / 小时 (0.825四舍五入的结果)  

<br>

