# High-performance hybrid flood model (HHFM)  
HHFM模型是由中国华南理工大学土木与交通学院水文水资源黄国如教授团队开发。

模型基于Godunov-type有限体积法和非结构网格离散方案求解浅水方程(SWE)和局部惯性方法(LInA)方程。该模型利用了NVIDIA统一计算设备架构Compute Unified Device Architecture (CUDA) 中图形处理器单元 (GPU) 的计算能力™,实现2D水动力模型的高速计算。同时，采用混合SWE与LInA求解方案，在保证精度的情况下,进一步提高计算效率。

模型具有令人满意的精度和稳定性，在复杂流态洪涝模拟中具有相当大的预测潜力。将GPU加速技术和混合求解模式应用于数值建模表现出强大的计算优势，在测试案例中可实现一到两个数量级的加速。

混合求解方法是一种实用精度-效率的权衡方案，可以在保证精度的情况下和GPU加速方法相互叠加，共同提高模型的求解效率。


# 应用
· 洪涝模拟。

· 洪涝风险评估。

· 洪涝预警与监测。

· 防汛应急与日常管理。

...


# 开发人员
Prof. Guoru Huang

Prof. Wenjie Chen

Dr. Weiqi Wang

Dr. Haijun Yu

Dr. ZhiWei Chen.            


# 模型可用性
该模型目前仅由科学合作共享 (联系人: 202010101646@mail.scut.edu.cn)。


# 主要参考文献
[1] Chen, Zhiwei, and Guoru Huang. "Numerical simulation study on the effect of underground drainage pipe network in typical urban flood." Journal of Hydrology 638 (2024): 131481.  

[2] Wang, Weiqi, Wenjie Chen, Guoru Huang, Jiahong Liu, Dawei Zhang, and Fan Wang. "A hybrid shallow water approach with unstructured triangular grids for urban flood modeling." Environmental Modelling & Software 166 (2023): 105748. 

[3] Wang, Weiqi, Wenjie Chen, and Guoru Huang. "Urban stormwater modeling with local inertial approximation form of shallow water equations: A comparative study." International Journal of Disaster Risk Science 12 (2021): 745-763. 

[4] Chen, Wenjie, Guoru Huang, Han Zhang, and Weiqi Wang. "Urban inundation response to rainstorm patterns with a coupled hydrodynamic model: A case study in Haidian Island, China." Journal of Hydrology 564 (2018): 1022-1035.  

[5] Yu, Haijun, Guoru Huang, and Chuanhao Wu. "Efficient finite-volume model for shallow-water flows using an implicit dual time-stepping method." Journal of Hydraulic Engineering 141, no. 6 (2015): 04015004.   

[6] Yu, Haijun, and Guoru Huang. "A coupled 1D and 2D hydrodynamic model for free-surface flows." In Proceedings of the Institution of Civil Engineers-Water Management, vol. 167, no. 9, pp. 523-531. Thomas Telford Ltd, 2014.   



