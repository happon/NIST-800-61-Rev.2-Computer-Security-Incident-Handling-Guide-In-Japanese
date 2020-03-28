## Executive Summary「エグゼクティブ・サマリー」

Computer security incident response has become an important component of information technology (IT) programs.  
コンピュータセキュリティのインシデント対応は、情報技術（IT）プログラムの重要な要素となっています。  

Cybersecurity-related attacks have become not only more numerous and diverse but also more damaging and disruptive.   
サイバーセキュリティに関連した攻撃は、より多くの数と多様性を持つだけでなく、より多くの損害を与え、破壊的なものになっています。  

New types of security-related incidents emerge frequently.  
新しいタイプのセキュリティ関連のインシデントが頻繁に発生しています。  

Preventive activities based on the results of risk assessments can lower the number of incidents, but not all incidents can be prevented.  
リスクアセスメントの結果に基づいた予防活動を行うことでインシデントの数を減らすことはできますが、すべてのインシデントを防ぐことはできません。    

An incident response capability is therefore necessary for rapidly detecting incidents, minimizing loss and destruction, mitigating the weaknesses that were exploited, and restoring IT services.   
したがって、インシデントを迅速に検出し、損失や破壊を最小限に抑え、悪用された弱点を緩和し、IT サービスを復旧させるためには、インシデント対応能力が必要となります。  

To that end, this publication provides guidelines for incident handling, particularly for analyzing incidentrelated data and determining the appropriate response to each incident.   
そのために、本書では、インシデント対応のためのガイドライン、特にインシデント関連のデータを分析し、各インシデントへの適切な対応を決定するためのガイドラインを提供しています。

The guidelines can be followed independently of particular hardware platforms, operating systems, protocols, or applications. 
このガイドラインは、特定のハードウェア・プラットフォーム、オペレーティング・システム、プロトコル、またはアプリケーションに依存せずに使用することができます。

<br/>

Because performing incident response effectively is a complex undertaking, establishing a successful incident response capability requires substantial planning and resources.  
インシデント対応を効果的に行うことは複雑な作業であるため、成功するインシデント対応能力を確立するためには、相当な計画とリソースが必要です。  

Continually monitoring for attacks is essential.  
攻撃を継続的に監視することが不可欠です。  

Establishing clear procedures for prioritizing the handling of incidents is critical, as is implementing effective methods of collecting, analyzing, and reporting data.  
インシデントへの対応に優先順位をつけるための明確な手順を確立することは、データの収集、分析、報告の効果的な方法を実施することと同様に非常に重要です。   

It is also vital to build relationships and establish suitable means of communication with other internal groups (e.g., human resources, legal) and with external groups (e.g., other incident response teams, law enforcement).   
また、他の内部グループ（人事部、法務部など）や外部グループ（他のインシデント対応チーム、法執行部など）との関係を構築し、適切なコミュニケーション手段を確立することも重要です。    

<br/>

This publication assists organizations in establishing computer security incident response capabilities and handling incidents efficiently and effectively.  
本書は、コンピュータセキュリティのインシデント対応能力を確立し、インシデントを効率的かつ効果的に処理するために、組織を支援するものです。  

This revision of the publication, Revision 2, updates material throughout the publication to reflect the changes in attacks and incidents.  
本書の改訂版であるリビジョン 2 では、攻撃やインシデントの変化を反映するために、本書全体の資料を更新しています。  

Understanding threats and identifying modern attacks in their early stages is key to preventing subsequent compromises, and proactively sharing information among organizations regarding the signs of these attacks is an increasingly effective way to identify them.  
脅威を理解し、最新の攻撃を早期に特定することは、その後の侵害を防ぐための鍵であり、これらの攻撃の兆候に関する情報を組織間で積極的に共有することは、攻撃を特定するための効果的な方法としてますます重要になってきています。  

<br/>

Implementing the following requirements and recommendations should facilitate efficient and effective incident response for Federal departments and agencies.   
以下の要件と推奨事項を実施することで、連邦省庁の効率的かつ効果的なインシデント対応が促進されるはずです。  

<br/>

### Organizations must create, provision, and operate a formal incident response capability.   
### 組織は、正式なインシデント対応能力を作成し、提供し、運用する必要があります。  

### Federal law requires Federal agencies to report incidents to the United States Computer Emergency Readiness Team (US-CERT) office within the Department of Homeland Security (DHS).   
### 連邦法では、連邦政府機関は、インシデントを国土安全保障省（DHS）内の米国コンピュータ緊急事態対応チーム（US-CERT）に報告することが義務付けられています。  

<br/>

The Federal Information Security Management Act (FISMA) requires Federal agencies to establish incident response capabilities.  
連邦情報セキュリティ管理法（FISMA）は、連邦政府機関にインシデント対応能力の確立を求めています。  

Each Federal civilian agency must designate a primary and secondary point of contact (POC) with US-CERT and report all incidents consistent with the agency’s incident response policy.  
各連邦民間機関は、US-CERT との一次および二次連絡窓口（POC）を指定し、その機関のインシデント対応方針に沿ってすべてのインシデントを報告しなければなりません。  

Each agency is responsible for determining how to fulfill these requirements.  
各機関は、これらの要件をどのように満たすかを決定する責任があります。  

<br/>

