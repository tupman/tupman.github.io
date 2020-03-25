---

title: 韩国猪Sapelovirus株全长基因组分析 
tags: 文献笔记
date: 2020-03-25
layout: post
subtitle: Full-Length Genomic Analysis of Korean Porcine Sapelovirus Strains
author: SIR
header-img:
keywords_post:
cover:
music-id: 

catalog: true
grammar_toc: true
grammar_abbr: true
grammar_table: true
grammar_tableExtra: true
grammar_deflist: true
grammar_emoji: true
grammar_footnote: true
grammar_ins: true
grammar_mark: true
grammar_sub: true
grammar_sup: true
grammar_align: true
grammar_center: false
grammar_checkbox: true
grammar_mathjax: true
grammar_mindmap: true
grammar_flow: true
grammar_sequence: true
grammar_plot: true
grammar_code: true
grammar_codeLinenums: true
grammar_html: true
grammar_linkify: true
grammar_typographer: true
grammar_video: true
grammar_audio: true
grammar_attachment: true
grammar_highlight: true
grammar_mermaid: true
grammar_classy: true
grammar_cjkEmphasis: true
grammar_cjkRuby: true
grammar_attrs: false
grammar_decorate: false
grammar_nunjucks: false
grammar_codeChunk: false
grammar_wavedrom: false
grammar_plantuml: true
grammar_xsjimg: false

---

[toc!?theme=colorful&depth=4]

## Abstract

- [ ] 猪Sapelovirus(PSV)是毕赤病毒科Sapelovirus属的一-种，与猪腹泻、肺炎、严重神经功能障碍和生殖功能衰竭密切相关。
- [ ] 然而，完整的PSV基因组的结构特征在很大程度上仍是未知的。
- [ ] 为了分析PSV基因组的结构特征，采用生物信息学技术对3株韩国PSV株的全长核营酸序列进行了测定和分析,并与其它已知的PSV株进行了比较。
- [ ] 韩国PSV基因组为7，542~7， 566个核苷酸，不包括39-聚(A)尾，呈现典型的微微病毒基因组结构;59非翻译区(UTR)-L-VP4-VP2-VP3-VP1-2A-2B-2C-3A-3B-3C3D-39UTR.鉴定了三个不同的顺式活性RNA元件，即59 UTR内核糖体进入位点(IRES)、2C编码区的顺式复制元件(CRE)和39 UTR，并对其结构进行了预测。
- [ ] 有趣的是，PSV菌株的CRE和39 UTR的结构特征不同。
- [ ] 这些第一个完整基因组序列的可得性将有助于进-步研究PSV的分子发病机制和进化特征。

## Introduction

- [ ] Picornavirus:是Picornavirales目中的一个正向单链rna病毒家族。它们会引起人类和动物不同程度的肠道、呼吸、神经、心脏、肝脏、粘膜和全身疾病。
- [ ] 虽然不同的微微病毒有不同程度的相关性,但所有的微微病毒都有一个相似的基因组组织，其中包括-个共价连接的59末端蛋白Vpg(病毒蛋白基因组连锁)，59个非翻译区(UTR)，-个大的开放阅读框架(ORF)，一个39 UTR和一个可变长度的多聚(A)尾。
- [ ] Picornavirus的基因组RNA含有多种不同的顺式活性RNA元件，它们是病毒RNA复制所必需的;59 UTR中的内部核糖体入口位点(IRES),ORF或59 UTR中的顺式复制元件(CRE)，39 UTR和39聚(A)尾
- [ ] 目前，已从起始序列、=级结构、起始密码;子的位置和不同细胞类型的活性等方面鉴定了五种不同类型的IRES元件。在大多数Picornavirus中，ORF编码的多蛋白被切割成4种结构的病毒颗粒蛋白(VP 4、VP2、VP3和VP1)和7种非结构蛋白(2A、2B、2C、3A、3B、3C和3D)。
- [ ] 此外，属的成员包括心脏病毒、弓形病毒、埃尔波病毒、Kobuvirus、Teschovirus、Senecavirus和Sapelovirus，它们在多蛋白的N端有一个领导蛋白(L)蛋白。
- [ ] 虽然猴2型微微病毒(SV-2-like Virus)和猪肠病毒8型(PEV-8)普被归类为肠道病毒属，但SV-2型病毒和PEV-8型病毒以及鸭皮病毒TW90A在缺乏肠道病毒的多蛋白的N端有L蛋白。
- [ ] 此外，这些病毒含有不同于肠道病毒属的2A蛋白，与V型IRES有高度不同的59 UTR.由于这些特殊的遗传特性，这些类人猿离类和猪皮病毒现在被指定为- -个新的微微病毒属--Sapelovirus的成员。
- [ ] PSV感染与各种症状有关，从无症状感染到腹泻、肺炎、脊髓灰质炎和生殖障碍等临床症状。
- [ ] 虽然PSVS可能是重要的病原体，因为其广泛的分布和高流行率,但几乎完整的基因组序列只有三个PSV毒株已经报道过; .-个来自英国。.2株来自中国(CSH和YC 2011株). 这促使我们对韩国PSV株与其他已知PSV株的全长遗传特性进行了比较。
- [ ] 在对韩国腹泻仔猪粪便中PSV感染的流行病学研究中，分离到3株PSV菌株。用抗PSV农壳蛋白单克隆抗体的免疫荧光法(IFA)、特异于PSV VP1编码区的一对引物的RT-PCR法和透射电镜对这些韩国PSV株进行了鉴定。
- [ ] 此外，还利用生物信息学技术分析了3株新分离株的病毒基因组，并与其它已知的PSV株进行了比较。

