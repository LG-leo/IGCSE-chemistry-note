





# Cambridge IGCSE Chemistry 0620 — 核心原理深度解析（Markdown + LaTeX 公式版）

---

# 一、States of Matter — 物质状态

## 1.1 三态的基本原理

物质的三种状态——固态、液态、气态——本质区别源于**粒子间距离、排列方式和运动自由度**的不同。

- **固态（Solid）**：粒子紧密排列，呈规则晶格结构，仅在固定位置做微小振动。
- **液态（Liquid）**：粒子间距稍大，可移动和滑动，但粒子间仍有较强吸引力。
- **气态（Gas）**：粒子间距远大于自身尺寸，自由快速运动，碰撞容器壁产生**压强**。

## 1.2 状态变化的能量本质

状态变化本质上是**热能**与**粒子动能/势能**之间的转化：

- **熔化（Melting）** 与 **沸腾（Boiling）**：固→液、液→气，需要吸收热能以克服粒子间的**吸引力**。
- **冷凝（Condensing）** 与 **凝固（Freezing）**：气→液、液→固，释放热能，粒子动能降低，吸引力将粒子拉近。

**加热/冷却曲线**的关键解读：平台期（温度不变）对应状态变化阶段，此时热量全部用于改变粒子间**势能**而非**动能**。

## 1.3 气体体积与温度、压强的关系

根据**动能粒子理论**，温度升高时粒子平均动能增大，碰撞容器壁的频率和力度增大，若体积不变则压强增大；若压强不变（如可自由膨胀），则体积增大。

核心关系式为（理想气体状态方程的基础形式）：

$$PV = nRT$$

其中：
- $P$ = 压强 (Pressure)
- $V$ = 体积 (Volume)
- $n$ = 物质的量 (number of moles)
- $R$ = 气体常数 (gas constant)
- $T$ = 绝对温度 (absolute temperature, 单位 K)

温度与粒子平均动能的关系：

$$\bar{E}_k = \frac{3}{2}kT$$

其中 $k$ 为玻尔兹曼常数，$\bar{E}_k$ 为粒子平均动能。

## 1.4 扩散（Diffusion）

扩散是粒子从高浓度区域自发向低浓度区域运动的过程，驱动力是**浓度梯度**。

**Graham 扩散定律**——扩散速率与气体**相对分子质量**的平方根成反比：

$$\text{Rate of diffusion} \propto \sqrt{\frac{1}{M_r}}$$

即：

$$\frac{\text{Rate}_1}{\text{Rate}_2} = \sqrt{\frac{M_{r2}}{M_{r1}}}$$

这一原理源于：在相同温度下，较轻分子的平均运动速度更快。

---

# 二、Atoms, Elements and Compounds — 原子、元素与化合物

## 2.1 原子结构

原子由**原子核**（含质子和中子）和核外**电子壳层**组成：

| 粒子 | 相对质量 | 相对电荷 |
|------|---------|---------|
| 质子 (Proton) | $1$ | $+1$ |
| 中子 (Neutron) | $1$ | $0$ |
| 电子 (Electron) | $\frac{1}{1840}$ (可忽略) | $-1$ |

**原子序数 / 质子数 (Atomic Number, $Z$)**：原子核中的质子数，决定元素种类。

**质量数 / 核子数 (Mass Number, $A$)**：质子数 + 中子数。

$$A = Z + N$$

其中 $N$ = 中子数。

原子符号表示法：

$$^{\,A}_{Z}\text{X}$$

## 2.2 电子排布

电子在**壳层（shells）** 中排列，从内到外依次填充，遵循 **2, 8, 8...** 规则。

关键规律：
- **族 (Group) 数** = 最外层电子数（I-VII族）
- **周期 (Period) 数** = 电子占据的壳层数
- **VIII族（稀有气体）**：最外层满电子（He 为 2，其他为 8），极其稳定

## 2.3 同位素（Isotopes）

同位素是**同一元素**中**质子数相同但中子数不同**的原子。

$$\text{同位素}: \quad ^{12}_{6}\text{C},\; ^{13}_{6}\text{C},\; ^{14}_{6}\text{C}$$

