AXLE-Research(欧盟的AXLE项目的学习研究)
=============
##概述        
AXLE-欧盟资助的创新型项目,旨在欧盟范围内进行超大规模数据的分析,与此同时要解决数据质量,隐私,安全和审计的问题.       
* 时间节点-2012年11月到2015年11月       
* 主要的参与机构:Portavita和其他来自工业界和学术界的四个合作伙伴       
看起来承办方是这个机构 Portavita,看了一下,荷兰的一家医疗IT供应商,号称拥有6万5千的在线自管理病人,欧洲第一远程医疗供应商,覆盖了70家医疗机构,6000多医务人员,为38万病人提供服务,看起来顶多也就是天朝一个县的量.   
* 数据分析的应用场景    
    - 公共卫生 要能够提供去表示话的患者数据集用以大众型的科学研究.主要 做慢病治疗的管理 比如说 患者随访的频率 ,随访对于患者健康的影响,不同的医疗机构 医务人员效率的比较...          
    - BI   主要是内部研究,研究人员只能获取已经去标识化后的患者数据.机构内部对不同医生 科室的质量评估,对不同治疗方式的监督和上报............
* 法律诉求       
    - 欧盟范围的:Directive95/46EC和Genral Data Protection Reguldation
        + 第一点要求:数据是属于患者个人的,敏感信息需要个人的授权         
        + 匿名化数据不受此法律约束
    - 荷兰的法律: 满足以下其中一点无需授权即可在研究中使用患者数据,这里的研究必须是大众型的,必须需要这些数据才能进行研究,病人本身不反对参与研究.   
        + 征询患者授权不方便,不可能暴露患者隐私的情况
        + 鉴于研究的性质,征询授权不可行,而且数据本身已经匿名化处理了,无法再标识   
* 病人授权    
    - Consent CDA来实现
* 去标识化技术    
    - 直接标识符:姓名,电话 各种号码(mask-suppression/移除字段,randomization/随机值替换,shffling/数据重组,hashing单向哈希) 降低数据可用性           
    - 间接标识符:性别 年龄 籍贯等地址()     
    - 其他医疗数据:诊断,用药,日期,()     
    - HIPAA中的Safe Harbor:18类标识符(16种采用mask技术,2种采用泛化(邮编,日期类))          
    - 传统statistical method(Re-identiication risk threshold depends on the risk of exposure)              
    - 再标识风险评估:k匿名算法
* HCS组件      


##材料        
1. [官网](http://axleproject.eu/)                  
2. [基于HL7 RIM数据库针对行数据的权限控制](https://github.com/AXLEproject/axle-access-control)               
3. [仿真数据库和性能基准测试](https://github.com/AXLEproject/axle-healthcare-benchmark)                    
4. [基于 Optimal Lattice Anonymization algorithm 算法的匿名化实现原型-python语言](https://github.com/AXLEproject/axle-ola-prototype)                 
5. 



Commodity12项目学习研究


##材料    
[官网](http://www.commodity12.eu/)      

      
      