## Materials and Methods

### 1.Origin of virus strains

**病毒株的来源**
- [ ] 采用rt-PCR和巢式聚合酶链反应(nested-pcr)方法，对2004-2007年间韩国45头不同牛群的仔猪粪便进行了psv感染筛查，并对psv vp1编码区进行了特异性引|物对的巢式PCR检测。
- [ ] 在PSV阳性的粪便标本中，利用猪肾细胞系LLC-PK,以3份rt-PCR强阳性的粪便样品分离PSV.RTPCR阳性粪便用0.01M磷酸盐乡缓冲液稀释10倍(pBS, pH7),离心30s， 12006g离心20 min.上清液经0.2mm注射器过滤。
- [ ] 过滤上清液用含1%抗生素(青霉素、链霉素和两性霉素B)和1 %NaHCO 3的Emem最小必需培养基(Emem)连续稀释10倍，用6孔板进行细胞感染。
- [ ] 悬浮液吸收1h，偶尔摇动，加入含1%抗生素和1 %NaHCO 3的Emem.培养3~4天，37 uC在5%CO2气氛中培养,每日检测细胞病变效应(CPE)。三菌斑纯化法克隆分离的PSV.
- [ ] PSV菌株(KS 04105、KS 05151和KS055217)在LLC-PK细胞中传代8次，包括分离、适应和三菌斑纯化。经IFA. RT-PCR和透射电镜(TEM)检测证实分高的病毒为PSVS,如下所述。

### 2.Transmission electron microscopy (TEM)

**透射电镜**
- [ ] LLC-PK细胞每株感染70%以上CPE,冷冻解冻3次，2000~ 6g离心30 min.为了获得纯化的病毒，每个上清液在S58A-0015转子上以200, 0006g超离心5小时,4uC(日立，日本东京)。
- [ ] 所得微丸在40 ml水中再悬浮，在pH7.0条件下与2%(W/V)磷钨酸钠混合。样品放置在美国哈特菲尔德的Forvar网格(电子显微镜科学)上5分钟，然后用滤纸除去多余的液体。
- [ ] 用高分辨率透射电子显微镜(日立)对样品进行了检测，测定了韩国基础科学研究所光州中心病毒库的纯度。

### 3.Immunofluorescence assay (IFA)

**免疫荧光法**
- [ ] 为了鉴定PSV菌株，IFA用针对PSV衣壳蛋白的153/5b5(IgG2a)单克隆抗体(由德国Greifswald-Insel Riems, Friedrich-Loefflerlnstitut，M Dauber博士提供)进行检测。.
- [ ] 每株LLC-PK细胞感染后，按上述方法孵育18h，用80%丙酮固定5 min,在4uC下干燥。用PBS(pH7.2)冲洗三次，用1: 40稀释的PBS(pH7.2)稀释的PSV衣壳蛋白单克隆抗体，在4uC下孵育一-夜.
- [ ] 用PBS冲洗三次(pH 7.2)，用FITC结合山羊抗鼠lgG抗体(美国圣克鲁斯圣克鲁斯生物技术)稀释1: 100(pH 7.2),室温下用FITC与山羊抗鼠lgG抗体孵育1h.
- [ ] 用PBS(pH 7.2)冲洗两次后，用49, 6-二氨基-2-苯环吲哚(DAPI)染色(Invitrogen,Lohne，德国)，用LSM共聚焦扫描显微镜(德国Jena，Carl Zeiss)进行检测。