**化学性质相同**的原因：化学性质由电子排布决定，同位素电子排布完全相同。

**物理性质不同**的原因：质量不同，影响扩散速率、密度等。

## 2.4 相对原子质量的计算

相对原子质量是各同位素的**加权平均质量**（相对于 $\frac{1}{12}$ 的 $^{12}\text{C}$ 原子质量）：

$$A_r = \frac{\sum (\text{isotopic mass} \times \text{relative abundance})}{100}$$

或写作：

$$A_r = \frac{\sum (m_i \times a_i)}{\sum a_i}$$

其中 $m_i$ 为同位素质量，$a_i$ 为丰度百分比。

---

# 三、Stoichiometry — 化学计量学

## 3.1 相对原子质量与相对分子质量

**相对原子质量 ($A_r$)**：某元素一个原子的平均质量与 $^{12}\text{C}$ 原子质量的 $\frac{1}{12}$ 之比。无量纲。

$$A_r = \frac{\text{average mass of one atom of the element}}{\frac{1}{12} \times \text{mass of one atom of }^{12}\text{C}}$$

**相对分子质量 ($M_r$)**：分子中所有原子的 $A_r$ 之和。对于离子化合物，使用**相对式量 (Relative Formula Mass)**。

$$M_r = \sum A_r(\text{each atom in the molecule})$$

## 3.2 摩尔与阿伏伽德罗常数

**摩尔 (mole, mol)** 是物质的量的 SI 单位，定义：1 mol 任何物质恰好含有 $6.02 \times 10^{23}$ 个基本粒子（原子、分子、离子等），此为**阿伏伽德罗常数 (Avogadro constant, $L$ 或 $N_A$)**。

$$N_A = 6.02 \times 10^{23} \text{ mol}^{-1}$$

核心公式：

$$n = \frac{m}{M}$$

其中：
- $n$ = 物质的量 (mol)
- $m$ = 质量 (g)
- $M$ = 摩尔质量 (g/mol)，数值上等于 $A_r$ 或 $M_r$

粒子数计算：

$$N = n \times N_A$$

## 3.3 气体摩尔体积

在**室温常压 (r.t.p.)** 下（25°C, 101 kPa / 1 atm），1 mol 任何气体所占体积均为 $24 \text{ dm}^3$。

$$V = n \times 24 \text{ dm}^3\text{mol}^{-1} \quad (\text{at r.t.p.})$$

## 3.4 溶液浓度

浓度表达方式：

$$c = \frac{n}{V}$$

其中：
- $c$ = 浓度 (mol/dm³ 或 mol/L)
- $n$ = 溶质的物质的量 (mol)
- $V$ = 溶液体积 (dm³)

**单位换算**：$1 \text{ dm}^3 = 1000 \text{ cm}^3$，$\text{cm}^3$ 转 $\text{dm}^3$ 需除以 1000。

也可以用 g/dm³ 表示：

$$\text{Concentration (g/dm}^3\text{)} = \text{Concentration (mol/dm}^3\text{)} \times \text{Molar Mass (g/mol)}$$

## 3.5 滴定计算

对于反应：$aA + bB \rightarrow \text{products}$

在滴定终点处：

$$\frac{n_A}{a} = \frac{n_B}{b}$$

即：

$$\frac{c_A V_A}{a} = \frac{c_B V_B}{b}$$

## 3.6 实验式（Empirical Formula）与分子式（Molecular Formula）

**实验式**是化合物中各原子最简单的整数比。

**分子式**是化合物中实际原子数。

$$n = \frac{M_r(\text{molecular formula})}{M_r(\text{empirical formula})}$$

## 3.7 产率与纯度

**理论产量**：根据化学方程式计算出的最大产物量。

**实际产量**：实验实际获得的产物量。

**百分比产率 (Percentage Yield)**：

$$\text{Percentage Yield} = \frac{\text{actual yield}}{\text{theoretical yield}} \times 100\%$$

**百分比纯度 (Percentage Purity)**：

$$\text{Percentage Purity} = \frac{\text{mass of pure substance}}{\text{total mass of sample}} \times 100\%$$

**百分比质量组成 (Percentage Composition by Mass)**：

