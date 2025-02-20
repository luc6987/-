# 宏观经济学 第二章 技术进步

> 每一代人都意识到资源有限对增长的限制，以及如果没有发现新的想法，增长将带来的附带损害。而每一代人都低估了他们发现新方法和新想法的能力。我们不断低估还有待发现的想法的广度。这些可能性不是相加的，而是成倍增加的。
> 
> —— 保罗·罗默

前一章揭示了经济发展的直接原因，即物质资本、人力资本和技术。从短期来看，即在索洛模型与人力资本的过渡动态过程中，相对于其自身静止状态，资本相对较少的经济体（无论是物质资本 $K(t)$ 还是人力资本 $H(t)$）享有高于其长期水平（$g_A$）的增长速度，从而使这些经济体至少部分地赶上其发展的滞后。这一性质可以通过以下方程总结：
$$g_{Y/L}(t) = g_A + (1 - \alpha) \phi \dot{u}(t) + \alpha \left( k(t)^{\alpha - 1} - k^{*\alpha - 1} \right)，$$
其中 $g_A$ 是技术的增长率，$\dot{u}(t)$ 是学习年限的延长，$k(t)^{\alpha - 1} - k^{*\alpha - 1}$ 是每单位有效劳动的物质资本与其长期值的差距的度量（正如我们所见，这一差距越大，物质资本的积累就越强劲）。

然而，从长期来看，过渡增长的来源注定会枯竭，因为学习年限（在初步估算中决定了每个人的人力资本存量）只能稳定下来，而物质资本快速积累带来的收益由于边际收益递减而逐渐减少。因此，尽管从长期来看，所考虑的三个发展因素可以解释每工人 GDP 水平的差异，但技术是每工人 GDP 增长的唯一动力。这一性质可以通过长期静止状态下的每工人生产表达式总结：
$$\frac{Y(t)}{L(t)} = \left(\frac{K(t)}{Y(t)}\right)^\alpha e^{\phi u^*} A(t)。$$
在这个表达式中，每单位生产的资本比率 $(K(t) / Y(t))^*$ 和人力资本项 $e^{\phi u^*}$ 可以在国家之间有所不同（因此可以解释每工人生产水平 $Y(t) / L(t)$ 的差异），但它们在时间上是恒定的（因此它们不对 $Y(t) / L(t)$ 的增长做出贡献）。最后，除了在长期每工人生产增长中的作用外，$A(t)$ 的水平还解释了富国和穷国之间约 50% 的发展差异（参见图 1.20）。

技术进步的这种双重重要性，作为发展差异的主要贡献者和长期增长的最终动力，值得特别关注。然而，在索洛增长模型中，技术进步是完全外生的，因此是未被解释的。这一缺陷导致了所谓的内生增长模型的发展，其目的是研究技术进步的来源以及它如何遵循个人选择的逻辑。在讨论技术创新在宏观经济动态中的作用之后，本章介绍了由 Paul Romer 在 1990 年提出的参考内生增长模型（即通过扩展产品种类的增长模型）。该模型表明，可以通过创新者的合理利益来解释技术进步，创新者从事研究与开发（R&D）活动，以获取与专利产品销售相关的垄断利润。新发明的产品加入到现有产品系列中，丰富了可用的投入品范围，从而使最终产品的生产越来越有效。我们还将研究内生技术进步模型的一个变体，即创造性破坏增长模型，其中新发明的中间产品比旧产品更具生产力，并倾向于取代它们。最后，我们将探讨均衡的最优性问题，即在市场均衡下，个人自由选择从事 R&D 活动时，经济是否产生了过多或过少的知识。