### 4.RNA extraction and RT-PCR

**RNA提取与RT-PCR**
- [ ] 用AccuPrep病毒RNA提取试剂盒(Bioneer,大田，韩国)从感染每株LLC-PK细胞的裂解液中提取总RNA.
- [ ] 为检测和扩增PSV RNA,采用- -对特异弓|物对PSV VP1编码序列(文件S1表S1)进行RT-PCR.
- [ ] 为鉴定每个菌株的全基因组序列，设计了10个引物组(文件S1表S1)，根据已发表的PSV-V13(GenBank ID: NC_ 003987)、CSH(GenBank ID: HQ 875059)和YC 2011株(GenBank ID: JX 286666)的基因组序列，对每个PSV株的ORF序列进行了扩增：标准的一步RT-PCR检测按前面所述进行。

### 5.5‘ and 3’ cDNA syntheses

- [ ] 每个菌株的cDNA都是根据制造商的指示，由美国山景城克隆科技公司(Clontech)的cDNA扩增试剂盒(Clontech，山景城)台成的。为获得39种适合种族的cDNA，将3.7 5ml的聚(A)尾RNA和1 ml的39-cDNA合成弓|物A混台,加热至72μC 3 min,再用热循环器冷却至42 uC 2 min.
- [ ] 用3.75ml的总RNA与1 ml的59-CDS引物A混台，72 uC孵育3 min, 22 uC冷却2 min.
- [ ] 将每39和59代cDNA的变性RNA与反应混合物(56-First-Strand缓冲液)、1 ml二硫苏糖醇(DTT)(20 Mm)、1ml dNTP混合液(10Mm)、0.25 ml RNase抑制剂(40 U/ml)和1ml SMARTScriber逆转录酶(100 U)混台。
- [ ] 样品在42 uC孵育90 min, 70 uC加热10min.台成的cDNA用7ml的三角EDTA缓冲液稀释，用于RACE PCR.

### 6.RACE PCR, cloning and sequencing

**RACE PCR、克隆和测序**
- [ ] 在39和59 RACE PCR反应中，采用优势2聚合酶链反应(Clontech); .39/59 RACE cDNA 5 ml, PCR级水32 ml, .106 Advantage 2 PCR缓冲液5 ml, dNTP混合液1 m(10 Mm),通用引物5 ml(10倍)，50 pmol/ml基因特异性引物(GSP)1m(文件S1表S1)，506 Advantage 2聚合酶混合物1 ml.
- [ ] 该反应是通过下列热循环程序进行的:94 uC或94.5uC 5个周期30s, 72 uC周期2min或3 min;3个周期分别为94uC或94.5uC 30s，65uC(GSP的外加熔化温度)30秒，72 uC 2 min或3 min;25步周期94 uC或94.5uC 30秒, 60 uC(将GSP的TM值降低3 uC至5 uC)30秒, 72uc2分钟或3分钟。
- [ ] 在1.5%(m/v)琼脂糖凝胶上分离RACE PCR产物，用普瑞林克快速凝胶提取试剂盒(Invitrogen)分离纯化条带。
- [ ] 将产物连接到TA Vector Systems(Enzynology，大田，韩国)，并导入DH5a感受态细胞。培养单个菌落，用杂交-Q质粒(GeneAll,汉城，韩国)纯化质粒。测序使用ABI系统3700自动DNA测序器(应用I生物系统，福斯特，美国).。

### 7.Full-length genomic characterization and secondary structure prediction

