# FISTA
FISTA Algorithm for Solving LASSO Problems

FISTA algorithm for LASSO problem: application of sparse regularization in
spherical radial basis functions (SRBFs) based regional geoid modeling;
generalized cross validation (GCV) or corrected Akaike information
criterion (AICc) are used to select the regularization coefficient.

The codes of the FISTA part are originally created by Wen Zaiwen, Liu
Haoyang and Hu Jiang, see:
https://bicmr.pku.edu.cn/~wenzw/optbook/pages/lasso_proxg/LASSO_Nesterov_inn.html
Reference: 
Liu Haoyang, Hu Jiang, Li Yongfeng, Wen Zaiwen (2021) Optimization: Modeling, Algorithms 
and Theory (in Chinese). China higher education press, Beijing

Yu Haipeng and Chang Guobin modified the original codes of the FISTA so
that they can be used for local gravity field modeling based on SRBFs.The
analytical expressions of GCV and AICc are derived by Chang Guobin and Yu
Haipeng, who also edited thess parts of the codes.

Yu Haipeng and Chang Guobin,
School of Environment Science and Spatial Informatics,
China University of Mining and Technology, Xuzhou, China
2021-08-28, last modified 2022-01-20

References 
----------

Chang GB, Qian NJ, Chen C, Gao JX (2020) Precise instantaneous velocimetry and accelerometry 
with a stand-alone GNSS receiver based on sparse kernel learning. Measurement 159: 107803. https://doi.org/10.1016/j.measurement.2020.107803
Liu HY, Hu J, Li YF, Wen ZW (2021) Optimization: Modeling, Algorithms and Theory (in Chinese). 
China higher education press, Beijing

Disclaimer
----------

The developers of these codes do not accept any liability in connection with the use of 
code provided here. The developers of these codes do not make any warranty of fitness, 
completeness, usefulness and accuracy of the codes for any intented or unintended purpose. 

