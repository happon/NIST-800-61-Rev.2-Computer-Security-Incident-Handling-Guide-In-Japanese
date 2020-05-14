# 1. Introduction 序 章

### 1.1 Authority 権 限

The National Institute of Standards and Technology (NIST) developed this document in furtherance of its statutory responsibilities under the Federal Information Security Management Act (FISMA) of 2002, Public Law 107-347.  
国立標準技術研究所（NIST）は、2002 年の連邦情報セキュリティ管理法（FISMA）（公法 107-347）に基づく法的責任を推進するために、この文書を作成しました。  

NIST is responsible for developing standards and guidelines, including minimum requirements, for providing adequate information security for all agency operations and assets, but such standards and guidelines shall not apply to national security systems.  
NIST は、すべての機関の業務と資産に適切な情報セキュリティを提供するために、最低限の要件を含む標準とガイドラインを策定する責任がありますが、このような標準とガイドラインは、国家安全保障システムには適用されないものとします。  

This guideline is consistent with the requirements of the Office of Management and Budget (OMB) Circular A-130, Section 8b(3), “Securing Agency Information Systems,” as analyzed in A-130, Appendix IV: Analysis of Key Sections. Supplemental information is provided in A-130, Appendix III.  
本ガイドラインは、管理予算局（OMB）通達 Circular A-130 の第 8b(3)項「省庁情報システムのセキュリティ確保」の要求事項と一致しており、A-130 の付録 IV: 重要な項の分析で分析されています。補足情報は、A-130「付録III」に記載されています。  

This guideline has been prepared for use by Federal agencies.  
本ガイドラインは、連邦政府機関が使用するために作成されたものです。  

It may be used by nongovernmental organizations on a voluntary basis and is not subject to copyright, though attribution is desired.  
非政府組織が任意で使用することができ、著作権の対象とはなりませんが、帰属表示が望まれます。  


Nothing in this document should be taken to contradict standards and guidelines made mandatory and binding on Federal agencies by the Secretary of Commerce under statutory authority, nor should these guidelines be interpreted as altering or superseding the existing authorities of the Secretary of Commerce, Director of the OMB, or any other Federal official.  
また、これらのガイドラインは、商務省長官、OMB長官、またはその他の連邦職員の既存の権限を変更したり、それに取って代わるものとして解釈されるべきではありません。 　

<br/>

### 1.2 Purpose and Scope「目的と範囲」

This publication seeks to assist organizations in mitigating the risks from computer security incidents by providing practical guidelines on responding to incidents effectively and efficiently.  
本書は、インシデントへの効果的かつ効率的な対応に関する実践的なガイドラインを提供することで、コンピュータセキュリ ティインシデントによるリスクを軽減するための組織を支援することを目的としています。  

It includes guidelines on establishing an effective incident response program, but the primary focus of the document is detecting, analyzing, prioritizing, and handling incidents.  
本書には、効果的なインシデント対応プログラムの確立に関するガイドラインが含まれていますが、本書の主な焦点は、インシデントの検出、分析、優先順位付け、および対応です。  

Organizations are encouraged to tailor the recommended guidelines and solutions to meet their specific security and mission requirements.  
組織は、推奨されるガイドラインとソリューションを、特定のセキュリティとミッションの要件を満たすように調整することが推奨されます。  

<br/>

### 1.3 Audience「対象者」

This document has been created for computer security incident response teams (CSIRTs), system and network administrators, security staff, technical support staff, chief information security officers (CISOs), chief information officers (CIOs), computer security program managers, and others who are responsible for preparing for, or responding to, security incidents.  
この文書は、コンピュータセキュリティインシデント対応チーム（CSIRT）、システムおよびネットワーク管理者、セキュリティスタッフ、技術サポートスタッフ、最高情報セキュリティ責任者（CISO）、最高情報責任者（CIO）、コンピュータセキュリティプログラムマネージャー、その他セキュリティインシデントへの準備や対応に責任を持つ人々のために作成されました。 　

<br/>

### 1.4 Document Structure「文章構成」

The remainder of this document is organized into the following sections and appendices:  
本書の残りの部分は、以下のセクションと付録で構成されています。  

■ Section 2 discusses the need for incident response, outlines possible incident response team structures, and highlights other groups within an organization that may participate in incident handling.  
■ セクション2では、インシデント対応の必要性について議論し、可能なインシデント対応チームの構造を概説し、インシデントハンドリングに参加する可能性のある組織内の他のグループを強調しています。  

■ Section 3 reviews the basic incident handling steps and provides advice for performing incident handling more effectively, particularly incident detection and analysis.  
■ セクション3では、基本的なインシデント対応のステップをレビューし、インシデント対応をより効果的に行うための アドバイス、特にインシデントの検出と分析を提供しています。  

■ Section 4 examines the need for incident response coordination and information sharing.   
■ セクション4では、インシデント対応の調整と情報共有の必要性を検討しています。  

■ Appendix A contains incident response scenarios and questions for use in incident response tabletop discussions.  
■ 付録Aには、インシデント対応の卓上ディスカッションで使用するためのインシデント対応シナリオと質問が含まれています。  

■ Appendix B provides lists of suggested data fields to collect for each incident.  
■ 付録Bは、各インシデントについて収集すべきデータフィールドのリストを提供しています。  

■ Appendices C and D contain a glossary and acronym list, respectively.  
■ 付録CとDには、それぞれ用語集と頭字語のリストが含まれています。  

■ Appendix E identifies resources that may be useful in planning and performing incident response.  
■ 付録Eは、インシデント対応の計画と実行に有用なリソースを特定しています。 

■ Appendix F covers frequently asked questions about incident response.  
■ 付録Fでは、インシデント対応に関するよくある質問を取り上げています。

■ Appendix G lists the major steps to follow when handling a computer security incident-related crisis.  
■ 付録 G には、コンピュータ・セキュリティ・インシデント関連の危機に対処する際に従うべき主な手順が記載されています。  

■ Appendix H contains a change log listing significant changes since the previous revision.  
■ 付録 H には、前回の改訂以降の重要な変更点をリストアップした変更ログが含まれています。 