**基因组全长特征及=级结构预测**
- [ ] 为了获得每个PSV株的完整核苷酸序列,将每个株的59和39个末端序列与内部ORF序列的核苷酸序列组合在一起。利用DNA基本模块(DNAsis MAX,Alameda, USA)将3个PSV株的全基因组和个体蛋白编码序列与其它已知的PSV株(文件S1表S2)进行比较。
- [ ] 基于核苷酸和氨基酸序列的系统发育分析采用近邻连接法和UPGMA分子进化遗传学分析(mega版本5.2),采用配对距离比较法。用NAMANVersion6.0程序(Lynnon,Vaudreuil, Canada)的同源性和距离矩阵法对3株PSV菌株与其它已知PSV株进行序列同源性计算。
- [ ] 利用CLC主I作台6.8.2程序(CLC BIO,Katrinebjerg,丹麦)对PSV基因组中的二级结构元素进行建模。

## Results

### 1.Virus isolation and identification

**病毒分离鉴定**
- [ ] 从三个不同养殖场分离的腹泻粪便标本中分离出3株韩国PSV菌株，并纯化菌斑。
- [ ] LLC- PK细胞经8代感染后，在接种后第1天出现CPE,表现为细胞收缩、包围和脱落(图1A，1B)， 用抗PSV衣壳蛋白单克隆抗体(图1A)在间接IFA中显示PSV特导h性胞浆荧光(图1A)。
- [ ] 用一对特异性引物对PSV VP1部分编码区进:行RT-PCR分析，从感染各株的LLC-PC细胞中扩增出-个636 bp的扩增片段(图S1C)。透射电镜显示，纯化后的病毒颗粒呈球形，直径约为30 nm(图1 B)。
- [ ] 没有观察到其他类似病毒的颗粒。这些结果证实了分离出的病毒为PSVS.

### 2.Genome organization

**基因组组织**
- [ ] 获得了3株韩国PSV株全基因组的完整核苷酸序列，并与先前测定的PSV序列进行了比较。在picornavirus RNAs中，这两个59个末端uu残基是从vpg的尿苷化过程中得到的，从而形成vpg-pu-pu.
- [ ] 然而，在先前描述的PSV序列中，中国CSH 和英国V13株的两个氨基酸残基为AC，中国YC 2011株的UA为不完全序列。
- [ ] 为了获得正确的59个末端起始残基，进行cDNA合成，然后用59个种族弓|物(文件S1表S1)进行59 RACE PCR。
- [ ] 用此方法，59个末端残基为UU, 3株韩国株的59 UTR长度比中国YC 201 1株长25个核苷酸(文件S1表S3)。
- [ ] 为了证实这一结果，用另一个59 RACE PCR引物(文件S1中的表S1)进行了59 RACEPCR，并观察到了相同的59个末端核苷酸残基UU。
- [ ] 除聚(A)尾外，韩国PSV株的全基因组长度为7, 542(KS 04105和KS 055217)至7，566个核苷酸(KS 05151)(文件S1表S3)。
- [ ] 这些序列包含一个大的ORF,其长度为6,966个核苷酸(菌株V13; 2, 322个氨基酸多蛋白前体)至6, 993个核苷酸(菌株CSH, KS05151, YC2011);2，331个氨基酸多蛋白前体)(文件S1中表S3)。
- [ ] 表1显示了根据与其他微微病毒的排列所确定的多聚蛋白的蛋白酶切割位点。
- [ ] 预计该多肽将被切割并加工成12种成熟肽:L-VP4-VP2-VP3-VP1-2A-2B-2C-3A-3B3CPro-3 DPol(圍2)。3株韩国PSV株的ORF序列两侧分别为59个UTR(491个核苷酸长)和39个UTR(82个核苷酸长)(文件S1表S3)。

### 3.Molecular and phylogenetic analyses