## 2.1 创新与技术进步
在最一般的层面上，技术进步 $A(t)$ 代表了一个经济体在某一时刻的知识状态，并且这些知识可以在其生产过程中被动员。知识状态随着时间的推移而变化，这是由于发现和创新（例如，微处理器）以及它们在企业中的传播（如个人电脑和更广泛的计算机工具）。创新可以是严格的技术性（如轮子、激光），也可以是组织性的（如激励工资、企业决策的去中心化）。值得注意的是，技术创新和组织创新通常是相辅相成的，特别是当技术创新的传播需要企业内部的工作重新组织时。这一现象的典型例子是信息和通信技术的普及，它伴随着企业组织的重要变革，强自治个体之间的横向关系部分取代了旧的纵向关系和严格编码的任务。

根据增长理论家保罗·罗默的说法，技术的一个本质特征是它的非竞争性。一旦一个想法被发明出来，任何知道它的人都可以利用它获利。换句话说，一旦想法被发明出来，其边际成本为零。我们立即看到，竞争均衡的范式在这里是有问题的。实际上，在完全竞争中，一个边际成本为零的生产要素的报酬本身也是零的。因此，在均衡状态下，想法的生产无法得到报酬。由于想法（通常）不会凭空出现，而是需要在研发上进行初始投资，竞争均衡完全消除了创新的激励，因为创新者无法收回成本。在现实中，这一悖论通过有意建立的不完全竞争制度（即授予发明者专利权）得到解决。这一权利允许发明者以高于想法边际成本（零）的价格出售其产品，从而随着时间的推移补偿初始的研发投资。我们在本章中研究的内生技术进步理论明确地形式化了这一机制，并研究了其对经济增长速度和均衡最优性的影响。

**定义** 当一个物品被一个人使用时，至少部分地阻止了其他人使用它时，这个物品是竞争性的（例如 CD）。相反，如果不是这样，它就是非竞争性的（例如音乐本身，如编码在 MP3 文件中的音乐）。

我们能否间接地衡量这些创新及其传播的速度？一种方法是依靠一些定量指标，例如专利申请数量或研究人员数量（绝对数量或相对于就业水平的数量）随时间的变化。图 2.1 和 2.2 说明了这些变化，并明确证明了在 20 世纪，特别是二战后，研发活动的加强。

正如我们所强调的，技术进步通常以所谓的工艺创新形式出现，这些创新需要企业内部工作组织的同步演变才能充分发挥效力。为了说明管理演变的重要性，Bloom、Sadun 和 Van Reenen（2012）的图 2.3 和 2.4 说明了过去三十年来欧洲和美国生产力演变与信息和通信技术（ICT）使用之间的关系。更具体地说，图 2.3 显示了欧洲的劳动生产率在 1980 年远低于美国，但在 80 年代和 90 年代趋于赶上。然而，这一趋势在 90 年代末发生逆转，美国的生产率增长变得比欧洲更为强劲，这在 2000 年代中期再次导致两地之间显著的生产率差距。一些研究表明，这一日益扩大的差距不能用计算机硬件生产部门（计算机、半导体等）的生产率增长来解释，因为这些部门在大西洋两岸的生产率增长是相同的。相反，我们观察到在计算机用户部门（如服务业）中，两地企业之间的生产率差距不断扩大。图 2.4 显示，平均而言，欧洲企业使用的计算机硬件少于美国企业（尽管相同的技术以几乎相同的成本可用），这一差距导致了较低的生产率。

如何解释这一现象？Bloom、Sadun 和 Van Reenen（2012）表明，欧洲企业对计算机工具的较少使用是由于部分不适当的管理实践，这导致了这种资本的较低回报率。计算机资本的较低回报率反过来又阻碍了对计算机的投资，导致每小时工作的计算机资本较少。这些研究完美地说明了技术和管理通常需要共同演变才能成为有效和可持续的增长来源。

为了理解技术进步的起源及其对经济长期增长的影响，我们需要理解是什么激励了创新活动。如果某些创新可能是偶然的结果或出于无私的研究活动（或由声望驱动），那么大多数创新，特别是应用研究，都是由追求金钱利润所驱动的。因此，我们需要理解经济主体在创新研究中投资时间和资源的激励（而不是使用现有的生产技术），然后将这种研发活动纳入增长理论。在下文中，我们研究了两个参考模型，其中技术进步是内生的，即通过有意的研发投资导致生产前沿的移动。在这两种情况下，激励研发的核心机制是专利申请的前景，这将使发明者在其发明的产品（或生产过程）上拥有垄断权。因此，追求垄断租金是激励和证明研发活动合理性的前提。

