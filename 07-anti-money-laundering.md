# 07 Anti-Money Laundering

反洗钱是典型的监管科技（合规端监管科技）应用，需要跟踪和学习最先进的金融科技。

![AML Knowledge Structure](.gitbook/assets/image%20%284%29.png)

![&#x53CD;&#x6D17;&#x94B1;&#x77E5;&#x8BC6;&#x7ED3;&#x6784;](.gitbook/assets/image%20%283%29.png)

进行反洗钱工作需要专注于下面这些主要方面：

1. 反洗钱工作离不开国际组织和专业机构。反洗钱金融行动特别工作组（FATA）是权威的国际反洗钱组织，被确定为打击恐怖主义融资的全球标准制定者。截至2020年，该组织共有37个成员以及20多名观察员，中国于2007年正式加入FATA，这标志着中国反洗钱工作进入到一个新阶段。2019年中国接任FATA轮值主席。金融情报中心（FIU）是各国的反洗钱专业机构，隶属央行的中国反洗钱监测分析中心就是国内的金融情报中心。
2. 对于反洗钱的流程和工具，KYC是基本的反洗钱工具，而且贯穿于金融交易流程的始终。身份验证是KYC的一个关键步骤，KYC的对象包括个人和企业实体，会对个人进行画像，同时也会注意保护个人隐私，防止敏感信息的泄露。
3. 可疑交易报告也是一种反洗钱的基本产品形态，就像（个人或企业）的信用报告支撑征信行业一样重要，也可以被视为合规端监管科技的典型产品。
4. 在反洗钱业务中受益所有人穿透是反洗钱的基本工作，往往需要结合大数据技术和复杂网络分析工具才能实现。
5. 涉及具体的技术：
   1. 金融网络分析和数据挖掘很早就在反洗钱领域得到深入应用。
   2. 基于资金关联和其他金融关联的资金情报网络，可以在庞大的资金流转网络中识别可疑资金流，提供反洗钱或反恐融资的线索，是继续反洗钱分析的重要技术手段，已经在国内外许多重大案件中得到成功应用。
   3. 情报可视化技术是可视化技术在数据视觉展现中的一种应用，在反洗钱工作中，可以将人群、账户以及相关的关联关系，用各种层次图、时序图或热图展现出来，提供分析效率。

下面对反洗钱知识结构中的八个部分分别加以详述 --

## 07.01 Anti-Money Laundering \(AML\)

洗钱的定义：指对犯罪所得进行处理并掩饰其非法来源，以期将犯罪所得用于合法或非法活动。

反洗钱：指预防通过各种方式掩饰、隐瞒毒品犯罪、黑社会性质的组织犯罪、恐怖活动犯罪、走私犯罪、贪污贿赂犯罪、破坏金融管理秩序犯罪等犯罪所得及其收益的来源和性质的洗钱活动的措施。

反洗钱往往和反恐融资交织在一起，被称为**反洗钱/打击资助恐怖主义（Anti-Money Laundering / Combating the Financing of Terrorism, AML/CFT）**。

洗钱活动的基本流程分为：

1. 资金处置（Placement）：洗钱分子将赃款存入合法金融机构是洗钱过程中最容易识别的一环，因为大量现金的存入非常可疑，而且银行按规定要上报巨额交易。
2. 资金离析（Layering）：即资金转移，是所以洗钱过程中最复杂的一环，其目的是想方设法让原始赃款难以被追踪。
3. 资金融合（Integration）：让赃款以貌似合法的形式重新进入主流经济体系。

![](.gitbook/assets/image%20%289%29.png)

![](.gitbook/assets/image%20%2810%29.png)

## 07.02 Financial Action Task Force on Money Laundering \(FATF\)

[反洗钱金融行动特别工作组（Financial Action Task Force on Money Laundering, FATF）](https://www.fatf-gafi.org/)，成立于1989年，是全球洗钱和资助恐怖主义的监督机构。这个政府间机构制定了旨在防止这些非法活动及其对社会造成的危害的国家标准。

除了FATF外，下面是其他与地区反洗钱相关的组织：

* 亚太反洗钱组织（APG）
* 欧亚反洗钱与反恐融资小组（EAG）
* 东南非洲反洗钱工作组（GABAC）
* 拉美金融行动特别行动组（GAFILAT）

FATF制定的反洗钱《[40项建议](https://www.fatf-gafi.org/publications/fatfrecommendations/documents/fatf-recommendations.html)》是世界上反洗钱和反恐融资的最权威文件。

![](.gitbook/assets/image%20%288%29.png)

![](.gitbook/assets/image%20%287%29.png)

下面是《[40项建议](https://www.fatf-gafi.org/publications/fatfrecommendations/documents/fatf-recommendations.html)》的名称：

| Item | Recommendation |
| :--- | :--- |
| A | AML/CFT POLICIES AND COORDINATION |
| A.1 | Assessing risks and applying a risk-based approach |
| A.2 | National cooperation and coordination |
| B | MONEY LAUNDERING AND CONFISCATION \(没收\) |
| B.3 | Money laundering offence |
| B.4 | Confiscation and provisional measures |
| C | TERRORIST FINANCING AND FINANCING OF PROLIFERATION |
| C.5 | Terrorist financing offence |
| C.6 | Targeted financial sanctions related to terrorism and terrorist financing |
| C.7 | Targeted financial sanctions related to proliferation |
| C.8 | Non-profit organization |
| D | PREVENTIVE MEASURES |
| D.9 | Financial institution secrecy laws |
| D.10 | CUSTOMER DUE DILIGENCE AND RECORD-KEEPING: Customer due diligence |
| D.11 | CUSTOMER DUE DILIGENCE AND RECORD-KEEPING: Record-keeping |
| D.12 | ADDITIONAL MEASURES FOR SPECIFIC CUSTOMERS AND ACTIVITIES: Politically exposed persons |
| D.13 | ADDITIONAL MEASURES FOR SPECIFIC CUSTOMERS AND ACTIVITIES: Correspondent banking |
| D.14 | ADDITIONAL MEASURES FOR SPECIFIC CUSTOMERS AND ACTIVITIES: Money or value transfer services |
| D.15 | ADDITIONAL MEASURES FOR SPECIFIC CUSTOMERS AND ACTIVITIES: New technologies |
| D.16 | ADDITIONAL MEASURES FOR SPECIFIC CUSTOMERS AND ACTIVITIES: Wire transfers |
| D.17 | RELIANCE, CONTROLS AND FINANCIAL GROUPS: Reliance on third parties |
| D.18 | RELIANCE, CONTROLS AND FINANCIAL GROUPS: Internal controls and foreign branches and subsidiaries |
| D.19 | RELIANCE, CONTROLS AND FINANCIAL GROUPS: Higher-risk countries |
| D.20 | REPORTING OF SUSPICIOUS TRANSACTIONS: Reporting of suspicious transactions |
| D.21 | REPORTING OF SUSPICIOUS TRANSACTIONS: Tipping-off and confidentiality |
| D.22 | DESIGNATED NON-FINANCIAL BUSINESS AND PROFESSIONS: DNFBPs: customer due diligence |
| D.23 | DESIGNATED NON-FINANCIAL BUSINESS AND PROFESSIONS: DNFBPs: Other measures |
| E | TRANSPARENCY AND BENEFICIAL OWNERSHIP OF LEGAL PERSONS AND ARRANGEMENTS |
| E.24 | Transparency and beneficial ownership of legal persons |
| E.25 | Transparency and beneficial ownership of legal arrangements |
| F | POWERS AND RESPONSIBILITIES OF COMPETENT AUTHORITIES, AND OTHER INSTITUTIONAL MEASURES |
| F.26 | REGULATION AND SUPERVISION: Regulation and supervision of financial institutions |
| F.27 | REGULATION AND SUPERVISION: Powers of supervisors |
| F.28 | REGULATION AND SUPERVISION: Regulatiohn and supervision of DNFBPs |
| F.29 | OPERATIONAL AND LAW ENFORCEMENT: Financial intelligence units |
| F.30 | OPERATIONAL AND LAW ENFORCEMENT: Responsibilities of law enforcement and investgative authorities |
| F.31 | OPERATIONAL AND LAW ENFORCEMENT: Powers of law enforcement and investigative authorities |
| F.32 | OPERATIONAL AND LAW ENFORCEMENT: Cash couriers |
| F.33 | GENERAL REQUIREMENTS: Statistics |
| F.34 | GENERAL REQUIREMENTS: Guidance and feedback |
| F.35 | SANCTIONS: Sanctions |
| G | INTERNATIONAL COOPERATION |
| G.36 | International instruments |
| G.37 | Mutual legal assistance |
| G.38 | Mutual legal assistance: freezing and confiscation |
| G.39 | Extradition |
| G.40 | Other forms of international cooperation |

## 07.03 Financial Intelligence Unit \(FIU\)

金融情报中心，又称金融情报机构，是一个旨在打击洗钱犯罪，专门负责收集、归纳分析有关可疑犯罪收入或被国家立法或规定要求的金融情报线索，并向执法部门传递情报的中央国家机构。

根据**FATF“建议29”**，各国应建立一个金融情报中心，作为全国性中心负责接收和分析**可疑交易报告**；与**洗钱**、相关上游犯罪和**恐怖主义融资**有关的其他信息，以及用于发布该分析结果的信息。

作为金融情报中心的国际组织埃格蒙特集团（[Egmont Group](https://egmontgroup.org/)）已经拥有167个成员（截至2021-09-21）。

不同国家和地区的金融情报中心分为下面4种：

* 司法型
* 执法型
* 行政型
* 混合型

下表列出了世界主要国家的金融情报中心 --

| 国家 | 金融情报中心 | 外文名 |
| :--- | :--- | :--- |
| 中国 | 中国反洗钱监测分析中心 | China Anti-Money Laundering Monitoring Analysis Center, CAMLMAC |
| 阿根廷 | 阿根廷金融情报中心 | [Financial Information Unit Argentina, UIF](http://www.uif.gov.ar/) |
| 比利时 | 比利时金融情报处理中心 | [Belgian Financial Intelligence Processing Unit, CTIF-CFI](http://www.ctif-cfi.be/website/index.php) |
| 澳大利亚 | 澳大利亚交易报告和分析中心 | [The Australian Transaction Reports and Analysis Centre, AUSTRAC](http://www.austrac.gov.au/) |
| 加拿大 | 加拿大金融交易和报告分析中心 | [Financial Transactions and Reports Analysis Centre of Canada, FINTRAC](http://www.fintrac-canafe.gc.ca/fintrac-canafe/1-eng.asp) |
| 巴西 | 金融行为控制委员会 | [Council for Financial Activities Control, COAF](https://www.coaf.fazenda.gov.br/) |
| 法国 | 法国金融情报中心 | [Intelligence Processing and Action against Illicit Financial Networks Unit, Tracifin](http://www.economie.gouv.fr/tracfin/accueil-tracfin) |
| 德国 | 德国金融情报中心 | [Financial Intelligence Unit Genmany, FIU](http://www.fiu.bund.de/) |
| 印度 | 金融情报部门 | [Financial Intelligence Unit-India, FIU-IND](http://fiuindia.gov.in/) |
| 爱尔兰 | 反欺诈调查局 | [Bureau of Fraud Investigation, MLIU](http://www.garda.ie/Controller.aspx) |
| 英国 | 英国金融情报中心 | [UK Financial Intelligence Unit, NCA](http://www.nationalcrimeagency.gov.uk/) |
| 美国 | 金融犯罪支付网络 | [The Financial Crimes Enforcement Network, FinCEN](https://www.fincen.gov/) |
| 日本 | 日本金融情报中心 | [Japan Financial Intelligence Center, JAFIC](http://www.npa.go.jp/sosikihanzai/jafic/index_e.htm) |
| 韩国 | 韩国金融情报中心 | [Korea Financial Intelligence Unit, KoFIU](https://www.kofiu.go.kr/eng/main.do) |
| 俄罗斯 | 联邦金融监控服务 | [Federal Financial Monitoring Service, Rosfinmonitoring](http://www.fedsfm.ru/en) |
| 瑞典 | 国家金融情报服务 | National Financial Intelligence Service, NFIS |
| 中国台湾 | 反洗钱部 | [Anti-Money Laundering Division, AMLD](http://www.mjib.gov.tw/en) |
| 突尼斯 | 突尼斯金融分析委员会 | [Tunisian Financial Analysis Committee, CTAF](http://www.ctaf.gov.tn/ctaf_f/eng/) |
| 土耳其 | 金融犯罪调查委员会 | [Financial Crimes Investigation Board, MASAK](http://www.masak.gov.tr/en/default) |

Refer to [here](https://www.fincen.gov/news/news-releases/fincen-and-chinas-camlmac-sign-memorandum-understanding-0), US FinCEN and China CAMLMAC signed a MOU at Dec 2015 to create a framework of facilitate expanded U.S.-China collaboration, communication, and cooperation between both nations' financial intelligence units \(FIUs\).

![](.gitbook/assets/image%20%2821%29.png)

![](.gitbook/assets/image%20%2817%29.png)

## 07.04 Know Your Customer \(KYC\)

了解你的客户（KYC）用于指代监督客户金融活动的银行监管和反洗钱法规。根据FATF“建议10”，各国应当禁止金融机构保持匿名账户或明显以假名开立的账户，各国应当要求金融机构在出现建议所规定的情形试，采取客户尽职调查。

Recommendations \# 10 - Customer Due Diligence

> Financial institutions should be prohibited from keeping anonymous accounts or accounts in obviously fictitious names.
>
> Financial institutions should be required to undertake customer due diligence \(CDD\) measures when:
>
> \(1\) establishing business relations;  
> \(2\) carrying out occasional transactions: \(a\) above the applicable designated threshold \(USD/EUR 15,000\); or \(b\) that are wire transfers in the circumstances covered by the Interpretive Note to Recommendation 16;  
> \(3\) there is a suspicion of money laundering or terririst financing; or  
> \(4\) the financial institution has doubts about the veracity or adequacy of previously obatined customer identification data.
>
> The principle that financial institutions should conduct CDD should be set out in law. Each country may determine how it imposes specific CDD obligations, either through law or enforceable means.
>
> The CDD measures to be taken are as followes:
>
> \(1\) Identifying the customer and verifying that customer's identity using reliable, independent source documents, data or information.  
> \(2\) Identifying the beneficial owner, and taking reasonable measures to verify the identity of the beneficial owner, such that the financial institution is satisfied that it knows who the beneficial owner is. For legal persons and arrangements this should include financial institutions understanding the ownership and control structure of the customer.  
> \(3\) Understanding and, as appropriate, obtaining information on the purpose and intended nature of the business relationship.  
> \(4\) Conducting ongoing due diligence on the business relationship and scrutiny of transactions undertaken throughout the course of that relationship to ensure that the transactions being conducted are consistent with the institution's knowledge of the customer, their busienss and risk profile, including, where necessary, the source of funds.

![](.gitbook/assets/image%20%2820%29.png)

![](.gitbook/assets/image%20%2819%29.png)

## 07.05 Suspicious Transaction Report \(STR\)

## 07.06 Beneficial Owner \(BO\)

## 07.07 Financial Intelligence Network

## 07.08 Intelligence Visualization