$$\% \text{ of element} = \frac{\text{total } A_r \text{ of element in formula}}{M_r \text{ of compound}} \times 100\%$$

---

# 四、Electrochemistry — 电化学

## 4.1 电解（Electrolysis）

**电解**：通过电流使离子化合物（熔融或水溶液）发生**分解**的过程。

电解池关键术语：
- **阳极 (Anode)**：正极（+），发生**氧化**反应（失去电子）
- **阴极 (Cathode)**：负极（-），发生**还原**反应（获得电子）
- **电解质 (Electrolyte)**：熔融或水溶液中能导电的离子化合物

**电荷传递路径**：
1. 外电路：电子从阳极流向阴极
2. 电解质内部：阳离子（$+$）向阴极移动，阴离子（$-$）向阳极移动

## 4.2 产物预测原理

**熔融态二元化合物**：
- 阴极：金属阳离子得电子 → 金属单质（或氢气）
- 阳极：非金属阴离子失电子 → 非金属单质

**半反应（离子半方程）**：

阴极（还原）：$$\text{M}^{n+} + n e^- \rightarrow \text{M}$$

阳极（氧化）：$$\text{X}^{m-} \rightarrow \text{X} + m e^-$$

## 4.3 电镀（Electroplating）

利用电解将一层金属镀到另一种金属表面，目的为提高**外观**和**抗腐蚀性**。

- 待镀物体作为**阴极**
- 镀层金属作为**阳极**
- 电解液为镀层金属的可溶性盐溶液

## 4.4 氢氧燃料电池

氢氧燃料电池将化学能直接转化为**电能**，唯一产物为**水**。

$$\text{Overall reaction:} \quad 2\text{H}_2 + \text{O}_2 \rightarrow 2\text{H}_2\text{O}$$

**阳极反应（氧化）**：

$$2\text{H}_2 \rightarrow 4\text{H}^+ + 4e^-$$

**阴极反应（还原）**：

$$\text{O}_2 + 4\text{H}^+ + 4e^- \rightarrow 2\text{H}_2\text{O}$$

与汽油发动机相比，燃料电池的优势：**零污染排放**、效率更高；劣势：**氢气的储存和运输困难**、成本较高。

---

# 五、Chemical Energetics — 化学能量学

## 5.1 放热反应与吸热反应

**放热反应 (Exothermic)**：反应向周围环境**释放**热能，环境温度升高。$\Delta H$ 为**负值**。

**吸热反应 (Endothermic)**：反应从周围环境**吸收**热能，环境温度降低。$\Delta H$ 为**正值**。

**焓变 (Enthalpy Change, $\Delta H$)**：

$$\Delta H = H_{\text{products}} - H_{\text{reactants}}$$

- 若 $\Delta H < 0$：放热反应
- 若 $\Delta H > 0$：吸热反应

## 5.2 活化能 (Activation Energy, $E_a$)

活化能是发生反应所需的**最低能量**，即碰撞粒子必须具有的最小动能，只有能量 $\geq E_a$ 的碰撞才能导致反应发生。

## 5.3 键能与焓变的关系

**断键**是吸热过程（需要能量），**成键**是放热过程（释放能量）。

反应的净焓变：

$$\Delta H = \sum (\text{bond energies of bonds broken}) - \sum (\text{bond energies of bonds formed})$$

即：

$$\Delta H = \sum E(\text{bonds broken}) - \sum E(\text{bonds formed})$$

- 若断键所需总能量 > 成键释放总能量 → $\Delta H > 0$（吸热）
- 若断键所需总能量 < 成键释放总能量 → $\Delta H < 0$（放热）

---

# 六、Chemical Reactions — 化学反应

## 6.1 反应速率 (Rate of Reaction)

### 碰撞理论 (Collision Theory)

反应发生的三要素：
1. 粒子必须**碰撞**
2. 碰撞必须具有**正确的取向**
3. 碰撞的粒子必须具有 $\geq E_a$ 的**动能**

### 影响反应速率的因素

**浓度**：浓度增大 → 单位体积内粒子数增加 → 碰撞频率增大 → 速率加快

**压强（气体）**：压强增大 → 气体体积减小 → 粒子密度增大 → 碰撞频率增大 → 速率加快

