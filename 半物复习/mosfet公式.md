# 静电势定义

$\phi(x)=\frac{E_{i,bulk}-E_i(x)}{q}$​

费米势：$\phi_F = \frac{kT}{q}ln\frac{N_B}{n_i}$

# 电荷有关方程

$Q_s = -\sqrt{4q\epsilon_0K_sN_A\phi_F}$表达了强反型时耗尽层电荷

耗尽时$Q_s = Q_{dep}$

$V_G = \frac{-Q_s}{C_{ox}}+\phi_s$

强反型时：$Q_s = Q_{inv}+Q_{dmax}$

此时：$V_G = \frac{-Q_s}{C_{ox}}+2\phi_F$

可以算出$Q_{inv}=-C_{ox}(V_G - V_T)$（这个式子在理想时普遍实用）

$V_T为阈值电压V_T = 2\phi_F+\frac{Q_{dmax}}{C_{ox}}$​​

$V_{GS}=\phi_s(y)+\gamma[\phi_s(y)+\phi_texp(\frac{\phi_s(y)-2\phi_F-V_{CS}(y)}{\phi_t})]$

# 实际mos

$V_T = V_{FB} + 2\phi_F + \frac{Q_{dmax}}{C_{ox}}$​

n型则平带电压不变符号，其余负号

# 平方律模型

原来直流特性为：$I_D =\mu_n\frac{W}{L}\int_{0}^{V_{DS}}Q_{inv}dV_{CS}$

如果不考虑漏极电压对栅下耗尽层的影响

那么反型层电荷只需要多提供给漏极电压即可

最终$I_D=\mu_nC_{ox}\frac{W}{L}(V_{GS}-V_T-V_{DS})V_{DS}$

但是当$V_{DS}=V_G-V_T$,反型层消失，沟道被夹断，此时电流将会保持最大值不变

$I_D = \frac{I_{Dsat}}{1-\frac{\Delta L}{L}}$

# 频率

本征截止频率：$f_T=\frac{g_m}{2\pi(C_{gs}+C_{gd})}=\frac{1}{2\pi\tau_d},\tau_d为沟道载流子延迟时间$

# 非理想效应

1. 沟道长度调制效应：$\Delta L=\gamma V_{DS}$

   所有项倍数（$1+\gamma V_{DS})$

   漏电导$g_{ds}=\gamma I_{Dsat}$

2. 体效应

   使计算阈值电压时，表面电势需要多计算$V_{SB}$​

   ![截屏2025-06-19 18.59.39](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 18.59.39.png)

3. 亚阈值电流

   当表面弱反型时，$I_D$不为0

   亚阈值摆幅$S=2.3\frac{kT}{q}(1+\frac{C_{sT}}{C_{ox}}),C_{sT}=\sqrt{\frac{q\epsilon_0K_sN_A}{2(2\phi_f+V_{SB})}}$

   关态电流$I_{Off}=100\frac{W}{L}10^{-\frac{V_T}{S}}$​​
   
   ![截屏2025-06-19 19.05.28](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 19.05.28.png)

# 沟道载流子延迟时间

$\tau_d=\frac{2}{3}\frac{L^2}{\mu_n(V_{GS}-V_T)}$

![截屏2025-06-19 18.57.28](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 18.57.28.png)

![截屏2025-06-19 19.02.51](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 19.02.51.png)

![截屏2025-06-19 19.11.36](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 19.11.36.png)

![截屏2025-06-19 19.12.29](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 19.12.29.png)

![截屏2025-06-20 02.25.10](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 02.25.10.png)

![截屏2025-06-20 02.30.17](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 02.30.17.png)