Establishing an incident response capability should include the following actions:  
インシデント対応能力を確立するには、以下のアクションを含むべきです。   

 Creating an incident response policy and plan  
 インシデント対応方針と計画の作成  

 Developing procedures for performing incident handling and reporting  
 インシデント対応と報告を行うための手順書の作成  

 Setting guidelines for communicating with outside parties regarding incidents  
 インシデントに関する外部とのコミュニケーションのためのガイドラインの設定  

 Selecting a team structure and staffing model  
 チーム体制とスタッフィング（人員配置）モデルの選択  

 Establishing relationships and lines of communication between the incident response team and other groups, both internal (e.g., legal department) and external (e.g., law enforcement agencies)  
 内部（法務部など）と外部（法執行機関など）の両方のインシデント対応チームと他のグループとの間の関係とコミュニケーションラインの確立  

 Determining what services the incident response team should provide  
 インシデント対応チームが提供すべきサービスの決定  

 Staffing and training the incident response team.   
 インシデント対応チームの人員配置と訓練  

<br/>

### Organizations should reduce the frequency of incidents by effectively securing networks, systems, and applications. 
### 組織は、ネットワーク、システム、およびアプリケーションを効果的に保護することで、インシデントの頻度を減らす必要があります。  

Preventing problems is often less costly and more effective than reacting to them after they occur.  
問題の発生を防ぐことは、問題が発生した後に対応するよりもコストがかからず、効果的であることが多いです。  

Thus, incident prevention is an important complement to an incident response capability.  
したがって、インシデント予防は、インシデント対応能力を補完する重要な役割を果たします。  

If security controls are insufficient, high volumes of incidents may occur.  
セキュリティ対策が不十分な場合、大量のインシデントが発生する可能性があります。  

This could overwhelm the resources and capacity for response, which would result in delayed or incomplete recovery and possibly more extensive damage and longer periods of service and data unavailability.  
これは、対応のためのリソースと能力を圧倒する可能性があり、その結果、復旧が遅れたり、不完全になったりして、被害が拡大したり、サービスやデータが利用できない期間が長くなったりする可能性があります。  

Incident handling can be performed more effectively if organizations complement their incident response capability with adequate resources to actively maintain the security of networks, systems, and applications.  
インシデント対応は、ネットワーク、システム、およびアプリケーションのセキュリティを積極的に維持するために、組織がインシデント対応能力を十分なリソースで補完することで、より効果的に実施することができます。  

This includes training IT staff on complying with the organization’s security standards and making users aware of policies and procedures regarding appropriate use of networks, systems, and applications.  
これには、組織のセキュリティ基準を遵守するための IT スタッフのトレーニングや、ネットワーク、システム、およびアプリケーションの適切な使用に関するポリシーや手順をユーザーに認識させることが含まれます。  

<br/>

### Organizations should document their guidelines for interactions with other organizations regarding incidents.  
### 組織は、インシデントに関する他の組織との相互作用に関するガイドラインを文書化すべきです。  

During incident handling, the organization will need to communicate with outside parties, such as other incident response teams, law enforcement, the media, vendors, and victim organizations.  
インシデント対応中、組織は、他のインシデント対応チーム、法執行機関、メディア、ベンダー、被害者組織などの外部関係者とコミュニケーションをとる必要があります。  

Because these communications often need to occur quickly, organizations should predetermine communication guidelines so that only the appropriate information is shared with the right parties.  
これらのコミュニケーションは、しばしば迅速に行われる必要があるため、組織は、適切な情報のみが適切な関係者と共有されるように、コミュニケーションのガイドラインを事前に決定しておくべきです。  
<br/>

### Organizations should be generally prepared to handle any incident but should focus on being prepared to handle incidents that use common attack vectors.  
### 組織は、一般的にあらゆるインシデントに対応できるように準備しておくべきであるが、一般的な攻撃手段を使用するインシデントに 対処できるように準備しておくことに重点を置くべきです。

Incidents can occur in countless ways, so it is infeasible to develop step-by-step instructions for handling every incident.  
インシデントは無数の方法で発生する可能性があるため、すべてのインシデントを処理するための手順ひとつひとつの指示書を作成することは不可能です。  

This publication defines several types of incidents, based on common attack vectors; these categories are not intended to provide definitive classification for incidents, but rather to be used as a basis for defining more specific handling procedures.  
本書では、一般的な攻撃手段に基づいて、いくつかのタイプのインシデントを定義しています。これらの分類は、インシデントを決定的に分類することを意図したものではなく、より具体的な処理手順を定義するための基礎として使用することを意図したものです。 


Different types of incidents merit different response strategies.  
異なるタイプのインシデントには、異なる対応戦略が必要です。  

The attack vectors are:   
主な攻撃手段  

 External/Removable Media: An attack executed from removable media (e.g., flash drive, CD) or a peripheral device.  
外部/リムーバブル メディア):リムーバブルメディア (フラッシュドライブ、CD など) または周辺機器から実行される攻撃。  

 Attrition: An attack that employs brute force methods to compromise, degrade, or destroy systems, networks, or services.  
破壊：システム、ネットワーク、またはサービスを侵害、劣化、または破壊するために、ブルートフォース方式を使用する攻撃。  

 Web: An attack executed from a website or web-based application.  
Web：Web サイトまたは Web ベースのアプリケーションから実行される攻撃。  

 Email: An attack executed via an email message or attachment.  
電子メール：電子メールメッセージまたは添付ファイルを介して実行される攻撃。 

 Improper Usage: Any incident resulting from violation of an organization’s acceptable usage policies by an authorized user, excluding the above categories.  
不適切な使用：認可されたユーザーが組織の許容される利用ポリシーに違反した結果、上記のカテゴリーを除くすべてのインシデント。  

 Loss or Theft of Equipment: The loss or theft of a computing device or media used by the organization, such as a laptop or smartphone.   
機器の紛失または盗難：ラップトップやスマートフォンなど、組織で使用されているコンピューティングデバイスやメディアの紛失や盗難。  

 Other: An attack that does not fit into any of the other categories.  
その他：他のどのカテゴリーにも当てはまらない攻撃。  
