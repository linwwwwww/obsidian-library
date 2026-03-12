# *Part I*
# Radial Motions and Radial Gas Flows in Local Spiral Galaxies 
 
#Author: Enrico M. Di Teodoro，J. E. G. Peek

## Intro
#### Why inflow observation is need？
* mergers cannot bring enough gas into spiral galaxies (Di Teodoro & Fraternali 2014) to sustain their star formation rate 
* while direct observation of gas accretion from the CGM/IGM still remains sparse and accretion rates very uncertain
#### hot cold mode（e.g., Kereš et al. 2005; Nelson et al. 2013; Stern et al. 2020）
#### relative to the chemical gradient
#### 21cm HI emission line detect gas flow：
* Atomic gas dominates at large radii（$R_{diskHI}$~3、4 $R_{disk*}$)
* gas surface density in the outskirts of disks is low enough that a significant radial accretion would imply detectable radial inward velocities.
* shows significant asymmetries
* disturb+small than the order of totation-->hard to say flows inward/outward
* chemical evolution
* 
## Data and sample
#### Data: 
best available H I surveys, including The H I nearby Galaxy Survey (THINGS; Walter et al. 2008), the Hydrogen Accretion in LOcal GAlaxieS survey (HALOGAS; Heald et al.
2011), the Local Volume H I Survey (LVHIS; Koribalski et al.
2018), the Westerbork survey of neutral Hydrogen in Irregular and SPiral galaxies (WHISP;, van der Hulst et al. 2001), the Very Large Array (VLA) Imaging of Virgo in Atomic gas survey (VIVA; Chung et al. 2009), the ATLAS3DH I survey (Serra et al. 2012) and the H I eXtreme galaxy survey (HIX; Lutz et al. 2017).

