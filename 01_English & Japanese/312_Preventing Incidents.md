### 3.1.2 Preventing Incidents
### 3.1.2 インシデントの予防

Keeping the number of incidents reasonably low is very important to protect the business processes of the organization.  
組織のビジネスプロセスを保護するためには、インシデントの数を適度に少なくすることが非常に重要です。 

If security controls are insufficient, higher volumes of incidents may occur, overwhelming the incident response team.  
セキュリティ管理が不十分な場合、インシデントが大量に発生し、インシデント対応チームを圧倒する可能性があります。

This can lead to slow and incomplete responses, which translate to a larger negative business impact (e.g., more extensive damage, longer periods of service and data unavailability).  
その結果、対応に時間がかかったり、不完全なものになったりして、ビジネスへの悪影響が大きくなる可能性があります（例：被害の拡大、サービスの長期化、データの利用不能など）。  

<br/>

It is outside the scope of this document to provide specific advice on securing networks, systems, and applications.  
ネットワーク、システム、およびアプリケーションのセキュリティ確保に関する具体的なアドバイスを提供することは、この文書の範囲外です。 

Although incident response teams are generally not responsible for securing resources, they can be advocates of sound security practices.  
インシデント対応チームは、一般的にリソースの安全確保には責任を負いませんが、健全なセキュリティ対策の提唱者となり得ます。 

An incident response team may be able to identify problems that the organization is otherwise not aware of;  
インシデント対応チームは、組織が他の方法では気付かない問題を特定できる可能性があります。

the team can play a key role in risk assessment and training by identifying gaps.  
インシデント対応チームは、ギャップを特定することで、リスク評価と訓練において重要な役割を果たすことができます。

Other documents already provide advice on general security concepts and operating system and application-specific guidelines.※  
他の文書では、一般的なセキュリティの概念や、オペレーティングシステムやアプリケーションに特化したガイドラインについてのアドバイスがすでに提供されています※。　

The following text, however, provides a brief overview of some of the main recommended practices for securing networks, systems, and applications:  
しかし、以下に、ネットワーク、システム、およびアプリケーションのセキュリティを確保するために推奨されている主な実践方法の概要について簡単に説明します。  

※ http://csrc.nist.gov/publications/PubsSPs.html provides links to the NIST Special Publications on computer security, which include documents on operating system and application security baselines.   
※ http://csrc.nist.gov/publications/PubsSPs.html は、コンピュータセキュリティに関する NIST の特別出版物へのリンクを提供しています。

■ **Risk Assessments.**  
■ **リスク評価**  

Periodic risk assessments of systems and applications should determine what risks are posed by combinations of threats and vulnerabilities.※１  
システムとアプリケーションの定期的なリスク評価は、脅威と脆弱性の組み合わせによってどのようなリスクが引き起こされているかを判断するべきです※１。  

This should include understanding the applicable threats, including organization-specific threats.  
これには、組織固有の脅威を含め、適用可能な脅威を理解することが含まれます。 

Each risk should be prioritized, and the risks can be mitigated, transferred, or accepted until a reasonable overall level of risk is reached.  
それぞれのリスクには優先順位をつけ、リスクの全体的な合理的なレベルに達するまで、リスクを軽減、移転、受容することができます。 

Another benefit of conducting risk assessments regularly is that critical resources are identified, allowing staff to emphasize monitoring and response activities for those resources.※２  
定期的にリスクアセスメントを実施するもう一つの利点は、重要な資源が特定され、スタッフはそれらの資源に対する監視と対応活動に重点を置くことができるという点です※２。 

※１ Guidelines on risk assessment are available in NIST SP 800-30, Guide for Conducting Risk Assessments, at http://csrc.nist.gov/publications/PubsSPs.html#800-30-Rev1.  
※１ リスク評価に関するガイドラインは、NIST SP 800-30, リスクアセスメントの実施の手引きhttp://csrc.nist.gov/publications/PubsSPs.html#800-30-Rev1 に掲載されています。  

※２ Information on identifying critical resources is discussed in FIPS 199, Standards for Security Categorization of Federal Information and Information Systems, at http://csrc.nist.gov/publications/PubsFIPS.html.  
※２ クリティカルなリソースの特定に関する情報は、FIPS 199「連邦情報および情報システムのセキュリティ分類基準」（http://csrc.nist.gov/publications/PubsFIPS.html）で議論されています。  

■ **Host Security.**  
■ **ホストセキュリティ**  