**温度**：温度升高 → 粒子平均动能增大 → 更多粒子能量 $\geq E_a$ → 有效碰撞比例增大 → 速率大幅加快（约每升高 10°C 速率翻倍）

**表面积（固体）**：表面积增大 → 暴露的粒子增多 → 碰撞频率增大 → 速率加快

**催化剂**：降低反应的**活化能 ($E_a$)** → 更多粒子能量 $\geq E_a$ → 速率加快，催化剂在反应前后**不变**。

## 6.2 可逆反应与化学平衡

**可逆反应**可用 $\rightleftharpoons$ 符号表示，反应可同时向正反两个方向进行。

### 动态平衡的条件（密闭系统）

当**正反应速率 = 逆反应速率**，且**反应物和生成物的浓度保持不变**时，系统达到**动态平衡**。

### Le Chatelier's 原理

如果改变平衡系统的条件（温度、压强、浓度），系统将向**抵消该变化**的方向移动。

**温度变化**：
- 升温 → 平衡向**吸热**方向移动
- 降温 → 平衡向**放热**方向移动

**压强变化**（适用于气体反应）：
- 增压 → 平衡向**气体分子数减少**的方向移动
- 降压 → 平衡向**气体分子数增加**的方向移动

**浓度变化**：
- 增加某种物质的浓度 → 平衡向**消耗该物质**的方向移动
- 减少某种物质的浓度 → 平衡向**生成该物质**的方向移动

**催化剂**：同时加快正逆反应速率，**不改变平衡位置**，只帮助更快达到平衡。

### 哈伯法 (Haber Process)

$$ \text{N}_2(g) + 3\text{H}_2(g) \rightleftharpoons 2\text{NH}_3(g) \quad \Delta H = -92 \text{ kJ/mol (放热)} $$

典型条件：450°C, 200 atm, 铁催化剂

### 接触法 (Contact Process)

$$ 2\text{SO}_2(g) + \text{O}_2(g) \rightleftharpoons 2\text{SO}_3(g) \quad \Delta H = -196 \text{ kJ/mol (放热)} $$

典型条件：450°C, 2 atm, 五氧化二钒 ($\text{V}_2\text{O}_5$) 催化剂

## 6.3 氧化还原反应 (Redox) 与氧化数

### 三种定义层次

**1. 氧得失定义（Core）**：
- **氧化**：获得氧
- **还原**：失去氧

**2. 电子得失定义（Supplement）**：
- **氧化**：失去电子
- **还原**：获得电子

**3. 氧化数变化定义（Supplement）**：
- **氧化**：氧化数**增加**
- **还原**：氧化数**降低**

### 氧化数规则

1. 单质中元素的氧化数 = $0$
2. 单原子离子的氧化数 = 离子电荷
3. 化合物中各元素氧化数之和 = $0$
4. 多原子离子中各元素氧化数之和 = 离子电荷

**氧化剂 (Oxidising Agent)**：使另一种物质氧化，自身被还原（自身氧化数降低，获得电子）。

**还原剂 (Reducing Agent)**：使另一种物质还原，自身被氧化（自身氧化数升高，失去电子）。

---

# 七、Acids, Bases and Salts — 酸、碱与盐

## 7.1 酸碱理论

**Arrhenius 定义（Core）**：
- 酸的水溶液含 $\text{H}^+$ 离子
- 碱（可溶为**碱液/alkali**）的水溶液含 $\text{OH}^-$ 离子

**Brønsted-Lowry 质子理论（Supplement）**：
- **酸**是**质子供体 (proton donor)**
- **碱**是**质子受体 (proton acceptor)**

**中和反应**的本质：

$$\text{H}^+(aq) + \text{OH}^-(aq) \rightarrow \text{H}_2\text{O}(l)$$

## 7.2 强酸与弱酸

**强酸 (Strong Acid)**：在水中**完全电离**，用 $\rightarrow$ 表示。

$$\text{HCl}(aq) \rightarrow \text{H}^+(aq) + \text{Cl}^-(aq)$$

**弱酸 (Weak Acid)**：在水中**部分电离**，用 $\rightleftharpoons$ 表示。

