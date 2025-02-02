# Chapter 7 X-射线光谱

## X-射线

- 天体物理中的 X 射线光谱主要来自（一般情况下高度电离）重离子的内壳层**电子跃迁**
  - 不同重离子给出的 X 射线谱大致相同，因为它们的差别主要在于外层电子
- 通常的定义是波长介于 0.01 至 100 埃（1 keV ~ 12 埃）
  - 软 X 射线：0.1～10 keV
  - 硬 X 射线：10 ～ 1000 keV
  - 波长更短的 $\gamma$ 射线一般来自放射性核过程，与原子的电子壳层结构无关
- 地球大气层对 X 射线非透明，观测天体的 X 射线辐射必须使用空间设备

## X 射线源

- 河内：X 射线双星
  - 主星：普通恒星
  - 伴星：致密天体（中子星/黑洞）——吸积主星物质产生 X 射线
- 河外：活动星系核、类星体（全波段强辐射，显著的 $\gamma$ 射线辐射）

## X-射线的产生

### 高次电离离子的跃迁

- 高能条件下，多电子复杂原子可以被高次电离，产生很高的有效电荷
  $$
  Z_{eff}=Z-(N-1)
  $$
  其外层价电子激发能级的能量随 $Z_{eff}^2$ 迅速增加，谱线能量也相应增加，移到 X 射线波段

- 在重离子的内层，不需要高次电离有效电荷也可以很高——内层电子贴近核心，外层电子的屏蔽作用非常有限

### 产生方式

- 光致电离：高能入射光子将一内壳层电子电离
  - 在 X 射线双星、激变变星、活动星系核中，吸积产生的高能辐射将其周围的较冷气体高次电离，但气体温度仍维持在 1-2 eV（仅由电子运动决定）
- 碰撞电离：炽热等离子体（$T_{\mathrm{e}} \sim 10^{7}-10^{8}\ \mathrm{K}$）中的高能电子将一**内壳层电子**电离（恒星耀斑、超新星遗迹、星系际介质）
- 电离之后，外层电子填充内层电子的空缺，可能会发生
  - X 射线荧光发射——释放 X 射线光子——重元素离子
  - 无辐射自电离——释放 Auger 电子——轻元素离子

### 线系

- n = 1, 2, 3, 4, 5…——K、L、M、N、O … 层
- K 线系：K 层以外电子跃迁到 K 层，发射的 X 射线能量最高，波长最短
- 其他线系依此类推

#### K$\alpha$ 线

- 内层电子跃迁选择定则依然是 $\Delta L=\pm 1, \ \Delta J=0, \pm 1$ 且总角动量不能从 0 到 0
- 当 K 层一个电子被高能 X 射线光子电离，留下的空穴被 L 层的电子跃入填充，产生的谱线称为 K$\alpha$ 线
- 能级图上：K 能级向 L$_{\rm{III}}$ 或 L$_{\rm{II}}$ （区分不同的光谱项能级——精细结构）跃迁，对应谱线为 K$\alpha_2$ 和 K$\alpha_2$

#### Fe K$\alpha$ 线

- 不同电离态的 K$\alpha$ 线在波长上非常接近，仅随电离度的减少略向长波方向移动——当电离度减小时，额外外壳层的电子屏蔽效应增强，有效电荷数减少，K$\alpha$ 线能量降低
- 中性 Fe 的 K$\alpha$ 线波长反而短于不少高次电离 Fe 的 K$\alpha$ 线波长——电离度小于 Fe IX 的铁离子所带的部分填充的 3d 壳层电子对 2p 的屏蔽比对 1s 电子要好，即 2p（L 层）对应有效电荷低，1s 对应有效电荷高，能级差加大

### 类氢离子 X 射线

- 对相对较轻的元素，需要高度电离才会有内层跃迁（内层电子被光致/碰撞电离后更倾向于释放 Auger 电子）

### 类氦离子 X 射线

- r，i，f 跃迁
  - r 跃迁：共振跃迁
  - i 跃迁：半禁线（自旋多重性改变）
  - f 跃迁：禁线
- 卫星线（辅线）
  - 高温高密度等离子体中，C、N、O、Fe 等被高度电离，形成类氢、类氦离子
  - 这些离子双电子复合，捕获一个电子形成次一级电离度的自电离双电子激发共振态，再经辐射退激发到束缚态或基态
  - 双电子复合过程中发射的**共振线**一般称为复合离子的卫星线或辅线
    - 类氢离子：1s$nl\to$2p$nl$
    - 类氦离子：1s$^2nl\to$1s2p$nl$
  - 本质上就是光致电离气体星云中的双电子复合线——辅线与共振线的强度比可以用来测定等离子体的电子温度

## 日冕光谱

- 高温下，大量高次电离离子产生发射线（曾被误认为有新元素的存在）

### 光学波段

