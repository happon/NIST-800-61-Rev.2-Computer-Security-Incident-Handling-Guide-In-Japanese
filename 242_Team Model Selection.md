### 2.4.2 Team Model Selection
### 2.4.2 チームモデルの選択

When selecting appropriate structure and staffing models for an incident response team, organizations should consider the following factors: 
インシデント対応チームの適切な構造と人員配置モデルを選択する際には、以下の要素を考慮する必要があります。  

■ **The Need for 24/7 Availability.**  
■ **24時間365日対応の必要性**  

Most organizations need incident response staff to be available 24/7.  
ほとんどの組織では、インシデント対応スタッフが24時間365日利用可能であることを必要としています。  

This typically means that incident handlers can be contacted by phone, but it can also mean that an onsite presence is required.  
これは通常、インシデント対応担当者が電話で連絡できることを意味しますが、オンサイトでの対応が必要な場合もあります。  

Real-time availability is the best for incident response because the longer an incident lasts, the more potential there is for damage and loss.  
インシデントが長引けば長引くほど、損害や損失の可能性が高まるため、インシデント対応にはリアルタイムで使用可能であることが最適です。  

Real-time contact is often needed when working with other organizations—for example, tracing an attack back to its source.  
他の組織と連携して攻撃の発生源を追跡するなど、他の組織と連携する際にもリアルタイムでの連絡が必要になることがよくあります。  

■ **Full-Time Versus Part-Time Team Members.**  
■ **フルタイムのチームメンバーとパートタイムのチームメンバー**   

Organizations with limited funding, staffing, or incident response needs may have only part-time incident response team members, serving as more of a virtual incident response team.  
資金、人員、またはインシデント対応のニーズが限られている組織では、パートタイムのインシデント対応チームメンバーしかいない場合があり、より仮想的なインシデント対応チームとして役割を果たしています。  

In this case, the incident response team can be thought of as a volunteer fire department.  
この場合、インシデント対応チームは、ボランティアの消防署と考えることができます。  

When an emergency occurs, the team members are contacted rapidly, and those who can assist do so.  
緊急事態が発生した場合には、チームのメンバーに迅速に連絡が入り、支援できる人が支援を行うことになります。  

An existing group such as the IT help desk can act as a first POC for incident reporting.  
ITヘルプデスクのような既存のグループは、インシデント報告のための最初のPOCとして機能することができます。 

The help desk members can be trained to perform the initial investigation and data gathering and then alert the incident response team if it appears that a serious incident has occurred.  
ヘルプデスクのメンバーは、初期調査とデータ収集を行い、重大なインシデントが発生したと思われる場合には、インシデント対応チームに警告を出すように訓練することができます。  

■ **Employee Morale.**  
■ **従業員の士気**  

Incident response work is very stressful, as are the on-call responsibilities of most team members.  
インシデントレスポンスの仕事は、ほとんどのチームメンバーのオンコール※の責任と同様に、非常にストレスの多い仕事です。  
（訳者注※：呼ばれたらすぐ対応すること）

This combination makes it easy for incident response team members to become overly stressed.  
この組み合わせにより、インシデント対応チームのメンバーは過度のストレスを感じやすくなります。  

Many organizations will also struggle to find willing, available, experienced, and properly skilled people to participate, particularly in 24-hour support.  
また、多くの組織では、特に24時間体制でのサポートに参加してくれる、意欲的で、利用可能で、経験豊富で、適切なスキルを持った人材を見つけるのに苦労することになります。  

Segregating roles, particularly reducing the amount of administrative work that team members are responsible for performing, can be a significant boost to morale.  
役割を分離し、特にチームメンバーが担当する管理業務の量を減らすことは、士気を大幅に向上させることができます。  

■ **Cost.**  
■ **コスト**  

Cost is a major factor, especially if employees are required to be onsite 24/7.  
コストは、特に従業員が年中無休で24時間体制で現場にいなければならない場合には、大きな要因となります。  

Organizations may fail to include incident response-specific costs in budgets, such as sufficient funding for training and maintaining skills.  
組織は、トレーニングやスキル維持のための十分な資金など、インシデント対応に特化したコストを予算に含めていないことがあります。  

Because the incident response team works with so many facets of IT, its members need much broader knowledge than most IT staff members.  
インシデント対応チームは、IT の多くの側面を扱うため、そのメンバーは、ほとんどの IT スタッフよりもはるかに幅広い知識を必要とします。  

They must also understand how to use the tools of incident response, such as digital forensics software.  
また、デジタル・フォレンジック・ソフトウェアなどのインシデント対応ツールの使い方も理解していなければなりません。  

Other costs that may be overlooked are physical security for the team’s work areas and communications mechanisms.  
その他、見落とされる可能性のあるコストとしては、チームの作業エリアの物理的なセキュリティや通信メカニズムなどがあります。  