$$\text{CH}_3\text{COOH}(aq) \rightleftharpoons \text{H}^+(aq) + \text{CH}_3\text{COO}^-(aq)$$

## 7.3 pH 标度

pH 用于衡量**氢离子浓度**：

$$\text{pH} = -\log_{10}[\text{H}^+]$$

其中 $[\text{H}^+]$ 单位为 mol/dm³。

- pH < 7：酸性
- pH = 7：中性
- pH > 7：碱性

## 7.4 氧化物分类

- **酸性氧化物 (Acidic Oxides)**：如 $\text{CO}_2, \text{SO}_2$，与非金属对应，与碱反应生成盐和水
- **碱性氧化物 (Basic Oxides)**：如 $\text{CuO}, \text{CaO}$，与金属对应，与酸反应生成盐和水
- **两性氧化物 (Amphoteric Oxides)**：如 $\text{Al}_2\text{O}_3, \text{ZnO}$，既能与酸又能与碱反应生成盐和水

## 7.5 盐的制备

**可溶性盐**制备方法：
- 酸 + 碱（滴定法）
- 酸 + 过量金属
- 酸 + 过量不溶性碱
- 酸 + 过量不溶性碳酸盐

**不可溶性盐**制备：**沉淀法 (Precipitation)**

### 溶解度通则

- 钠盐、钾盐、铵盐：均溶
- 硝酸盐：均溶
- 氯化物：溶（除 $\text{AgCl}, \text{PbCl}_2$）
- 硫酸盐：溶（除 $\text{BaSO}_4, \text{CaSO}_4, \text{PbSO}_4$）
- 碳酸盐：不溶（除 $\text{Na}_2\text{CO}_3, \text{K}_2\text{CO}_3, (\text{NH}_4)_2\text{CO}_3$）
- 氢氧化物：不溶（除 $\text{NaOH}, \text{KOH}, \text{NH}_4\text{OH}, \text{Ca(OH)}_2$ 部分溶）

## 7.6 结晶水

**水合 (Hydrated)**：物质化学结合了一定数量的水分子，如 $\text{CuSO}_4 \cdot 5\text{H}_2\text{O}$

**无水 (Anhydrous)**：不含水分子

---

# 八、The Periodic Table — 元素周期表

## 8.1 周期表的结构原理

元素按**原子序数（质子数）递增**排列成周期和族。

**周期 (Period)** 的规律：从左到右，**金属性减弱，非金属性增强**。

**族 (Group)** 的规律：同族元素**最外层电子数相同**，因此**化学性质相似**。

- I-VII 族：族数 = 最外层电子数 = 常见阳离子电荷数
- 电子壳层数 = 周期数

## 8.2 第 I 族—碱金属

趋势（向下）：**熔点降低、密度增大、反应性增强**

反应性增强的原因：原子半径增大，最外层电子离原子核更远，受核吸引力更弱，更容易失去。

## 8.3 第 VII 族—卤素

趋势（向下）：**密度增大、反应性减弱、颜色加深**

- 氟：淡黄色气体
- 氯：黄绿色气体
- 溴：红棕色液体
- 碘：灰黑色固体

**置换反应**：更活泼的卤素能将较不活泼的卤素从其化合物中置换出来。

$$\text{Cl}_2 + 2\text{Br}^- \rightarrow 2\text{Cl}^- + \text{Br}_2$$

反应性减弱的原理：原子半径增大，获得额外电子的能力减弱。

## 8.4 过渡元素

**特性**：
1. 高密度
2. 高熔点
3. **形成有色化合物**
4. 常用作**催化剂**
5. 具有**可变氧化态**（如 $\text{Fe}^{2+}$ 和 $\text{Fe}^{3+}$）

## 8.5 稀有气体（第 VIII 族）

**最外层电子全满**（He: 2; Ne, Ar, Kr, Xe, Rn: 8），故**极不活泼**，**单原子分子**存在。

---

# 九、Metals — 金属

## 9.1 金属键

金属键是**正金属离子**与**离域电子"海洋"**之间的**静电吸引力**。

金属的特性解释：
- **导电性**：离域电子可自由移动
- **延展性/可锻性**：金属离子层可滑动而不破坏金属键（离域电子保持吸引力）

