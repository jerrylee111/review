理想晶体管分析中的假设：非简并，均匀掺杂，E，C区准中性区宽度大于少子扩散长度

![截屏2025-06-18 10.10.15](/Users/liruijie/Desktop/中转/截屏2025-06-18 10.10.15.png)



# 基本参数

1. 发射效率：$\frac{I_{En}}{I_E} = (1+\frac{D_{pe}p_{e0}W_b}{D_{nb}n_{b0}L_{pe}})^{-1}$
2. 基区输运系数：$\frac{I_{Cn}}{I_{En}} = 1 - \frac{1}{2}(\frac{W_b}{L_{nb}})^2$​
3. 共基极短路电流放大系数：$\frac{I_C}{I_E}$
4. 共发射极短路电流放大系数：$\frac{I_C}{I_B}$

# 电流有关公式

1. $I_C = \beta_{DC}I_B + I_{CE0}$
2. $I_C=\alpha_{DC}I_E+I_{CB0}$
3. ![61750211424_.pic](/Users/liruijie/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/f596a5b6e8f5ef94ed5574004eaf16d9/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/61750211424_.pic.jpg)

其中又有$I_E =I_{F0}(exp(\frac{qV_{BE}}{kT}) - 1) - \alpha_RI_{R0}(exp(\frac{qV_{BC}}{kT}) - 1), I_C=\alpha_FI_{F0}(exp(\frac{qV_{BE}}{kT}) - 1) - I_{R0}(exp(\frac{qV_{BC}}{kT}) - 1))$​



![截屏2025-06-18 10.27.38](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-18 10.27.38.png)

# 时间有关公式

基区渡越时间：$\tau_t = \frac{W^2}{2D_{nb}}$

# 非理想效应

1. early电压：$V_A = \frac{qN_BW}{C_{JBC}}, \frac{dI_C}{dV_{BC}}=\frac{I_C}{|V_A|}$
2. kirk效应：临界电流密度$J_{CR} = qV_{sat}(\frac{2\epsilon_0K_sV_CB}{qW_C^2}+N_C)$
3. 基区穿通：$V_{BCpunch}=\frac{qW_b^2N_B^2}{2\epsilon_0K_sN_C}$

# 动态响应模型

1. 跨导：$g_m = \frac{qI_D}{kT}$
2. $C_{\pi}=(\frac{\tau_{tE}}{\beta_{DC}}+\tau_{tB})g_m$
3. 截止频率$f_{\beta}=f_{T}/\beta_{DC}$特征频率$f_{T}=\frac{1}{2\pi(C_\pi+C_{JBE}+C_{JBC})/g_m}=\frac{1}{2\pi\tau_{tEC}}$
4. $g_0 = \frac{I_C}{V_A}$

![截屏2025-06-20 00.50.35](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 00.50.35.png)

![截屏2025-06-20 01.06.42](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.06.42.png)

![截屏2025-06-20 01.14.50](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.14.50.png)

![截屏2025-06-20 01.25.04](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.25.04.png)

![截屏2025-06-20 01.25.39](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.25.39.png)

# 基区穿通

**BC结耗尽区在未发生雪崩击穿前已扩展到BE结空间电荷区，这种现象称为**基区穿通。

![截屏2025-06-20 01.44.45](/Users/liruijie/Library/Application Support/typora-user-images/截屏2025-06-20 01.44.45.png)
