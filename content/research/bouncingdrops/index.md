---
title: 弹跳液滴与界面流动不稳定性
summary: 液滴弹跳通常需要一个界面（固体表面或气液界面），但是我们发现，液滴竟然可以在连续的流体内部发生弹跳！点击查看详情
date: 2020-12-01
tags: ["ll","multicomponent","drops"]
type: landing
# choose from landing, page, pages, post, posts, book,
toc: ture
backlinks: false
# 
share: false
# Show author bio
profile: true
# authors: ["p2黄理琛"]
image:
  placement: 1
#   caption: 'Photo by [Geo](https://github.com/gcushen/)'
#   focal_point: 'Center'
  preview_only: false

# Show publish date
show_date: false
# Show reading time
reading_time: true
# Show breadcrumb navigation
show_breadcrumb: false
# Hide header
header:
  navbar:
    enable: true
# Next in series
pager: true
# Show recommendations
show_related: true
sections:
  - block: markdown
    content:
      title: 无壁面液滴弹跳的系列研究
      text: |-
            
            ## **这一系统性研究耗时经年（5~6年），主要分为三个阶段**:
            1. 弹跳现象的发现 (2017-2019)
            2. 追踪到弹跳现象的本质：Marangoni 流动不稳定性，并解释之 (2019-2022)
            3. 弹跳轨迹（振幅与周期）的解释 (2021-2023)<br>
            <br>

            ## 1. 液滴在密度分层液体中的连续弹跳及其突然终止现象

            本文报道了一项关于自驱动油滴在垂直分层的乙醇-水混合物中运动的实验与数值模拟研究。研究发现，油滴在重力作用下缓慢下沉后，**尚未达到密度匹配位置时突然向上跳跃**，并持续以**振幅递增的方式反复弹跳**约30分钟，最终**毫无征兆地停止运动**（“突然死亡”）。这一现象挑战了传统液滴弹跳需依赖界面或壁面的认知，首次展示了**连续介质内无边界条件下的液体弹跳行为**。

            
            {{< spoiler text="**现象与机理概述**" >}}
              1. **弹跳动力学**：  
                油滴初始因密度略大于下层液体而下沉，但随着下沉，其表面**乙醇浓度梯度引发的马兰戈尼应力**逐渐增强。当浮力射流（由油滴拖拽液体形成）减弱时，马兰戈尼流占据主导，形成**向下补充流**，将乙醇富集液体拉至油滴顶端，**降低顶端表面张力**。此过程触发**指数级增长的马兰戈尼速度**，使液滴突然跃升。重力作用下液滴重新下沉，系统周期性恢复，导致重复弹跳。

              2. **振幅增强与突然死亡**：  
                每次弹跳后，液滴下沉更深，累积的界面能转化为更大动量，导致弹跳高度增加。同时，剧烈的流动混合**削弱周围液体的浓度梯度**，马兰戈尼驱动力逐渐衰减。最终，当浮力射流强度超过残余马兰戈尼应力时，液滴无法再触发跳跃，发生“**突然死亡**”。

            {{< /spoiler >}}



            <!--1. 液滴在分层液体中的自主弹跳及其突然死亡现象

            ### 关键发现  
            在**稳定密度分层的乙醇-水混合液**中，密度介于乙醇-水之间的**油滴（trans-Anethole）**展现出独特的**无界面自主弹跳行为**：  
            - **运动特征**：  
              - **初始阶段**：油滴因重力缓慢下沉，但未达到密度匹配位置时**突然跃升**（跳跃高度达直径4倍）。  
              - **持续弹跳**：油滴经历**26次周期性跳跃**，每次下沉深度逐次增加而跃升高度保持约 6 mm（对应乙醇浓度 60 wt%），导致**跳跃幅度逐步扩大**。  
              - **突然停止**：经过约30分钟后，弹跳行为骤然终止，液滴缓慢沉降至密度匹配的位置。  

            ### 原理
            #### Marangoni 应力与重力的动态耦合  
            1. **Marangoni 流动触发跳跃**：  
              - **表面张力梯度驱动**：油滴上方乙醇浓度更高，导致液滴顶端与底端表面张力差异（Δσ），产生**向下Marangoni流动**（图2d）。  
              - **非线性正反馈**：Marangoni流将高乙醇液体拉至液滴顶部，进一步放大Δσ，形成指数增长的流动性（图3b，**指数增长时间常数τ≈0.08 s**）。  

            2. **重力作用的双面性**：  
              - **能量储存**：液滴下沉时，周围低乙醇浓度的液体通过对流包裹液滴，**累积界面能**（图2a）。  
              - **系统恢复**：重力作用使液滴再次下沉，重置周围流体梯度，为下一次跳跃准备条件。<br>
              <br>-->




            至此，我们只是知道了弹跳液滴为什么会弹跳。但是是否有什么东西遗漏了？<br>

            ### 悬停液滴的发现
            
            是的，直至我们发现，足够小的液滴可以在比较弱的背景浓度梯度中悬停，而大液滴或大浓度梯度不可以。这个现象的物理本质才浮出水面：**Marangoni 流动不稳定性**。

            ## 2. 液滴在稳定分层液体中的 Marangoni 流动不稳定性

            ### 研究背景  
            **Marangoni 不稳定性**广泛存在于界面存在浓度或温度梯度的多相流体系统中，对晶体生长、乳液稳定性和活性液滴运动等领域至关重要。传统观点认为，在小尺度下浮力效应可忽略，**稳定密度分层对 Marangoni 流的影响被长期忽视**。然而，本系列研究通过实验与理论结合，揭示了稳定分层在触发新型**振荡型 Marangoni 不稳定性**中的关键作用，并建立了统一的尺度理论框架。  

            ---

            ### 物理机理  
            #### 浓度梯度与流动耦合  
            当**不混溶液滴**（如硅油）浸入乙醇-水的稳定分层液体时：  
            1. **Marangoni 应力**：液滴表面张力梯度（由乙醇浓度梯度引起）驱动流体沿界面流动。  
            2. **密度分层与浮力**：稳定密度梯度引发浮力效应，与 Marangoni 流形成竞争。  
            3. **动力学平衡**：  
              - **低粘度液滴**：Marangoni 对流与扩散竞争（扩散主导阈值判据）。当对流速率超越扩散（即 **$Ma/Ra^{1/2} > 275$**），流场失稳引发液滴振荡。  
              - **高粘度液滴**：边界层增厚导致**黏性应力无法平衡浮力**（黏性主导阈值判据），临界半径由 **$Ra/Ma > const$** 决定。  

            ---

            ### 创新方法  
            #### 实验突破  
            - **分层流体制备**：通过改进双桶法 (Double bucket method) 实现宽范围线性浓度梯度（3~150 m⁻¹），结合激光偏转技术精准测量分层。  
            - **多参数空间探索**：系统改变液滴半径（**R=20~500 μm**）、粘度（**5~100cSt**）和分层强度，首次揭示不同粘度下的失稳机制分岔（图3, 图8）。  

            #### 理论框架  
            - **统一无量纲判据**：引入 **Marangoni 数（$Ma = VₘR/D$）** 和 **Rayleigh 数（$Ra = gR^4∇ρ/μD$）**，发现：  
              - **扩散主导区（$δ < R$）**：不稳定性由对流-扩散竞争触发，判据 $Ma/Ra^{1/2} > const$（也即$dw/dy > (dw/dy)_{cr}$）。  
              - **黏性主导区（$R < δ$）**：不稳定性源于浮力突破黏性应力，判据 $Ra/Ma > const$（或$R > R_{cr}$）。  
            - **有趣的是**:
              - 在**扩散主导区（$δ < R$）**，判据 $Ma/Ra^{1/2} > const$ 代表了只要溶液的浓度梯度超过一定阈值，流动就会失稳，**与液滴半径 $R$ 无关**。
              - 在**黏性主导区（$R < δ$）**：判据 $Ra/Ma > const$ 代表了只要液滴足够大，流动就会失稳，**与背景的浓度梯度无关**。 <br>
              以上两个结论都得到了实验的证实。<br>
              也就是说，在触发失稳时，**实验的两个独立参数**：液滴半径 $R$ 与背景浓度梯度，**是解耦的**。

            ---

            ### 结论与指导意义  
            #### 核心发现  
            1. **稳定分层的放大效应**：在受限几何中（如微型容器），**浮力效应**通过边界层与尺度的耦合**显著增强**，导致失稳阈值降低。  
            2. **粘度依赖的机制转换**：液滴粘度通过改变 Marangoni 边界层厚度 $δ$，使失稳机制在扩散主导（低 $μ^\prime$）与黏性主导（高 $μ^\prime$）间连续过渡。  

            #### 应用价值  
            - **微流体控制**：指导微型液滴/气泡在分层介质中的运动设计，例如药物递送中的定向迁移。  
            - **材料加工**：优化晶体生长过程中的温度/浓度梯度参数，抑制界面振荡缺陷。  
            - **乳液稳定性**：为高精度食品/化妆品乳液中 Marangoni 效应的调控提供理论支撑。  

            #### 理论延拓  
            该框架可推广至**热 Marangoni 系统**（如温度梯度低至 3 K/mm 即可触发流动不稳定性，导致流动振荡），并拓展至气泡、多液滴相互作用等复杂场景，为多组分流体动力学研究提供指导（DOI:[10.1103/PhysRevLett.126.124502](https://doi.org/10.1103/PhysRevLett.126.124502)）。  


            <!--### 小油滴的奇幻漂流：你从未见过的液体弹跳艺术

            想象一颗油滴沉入鸡尾酒般的分层溶液中，突然像弹簧般反复弹跳，最终离奇"死亡"——这不是魔法，而是流体力学的最新发现！在2023年这项突破性研究中，科学家们揭开了液滴在分层溶液中上演"蹦床秀"的奥秘。

            #### 实验奇观：粘性舞蹈与弹跳陷阱
            当硅油滴进入乙醇-水的"彩虹层"时，它们会经历神奇的动力学表演：
            - **低粘度油滴（5cSt）**：前两次弹跳可跃升5毫米（比身宽大50倍！），但随着时间推移会升级成更夸张的跳跃
            - **高粘度油滴（100cSt）**：60秒内爬升2毫米后，以电影慢动作般的优雅姿态缓缓坠落
            - **最终詸局**：30分钟后所有主演突然"谢幕"，在实验容器中静止不动

            #### 科学解密：看不见的液体引擎
            这场视觉盛宴的背后，是一场激烈的物理博弈：
            1. **Marangoni效应**：液滴表面张力差异创造微型推进器，形成自下而上的动力引擎
            2. **分层结构**：上层富乙醇、下层富水的溶液形成自然升降梯道
            3. **粘性对抗**：油滴内部"糖浆"般的高粘度与溶液阻力交织成复杂博弈
            4. **能量循环**：每次下沉储存势能，表面张力积蓄能量驱动下一次爆发式跳跃

            #### 科技启示：改写教科书的神奇系数
            研究团队首次揭开两个关键密码：
            - 发现了**强分层环境中新型阻力公式**，修正了传统流体理论
            - 通过超算模拟证实：**高粘油滴的阻力系数比预期高70%**
            - 创新性提出"流体记忆效应"概念——液滴会记住运动轨迹改变周围流场

            #### 余韵未了：  
            这项突破不仅解释了海洋中微塑料的移动密码，更为设计新一代药物微胶囊运输系统提供了灵感。下一篇《自然》封面，或许就是模仿这种弹跳机制的微型机器人！这一发现再次证明：最迷人的物理剧，正在微观世界的舞台上悄然上演。

            **重磅预告**：该团队已成功复现2mm油滴连续弹跳12小时，暗示着永动机的科学启示？点击链接观看实验室实拍视频，见证流体力学的魔法时刻！-->

            ### 上一部分系统性地解释了液滴从悬停（流动稳定）变到弹跳（流动失稳）的物理机理。接下来的第3部分则详细研究了液滴开始弹跳以后，弹跳的高度以及周期是如何变化的。<br>
            <br>

            ## 3. 强分层液体中弹跳油滴升降运动机制研究

            ### 核心发现  
            在**乙醇-水强分层体系**中，弹跳液滴的**运动轨迹特性**（跳跃高度、上升/下沉时间）显著依赖于液滴半径、分层强度与粘度。我们发现：
            - **弹跳轨迹不对称性**：低粘度液滴（5 cSt）呈现快速上升-缓慢下沉特征，上升时间为下沉时间的1/3，这与Marangoni流动和边界层动力学的阶段性优势相关。
            - **阻力系数双标度律**：引入分层修正的阻力系数($C_D^S$)解释运动特性：
              - **低粘度液滴**：上升阶段$C_D^S ∝ Ri^{0.47}/Re$，与文献中固体颗粒结果一致；下沉阶段$C_D^S ∝ Ri^{0.25}/Re$，反映扩散主导的黏性-扩散机制。
              - **高粘度液滴**（100 cSt）：强分层下发现新标度$C_D^S ∝ Ri^{0.66±0.01}/Re$，揭示分层层流与Marangoni流动的非线性耦合效应。

            ### 关键机理  
            #### 阶段动力学解耦  
            1. **上升阶段**：强烈Marangoni流动压缩液滴顶端等密度面，诱发涡旋内循环（图7a），显著降低界面张力梯度，形成指数加速过程（$τ_{rise} ≈ 0.08s$）。
            2. **下沉阶段**：Marangoni效应减弱，液滴拖曳低乙醇液体形成的“密度尾流”增强浮力阻力，导致速度衰减（图7b）。

            #### 分层-黏度耦合效应  
            - **低粘度体系**：$Re\sim O(10^1)$, $Fr\sim O(10^{-1})$下，阻力受湍流尾流与黏性边界层竞争支配，与Yick等（2009）经验律吻合。
            - **高粘度体系**：强分层（$Ri\sim 10^1$）引发双扩散机制，数值模拟揭示异于经典理论的标度关系，表明分层长度尺度与黏性耗散层的复杂相互作用。



            ### 参考文献

            1. **Li, Y.**, Diddens, C., Prosperetti, A., Chong, K. L., Zhang, X., & Lohse, D.    
              Bouncing Oil Droplet in a Stratified Liquid and its Sudden Death.  
              [_Physical Review Letters_](https://doi.org/10.1103/PhysRevLett.122.154502), **122**, 154502 (2019).  
                  - (首次发现分层液体中油滴的非稳态弹跳行为，揭示Marangoni应力与重力竞争机制）

            2. **Li, Y.** , Diddens, C., Prosperetti, A., & Lohse, D.     
              Marangoni Instability of a Drop in a Stably Stratified Liquid.  
              [_Physical Review Letters_](https://doi.org/10.1103/PhysRevLett.126.124502), **126**, 124502 (2021).    
                  - (提出稳定分层触发振荡不稳定性的临界判据，建立扩散主导机制的理论框架） 

            3. **Li, Y.** , Meijer, J. G., & Lohse, D.    
              Marangoni Instabilities of Drops of Different Viscosities in Stratified Liquids.  
              [_Journal of Fluid Mechanics_](https://doi.org/10.1017/jfm.2021.983), **932**, A11 (2022).  
                  - (揭示液滴黏度对稳定性的非线性调控机制，提出统一跨尺度理论模型）

            4. Meijer, J. G., **Li, Y.**, Diddens, C., & Lohse, D.    
              On the rising and sinking motion of bouncing oil drops in strongly stratified liquids.     
              *[Journal of Fluid Mechanics](https://doi.org/10.1017/jfm.2023.415)*, **966**, A14 (2023). 

            5. **Li, Y.**    
               Research progress on the Marangoni instability of a drop/bubble immersed in linearly stratified liquids.     
               [_Journal of Theoretical and Applied Mechanics_](https://doi.org/10.6052/0459-1879-24-034), **56(6)**: 1540-1551 (2024).


    
---

Congratulations to Jian Yang and Monica Hall for winning the Best Paper Award at the 2020 Conference on Wowchemy for their paper “Learning Wowchemy”.

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.

Sed eu dui nec ligula bibendum dapibus. Nullam imperdiet auctor tortor, vel cursus mauris malesuada non. Quisque ultrices euismod dapibus. Aenean sed gravida risus. Sed nisi tortor, vulputate nec quam non, placerat porta nisl. Nunc varius lobortis urna, condimentum facilisis ipsum molestie eu. Ut molestie eleifend ligula sed dignissim. Duis ut tellus turpis. Praesent tincidunt, nunc sed congue malesuada, mauris enim maximus massa, eget interdum turpis urna et ante. Morbi sem nisl, cursus quis mollis et, interdum luctus augue. Aliquam laoreet, leo et accumsan tincidunt, libero neque aliquet lectus, a ultricies lorem mi a orci.

Mauris dapibus sem vel magna convallis laoreet. Donec in venenatis urna, vitae sodales odio. Praesent tortor diam, varius non luctus nec, bibendum vel est. Quisque id sem enim. Maecenas at est leo. Vestibulum tristique pellentesque ex, blandit placerat nunc eleifend sit amet. Fusce eget lectus bibendum, accumsan mi quis, luctus sem. Etiam vitae nulla scelerisque, eleifend odio in, euismod quam. Etiam porta ullamcorper massa, vitae gravida turpis euismod quis. Mauris sodales sem ac ultrices viverra. In placerat ultrices sapien. Suspendisse eu arcu hendrerit, luctus tortor cursus, maximus dolor. Proin et velit et quam gravida dapibus. Donec blandit justo ut consequat tristique.