## 9.2 反应性顺序 (Reactivity Series)

按反应性从强到弱：

$$\text{K} > \text{Na} > \text{Ca} > \text{Mg} > \text{Al} > \text{C} > \text{Zn} > \text{Fe} > \text{H} > \text{Cu} > \text{Ag} > \text{Au}$$

反应性体现在：**形成正离子的倾向**。越活泼的金属，越容易失去电子形成阳离子。

## 9.3 合金 (Alloys)

合金是金属与其他元素的**混合物**。因不同原子大小不同，破坏了金属层的规则排列，使**层间滑动受阻**，因此合金比纯金属**更硬、更强**。

## 9.4 金属腐蚀

铁的**生锈 (Rusting)**：需要同时有**氧气**和**水**。

$$\text{铁锈} = \text{水合氧化铁(III)} \quad \text{Fe}_2\text{O}_3 \cdot x\text{H}_2\text{O}$$

**防护方法**：
- **屏障法**（油漆、涂油、镀塑料）：隔绝氧气和水
- **镀锌 (Galvanising)**：既是屏障又提供**牺牲保护 (Sacrificial Protection)**
- 牺牲保护原理：锌比铁更活泼，优先失去电子被氧化，从而保护铁

## 9.5 金属的提取

提取方法与金属在反应性系列中的位置相关：
- 反应性较低的金属（如 $\text{Cu, Ag, Au}$）：可直接从矿石中获得
- 中等反应性的金属（如 $\text{Zn, Fe}$）：用**碳还原**（如高炉炼铁）
- 高反应性金属（如 $\text{Al}$）：**电解**提取

### 高炉炼铁

核心还原反应：

$$\text{Fe}_2\text{O}_3 + 3\text{CO} \rightarrow 2\text{Fe} + 3\text{CO}_2$$

炉渣生成（除去杂质 $\text{SiO}_2$）：

$$\text{CaO} + \text{SiO}_2 \rightarrow \text{CaSiO}_3$$

### 铝的提取（电解法）

铝土矿 ($\text{Al}_2\text{O}_3$) 溶于熔融冰晶石 ($\text{Na}_3\text{AlF}_6$) 以降低熔点。

阴极反应：

$$\text{Al}^{3+} + 3e^- \rightarrow \text{Al}(l)$$

阳极反应：

$$2\text{O}^{2-} \rightarrow \text{O}_2 + 4e^-$$

阳极碳棒与氧气反应生成 $\text{CO}_2$，因此阳极**需要定期更换**。

---

# 十、Chemistry of the Environment — 环境化学

## 10.1 水的检测与纯度

**水的测试**：
- 无水硫酸铜（白色）遇水变蓝：$\text{CuSO}_4 + 5\text{H}_2\text{O} \rightarrow \text{CuSO}_4 \cdot 5\text{H}_2\text{O}$
- 无水氯化钴（蓝色）遇水变粉红：$\text{CoCl}_2 + 6\text{H}_2\text{O} \rightarrow \text{CoCl}_2 \cdot 6\text{H}_2\text{O}$

**纯度检测**：纯水的熔点为 0°C，沸点为 100°C。含有杂质会改变这些物理常数。

## 10.2 空气组成与污染物

**清洁干燥空气组成**：
- 氮气 ($\text{N}_2$)：~78%
- 氧气 ($\text{O}_2$)：~21%
- 稀有气体 + 二氧化碳：~1%

**主要空气污染物及其来源**：

- $\text{CO}_2$：碳燃料完全燃烧 → **全球变暖**
- $\text{CO}$：碳燃料不完全燃烧 → **有毒气体**
- 微粒 (Particulates)：不完全燃烧 → **呼吸问题**
- $\text{CH}_4$：动植物分解、动物消化 → **全球变暖**
- $\text{NO}_x$：汽车引擎高温 → **酸雨、光化学烟雾**
- $\text{SO}_2$：含硫燃料燃烧 → **酸雨**

## 10.3 温室效应原理

温室气体（$\text{CO}_2, \text{CH}_4$）**吸收和反射**地球表面辐射出的**热辐射**，减少热量向太空的散失，导致全球变暖。