**分子和系统发育分析**
- [ ] 将3株韩国株的全基因组序列(不包括聚(A)尾)和多蛋白序列与GenBank数据库中其他已知的PSVS和具有代表性的Picornavirus毒株进行了比较。.
- [ ] 韩国PSV株与其它PSV株(表2)具有较高的核苷酸同源性(84.7%~94.0%)和推导氨基酸同源性(92.9%~98.39%)，但与离、猴皂苷病毒株的核苷酸序列和多蛋白序列同源性较低(表2)。
- [ ] 对基因组中的每个主要功能单元，包括59和39个UTRs、衣壳编码区(P1)和编码PSVS的非结构蛋白(P2和P3)的区域进行了系统遗传学分析(图3).
- [ ] 在每株树中都包含有代表性的猴病毒和离隐核病毒参考株。3株韩国PSV毒株的59条UTR序列位于同-簇内，与英国株V13的亲缘关系较中国株CSH和YC 2011密切(图3A)。.
- [ ] 5株毒株(KS 04105、KS 055217、KS05151、V13和YC 2011)的39个UTR序列长82个，中国株CSH全长68个核苷酸，可能是序列不完全所致(文件S1表S3)。
- [ ] 然而，它们在系统发育上非常接近(图3B)。
- [ ] 所有PSV株的领导蛋白序列长度为252个核苷酸(84个氨基酸)(文件S1表S3),氨基酸同源性较高(95.2~ 100%)(文件S1表S4)。
- [ ] PSV前导多肽缺乏蛋白水解活性所必需的催化残基基序,不含锌指基序([Cys2His2样折叠基序]或酪氨酸磷酸化基序[KR]-x(2，3)-[ED]-x(2, 3)-Y].
- [ ] PSV衣壳区的核苷酸和推导的氨基酸序列的长度从2430到2454个核苷酸(编码810到818个氨基酸，表S3在文件S1)。
- [ ] 为了研究PSV菌株之间的遗传关系，对所有6个PSV株的衣壳蛋白序列和每个成熟的衣壳蛋白VP1-VP4(文件S1中表S4)的序列进行了配对序列的计算。所有PSV株在衣壳完整编码序列中的核苷酸同源性为88.4%~97.7%.
- [ ] PSV株在VP1编码序列中的核苷酸同源性为85.6%~98.29(文件S1表S4)。PSV株VP1蛋白的系统发育分析如图3所示。KS 05151. CSH和YC 2011菌株的VP1序列与其他菌株相比，编码了另外8个氨基酸(文件S1表S3)。
- [ ] 所有PSV株的P2区长度为1989年核苷酸(663个氨基酸)，P3区长为2235-2238个核苷酸(745-746个氨基酸)(文件S 1表S3)。.P2区和P3区的氨基酸序列同源性很高,分别4919%95959.99.0%(文件S表S4)。

### 4.Analysis of the RNA structures within the 59UTR

**59 UTR中RNA结构的分析**
- [ ] 如_上所述，使用59 RACE可以确定韩国PSV的完整59 UTR序列(长度约为491 nt);这些毒株的59 UTR比中国的PSV株(YC201 1)长25个核苷酸。
- [ ] 这允许预测PSV 59 UTR中的二级结构元素(图4)。在最极端的59个末端是两个茎环结构，标记结构域la和lb。后者包括两个较小的茎环结构，标记为|C和ID.
- [ ] 59 UTR还包含另外两个域,分别标记为第二域和第三域。它们代表IRES的基本组成部分，并以与其他第lV类IRES元素相同的方式进行标记。
- [ ] 结构域III包含多个亚域，包括伪结(IIIf)和高度保守的茎环IIID和IIIe，它们与HCV IRES类似，直接与40S核糖体亚基相互作用。

### 5.Analysis of 39UTR sequence

