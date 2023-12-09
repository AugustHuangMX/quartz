

To analyze the laws as an "Economist".

[[Review Class on Microeconomics]]

[[Property Law]]

[[ECON4008 Midterm Review]]

[[ECON4008 Question List]]


# Tort Law 侵权法

Definition of tort: Wrongful acts that cause harm or injury.

## Comparison between [[Contract Law]] and [[Tort Law]] 

-  [[Contract Law]]: Situation where someone harms you by *breaking a promise* they had made
- [[Tort Law]]: Situation where someone harms you *without having made any promises*. 不存在任何违约情况，所以不可能有合同法。

所以在财产法，合同法之外，需要另一种实体私法

[[Coase]] states that with [[Transaction Cost]], we may not able to reach efficiency under property law.


Previous Conclusion :

1. Property law works well for simultaneous trade
2. Contracts allow for non-simultaneous trade ( You can breach the contract, but you have to compensate.)

### Our Goal:

1. Minimize transaction cost. (Let two parties communicate easier)
2. Allocate rights as efficiently as possible

If we say the [[Property Law]] and the [[Contract Law]] are both *voluntary*, then the [[Tort Law]] is more like *involuntary*, since no body wants to deal with each other previously before harm... That is to say, [[Tort Law]] covers those situations with very high [[Transaction Cost]] to agree anything in advance.

After understanding these, we will move to the [[Tort Law]] .

---

## Classic Legal Theory of [[Tort Law]]

- Plaintiff: 原告, or can be understand like victim
- Defendant: 被告 or can be act as injurer.

The plaintiff must provide 3 basic elements:

1. Harm
2. Causation
3. Breach of duty

### Element 1: Harm

![[截屏2023-11-13 20.23.41.png|400]]

Remember one thing: **If no harm, then no tort**.

Perfect Compensation: restore the victim to original level of well-being. But it will separated by the tangible and intangible harms. (Like emotional damage, pain and suffering, you can't measure them directly by money). The courts are more willing to compensate the tangible ones, like medical costs and so on.

### Element 2: Causation

The defendant must to have caused the harm to the plaintiff.

Proximate Cause: 被告的行为不能与伤害之间间隔太远，否则它不是近因 (Proximate cause)


### Element 3: Breach of Duty

| Strict Liability| Negligence|
|---|---|
|Harm|Harm
|Causation|Causation|
| |Breach of duty (fault)|

When someone breaches a duty he owes to the defendant, and this leads to the harm, the injurer is at fault, or negligent

#### Under the Negligence Rule Method...

I am only liable if I failed to take the required standard of care. 如果我尽力了，但意外还是发生，则我没有过错。

那么问题就被转移到了：这个“我是否尽到应尽的义务（standard of care）”究竟由谁来定义？怎么定义？

	通常来说政府会设立 safety regulation 来确定标准，比如高速限速等。但是也有模糊标准（vague standard），比如对鲁莽驾驶的定义（大雾天还开很快），common law（普通法）就是把你当成一个理性人来预判你的行为

#### Strict liability versus negligence

Strict Liability Rule: 原告一定要证明存在伤害和因果关系。如果原告能够证明被告的行为直接导致了对他的伤害，那么被告就需要承担责任，无论他是否是过错方

Negligence Rule: 过失责任原则。原告必须证明除了有存在和因果关系，还需要证明被告存在过失。如果被告（像之前提到过的）已经尽力了，那么他就不应该被惩罚。

**出题爱这么出！需要注意！**

## Precaution

通过预防来降低意外发生的概率，考试就比较喜欢这么出，因为涉及到概率，那么期望（expectation）也会随之降低。

预防不是施害者才可以做，受害者也可以通过各种手段采取预防。

再次强调：本门课很强调效率！所以自然而然就会带来两个问题：什么才是最优的预防程度呢？我们如何设计一个方法来得到这个最优预防程度？

### Simple economic model for thinking about tort law

为了让模型变得更加简单，我们先来介绍一个简单的单边受害模型 （unilateral harm）。因为现实中往往伤害是同时发生，汽车把自行车撞了，汽车也会有损害，但是这里，我们假设汽车啥事没有。

因此，这里只有一个受害者。

一些标识：

- $x$ 是预防的程度
- $w$ 是每一“单位”预防的成本
- $p(x)$ 是发生意外的概率，自然是和 $x$ 有关
- $A$ 是意外发生后的成本（可以理解为对受害者带来的伤害）自然地，expected cost of accidents is $p(x)A$

![[截屏2023-12-09 11.31.40.png|500]]


我们可以很容易得到我们想要的模型公式：为了让成本最小化，也就是预防的成本和意外发生的成本加起来最小：
$$
min_x\{wx+p(x)A\}
$$
求导之后，得到：

$$
w+p'(x)A = 0
$$

$$
w = -p'(x)A
$$

左边是预防的边际成本，右边是预防的边际收益。

发生的意外的概率符合边际递减，所以它是个反函数形的曲线。

上面建立的模型都是所谓的“最理想的总模型”，它可以让成本最小化，也就是 Efficiency。但是在现实生活中，法院采取的规则可能不一样，这些规则会影响受害者和施害者的决策。本门课出现过的规则如下：（考试百分之百考）

1. No liability rule 
2. Strict liability rule  
3. Negligence rule

### No Liability Rule

No Liability Rule 意味着施害者不需要为意外付出任何代价。这也意味着他没有任何去采取预防的动机。那么，之前提到的模型，就全部由受害者承担，也就是说预防成本和意外发生的成本都由他来负责。受害者的预防是高效的（Efficient）

Victim precaution imposes no externality on injurer。也就是说，受害者采取预防措施防止自己遭受伤害，这些措施不会对施害者有直接的影响，也就是说施害者不会因为受害者的预防措施的实施而承担成本或者获得好处。

结果：

- 施害者：$x = 0$
- 受害者：$x = x^{ * }$



### Accidents between businesses and their own customers: No Liability

#### If customers correctly judge risks,
- Restaurants take efficient precaution
- Customers demand efficient number of meals

#### If customers can only judge average level

- Restaurants take no precaution
- Since customers know this, demand efficient (low) number 

#### If customers can only judge average level

- Restaurants take no precaution


## To sum up the effects of errors and uncertainty

if $e>0$ that means $x > x^ *$ v.v. 


### Under strict liability:

Random errors in setting damages have no effect: $A + \epsilon$ 

Systematic errors in setting damages will skew the injurer's incentives in the same direction: $A + e + \epsilon > 0$  

When under [[Strict Liability]]:

Cost to the injurer is $wx + P(x)(A + e + \epsilon)$ 

Here, $e$ stands for *systematic error* and $\epsilon$ stands for *random error*, $A + e + \epsilon$ are the social cost in an accidents.

So, injurer tries to minimize the cost,

For the F.O.C condition: $w = -P'(x)(A+e+\epsilon)$ v.s. $-P'(x)A$ which is the *marginal social benefit*

$w$ is the *marginal cost of precaution,* $w = -P'(x)(A+e+\epsilon)$ is the *marginal benefit of precaution to the injurer* (notice that it is not for the whole society)

Once you think about expected cost the injurer minimizes 

$$\mathbb E[wx + P(x)(A+e+\epsilon)] = wx + P(x)(A+e)$$


 $w = -P'(x)(A+e)$ v.s. $-P'(x)A$

![[IMG_FA0F8752D858-1 1.jpeg|600]]