## 2.2 通过扩展产品种类实现增长
最简单的内生增长模型类别是那些通过 R&D 活动扩展用于生产最终产品的中间产品（或机器）种类的模型。为了清晰起见，我们将在此仅关注中间产品种类的扩展，并忽略所有其他潜在的增长来源。特别是，我们将考虑一个没有资本积累（物质或人力）和人口增长的内生增长模型（假设人口恒定并标准化为 $L=1$）。相反，我们将精确而严格地描述创新过程和新中间产品的创造。

与第 1 章的模型一样，时间是连续的，从 $t=0$ 到 $t=+\infty$。经济由两个部门组成：
- **最终产品部门**：该部门的个体通过结合现有的不同中间产品来生产最终产品，使用的是一种生产要素不完全替代的生产技术。该部门的生产者在他们销售的产品市场（最终产品）和购买的产品市场（中间产品）上都处于完全竞争状态。
- **创新或 R&D 部门**：该部门的个体发明新的中间产品，从而扩展可用于生产最终产品的中间产品种类（这是新中间产品发明的阶段）。由于他们的发明受专利保护，每个创新者在其发明的中间产品市场上处于垄断地位，并从向最终产品生产者销售中间产品中获得纯利润流（新中间产品商业化阶段）。由于存在大量部分可替代的中间产品，中间产品市场将表现出一种垄断竞争形式。

**定义** 垄断竞争是一种市场结构，其中每个公司生产一种差异化产品，并由于这种产品与其他公司销售的产品不完全替代而享有市场权力。

我们称 $\phi \in [0,1]$ 为在最终产品部门工作的劳动人口比例，剩余的 $1-\phi$ 从事 R&D 部门。在模型求解的第一阶段，我们将 $\phi$ 视为外生参数，并计算在给定 $\phi$ 的情况下每个部门的生产和利润水平。在求解的第二阶段，我们将展示 $\phi$ 如何通过自由进入条件在均衡中确定，假设个体是完全流动的，并选择对他们最有利的部门。