**39 UTR序列分析**
- [ ] PSV 39 UTR高度保守。根据39 UTR的大小，PSV可分为V13型群(KS 04105. KS05151. KS 055217. YC 2011和V13株), 分别为82个核苷酸长和62个核苷酸长(图5A).
- [ ] 这两个亚组都有两个共同的结构域，可以形成一一个茎环结构(域X和Y）。V13样群包含第三个茎环区(称为Z[图5B,5C])，位于Y域的上游(图5B，5C)。
- [ ] 在3株韩国株和YC 2011株中，在Z结构域(KS05151株中NT 7485~7492)与结构域X环(KS05151株中NT 7549~7556)之间有8个核苷酸相互作用，形成环-环内接吻’ RNA相互作用(图5B)。
- [ ] V1 3株在结构域Z(NT 7411~741 6)和结构域X(NT 7475~7480)之间存在7个核苷酸的潜在相互作用，形成类似的分子内‘接吻’RNA相互作用(图5C)。
- [ ] 由于缺乏结构域Z(图5A，5D), CSH样的群序列没有被预测会形成环环内分子内的'接吻’RNA相互作用(图5A, 5D)。

### 6.Identification of a cis-acting RNA element (CRE)

**顺式作用RNA元件的鉴定**
- [ ] CRE是Picornavirus rna复制中必不可少的元素。这些相对较短的元素可以位于基因组的不同位置;它们作为vpg的小便化模板，形成vpg-pu-pu,并包含一个基本的母模AAAYA.
- [ ] 对三个韩国株(KS 04105、KS 05151、KS055217)和包括中国株(CSH和YC 2011)和英国株(V13)在内的其他PSV株的序列分析表明，这些毒株的基因组中存在多个AAACA基序。
- [ ] 然而，如图6所示，只有2C编码序列(即KS05151基因组中的核苷酸4491至4550)中才能发现含有AAAC A基序的裸露环的茎环结构。这个发夹环包含16个核苷酸。
- [ ] 有趣的是，KS 04015、KS 05105、KS055217和YC 2011菌株在这个循环结构中有两个AAACA基序(图6)。

## Discussion

- [ ] 本文报道了从猪腹泻标本中分离出三株韩国PSV菌株KS 05151、KS 04105和KS055217.通过RT-PCR、IFA和TEM检测，将韩国PSV菌株鉴定为PSV.测定了韩国PSV株的基因组序列，证明是首次获得完整的PSVS基因组序列。
- [ ] 它们有一个典型的基因组组织，用于心脏病毒、阿弗他病毒、埃博病毒、小牛病毒、Teschovirus和Senecavirus的成员。此外，这些毒株与肠病毒属有不同的2A蛋白，与IV型IRES有59 UTR。
- [ ] 这59个微微病毒的utrs是高度结构化的，并且包含一个IRES,通过内部核糖体结合来指导ra翻译。
- [ ] Picornavirus IRES目前根据起始密码子的位置和在不同细胞类型中的活性，被划分为五种不同的类型:初级序列、二级结构、起始密码子位置和活性。
- [ ] 在先前的研究[16]中，PSV V13株和猴Selovirus SV2株的IRES元件与猪病毒1型和丙型肝炎病毒|V型IRES元件在功能和结构上均有关联。
- [ ] 对韩国PSV株和PSV V13株的比较序列分析表明，IRES元件的结构特征在包括韩国PSV株在内的所有PSV种中都有很好的保守性，但缺乏-个结构域lIl。
- [ ] 在59个UTR末端，肠道病毒和鼻病毒含有一个三叶草结构，与ma复制有关。为了确定PSV在59 UTR处是否有三叶草RNA结构，需要知道完整的59 UTR.
- [ ] 然而，包括英文版V1 3和中国CSH和YC 2011株在内的已知PSV株的序列缺乏Picornavirusrna复制所必需的59个末端Uu残基。
- [ ] 利用59个小种，与最近测序的中国YC 2011株相比，又鉴定出25个核苷酸，其中包括59个末端Uu残基。与肠道病毒和鼻病毒[38]不同，韩国PSV株在59 UTR处没有三叶草RNA结构。
- [ ] 然而,在59个末端80个核苷酸中存在两个保守的茎环基序(图4).这些结构的作用尚不清楚，但它们可能在rna复制中起到类似于肠病毒三叶草结构的作用。
- [ ] 总的来说，PSVS的59 utrs相当短，例如脊髓灰质炎病毒59 UTR长度约为740个核苷酸,口蹄疫病毒(Fmdv)59UTR则超过1300个核苷酸。
- [ ] 衣壳区前有L蛋白的苦病毒为心脏病毒属、Aphthvirus属、Erbovirus属 、Kobuvirus属、Teschovirus属和Sapelovirus属。在口疮病毒和erbovirus中，L蛋白是木瓜蛋白酶样半胱氨酸蛋白酶，能够切割自身的羧基末端，并能诱导真核细胞起始因子(Evf4G的断裂，从而导致宿主细胞蛋白合成的关闭。
- [ ] 摘要脑心肌炎病毒(-种心脏病毒)的L蛋白与锌结合,在病毒感染过程中被磷酸化，并被报道影响基因组翻译的效率。病毒蛋白的性质尚不清楚;
- [ ] 般来说，微微病毒39 UTRs的长度在40到165个核苷酸之间。PSV中39位UTR的长度为82个核苷酸(菌株V13, YC 2011, KS04105，KS 05151和KS 055217),尽管CSH株有一个较短的序列(68个核苷酸)。
- [ ] 在先前的报道[12]中，PSV株V13被预测在39UTR区域包含三个茎环结构，使用3D编码区末端的9个核苷酸。
- [ ] 在本研究中，韩国病毒KS 04105、KS05151和KS 055217加中国YC 2011株均具有这三个茎环结构(X、Y和Z), 而CSH株由于序列较短，仅表现出两个茎环结构(X和Y)。
- [ ] 终止密码子(UGA)所在的区域Z是PSVS中39UTR中最保守的区域，而Y和X被认为是可变区域(图5B，5C), 因为它们在长度和核苷酸序列上都表现出异质性。
- [ ] 5株PSV株与CSH株之间的差异可能是由于CSH 39 UTR区39末端序列不完整所致。此外，除CSH菌株外，还有5株菌株在X和Z结构域之间存在分子内接吻RNA相互作用。
- [ ] 由于CSH 39 UTR区缺乏39末端序列，无法预测分子内接吻RNA的相互作用(图5D)。有趣的是，V13菌株有7个核苷酸的分子内相互作用，而3个韩国和1个中国菌株的分子内相互作用有8个核苷酸。
- [ ] 39 UTR在Picornavirus复制中起着重要作用。这种相互作用被中断的突变病毒连续传代后，产生了第三级接吻相互作用恢复的回复剂，这表明了这种相互作用在肠道病毒39UTR中的功能重要性。
- [ ] 需要进一步研究，通过修改相关的PSV核苷酸序列来确定这些区域对PSV复制是否重要。
- [ ] 已在皮氏科6个属中鉴定出一种微囊病毒CRE;肠道病毒， 鼻病毒, 心脏病毒，弓形病毒，Parechovirus和肝病毒，然而，目前还没有关于Sapelovirus、Kobuvirus、Erbovirus、 Teschovirus、 Avi肝病毒、Senecavirus和Temovirus属病毒的推测CRE的报道。
- [ ] 不同属间的CRE在基因组RNA中的位置各不相同。
- [ ] 它位于肠道病毒2C编码区[6，36]、B鼻病毒VP1编码区[32]、C犀牛病毒VP2编码区[38]和心脏病毒编码区[52]、parechovirus病毒VP0编码区[4]和肝病毒3D编码区。
- [ ] 在FMDV中，CRE位于IRES的 上游。在本研究中，所有PSV毒株的2C编码区都存在一个可能的Cre。
- [ ] 通常，AAACA基序位于Picornavirus Cres的循环中，第-和第二A残基参与为向VPG添加尿苷提供模板。
- [ ] 与其他已知的Cres相比，PSV菌株在CAAACATAATAAACAA序列中有两个AAAACA基序的拷贝。
- [ ] 这表明，这些AAACA基序中的一个或两个可能参与了在VPG中添加尿苷的模板作用。未来的功能分析是需要确定一个或两个主题是模板的尿酸化VPG,以使VPG-PU-pUOHl。
- [ ] 在本研究中，我们与其他已知的PSV菌株进行了比较，对3株韩国PSV菌株的结构特征进行了表征。
- [ ] 所有PSV毒株均表现出典型的小核糖核酸病毒基因组结构。我们已经在59UTR和39UTR中发现了可能的RNA结构，并在2C编码序列中发现了一个Cre。
- [ ] 有趣的是，Cre在2C编码序列中的结构特征和39 UTR的结构特征在最近和过去几十年中流传的菌株之间是不同的。
- [ ] 这些第一批完整的PSV基因组数据(韩国PSV株KS 05151、KS 04105和KS 055217)将为进一步研究该病毒的分子致病机制和进化特性提供参考。

## References

本文献链接[Full-length genomic analysis of Korean porcine Sapelovirus strains](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=SJDJ&dbname=SJDJ_01&filename=SJDJ402787B22A644358CEBE6E948C0C4D85&v=MDk2NDZVMjVOeGl4N3Eyd3FBPU5pZlBaTGU0SE5iRXFQMUhacG9KQ0hnNnloNWduMDBJVGdycnFCcEdlY0dRTWJLYUNKVWFGMXVRVXIvUEpsY1NibUtDR1lDR1FsZkJyTA==)