##### Sample selection:
1.criteria
(i) rotation velocity >100 km/s
(ii) sensitivity of the H I data :a H I column-density sensitivity better than ∼ 5 × 10^19cm−2
(iii) number of resolution elements :>15
(iv) the inclination angle. 30° < i < 80° ($\color{#FF0000}{不太懂为啥选倾角比较中间的，不选face-on的比较好理解，edge-on的不选不太理解}$ ：如果是整体的gas有inflow会抵消)
2. result:
Our galaxies have distances D < 40 kpc, log stellar masses ~ 9~11, and morphology ranging from early-type disks (e.g., S0, Sa) to late-type disks (e.g., Sb, Sc). from different environment

3. ancillary data:
**Distance**: the Extragalactic Distance Database (EDD; Tully et al.2009) and the CosmicFlows project (Tully et al. 2016). 
SFR:45/54 Leroy et al. (2019); 9: we estimate **SFRs** from WISE W3-band luminosities at 12 μm, following the calibrations of Cluver et al. (2017).
**Optical image**: Sloan Digital Sky Survey (SDSS; Eisenstein et al. 2011), the Panoramic Survey Telescope and Rapid Response System survey (Pan-STARRS; Chambers et al. 2016), or the Dark Energy Spectroscopic Instrument (DESI) Legacy Surveys (Legacy, Dey et al. 2019).
## Method
Fig1:twist in P-V图：
 radial flow will cause the twist in P-V minor-axis; warp twist minor and major
#### **BB**：
center：optical z band; mask：threshold of 5 × σrmsand a secondary threshold of 2 × σrms, where σrms is the rms noise of the data
BB Fit process: 
1. radial motions are null while the geometrical and the other kinematical parameters are kept free.
2. the inclination and position angles are regularized to some function and only the rotation velocity and velocity dispersion are fitted.
	The first two steps aim to determine **the rotation curve and the warp** and follow a classical tilted-ring modeling procedure.In these two steps, we set a $cos^2\theta$ weight for the fit, because the information on the rotation velocity/warp is mostly near the major axis (θ ; 0°), and we excluded pixels that lie within 20° from the minor axis, which allowed us to minimize any effect of possible radial motions on the fit
3. we only fitted for the radial velocity and we fixed all other parameters to the values previously determined.set a $sin^2\theta$ weight，to maximize using the data near the minor axis

## Result

*  we conclude that spiral galaxies in the local universe do not seem to have any systematic radial gas inflow/outflow in their outer disks.（Fig 5
* the amount of cold gas accreted alone seems insufficient to feed the star formation occurring in the stellar disk of most local spiral galaxies.（Fig 6）
### Discussion
**disadvantage**：
1. sysmetric
2. gas always moves in circular orbits.
3. Finally, we also assumed that H I disks have a constant scale height and that there are no significant vertical motions.
**compare with Schmidt et al. (2016）的结果**：mass flow rate 更小，原因：mask不同，Schmidt也许高估the H I column density in the faint outskirts of disks, because noisy pixels with positive values may be included in the mask without their negative counterparts.


# A SEARCH FOR KINEMATIC EVIDENCE OF RADIAL GAS FLOWS IN SPIRAL GALAXIES（2004）

^836602

## abstract：
radio/optical/near-infrared 
all galaxies deviate from pure rotation curve 20~60km/s
no unambiguous radial inflow，上限是5-10km/s
spiral 星系的不对称性对inflow探测的限制很大
## Intro
possible role in fueling nuclear activity and star formation in the inner disks of galaxies has been discussed by Shlosman, Frank, & Begelman (1989) and Blitz (1996), respectively./the context of evolution along the Hubble sequence (e.g., Norman, Sellwood, & Hasan 1996) and the formation of exponential stellar disks (Lin & Pringle 1987; Ferguson & Clarke 2001).

flow expected to be subsonic

other approach：
*  model grativational potential by the stellar(limitation: M/L,deprojection)

this work 3 type inflow:
1. uniform inflow; 2. elliptical stream(spiral stream); 3. outer warp accretion

bar - shock - inflow（因为不能很好的建模shock 所以没有考虑带bar星系）
$\color{#FF0000}{不太了解bar-shock-inflow的关系}$ 
## Method
* CO image：
use IRAM map to regenerate a combined (single dish+interferometer) CO data cube for this galaxy by using the IMMERGE technique---〉resulting in combined data cubes that are sensitive to emission on both large and small scales.
HI image

velosity been masked by rotation model

position angle：angle between major axis and N-S

pitch angle:桨距角：风机叶片和风轮平面的夹角
三个模型：
* inflow (比较简单)
* elliptical
* spiral
之后推演一下


![[1391663389846_.pic.jpg]]

line of nodes:星系坐标系和天球坐标系相交线
position angle$T_{nod}$  北方向和相交线的夹角
$\phi$ xy 平面上的角 
$\theta_{obs}$ xy平面上短轴和视线方向的角
az：星系盘面上和长主轴（短轴）的夹角

### Result
![[Screen Shot 2022-09-14 at 10.58.06 AM.png]]

# Radial gas motions in The H I Nearby Galaxy Survey (THINGS)
#Author Schmidt
abstract：
VLA THINGS survey 
10 nearby galaxies
outerparts：<3 $r_{25}$
new Fourier decomposition

### Intro
**kinematic model**:
	Kinematic studies assuming flat discs and models of particular streaming motions were conducted by [[Wong et al#^836602]](2004, search for radial inflow based on CO and H I observations of seven spiral galaxies), Spekkens & Sellwood (2007, bar-like streaming motions in NGC 2976 based on Hα and CO observations; development of the VELFIT code1) and Sellwood & Sanchez (2010, improvement) **DISKFIT** (Sellwood & Spekkens 2015),2an improved version of VELFIT which is not strictly limited to constant inclination and can also operate on photometric data
why inflow observation is need
1. natural outcome of cosmological structure formation calculation.streams(Dekel et al.(2009) and Ceverino, Dekel & Bournaud (2010));3/4fed by streams(Agertz, Teyssier & Moore 2009),turbulence(Klessen & Hennebelle 2010)
2. stellar content increase/overall HI constant(Hopkins, McClure-Griffiths & Gaensler 2008; Prochaska & Wolfe 2009)
3. the presence of deuterium in the solar neighbourhood (Linsky 2003)


### Data
selection criteria：**intermediate inclination**（30-40度）
distance 3-15Mpc; resolution 100-500pc
**natural weighting**:  more suitable for us since it provides better signal-to-noise (S/N) and better recovers diffuse emission
Compare with single dish suvery:Effelsberg–Bonn H I Survey (EBHIS, Kerp et al. 2011) and optical:NED
SFR: GALEX far-UV (FUV) images. 

## Theory and Method

position angle: angle between the apparent major axis of the disc (PA) and N

fix center, free i,PA
理论上对rotation velosity 和radial velosity 建模
![[999F6E49-286D-4AEC-BCFA-9059FB33950A.png]]
D0 B0零阶项，高阶项表示对theta az角的依赖
![[0862CB22-137A-4576-AC9D-76D6D7259674.png]]!
[[WeChat801c7ab1c86b3d8bb27d4a4dd68afc8f.png]]
实际观测中对观测到的傅立叶展开：
![[C1E1958B-E699-44B8-B513-1C014CBE7250.png]]

**2 步求解**：
1.一阶的tilted ring fit inclination and PA; 2. 傅立叶速度分解
$\color{#FF0000}{先直接拟合速度？}$

include the radial velocity component already in determining the ring geometry
与without radial motion 做比较（实际的星系，mock星系）
比较的结论：如果在第一步的拟合中没有包括radial velosity，inclination会进行补偿，因此在without radial motion的第二步分解中得到的radial component值很小。

**同步拟合**：
We fit all five Fourier parameters (c0, s1, c1, s2, c2) as well as i and PA
c3和i耦合，很难同时拟合，因此拟合到2阶

**error measure**：
Sellwood & Sanchez (2010) advertise a concept that uses the residuals of the fit as a noise source.残差可以作为噪声场的先验。($\color{#FF0000}{具体不是很懂，可以之后看看这篇文章}$)
仿照这篇文章去对每个ring的残差旋转，然后结合所有的环的残差。

**compare HI and SFR**：
![[A29C0F2B-B638-4B2C-8A8C-29E2AEDE53D6.png]]
假设没有时间变化项（第一项）

**[Brandt model of rotation curve](https://ned.ipac.caltech.edu/level5/Faber/Faber3_1.html)**
A simple and commonly used approximation is based on [Brandt's (1960)](https://ned.ipac.caltech.edu/level5/Faber/Faber_references.html#28) parametrization of the rotation curve:

 ![Equation 1](https://ned.ipac.caltech.edu/level5/Faber/Equations/eq1.gif) 
**overlapping**
拟合时对inclination和PA的限制

fitting [Gauss–Hermite functions](https://en.wikipedia.org/wiki/Gauss%E2%80%93Hermite_quadrature) to the H I spectra of each spatial resolution element

## Results

展示了不同星系的结果
通过HI的map分布和flow 相互检验，例如300arcsec inflow达到最大，则200-300arcsec处应当HI密度最大，有堆积

* 有许多星系的flow带来的HI 质量>SFR rate，可能是继续堆积或者星系喷泉等过程。
* 傅立叶分解项和inclination、PA的同时拟合可以减少先拟合inclination而带来flow的耦合，但是只能到2阶

## My Points
* 或许可以先尝试在模拟里mock其过程。
* 比较了2021 DiTeodoro和2016Schmidt两篇：
	1.2021里comment说radial flow大小差不多10km/s，HI的数密度测量有差距
	2.比较方法：
	2021是先fit geometry，再求radial velosity
	2016是同时fit，并且认为inclination会先行补偿radial flow，对radial flow的结果有影响
	3.结果：整体来说差不多，部分星系2016测量出来的radial flow大一些（可能就是inclination 补偿的影响？
	 $\color{#FF0000}{如果模型里加入了warp，应该是怎么样的结果？}$

---------------------------
# *Part II*

# COPLANAR GAS INFLOW CAN BE HIDDEN WITHIN WARPED GALACTIC GAS DISKS
#Author Enci Wang, Simon J. Lilly
Abstract:
Through the examination of nearby galaxies & mock velocity fields, found radial inflows are  hidden in warped disks

*Note*: Di Teodoro 2021中也讨论过warp对radial inflow测量的影响，其认为P-V图可以分辨出warp和radial inflow。体现在warp和radial inflow都会对P-V minor axis有影响，而radial inflow不会影响P-V major axis，warp会

## Intro:
是系列文章，paper I：
提出MAD：modified disk of sf galaxies：gas inflow decrease with the distance to center
磁场-旋转不稳定性是粘滞力的来源，其向里传输mass，向外传输角动量，生成与观测相符的SFR面密度,但是金属丰度和动力学待检验。
paper II：检验了金属风度
paper III：kinematic：
outskirt inflow speed **50-100km/s** ~> IllustrisTNG-100 simulations (Nelson et al. 2018), Wang et al. (2022) ∼**55 km s−1** at a radius of 10 times of half-mass radius
-------------------->Schmidt 2016,Di Teodoro **10kms/s**
提出warp可能是原因

## MAD 模型


outflow: 
平面外的outflow+ inflow ---> 有效 outflow, proportional to SFR；SFR proportional to gas surface density
Return Mass fraction ：R=0.4
气体盘稳态，指数形式的SFR profile 
B磁场 B $\propto \Sigma^{0.15}_{SFR}$  Z $\propto \Sigma_{SFR}$  independent  of SFE
![[4837F668-CA95-4839-8815-E843CE164A44.png]]
![[9145EE97-E9F5-478B-ADB8-68B33C6F511C.png]]
**$\color{#396566}{radial\ inflow ～SFR_{tot}}$**, 并且是每个r处是整圈气体在流动

结果（图1图2）：inflow随半径增大，小半径时和观测一样，ourskirt和模拟（10倍half mass radius）一样，ourskirt处气体呈旋进轨迹，气体运动不再在远离恒星盘的地方受到旋转支持
## 2d投影速度场

动力学主轴（定义为最大投影速度）和最小轴将偏离几何轴，通过模型给出了这个角的解析值，minor轴的偏转比major轴大，但是两者的差距和倾角有关

对Di 2021 的评论：该方法有效地将运动主轴的径向变形归因于仅存在翘曲，并忽略由径向流引起的运动主轴的变形，低估了radial flow对运动主轴的影响。(前两步只fit了warp) ![[Screen Shot 2022-09-25 at 11.19.10 AM.png]]
P-V slice
![[Screen Shot 2022-09-25 at 11.19.37 AM.png]]
$\color{#FF0000}{在Di2021的这篇文章中，是否未考虑主轴的偏转？只考虑了动力学主轴，之后试着重复一下这个model}$
$\color{#FF0000}{我的想法：在Di2021的这篇文章中，其讨论的是运动学主轴的distortion， 而Wang2022讨论的是运动学主轴和几何主轴的夹角，应该是两个东西，Wang2022中的评论有失偏颇；而2016那篇文章中提出radial flow和inclination是有耦合的，这确实应当会有影响，从Di2021图里看出应该是有一些影响的，可能和设置的radial inflow 值有关系}$
忽视radial flow 可能会高估旋转速度

区分radial flow 和warp：
If radial inflow is the dominant effect in distorting the isovelocity contours of the galaxy, then we would therefore expect that the twists of the kinematic major axis and of the spirals arms should always be in the same sense,而warp和悬臂没有关系；只能从统计学的意义来测（若随机，则warp占主导）（有一个很强的假设：spiral要follow这个盘的运动，换句话说，星系转的方向和悬臂的方向是反的
利用Di 2021的样本来测，接近50%随机，warp占主导

## Mock galaxies
Method：用BBarolo模拟气体

结论：
* warp模型可以fit上radial flow，最大的误差15km/s
*  PA会fit的不准（因为运动主轴偏离几何主轴）
* $\color{#FF0000}{Q:inclination的测的比较准确，而Schimit2016那篇文章中说会对inclination有影响，感觉有点矛盾 A:应该是样本数量比较少，后面200个样本时也改变了inc值}$
* 大PA和INC会fit得不准，可能是更多的气体重叠。**由于小倾角的强简并，大倾角的更容易有观测到radial motion**
* 从样本中match观测样本的PAInc，画MAE和半径的图，结果类似，表明radial flow 可能隐藏在warp模型中
 $\color{#FF0000}{有可能是fit时的过程问题，如schmit2016同时fit会不会有改变}$
 

# Non-circular flows in HIghMass galaxies in a test of the late accretion hypothesis
#Author Bisaria Dhruv
## Intro
4 HI Monster M_HI>10^10Msun large MHI/M* ratio(0.24~9.2)
two reason for the high HI fraction:
1. low SFR--->observed high SFR
2. extra gas source---->need observed
## Method
sample:
4 galaxies![[Screen Shot 2022-09-27 at 4.13.16 PM.png]]
**Halpha波段**
Moon has effect on the observation
Disk Fit：
only flat disk, no warp ---> based on observation
fit major/minor轴的北侧/南侧
图4:这三个星系在内侧0-3（0-5）kpc都呈现了非circular的flow，可能是bar，特别是9334星系可以在optical图像里看到，而diskfit这个软件对bar和radial flow拟合有简并

图6&7:UGC 8475 and UGC 9334 rotation curve ：边缘有翘起，但是光学图上看起来没有warp

UGC7899 用对称flow和radial flow 拟合，差别不大。和前人结果R band和HI的ratation curve一致，可能有warp
$\color{#FF0000}{why\ I\ don't\ find\ the\ size\ of\ slit\ among\ the\ major\ axis?\ is\ it\ the\ resolution\ of\ the\ observation}$
## Discussion
hot accretion test：
simulation认为HIghMass星系应当是hot accretion
Pezzulli & Fraternali（2016）给出吸积率定义式：
![[Screen Shot 2022-09-28 at 4.00.24 PM.png]]
α is a unitless parameter measuring the local angular momentum deficit of the infalling material relative to the corotating disc flow 

# *Part III* 
# Accretion, radial flows and abundance gradients in spiral galaxies
#Author Gabriele Pezzulli and Filippo Fraternali
## Abstract
* theory：the decomposition of the gas flow/solve the equation of metallicity evolution
* prediction vertification：the material accreting on the Milky Way should rotate at 70–80 per cent of the rotational velocity of the disc, in agreement with previous estimates
## intro
chemical evolution provide an alternative way
## 2 .Model
主要用到的假设：
指数盘，Kennicutt–Schmidt law, independent annuli, 计算金属时（assumes instantaneous recycling）; radial gas flows are dominated by accretion ；角动量守恒
定义概念：
effective accrection(accrection to sustain the structure)
$\alpha$：盘和吸积气体的相对角动量差

## 应用
redistribution effect
结果：（图2）速度预测在1km/s左右$\color{#FF0000}{相距其他观测/理论较低。如果是这个速度应该很难被观测到}$
## 金属
特征线： https://www.zhihu.com/question/40518374
（图三）：更强的radial flow使得r小的（即内部的）的区域金属丰度大于外围：原因是：1.外围被稀释更多，2.radial flow向内将金属带入
SFRD 检验

## inside-out模型
采用了不同的$\Sigma$ eff（inside-out模型）

# Gas infall and radial transport in cosmological simulations of Milky Way-mass disks
Simulation：Fire +CR（without CR，气体吸积 similar）
径向分量和悬臂有关
低密度电离气体以相对较高的径向速度吸积，同时表现出整体的共旋转感。当这种气体与磁盘边缘汇合时，它不再容易向内流动，平均而言，这会导致它在径向上减速。这种积累导致密度和中性分数增加（由于更有效的自我屏蔽）implying that ionization is not the main factor determining the extent of the HI disk
$\color{#FF0000}{对于边界定义来讲，观测中sharp drop offs 10^{18}~10^{19},和现在观测极限一致，观测时可以看edge外的gas的角动量情况}$
HVC/IVC: We flag HVCs as any particle with deviations from the galactic rotation curve11above 70 km/s. IVCs are identified as particles with deviations of 40-70 km/s
HVC/IVC的结论：0-30% accretion
ring-average velosity/peak velocity
Ho, S. H., & Martin, C. L. 2020, ApJ, 888, 14# 观测
Zheng et al. (2017) observed 7 UV bright disk stars in M33 as background sources using the COS in order to identify significant ionized gas accretion.
Accretion velocity was Vacc = 100+15 −20kms−1and estimated mass flux was 2.9 M?yr−1(5.8 M?yr−1if flows are axisymmetric).
数值符合理论模型：theoretical models of “gravito-turbulent” disks or disks with an effective “turbulent viscosity” (Gammie 2001; Rice et al. 2005; Cossins et al. 2009; Hopkins & Christiansen 2013)
观测只能观测到一个时间点，径向运动容易被混淆

# A unified model for galactic discs: star formation, turbulence driving, and mass transport
从理论推ks关系、dispersion-SFR关系、Q～1、SFR～M_H2 这几个经验关系
假设：
1 starforming/ISM区域，吸积率不只受恒星potential的影响。
2 引力不稳定引起的gas transport会阻止盘走向更不稳定
3.Qg<Q\_*

模型：
1.引力不稳定性：
Q
2.z方向力平衡
 the force exerted by the gradient in thermal, turbulence and gravity force（提到磁场力但是说可以忽略）
3.能量守恒
1）扰动耗散
2）恒星形成注入
4.radial transport
**if we observe a galaxy’s velocity dispersion to be close to σsf, we can conclude that the turbulence within it is primarily powered by star formation, whereas if we observe the velocity dispersion to be > σsf, we can conclude that the turbulence is primarily powered by gravity**
5.Mass inflow rate
Mass inflow rate 正比与sigmagas^3 
: local spirals and dwarfs with modest velocity dispersions and modest star formation rates have σg/σsf≈ 1, and as a result also have low-mass inflow rates, ∼10−2Msunyr−1 for the dwarf and ∼1 Msunyr−1for the spiral. In contrast, rapidly star-forming ULIRGs and high-redshift galaxies have high σg/σsf and high inflow rates.
模型对inflow rate的限制不是很大

Predict:
. We also predict that high gas inflow rates should be measurable in nearby starburst galaxies, whose kinematics have yet to be analysed for inflow.