## 10.4 光合作用

$$\text{6CO}_2 + 6\text{H}_2\text{O} \rightarrow \text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2 \quad (\text{叶绿素，光照})$$

---

# 十一、Organic Chemistry — 有机化学

## 11.1 同系列 (Homologous Series)

同系列是具有**相同官能团**和**相同通式**的化合物家族，各成员相差一个 $-\text{CH}_2-$ 单元，物理性质呈现渐变趋势，化学性质相似。

**四大同系列的通式**：

| 系列 | 通式 | 官能团 | 键型 |
|------|------|--------|------|
| 烷烃 (Alkanes) | $\text{C}_n\text{H}_{2n+2}$ | 无（C-C 单键） | 饱和 |
| 烯烃 (Alkenes) | $\text{C}_n\text{H}_{2n}$ | $\text{C}=\text{C}$ 双键 | 不饱和 |
| 醇 (Alcohols) | $\text{C}_n\text{H}_{2n+1}\text{OH}$ | $-\text{OH}$ (羟基) | — |
| 羧酸 (Carboxylic acids) | $\text{C}_n\text{H}_{2n+1}\text{COOH}$ | $-\text{COOH}$ (羧基) | — |

**饱和 vs 不饱和**：
- 饱和：所有 C-C 键均为**单键**
- 不饱和：含有一个或多个 C-C **双键**（或三键）

## 11.2 同分异构体 (Structural Isomers)

同分异构体是**分子式相同但结构式不同**的化合物。

如 $\text{C}_4\text{H}_{10}$ 有两种：
- 正丁烷：$\text{CH}_3\text{CH}_2\text{CH}_2\text{CH}_3$
- 异丁烷：$\text{CH}_3\text{CH}(\text{CH}_3)\text{CH}_3$

## 11.3 石油分馏

石油是多种烃的**混合物**，通过**分馏 (Fractional Distillation)** 根据沸点差异分离。

分馏塔中：
- 塔底：长链烃（高沸点、高黏度）
- 塔顶：短链烃（低沸点、高挥发性、低黏度）

## 11.4 烷烃的取代反应

烷烃较为不活泼，但可在**紫外光**条件下与氯气发生**取代反应 (Substitution)**：

$$\text{CH}_4 + \text{Cl}_2 \xrightarrow{\text{UV}} \text{CH}_3\text{Cl} + \text{HCl}$$

取代反应是一个原子或基团被另一个原子或基团**替换**。

## 11.5 烯烃的加成反应

烯烃因含 C=C 双键，发生**加成反应 (Addition)**，双键打开，两端各加一个原子，**只生成一种产物**。

**与溴/溴水反应**（用于测试不饱和度）：

$$\text{C}_2\text{H}_4 + \text{Br}_2 \rightarrow \text{C}_2\text{H}_4\text{Br}_2 \quad (\text{红棕色溴水褪色})$$

**与氢气加成**（Ni 催化剂）：

$$\text{C}_2\text{H}_4 + \text{H}_2 \xrightarrow{\text{Ni}} \text{C}_2\text{H}_6$$

**与水加成**（酸催化剂）：

$$\text{C}_2\text{H}_4 + \text{H}_2\text{O} \xrightarrow{\text{酸}} \text{C}_2\text{H}_5\text{OH}$$

### 裂化 (Cracking)

将长链烷烃在**高温**和**催化剂**下分解为短链烷烃和烯烃（以及氢气）。

$$\text{C}_{16}\text{H}_{34} \rightarrow \text{C}_8\text{H}_{18} + \text{C}_8\text{H}_{16}$$

## 11.6 乙醇的制备

**发酵法**：葡萄糖在酵母作用下，25-35°C 无氧条件：

$$\text{C}_6\text{H}_{12}\text{O}_6 \rightarrow 2\text{C}_2\text{H}_5\text{OH} + 2\text{CO}_2$$

**乙烯水合法**：乙烯与蒸汽在酸催化下加压反应。

## 11.7 羧酸与酯化反应

**羧酸**与**醇**在酸催化下生成**酯 (Ester)** 和水：

