冶金结附近的空间电荷区是由电离受主和电离施主引起的

通常内建电势小于禁带宽度对应的电压值

欧姆接触升高了结的内建电压

不能用载流子扩散方程确定耗尽区内的少数载流子浓度和电流大小，因为耗尽区内电场不为0

“pn结定律”：$pn = n_i^2exp(\frac{qV_A}{kT})$​

结电容的物理起因是多子离开和进入耗尽区

# 求解一般pn结的基本公式

首先是电场$\frac{dE(x)}{dx} = \frac{\rho}{\varepsilon_0K_s}$其中$\rho$为电荷密度，一般来说根据耗尽层近似以及空间电荷区，$\rho$​即电离施主受主浓度

求解电势$\frac{d\phi}{dx} = -E(x)$

以上涉及到求解微分方程，就需要初始条件，一般初始条件是$\phi(-x_p) = 0, E(-x_p) = 0, E(x_n) = 0$​

内建电势$V_a = \frac{k_0T}{q}\frac{n(x_n)}{n(-x_p)} = \frac{k_0T}{q}\frac{N_AN_D}{n_i^2}$

耗尽层宽度$W_{dep} = \sqrt{\frac{2\epsilon_0K_s}{q}(\frac{1}{N_A}+\frac{1}{N_D})(V_A - V)}$

电荷中和$x_nN_D = x_pN_A$​

爱因斯坦关系$\frac{D_n}{\mu_n} = \frac{k_0T}{q}$

# 电流有关公式

扩散电流：$J_{n-diff} = qD_n\frac{dn}{dx}, J_{p-diff} = -qD_p\frac{dp}{dx}$

漂移电流：$J_{n-r} = q\mu_nnE, J_{p-r} = q\mu_ppE$​

n区空穴扩散电流：$J_{p_n-diff} = q\frac{D_p}{L_p}\Delta p_{n}(x)$​

p区电子扩散电流：$J_{n_p-diff} = -q\frac{D_p}{L_p}\Delta n_p(-x)$​

连续性方程：$\frac{dp(x, t)}{dt} = -\frac{1}{q}\div J_p - \frac{\Delta p(x, t)}{\tau_p} + g_p$​

耗尽区产生电流：$J_{R-G} = \frac{qW_{dep}n_i}{2\tau_{dep}}(exp(\frac{qV_a}{2kT}) - 1)$

# 载流子分布

耗尽层n区边界少子浓度$\Delta p_{n}(x_n) = p_{n_0}(e^{\frac{qV_a}{kT}} - 1), \Delta n_p(-x_p) = n_{p0}(e^{\frac{qV_a}{kT}} - 1)$

如果是长二极管，那么少子浓度分布为$\Delta p_{n}(x) = p_{n_0}(e^{\frac{qV_a}{kT}} - 1)e^{-\frac{x}{L_p}}, \Delta n_p(-x) = n_{p0}(e^{\frac{qV_a}{kT}} - 1)e^{-\frac{x}{L_n}}$​

短二极管就把$L_p$换成$W$​即可，$L = \sqrt{D\tau}$，此外还要变成线性分布

# 雪崩电压问题

雪崩击穿要求：$\int\alpha_{eff}dx = 1$，这其中$\alpha_{eff} = Ci|E|^7(对Si来说)$​​​

$V_{BR} \rightarrow N_D^{-\frac{3}{4}}$

# 电荷存储机制

$\frac{dQ_p}{dt} = I_{diff} - \frac{Q_p}{\tau_p}$

# 存储延迟时间

$t_s = \tau_tln(1+\frac{I_F}{I_R})$

# 小信号电阻和电容

扩散导纳：$G_D = \frac{qI_D}{kT} = \frac{q}{kT}A_En_i^2(\frac{qD_p}{L_pN_D} + \frac{qD_n}{L_nN_A})exp(\frac{qV_A}{kT})$

扩散电容：$C_D = \frac{1}{2}\frac{q}{kT}(I_{p, DIFF}\tau_p+I_{n, DTFF}\tau_n) = \frac{1}{2}\frac{q^2A_E}{kT}(p_{n0}L_p + n_{p0}L_n)exp(\frac{qV_A}{kT})$

势垒电容：$C_J = A_E\frac{\epsilon_0K_s}{W_{dep}}$​

# 几张需要注意的图



![31750166359_.pic](/Users/liruijie/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/f596a5b6e8f5ef94ed5574004eaf16d9/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/31750166359_.pic.jpg)

![21750166358_.pic](/Users/liruijie/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/f596a5b6e8f5ef94ed5574004eaf16d9/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/21750166358_.pic.jpg)

![41750166360_.pic](/Users/liruijie/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/f596a5b6e8f5ef94ed5574004eaf16d9/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/41750166360_.pic.jpg)

![11750166357_.pic](/Users/liruijie/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/f596a5b6e8f5ef94ed5574004eaf16d9/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/11750166357_.pic.jpg)

![截屏2025-06-19 23.38.51](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-19 23.38.51.png)

![截屏2025-06-20 00.16.57](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 00.16.57.png)

![截屏2025-06-20 00.18.54](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 00.18.54.png)

![截屏2025-06-20 01.38.07](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.38.07.png)