### 2.2.1 最终产品部门
我们首先描述最终产品生产者的最优行为。每个个体使用以下生产技术生产：
$$
\begin{align}
y(t)& = \sum_{i=1}^{A(t)} x(i,t)^\alpha,\alpha \in ]0,1[ \quad (2.1)\\
&=x(1,t)^\alpha+x(2,t)^\alpha+\dots+x(A(t),t)^\alpha
\end{align}
$$
其中 $y(t)$ 是在 $t$ 时刻生产的最终产品数量，$x(i,t)$ 是在 $t$ 时刻用于生产最终产品的中间产品 $i$ 的数量，$A(t)$ 是在 $t$ 时刻可用的中间产品种类数，即产品种类。这个数量是时间的函数，因为它是累积创新的结果（我们将在下一节中确定）。

为了便于分析，我们不强制 $A(t) \in \mathbb{N}$，而是允许产品种类的连续扩展。因此，我们将使用以下生产函数的连续近似：
$$y(t) = \int_0^{A(t)} x^\alpha(i,t) di . \quad (2.2)$$

由于一部分个体 $\phi$ 从事最终产品的生产，$t$ 时刻该产品的总产量为：
$$Y(t) = \phi \int_0^{A(t)} x(i,t)^\alpha di . \quad (2.3)$$

在任何时刻 $t$，每个最终产品生产者选择每种中间产品 $x(i,t)$，$i \in [0, A(t)]$ 的数量，以最大化其利润 $\rho(t)$，即其生产 $y(t)$ 与生产该数量所需的中间产品总成本之间的差额。设 $p(i,t)$ 为 $t$ 时刻中间产品 $i$ 的价格（以最终产品计价），最终产品生产者将其视为给定（我们记得他们在投入品市场上处于完全竞争状态）。这些生产者解决以下问题：
$$\max_{x(i,t), i \in [0, A(t)]} \rho(t) = y(t) - \int_0^{A(t)} p(i,t) x(i,t) di \quad (2.4)$$
在约束条件 (2.2) 下。对于任何中间产品 $i \in [0, A(t)]$，一阶条件将该产品的边际生产率 $\alpha x(i,t)^{\alpha - 1}$ 等同于其成本 $p(i,t)$：
$$\alpha x(i,t)^{\alpha - 1} = p(i,t).$$

这一阶条件给出了最终产品生产者在 $t$ 时刻对中间产品 $i$ 的需求量，对于所有 $(i,t) \in [0,1] \times [0,+\infty[$。我们得到中间产品 $i$ 在 $t$ 时刻的个体需求函数：
$$x(i,t) = \left( \frac{\alpha}{p(i,t)} \right)^{1/(1-\alpha)}, \quad (2.5)$$
不出所料，它随着价格的下降而减少（因为 $\alpha \in ]0,1[$）。我们注意到这个函数具有恒定弹性（它是等弹性的），其弹性为：
$$\frac{\partial x(i,t)}{\partial p(i,t)} \cdot \frac{p(i,t)}{x(i,t)} = -\frac{1}{1-\alpha} < 0.$$

需求对价格的弹性反映了从最终产品生产者的角度来看，中间产品的不完全替代性。我们上面提到，并将在下面明确研究，每个中间产品生产者在生产和销售该产品时处于垄断地位。然而，生产函数 (2.1)（或其连续近似 (2.2)）表明，中间产品在最终产品的生产中是部分可替代的：如果中间产品 $i$ 的价格非常高，仍然可以部分减少其使用，同时通过增加其他中间产品的使用来部分补偿由此引起的生产下降。生产函数的替代性程度取决于参数 $\alpha$，它决定了生产函数的凹性。$\alpha$ 越小，这种凹性越大，生产函数对生产要素的不对称使用的惩罚越大，每个卖家的市场权力越强。

为了更好地理解这一点，我们以一个静态经济中两个产品的生产函数为例，并假设（为了论证的清晰）两个中间产品的价格相等并标准化为 1。在这些假设下，生产函数 (2.1) 变为 $y(x_1, x_2) = (x_1^\alpha + x_2^\alpha)^{1/\alpha}$，中间产品的最优需求（方程 (2.5)）为 $x_1 = x_2 = (\alpha)^{1/(1-\alpha)}$，因此最终产品的生产水平为 $y = 2^{1/\alpha} (\alpha)^{1/(1-\alpha)}$。从这里出发，我们可以问最终产品生产者在总生产成本不变的情况下，用一个产品替代另一个产品的成本是多少。直观上，替代成本应该随着技术允许中间产品的高度替代性而降低。在总生产成本不变的情况下，中间产品 1 使用量的增加 $\Delta > 0$ 必须伴随着中间产品 2 使用量的相同减少（假设两个中间产品的价格相同）。这种偏离最优生产结构会导致最终产品的（比例）损失：
$$\frac{y(\bar{x}, \bar{x}) - y(\bar{x} + \Delta, \bar{x} - \Delta)}{y(\bar{x}, \bar{x})} = 1 - \left( \frac{2}{1 + \Delta^{\alpha - 1}} \right)^{1/\alpha} + \left( \frac{1 - \Delta^{\alpha - 1}}{1 + \Delta^{\alpha - 1}} \right)^{1/\alpha}.$$

当 $\alpha \to 1$ 时，$y(x_1, x_2)$ 是线性的，这种损失趋于零，这意味着中间产品是完全可替代的。相反，当 $\alpha \to 0$ 时，比例损失趋于 1，即中间产品的重新分配会导致等量的最终产品损失。随着 $\alpha$ 从 1 减少到 0，中间产品变得越来越不可替代。