All hosts should be hardened appropriately using standard configurations.  
すべてのホストは、標準的な設定を用いて適切にセキュリティを強化する必要があります。 

In addition to keeping each host properly patched, hosts should be configured to follow the principle of least privilege—granting users only the privileges necessary for performing their authorized tasks.  
各ホストのパッチを適切に適用することに加えて、権限のあるタスクを実行するために必要な権限のみをユーザに付与するという原則に従うように設定されている必要があります。 

Hosts should have auditing enabled and should log significant security-related events.  
監査を有効にし、セキュリティ関連の重要なイベントをログに記録しなければなりません。 

The security of hosts and their configurations should be continuously monitored.※３  
ホストとその設定のセキュリティを継続的に監視する必要があります※３。 

Many organizations use Security Content Automation Protocol (SCAP)※４ expressed operating system and application configuration checklists to assist in securing hosts consistently and effectively.※５  
多くの組織は、一貫して効果的にホストのセキュリティを確保するために、Security Content Automation Protocol (SCAP)※４ で表現されたオペレーティングシステムとアプリケーションの設定チェックリストを使用しています※５。

※３　For more information on continuous monitoring, see NIST SP 800-137, Information Security Continuous Monitoring for Federal Information Systems and Organizations (http://csrc.nist.gov/publications/PubsSPs.html#800-137).  
※３　継続的監視の詳細については、NIST SP 800-137 「連邦政府の情報システムと組織のための情報セキュリティの継続的な監視」(http://csrc.nist.gov/publications/PubsSPs.html#800-137)を参照してください。   

※４　More information on SCAP is available from NIST SP 800-117 Revision 1, Guide to Adopting and Using the Security Content Automation Protocol (SCAP) Version 1.2 (http://csrc.nist.gov/publications/PubsSPs.html#800-117).   
※４　SCAP の詳細については、NIST SP 800-117 Revision 1, 「セキュリティ・コンテンツ・オートメーション・プロトコル(SCAP)の採用と使用の手引き」Version 1.2 (http://csrc.nist.gov/publications/PubsSPs.html#800-117) を参照してください。

※５　NIST hosts a security checklists repository at http://checklists.nist.gov/.  
※５　NIST はセキュリティチェックリストのリポジトリを http://checklists.nist.gov/ で公開しています。  　


■ **Network Security.**  
■ **ネットワークセキュリティ**

The network perimeter should be configured to deny all activity that is not expressly permitted.  
ネットワークの境界は、明示的に許可されていないすべてのアクティビティを拒否するように設定する必要があります。

This includes securing all connection points, such as virtual private networks (VPNs) and dedicated connections to other organizations.  
これには、仮想プライベート ネットワーク (VPN) や他の組織への専用接続など、すべての接続ポイントのセキュリティを確保することが含まれます。

■ **Malware Prevention.**  
■ **マルウェアの予防**

Software to detect and stop malware should be deployed throughout the organization.  
マルウェアを検出して停止させるためのソフトウェアは、組織全体に配備されている必要があります。 

Malware protection should be deployed at the host level (e.g., server and workstation operating systems), the application server level (e.g., email server, web proxies), and the application client level (e.g., email clients, instant messaging clients).30  
マルウェア対策は、ホストレベル（サーバやワークステーションのオペレーテ ィングシステムなど）、アプリケーションサーバレベル（電子メールサーバ、ウェブプロキシなど）、アプリケーションクライアントレベル（電子メールクライアント、インスタントメッセージングクライアントなど）で展開する必要があります。

■ **User Awareness and Training.**  
■ **ユーザーの意識向上とトレーニング**

Users should be made aware of policies and procedures regarding appropriate use of networks, systems, and applications.  
ネットワーク、システムおよびアプリケーションの適切な使用に関するポリシー・手順をユーザーに周知すべきです。 

Applicable lessons learned from previous incidents should also be shared with users so they can see how their actions could affect the organization.  
また、過去のインシデントから得られた適用可能な教訓をユーザーと共有し、自分たちの行動が組織にどのような影響を与えるかを確認できるようにする必要があります。 

Improving user awareness regarding incidents should reduce the frequency of incidents.  
インシデントに関するユーザの意識を向上させることで、インシデントの頻度を減らすことができます。

IT staff should be trained so that they can maintain their networks, systems, and applications in accordance with the organization’s security standards.  
IT スタッフは、組織のセキュリティ基準に従ってネットワーク、システム、およびアプリケーションを維持できるように訓練を受けるべきです。 