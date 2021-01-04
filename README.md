# 1. 资料
## 1.1 论文期刊
### [六自由度工业机器人的机械手机电一体化设计_李俊雨.pdf](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2020&filename=SDJI202003093&v=AY%25mmd2BbFE2K9sDAmWRAhWPO0KG7QwjQgS2NH1iQ36G900VFddC3FhAmIqZcVoyZyY2X)

### [6自由度机器人手臂的设计与应用_鲍敏.pdf](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2019&filename=HLKX201925057&v=noY3KdLl2SU7mFIvVw61Q4KSYCOomTCAKdbBzopKUGW8oZ9SikQTayPfQHhshR%25mmd2BG)

### [六自由度机器人本体设计及轨迹规划与虚拟仿真_王杰.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201502&filename=1015574537.nh&v=le%25mmd2Ftyx0YS5c19rbYa2%25mmd2Bm1pUM3ztEqY%25mmd2Fiv3kpYNKYdtTYxw7kOoIWbrsv1Gr0TLH%25mmd2F)

### [六自由度焊接机器人本体结构设计与开发_欧爽翔.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201501&filename=1014379583.nh&v=yebcuv0x4wzyEQL40GBb7sthzA15lpXqb8%25mmd2F9vqPEVZge1YxQIPwh%25mmd2FlpdhnhrSm%25mmd2Bh)

### [六自由度关节型喷涂机器人结构设计及分析_陈磊.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201601&filename=1015967228.nh&v=dxHUvHKNw7IR4OsrKPi8StGpp3vyFX9vU0c7sFx0To00819rpPIImw1dNAEELkv6)

### [六自由度喷涂机器人的结构设计与仿真研究_沈思思.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201502&filename=1015579930.nh&v=hqythXUgxUDtTGzr4cJ97kzUGu7VHVUf6n95Oz20Hj0j%25mmd2BaftN%25mmd2FetNaG%25mmd2BaqIStJ0y)

### [六自由度点焊机器人结构设计与动态性能分析_张立志.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201301&filename=1013116093.nh&v=HCsHSZq8V%25mmd2BN3GDHRMyhlnX8rB1F2eJL2R3ULcfPQCjEJeLfo8vaEa8IerG%25mmd2F7p92K)

### [关节机器人伺服系统的动态特性分析和参数优化_秦智超.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFDTEMP&filename=1020112553.nh&v=85RBQ8CJQXwku6f4Rf0rT0AnHpCaNAW4VOmjmMr7ZZFx%25mmd2FRsjd3e5MgqsRQyDYxF7)

### [六轴工业机械臂运动控制系统设计与实现_齐杨.caj](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD201902&filename=1019601720.nh&v=YaDRllrP%25mmd2B64GF8R1vfvBKDNfJo7c3CrlXWTABCZGQTC3HttYaOhNAtsx2GEp9naz)

### [机器人控制模块中的执行驱动技术研究——一维工作平台电机选型计算](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2019&filename=DJDJ201902016&v=8y4ulTqB%25mmd2BGImjBgIB7KtURJYJ1RlFhYBCzHwC63092x%25mmd2Fvp7vaBoCwoBCYpRBmXuQ)


## 1.2 其他资料

伺服电机选型大难题？看完这篇文章的人都说会了 <https://zhuanlan.zhihu.com/p/101149851>
 松下伺服电机选型手册<https://wenku.baidu.com/view/2b6079d333d4b14e852468ef.html>
 安川伺服电机综合选型手册
<https://www.docin.com/p-283501384.html>
伺服电机选型手册
<https://max.book118.com/html/2019/0806/5310100023002113.shtm>

# 2. 电机与减速器的选型计算


## 2.1 计算过程
>角速度与转速的关系：
>$$\omega =\pi \times n$$

已知第六轴的最大角速度为$\omega=360^{°}/s$，则第六轴的转速$n=60r/min$。质量为$m_{6}=0.23kg$，体积$V_{6}=86729.23mm^{3}$，转动惯量为$J_{6x}=57.67kg\cdot mm^{2}$，$J_{6y}=349.23kg\cdot mm^{2}$，$J_{6z}=349.82kg\cdot mm^{2}$，则电机初选电机转速为$n=2000r/min$，据此选择电机额定转速和减速器减速比，因此初选减速器的减速比为60。

# 3. 其他

>## 3.1 markdown里的代码注释

```python
import turtle
def paintor():
    pass

if __name__ == "__main__":
    paintor()
    pass
```
