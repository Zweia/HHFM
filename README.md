# High-performance hybrid flood model (HHFM)  
The HHFM model was developed by Prof. Guoru Huang's team of hydrology and water resources at the School of Civil Engineering and Transportation, South China University of Technology, China.  

The model is based on the Godunov-type finite volume method and unstructured grid discretization scheme for solving the shallow water equation (SWE) and local inertia approach (LInA) equations. The model utilizes the computational power of the Graphics Processor Unit (GPU) in NVIDIA's Compute Unified Device Architecture (CUDA) to achieve high-speed computation of the 2D hydrodynamic model. At the same time, a hybrid SWE and LInA solution is used to further improve computational efficiency while maintaining accuracy.  

The model has satisfactory accuracy and stability, which has considerable prediction potential in complex flow simulation of floods. The application of GPU acceleration techniques and hybrid solution approach to numerical modeling exhibits strong computational advantages, with one to two orders of magnitude speedups achieved in the test cases.  

The hybrid solution approach is a practical accuracy-efficiency trade-off that can be overlaid with the GPU acceleration approach to jointly improve the model-solving efficiency with guaranteed accuracy.


# Applications  
* Flood simulation  

* Flood risk assessment

* Flood warning and monitoring  

* Flood emergency response and daily management

* ...


# Developers  
Prof. Guoru Huang  

Prof. Wenjie Chen

Dr. Weiqi Wang

Dr. Haijun Yu

Dr. ZhiWei Chen              


# Model availability
The model is currently only shared by the Scientific Collaboration (contact: 202010101646@mail.scut.edu.cn).


# Main references
[1] Chen, Zhiwei, and Guoru Huang. "Numerical simulation study on the effect of underground drainage pipe network in typical urban flood." Journal of Hydrology 638 (2024): 131481.  

[2] Wang, Weiqi, Wenjie Chen, Guoru Huang, Jiahong Liu, Dawei Zhang, and Fan Wang. "A hybrid shallow water approach with unstructured triangular grids for urban flood modeling." Environmental Modelling & Software 166 (2023): 105748. 

[3] Wang, Weiqi, Wenjie Chen, and Guoru Huang. "Urban stormwater modeling with local inertial approximation form of shallow water equations: A comparative study." International Journal of Disaster Risk Science 12 (2021): 745-763.    

[4] Chen, Wenjie, Guoru Huang, Han Zhang, and Weiqi Wang. "Urban inundation response to rainstorm patterns with a coupled hydrodynamic model: A case study in Haidian Island, China." Journal of Hydrology 564 (2018): 1022-1035.  

[5] Yu, Haijun, Guoru Huang, and Chuanhao Wu. "Efficient finite-volume model for shallow-water flows using an implicit dual time-stepping method." Journal of Hydraulic Engineering 141, no. 6 (2015): 04015004.   

[6] Yu, Haijun, and Guoru Huang. "A coupled 1D and 2D hydrodynamic model for free-surface flows." In Proceedings of the Institution of Civil Engineers-Water Management, vol. 167, no. 9, pp. 523-531. Thomas Telford Ltd, 2014.   