■ **Staff Expertise.**  
■ **スタッフの専門知識**  

Incident handling requires specialized knowledge and experience in several technical areas; the breadth and depth of knowledge required varies based on the severity of the organization’s risks.  
インシデント対応には、いくつかの技術分野における専門的な知識と経験が必要です。  

Outsourcers may possess deeper knowledge of intrusion detection, forensics, vulnerabilities, exploits, and other aspects of security than employees of the organization.  
外部委託企業は、侵入検知、フォレンジック、脆弱性、エクスプロイト、その他のセキュリティの側面について、組織の従業員よりも深い知識を持っている可能性があります。  

Also, MSSPs may be able to correlate events among customers so that they can identify new threats more quickly than any individual customer could.  
また、MSSP※は、顧客間のイベントを相関させることができるため、個々の顧客よりも迅速に新たな脅威を特定することができるかもしれません。  
（訳者注※：マネージドセキュリティサービスプロバイダ）  

However, technical staff members within the organization usually have much better knowledge of the organization’s environment than an outsourcer would, which can be beneficial in identifying false positives associated with organizationspecific behavior and the criticality of targets.  
しかし、組織内の技術スタッフは、通常、外部委託企業よりも組織の環境についての知識が豊富であるため、組織固有の行動やターゲットの重要性に関連した誤検知を特定する上で有益である可能性があります。  

Section 2.4.3 contains additional information on recommended team member skills.  
2.4.3 節には、推奨されるチームメンバーのスキルに関する追加情報が記載されている。  

When considering outsourcing, organizations should keep these issues in mind:  
アウトソーシングを検討する際には、これらの問題を念頭に置いておくべきです。  

■ **Current and Future Quality of Work.**  


Organizations should consider not only the current quality (breadth and depth) of the outsourcer’s work, but also efforts to ensure the quality of future work— for example, minimizing turnover and burnout and providing a solid training program for new employees.  


Organizations should think about how they could objectively assess the quality of the outsourcer’s work.   


■ **Division of Responsibilities.**  


Organizations are often unwilling to give an outsourcer authority to make operational decisions for the environment (e.g., disconnecting a web server).  


It is important to document the appropriate actions for these decision points.  


For example, one partially outsourced model addresses this issue by having the outsourcer provide incident data to the organization’s internal team, along with recommendations for further handling the incident.  


The internal team ultimately makes the operational decisions, with the outsourcer continuing to provide support as needed.  


■ **Sensitive Information Revealed to the Contractor.**  


Dividing incident response responsibilities and restricting access to sensitive information can limit this.  


For example, a contractor may determine what user ID was used in an incident (e.g., ID 123456) but not know what person is associated with the user ID.  


Employees can then take over the investigation.  


Non-disclosure agreements (NDAs) are one possible option for protecting the disclosure of sensitive information.  


■ **Lack of Organization-Specific Knowledge.**  


Accurate analysis and prioritization of incidents are dependent on specific knowledge of the organization’s environment.  


The organization should provide the outsourcer regularly updated documents that define what incidents it is concerned about, which resources are critical, and what the level of response should be under various sets of circumstances.  


The organization should also report all changes and updates made to its IT infrastructure, network configuration, and systems.  


Otherwise, the contractor has to make a best guess as to how each incident should be handled, inevitably leading to mishandled incidents and frustration on both sides.  


Lack of organization-specific knowledge can also be a problem when incident response is not outsourced if communications are weak among teams or if the organization simply does not collect the necessary information.  


■ **Lack of Correlation.**  


Correlation among multiple data sources is very important.  


If the intrusion detection system records an attempted attack against a web server, but the outsourcer has no access to the server’s logs, it may be unable to determine whether the attack was successful.  


To be efficient, the outsourcer will require administrative privileges to critical systems and security device logs remotely over a secure channel.  


This will increase administration costs, introduce additional access entry points, and increase the risk of unauthorized disclosure of sensitive information.  


■ **Handling Incidents at Multiple Locations.**  


Effective incident response work often requires a physical presence at the organization’s facilities.  


If the outsourcer is offsite, consider where the outsourcer is located, how quickly it can have an incident response team at any facility, and how much this will cost.  


Consider onsite visits; perhaps there are certain facilities or areas where the outsourcer should not be permitted to work.  


■ **Maintaining Incident Response Skills In-House.**  


Organizations that completely outsource incident response should strive to maintain basic incident response skills in-house.  


Situations may arise in which the outsourcer is unavailable, so the organization should be prepared to perform its own incident handling.  


The organization’s technical staff must also be able to understand the significance, technical implications, and impact of the outsourcer’s recommendations. 