- 最强的三条发射线（光学波段）
  - 绿线 $[\mathrm{Fe}\ \mathrm{XIV}]\ 5302 \overset\circ{\mathrm{A}}$ 3s$^{2}$3p $^{2} \mathrm{P}^o_{1 / 2}\to\ ^{2} \mathrm{P}^o_{3 / 2}$
  - 黄线 $[\mathrm{Ca}\ \mathrm{XV}]\ 5694 \overset\circ{\mathrm{A}}$ 2s$^{2}$3p$^2$ $^{3} \mathrm{P}_{0}\to\ ^{3} \mathrm{P}_1$
  - 绿线 $[\mathrm{Fe}\ \mathrm{X}]\ 6374 \overset\circ{\mathrm{A}}$ 3s$^{2}$3p$^5$ $^{2} \mathrm{P}^o_{3 / 2}\to\ ^{2} \mathrm{P}^o_{1 / 2}$
- 日冕线来自高度电离重元素离子基态光谱项具有同一宇称的精细结构能级间的电偶极禁戒跃迁（磁偶极、电四极）——对应星云中的红外光谱——只是因为温度高，电离度高（[Fe X] 和 [Fe XIV] 要求电子温度 $10^6\text { K}$），有效电荷高，精细结构谱线移到了光学波段

### 红外波段

- 一般将电离势高于 100 eV 的离子发射的谱线统称为**冕线**
- 普遍存在于共生星、激变变星、新星、超新星的光谱中（炽热等离子体）
- 大量高激发离子精细结构产生的发射线位于红外波段（Infrared Space Observatory – ISO）

## 多电子原子的同位素位移

- 计入原子核运动时，多电子原子体系的哈密顿量动能项为
  $$
  T=\frac{\vec{p}{N}^{2}}{2 M}+\sum_{i=1}^{N} \frac{\vec{p}{i}^{2}}{2 m_{e}}
  $$
  根据动量守恒
  $$
  \vec{p}{N}=-\sum_{i=1}^{N} \vec{p}{i}
  $$
  因此
  $$
  T=\frac{1}{2 M}\left({\sum} \vec{p}i\right)^{2}+\frac{1}{2 m_{e}} \sum p_{i}^{2}\\
  =\frac{M+m_e}{2Mm_e}\sum p_i^2+\frac1M\sum\vec p_i\cdot\vec p_j\\
  =\frac{1}{2\mu}\sum p_i^2+\frac1M\sum\vec p_i\cdot\vec p_j
  $$

- 第一项：不同**核质量**同位素之间的能移——正常质量位移

- 第二项：比质量位移

### 正常质量位移

- 相对 $E_\infty$
  $$
  \delta E=E_{M}-E_{\infty}=\frac{R_{\infty} Z^{2}}{n^{2}}-\frac{R_{M} Z^{2}}{n^{2}}=-E_{\infty} \frac{m_{e}}{M+m_{e}}>0
  $$
  从而相对核质量无穷大，即约化质量等于核质量的情况，正常质量位移是一个正值，能级的绝对值减小

- 不同核质量的同位素之间的正常质量位移
  $$
  \Delta E=\delta E\left(M_{1}\right)-\delta E\left(M_{2}\right)=-E_{\infty}\left(\frac{m_{e}}{M_{1}+m_{e}}-\frac{m_{e}}{M_{2}+m_{e}}\right) \approx E_{\infty} \frac{m_{e}\left(M_{1}-M_{2}\right)}{M_{1} M_{2}}
  $$
  若 $M_1<M_2$，则 $\Delta E>0$，即核质量较小原子的能级能量绝对值更小——相对于电离极限被压缩了

- 波长位移（以波数计）
  $$
  \Delta \sigma=\sigma_{1}-\sigma_{2}=\sigma_{\infty} \frac{m_{e}\left(M_{1}-M_{2}\right)}{M_{1} M_{2}}=\frac{\sigma}{1822.9} \frac{A_{1}-A_{2}}{A_{1} A_{2}}
  $$
  $A$ 为相对分子量

  - 质量较大同位素跃迁的波长较短，落在质量较小的同位素同一跃迁的蓝端
  - 核质量最小的 H 和 D 的正常质量位移最大

### 比质量位移

- 大小与正常质量位移相当，方向可能相同（正的比质量位移）也可能相反（负的比质量位移）
- 难以精确计算，但和正常质量位移一样随原子质量增加迅速减小
  - 对元素周期表后三分之一的元素不再重要
  - 对中间部分的元素相当重要，并在确定其他同位素效应时引入相当大的不确定性

### 体积同位素效应

- 体积/场位移——同一元素不同同位素所含中子数不同，原子核的体积、形状和电荷分布也有所不同
- s 电子的核穿透效应最大，体积位移一般只对 **s 壳层上的电子数发生变化的跃迁**重要，大小随原子核大小的增加而增加
- 非常难以计算（取决于电子电荷的分布以及原子核的电荷分布）
- 对不同同位素同一跃迁的相对同位素位移的测定以及其所含体积位移效应的估算，可为原子核模型的建立提供重要数据

### 核自旋——多电子原子的超精细结构

- 同一元素不同同位素的核自旋不同，**非零核自旋**和**电子角动量**耦合，形成特定的**超精细结构**谱线——测定天体中同位素丰度比
- 原子总角动量 $F=J+I$
  - 如果 $J>I$，精细结构分裂为 $2I+1$ 个超精细结构
  - 如果 $J<I$，精细结构分裂为 $2J+1$ 个超精细结构
