## 游戏
游戏行业竞争激烈，高可用性，低卡顿是留住玩家、用户的前提。边缘安全加速平台平台（EdgeOne）从游戏的安全和加速两个维度为游戏供应商提供支撑，确保玩家可以拥有优质的游戏体验。

### 安全方面
EdgeOne 在设计过程中利用腾讯自身的海量流量数据优势以及游戏领域的深入积累，详细分析了游戏领域的主要攻击模型和协议，可以为游戏服务在各种复杂和大流量的攻击中提供全方位的防护，能够过滤和防护出现的各种攻击，包括不限于：TCP 反射、TCP 连接攻击、TCP 四层 CC、HTTP CC 等。
![](https://qcloudimg.tencent-cloud.cn/raw/9119d3c9f1d7ee84bce60113f781322b.png)

EdgeOne 深入分析了游戏领域的不同游戏组件的需求差异，针对游戏大厅服、战斗服和游戏官网/论坛的防护提供了不同的解决方案。
- 游戏大厅服：EdgeOne 提供大带宽防护，确保在大量的攻击的情况下，游戏大厅依然可以提供稳定高可靠的访问，满足游戏登录、组队、充值等诉求。
- 战斗服：EdgeOne 深入了解到战斗服务器对时延的敏感要求，在大带宽的防护基础上提供了链路智能调度的功能，实时感知当前链路的时间延迟，发现链路时延增加后，提供灵活高效的调度能力，确保游戏体验不因攻击而受到影响。整个防护过程均在无需人工干预、玩家无感知的前提下精确区分攻击流量和正常流量，实现自动化、智能化的清洗。
- 游戏官网/论坛：EdgeOne 基于腾讯在 Web 领域的防护积累，提供了 WAF（Web Applicaiton Firewall）能力，能有效保护游戏官网应对 Web 攻击、入侵、漏洞利用、挂马、篡改、后门、爬虫等网站及 Web 业务安全防护问题。


### 加速方面
EdgeOne 基于腾讯全球部署的海量边缘计算节点（具体部署位置详见 EdgeOne 资源介绍），就近接入。
- 针对游戏官网部署，游戏包更新等静态业务，均可以实现从传统的集中式数据中心到 EdgeOne 边缘节点的缓存，用户仅仅访问位于边缘节点的网站和游戏包资源即可，这样极大减少了数据重复传输的链路开销，降低访问时延提升用户体验的同时，也帮助用户降低本地成本。
- 针对一些需要返回源站访问的动态数据，腾讯根据用户诉求提供了两种方案，针对时间延迟不敏感的数据，可以通过互联网进行回源访问获取；针对时间延迟敏感，有加速需求的数据，提供了回源加速能力，提供专门的高速专有线路进行回源加速，满足游戏中的时间敏感的应用场景诉求。


## 视频
视频领域主要分为视频点播、视频在线直播两种应用场景。

### 视频点播
为用户提供高速流畅的观影体验，为视频制作方提供高效便捷的视频上传。 
- 用户观影体验：EdgeOne 基于算法（根据数据的点播数量和热点话题）将高频率的热点视频从远程的集中式数据中心下载到全球部署的海量边缘计算节点（具体部署位置详见 EdgeOne 资源介绍），通过这种方式拉近了观影用户和视频存储位置之间的距离，极大的缩短了视频的传输距离，减少了传输时间延迟，提升了视频播放的稳定性。

### 视频上传
EdgeOne 根据用户对时延和成本的要求，提供了两种解决方案。
- 针对上传时间延迟不敏感的场景，用户可以选择低成本的互联网将数据从本地上传到腾讯的数据中心和边缘节点。
- 针对上传时间延迟的敏感的场景，用户可以选择 EdgeOne 提供的加速网络，加速网络提供了低延迟、高稳定的加速能力，能保证视频可以快速的上传到腾讯的数据中心和边缘节点。

### 在线直播
EdgeOne 能智能识别用户和直播提供方的所在位置，针对收视方和直播提供方较近的用户，实现数据流的就近交互，有效减少链路开销，提升直播互动效果；针对直播方和收视方距离较远的情况，EdgeOne 提供了链路加速功能，确保视频信息流可以在高速加速网络中进行高速传递，满足低时延迟的直播互动需求。

除了上述的加速能力之外，DDoS 和 WAF 的也对视频网站提供了强大防护功能，DDoS 有效保护视频网站免受各种四层和七层的网络攻击，可以为用户提供稳定的服务。

## 电商与零售
电商领域需要提供流畅的访问体验支撑用户浏览和选购商品，EdgeOne 产品提供了针对电商和零售网站的加速能力，可以将传统数据中心的静态网站内容缓存到腾讯的海量的边缘节点中，不同的地域的用户都可以实现高速稳定的就近访问。针对一些动态数据，例如 频繁刷新和调整的价格和折扣等内容，EdgeOne 提供了数据回源访问的加速能力，通过高速加速链路提升用户使用体验。

此外，电商行业在业务高峰期，尤其是年中、年末等多个活动周期，易因同行恶意竞争，或黑客勒索等原因，遭到 DDoS、CC 和 Web 攻击，导致服务不可用等事故，造成商家信誉受损，商家、用户流失，造成巨额经济损失。EdgeOne 产品提供了 DDoS/CC 攻击防护、 Web 攻击防护、API 防护安全能力，能有效抵御 DDoS、CC、Web 攻击，避免尤其是在活动高峰期间的攻击造成的服务不可用。

## 传统企业与金融
金融领域类别众多，包括但不限于银行、证券、基金、股票等，是黑客攻击的主要目标领域之一。金融业务对可用性要求非常高，当攻击消耗系统和网络资源造成业务中断时，正常用户无法进行交易下单，将造成严重的经济损失。

同时金融业务源站存储有大量敏感数据，如源站被攻破导致信息泄露，会导致更大影响和损失。EdgeOne 产品提供了 DDoS/CC 攻击防护、 Web 攻击防护、API 防护安全能力，能有效保障金融应用的稳定性和高可用，抵御 Web 攻击，降低源站内容、数据泄露风险。


