### 4.2.2 Partially Automated 
### 4.2.2 部分的な自動化

Organizations should attempt to automate as much of the information sharing process as possible to make cross-organizational coordination efficient and cost effective.  
組織は、組織間の連携を効率的かつ費用対効果の高いものにするために、情報共有プロセスを可能な限り自動化することを試みるべきです。 

In reality, it will not be possible to fully automate the sharing of all incident information, nor will it be desirable due to security and trust considerations.  
実際には、すべてのインシデント情報の共有を完全に自動化することは不可能であり、また、セキュリ ティと信頼性の観点からも望ましいことではありません。

Organizations should attempt to achieve a balance of automated information sharing overlaid with human-centric processes for managing the information flow. d
組織は、自動化された情報共有と、情報の流れを管理するための人間中心のプロセスとのバランスを取ることを試みるべきです。

<br/>

When engineering automated information sharing solutions, organizations should first consider what types of information they will communicate with partners.  
自動化された情報共有ソリューションを設計する際には、組織はまず、パートナーとどのようなタイプの情報をやり取りするかを検討する必要があります。

The organization may want to construct a formal data dictionary enumerating all entities and relationships between entities that they will wish to share.  
組織は、共有したいすべての組織や事業体等間の関係を列挙した正式なデータ辞書を構築したいと思うかもしれません。

Once the organization understands the types of information they will share, it is necessary to construct formal, machine-processable models to capture this information.  
組織が共有する情報の種類を理解したら、この情報を取り込むための形式的で機械処理可能なモデルを構築する必要があります。

Wherever possible, an organization should use existing data exchange standards for representing the information they need to share.※  
可能な限り、組織は共有する必要のある情報を表現するために、既存のデータ交換標準を使用すべきです※。   

The organization should work with its partner organizations when deciding on the data exchange models to ensure that the standards selected are compatible with the partner organization’s incident response systems.  
組織は、データ交換モデルを決定する際、パートナー組織と協力して、選択した標準がパートナー組織のインシデント対応システムと互換性があることを確認すべきです。 

When selecting existing data exchange models, organizations may prefer to select multiple models that model different aspects of the incident response domain and then leverage these models in a modular fashion, communicating only the information needed at a specific decision point in the life cycle.  
既存のデータ交換モデルを選択する場合、組織は、インシデント対応領域の異なる側面をモデル化した複数のモデルを選択し、モジュール方式でこれらのモデルを活用し、ライフサイクルの特定の意思決定ポイントで 必要な情報のみを通信することを好むかもしれません。

Appendix E provides a non-exhaustive list of existing standards defining data exchange models that are applicable to the incident response domain.  
付録Eは、インシデント対応ドメインに適用可能なデータ交換モデルを定義する既存の標準の非網羅的リストです。 

<br/>
 
In addition to selecting the data exchange models for sharing incident information, an organization must also work with its partner organizations to agree on the technical transport mechanisms for enabling the information exchange to occur in an automated fashion.  
インシデント情報を共有するためのデータ交換モデルを選択することに加えて、組織は、パートナー組織と協力して、情報交換が自動化された方法で行われるための技術的な転送メカニズムに合意しなければなりません。

These transport mechanisms include, at a minimum, the transport protocol for exchanging the information, the architectural model for communicating with an information resource, and the applicable ports and domain names for accessing an information resource in a particular organization.  
これらのトランスポートメカニズムには、少なくとも、情報を交換するためのトランスポートプロトコル、情報リソースと通信するためのアーキテクチャモデル、および特定の組織で情報リソースにアクセスするための適用可能なポートとドメイン名が含まれます。 

For example, a group of partner organizations may decide to exchange incident information using a Representational State Transfer (REST) architecture to exchange IODEF/Real-Time Inter-Network Defense (RID) data over Hypertext Transfer Protocol Secure (HTTPS) on port 4590 of a specific domain name within each organization’s DMZ.  
例えば、パートナー組織のグループは、各組織のDMZ内の特定のドメイン名のポート 4590 のハイパーテキスト転送プロトコルセキュア（HTTPS）を介して IODEF/Real-Time Inter-Network Defense（RID）データを交換するために、REST（Representational State Transfer）アーキテクチャを使用してインシデント情報を交換することを決定することができます。  

※ According to the National Technology Transfer and Advancement Act (NTTAA), “all Federal agencies and departments shall use technical standards that are developed or adopted by voluntary consensus standards bodies”. See http://standards.gov/nttaa.cfm for more details.  
※ National Technology Transfer and Advancement Act (NTTAA)によると、「すべての連邦政府機関および省庁は、自主的なコンセンサス基準機関によって開発または採択された技術基準を使用しなければならない」とされています。詳細は http://standards.gov/nttaa.cfm を参照のこと。