$$\text{CH}_3\text{COOH} + \text{C}_2\text{H}_5\text{OH} \xrightarrow{\text{H}^+} \text{CH}_3\text{COOC}_2\text{H}_5 + \text{H}_2\text{O}$$

这是一个**酯化反应 (Esterification)**，属于**缩合反应 (Condensation)**。

## 11.8 聚合物 (Polymers)

### 加成聚合 (Addition Polymerisation)

单体含 C=C 双键，双键打开后相连形成长链：

例如聚乙烯：$n$ 个 $\text{CH}_2=\text{CH}_2$ 单体 → $[-\text{CH}_2-\text{CH}_2-]_n$

### 缩合聚合 (Condensation Polymerisation)

单体间反应，每次键合时**脱去一个小分子**（如水）。

**聚酰胺 (Polyamide)**：二羧酸 + 二胺 → 形成酰胺键 $-\text{CO}-\text{NH}-$

**聚酯 (Polyester)**：二羧酸 + 二醇 → 形成酯键 $-\text{CO}-\text{O}-$

### 蛋白质

蛋白质是**天然聚酰胺**，由**氨基酸**单体通过缩合聚合形成。

氨基酸通式：

$$\text{H}_2\text{N}-\text{CHR}-\text{COOH}$$

其中 R 为不同侧链。

---

# 十二、Experimental Techniques — 实验技术与分析

## 12.1 色谱法 (Chromatography)

**$R_f$ 值（保留因子）**：

$$R_f = \frac{\text{distance travelled by substance}}{\text{distance travelled by solvent front}}$$

$R_f$ 值在固定条件下是物质的特征值，用于**鉴定未知物质**。

## 12.2 离子鉴定

### 阴离子测试

| 离子 | 试剂 | 现象 |
|------|------|------|
| $\text{CO}_3^{2-}$ | 稀酸 | 产生 $\text{CO}_2$（使石灰水变浑浊）|
| $\text{Cl}^-, \text{Br}^-, \text{I}^-$ | 稀 $\text{HNO}_3$ + $\text{AgNO}_3$ | 产生沉淀（白色/淡黄/黄色）|
| $\text{SO}_4^{2-}$ | 稀 $\text{HNO}_3$ + $\text{Ba}(\text{NO}_3)_2$ | 白色 $\text{BaSO}_4$ 沉淀 |
| $\text{NO}_3^-$ | Al 箔 + $\text{NaOH}$ | 产生 $\text{NH}_3$ |

### 阳离子测试

使用 $\text{NaOH}$ 或 $\text{NH}_3$ 溶液可生成特征颜色的氢氧化物沉淀（如 $\text{Cu}^{2+}$ 蓝色、$\text{Fe}^{3+}$ 红棕色、$\text{Fe}^{2+}$ 绿色等）。

### 焰色测试

不同金属离子在火焰中呈现特征颜色：
- $\text{Li}^+$：红色
- $\text{Na}^+$：黄色
- $\text{K}^+$：紫色（透过钴玻璃观察）
- $\text{Ca}^{2+}$：砖红色
- $\text{Ba}^{2+}$：苹果绿色
- $\text{Cu}^{2+}$：蓝绿色

## 12.3 气体鉴定

| 气体 | 测试方法 | 阳性结果 |
|------|---------|---------|
| $\text{NH}_3$ | 湿润红色石蕊试纸 | 变蓝 |
| $\text{CO}_2$ | 通入石灰水 | 变浑浊 |
| $\text{Cl}_2$ | 湿润石蕊试纸 | 先变红后漂白 |
| $\text{H}_2$ | 点燃木条 | 爆鸣声 |
| $\text{O}_2$ | 带火星木条 | 复燃 |
| $\text{SO}_2$ | 酸性 $\text{KMnO}_4$ 溶液 | 紫色褪去 |

---

> **总结**：Cambridge IGCSE Chemistry 0620 涵盖的上述 12 大主题，从微观粒子世界到宏观化学反应，从理论原理到实验技术，构成了一个完整的化学认知体系。每个公式、每个原理背后都是对物质世界运行规律的深度揭示。掌握这些核心概念的内在逻辑联系，比单纯记忆公式更为重要。
