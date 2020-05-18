### 2.4.1 Team Models
### 2.4.1 チームモデル

Possible structures for an incident response team include the following:  
インシデント対応チームの構成には、以下のようなものがあります。 

■ **Central Incident Response Team**  
■ **中央インシデント対応チーム**

A single incident response team handles incidents throughout the organization.  
単一のインシデント対応チームが、組織全体のインシデントを処理します。  

This model is effective for small organizations and for organizations with minimal geographic diversity in terms of computing resources.   
このモデルは、小規模な組織や、コンピューティングリソースの点で地理的な多様性が少ない組織に有効です。  

■ **Distributed Incident Response Teams.**  
■ **分散型インシデント対応チーム**

The organization has multiple incident response teams, each responsible for a particular logical or physical segment of the organization.  
組織には複数のインシデント対応チームがあり、それぞれが組織の特定の論理的または物理的セグメントを担当します。  

This model is effective for large organizations (e.g., one team per division) and for organizations with major computing resources at distant locations (e.g., one team per geographic region, one team per major facility).  
このモデルは、大規模な組織（例：1部門につき1チーム）や、離れた場所に主要なコンピューティングリソースを持つ組織（例：地理的な地域につき1チーム、主要な施設につき1チーム）に有効です。  

However, the teams should be part of a single coordinated entity so that the incident response process is consistent across the organization and information is shared among teams.  
しかし、インシデント対応プロセスが組織全体で一貫しており、情報がチーム間で共有されるように、チームは単一の調整された組織の一部でなければなりません。  

This is particularly important because multiple teams may see components of the same incident or may handle similar incidents.  
複数のチームが同じインシデントの構成要素を見たり、類似のインシデントを扱う可能性があるため、これは特に重要です。  

■ **Coordinating Team.**  
■ **調整チーム**

An incident response team provides advice to other teams without having authority over those teams—for example, a departmentwide team may assist individual agencies’ teams.  
インシデント対応チームは、他のチームに対する権限を持たずに、他のチームにアドバイスを提供します。  

This model can be thought of as a CSIRT for CSIRTs.  
このモデルは、CSIRT のための CSIRT と考えることができる。  

Because the focus of this document is central and distributed CSIRTs, the coordinating team model is not addressed in detail in this document.16  
本文書では、中央および分散型 CSIRT に焦点を当てているので、調整チームモデルについては、本文書では詳細には触れていません。  

<br/>

Incident response teams can also use any of three staffing models:  
インシデント対応チームは、3つのスタッフ配置モデルのいずれかを使用することもできます。  

■ **Employees.**  
■ **従業員**

The organization performs all of its incident response work, with limited technical and administrative support from contractors.  
組織がインシデント対応業務のすべてを行い、限られた技術的および管理的なサポートを請負業者から受けます。  

■ **Partially Outsourced.**  
■ **部分的な外部委託**

The organization outsources portions of its incident response work.  
組織は、インシデント対応業務の一部を外部に委託しています。  

Section 2.4.2 discusses the major factors that should be considered with outsourcing.  
アウトソーシングを検討する際に考慮すべき主な要因については2.4.2項で論じています。  

Although incident response duties can be divided among the organization and one or more outsourcers in many ways, a few arrangements have become commonplace:  
インシデント対応業務は、組織と外部委託先の間で様々な方法で分担することができますが、いくつかの取り決めがあることが一般的です。 

– The most prevalent arrangement is for the organization to outsource 24-hours-a-day, 7-days-aweek (24/7) monitoring of intrusion detection sensors, firewalls, and other security devices to an offsite managed security services provider (MSSP).The MSSP identifies and analyzes suspicious activity and reports each detected incident to the organization’s incident response team.  
– 最も一般的なのは、侵入検知センサー、ファイアウォール、およびその他のセキュリティデバイスの監視を、組織がオフサイトのマネージドセキュリティサービスプロバイダ（MSSP）に24時間、週7日（24時間/週7日）委託することです。  

– Some organizations perform basic incident response work in-house and call on contractors to assist with handling incidents, particularly those that are more serious or widespread.  
– 組織によっては、基本的なインシデント対応業務を社内で行い、特に深刻なインシデントや広範囲に及ぶインシデントの場合は、請負業者に対応を依頼する場合もあります。  

■ **Fully Outsourced.**  
■ **完全な委託**  

The organization completely outsources its incident response work, typically to an onsite contractor. This model is most likely to be used when the organization needs a full-time, onsite incident response team but does not have enough available, qualified employees.It is assumed that the organization will have employees supervising and overseeing the outsourcer’s work.  
組織は、インシデント対応業務を完全に外部に委託します。このモデルは、組織がフルタイムのインシデント対応チームを必要としていますが、十分な資格を持った従業員がいない場合に使用される可能性が高いです。  
