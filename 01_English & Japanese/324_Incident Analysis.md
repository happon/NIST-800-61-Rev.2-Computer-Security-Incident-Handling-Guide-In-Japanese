### 3.2.4 Incident Analysis
### 3.2.4 インシデント分析

Incident detection and analysis would be easy if every precursor or indicator were guaranteed to be accurate;  
すべての前兆や兆候が正確であることが保証されていれば、インシデントの検出や分析は簡単です。  

unfortunately, this is not the case. For example, user-provided indicators such as a complaint of a server being unavailable are often incorrect.  
しかし、残念ながらそうではありません。例えば、サーバーが利用できないという苦情など、ユーザーが提供した兆候が正しくないことがよくあります。  

Intrusion detection systems may produce false positives— incorrect indicators. These examples demonstrate what makes incident detection and analysis so difficult:  
侵入検知システムは、誤ったポジティブ、つまり不正確な兆候を生成することがあります。これらの例は、インシデントの検出と分析を困難にしていることを示しています。 

each indicator ideally should be evaluated to determine if it is legitimate.  
理想的には、それぞれの指標は、その正確性を判断するために評価されなければなりません。  

Making matters worse, the total number of indicators may be thousands or millions a day.  
さらに悪いことに、兆候の総数は1日に何千、何百万ということもあります。  

Finding the real security incidents that occurred out of all the indicators can be a daunting task.  
すべての兆候の中から実際に発生したセキュリティインシデントを見つけるのは、大変な作業になります。  

<br/>

Even if an indicator is accurate, it does not necessarily mean that an incident has occurred.  
また、兆候が正確であったとしても、必ずしもインシデントが発生したとは限りません。   

Some indicators, such as a server crash or modification of critical files, could happen for several reasons other than a security incident, including human error.  
サーバーのクラッシュや重要なファイルの変更など、いくつかの兆候の中には、人為的なミスなど、セキュリティインシデント以外のいくつかの理由で発生する可能性があります。  

Given the occurrence of indicators, however, it is reasonable to suspect that an incident might be occurring and to act accordingly.  
しかし、兆候が発生していれば、インシデントが発生しているかもしれないと疑い、それに応じて行動することは理にかなっています。  

Determining whether a particular event is actually an incident is sometimes a matter of judgment.  
特定の事象が実際にインシデントであるかどうかの判断は、時に判断の問題となります。  

It may be necessary to collaborate with other technical and information security personnel to make a decision.  
判断を下すために、他の技術担当者や情報セキュリティ担当者と協力することが必要な場合もあります。  

In many instances, a situation should be handled the same way regardless of whether it is security related.  
多くの場合、状況がセキュリティ関連であるかどうかに関係なく、同じ方法で処理されるべきです。   

For example, if an organization is losing Internet connectivity every 12 hours and no one knows the cause, the staff would want to resolve the problem just as quickly and would use the same resources to diagnose the problem, regardless of its cause.  
例えば、ある組織でインターネット接続が12時間ごとに失われ、誰も原因がわからない場合、スタッフは同じように迅速に問題を解決したいと考え、原因に関係なく同じリソースを使って問題を診断することになるでしょう。  

<br/>

Some incidents are easy to detect, such as an obviously defaced web page.  
インシデントの中には、明らかに改ざんされたウェブページなど、検出しやすいものもあります。  

However, many incidents are not associated with such clear symptoms.  
しかし、多くのインシデントは、そのような明確な症状とは関連していません。  

Small signs such as one change in one system configuration file may be the only indicators that an incident has occurred.  
システム構成ファイルの変更のような小さな兆候だけが、インシデントが発生したことを示す唯一の兆候かもしれません。  

In incident handling, detection may be the most difficult task.  
インシデントハンドリングでは、検出が最も困難な作業かもしれません。   

Incident handlers are responsible for analyzing ambiguous, contradictory, and incomplete symptoms to determine what has happened.  
インシデントハンドラーは、何が起こったのかを判断するために、曖昧で、矛盾した、不完全な症状を分析する責任があります。  

Although technical solutions exist that can make detection easier, the best remedy is to build a team of highly experienced and proficient staff members who can analyze the precursors and indicators effectively and efficiently and take appropriate actions.  
検出を容易にする技術的な解決策は存在しますが、最良の解決策は、前兆や兆候を効果的かつ効率的に分析し、適切な行動をとることができる、経験豊富で熟練したスタッフのチームを構築することです。  

Without a well-trained and capable staff, incident detection and analysis will be conducted inefficiently, and costly mistakes will be made.  
十分な訓練を受けた有能なスタッフがいなければ、インシデントの検出と分析は非効率的に行われ、コストのかかるミスを犯すことになります。  

The incident response team should work quickly to analyze and validate each incident, following a predefined process and documenting each step taken.  
インシデント対応チームは、事前に定義されたプロセスに従って、各インシデントの分析と検証を迅速に行 い、各ステップを文書化する必要があります。 

When the team believes that an incident has occurred, the team should rapidly perform an initial analysis to determine the incident’s scope, such as which networks, systems, or applications are affected;  
インシデントが発生したとチームが判断した場合、チームは迅速に初期分析を行い、どのネットワーク、システム、またはアプリケーションが影響を受けるのかなど、インシデントの範囲を決定する必要があります。 

who or what originated the incident; and how the incident is occurring (e.g., what tools or attack methods are being used, what vulnerabilities are being exploited).  
インシデントが発生したのは誰なのか、何が原因なのか、インシデントがどのように発生しているのか（どのようなツールや攻撃方法が使用されているのか、どのような脆弱性が悪用されているのかなど）。

The initial analysis should provide enough information for the team to prioritize subsequent activities, such as containment of the incident and deeper analysis of the effects of the incident.  
初期分析は、インシデントの封じ込めやより深いインシデントの影響分析など、チームがその後の活動に優先順位をつけるのに十分な情報を提供しなければなりません。 

Performing the initial analysis and validation is challenging.  
初期分析と検証を行うことは困難です。 

The following are recommendations for making incident analysis easier and more effective:  
以下は、インシデント分析をより簡単で効果的なものにするための推奨事項です。

■ **Understand Normal Behaviors.**  
■ **正常な動作を理解する**  

Incident response team members should study networks, systems, and applications to understand what their normal behavior is so that abnormal behavior can be recognized more easily.  
インシデント対応チームのメンバーは、ネットワーク、システム、およびアプリケーションを研究し、異常な動作をより簡単に認識できるように、その正常な動作を理解する必要があります。   

No incident handler will have a comprehensive knowledge of all behavior throughout the environment, but handlers should know which experts could fill in the gaps.  
インシデントハンドラーは、環境全体のすべての行動について包括的な知識を持っているわけではありませんが、どの専門家がそのギャップを埋めることができるかを知っておく必要があります。 

One way to gain this knowledge is through reviewing log entries and security alerts.  
この知識を得るための一つの方法は、ログエントリとセキュリティアラートを確認することです。 

This may be tedious if filtering is not used to condense the logs to a reasonable size.  
これは、ログを適切なサイズに凝縮するためのフィルタリングが使用されていない場合、退屈な作業になるかもしれません。 

As handlers become more familiar with the logs and alerts, they should be able to focus on unexplained entries, which are usually more important to investigate.  
ハンドラーがログやアラートに慣れてくると、原因不明のエントリに焦点を当てることができるようになり、通常は調査することがより重要になります。 

Conducting frequent log reviews should keep the knowledge fresh, and the analyst should be able to notice trends and changes over time.  
頻繁にログのレビューを行うことで、知識を新鮮なものに保つことができ、分析者は時間の経過とともに傾向や変化に気づくことができるようになります。 

The reviews also give the analyst an indication of the reliability of each source.  
また、レビューにより、各ソースの信頼度の指標も得ることができます。

（以下はrev.1日本語オリジナル）
ログをレビューし、興味のあるエントリーを調査することは、インシデントを処理する準備にもなります。インシデントの処理では、これらのスキルが必要になります。　　
（ここまで）  

■ **Create a Log Retention Policy.**  
■ **ログ保持ポリシーの作成**  
Information regarding an incident may be recorded in several places, such as firewall, IDPS, and application logs.  
インシデントに関する情報は、ファイアウォール、IDPS、アプリケーション ログなど、いくつかの場所に記録される可能性があります。

Creating and implementing a log retention policy that specifies how long log data should be maintained may be extremely helpful in analysis because older log entries may show reconnaissance activity or previous instances of similar attacks.  
ログデータの保持期間を指定したログ保持ポリシーを実装すると、古いログエントリには、偵察活動や以前に同様の攻撃が行われたことが示されている可能性があるため、分析に非常に役立つ可能性があります。 

Another reason for retaining logs is that incidents may not be discovered until days, weeks, or even months later.  
ログを保持するもう一つの理由は、数日後、数週間後、あるいは数ヶ月後にならないとインシデントが発見されない可能性があることです。 

The length of time to maintain log data is dependent on several factors, including the organization’s data retention policies and the volume of data. See NIST SP 800-92, Guide to Computer Security Log Management for additional recommendations related to logging.34  
ログデータの保持期間は、組織のデータ保持ポリシーやデータ量など、いくつかの要因に依存します。ログに関する追加の推奨事項については、NIST SP 800-92「Guide to Computer Security Log Management」を参照してください。

■ **Perform Event Correlation.**  
■ **イベント相関処理の実施**  
Evidence of an incident may be captured in several logs that each contain different types of data—a firewall log may have the source IP address that was used, whereas an application log may contain a username.  
インシデントの証拠は、異なるタイプのデータを含む複数のログに記録されることがあります。ファイアウォールログには使用されたソースIPアドレスが記録され、アプリケーションログにはユーザー名が記録されることがあります。

A network IDPS may detect that an attack was launched against a particular host, but it may not know if the attack was successful.  
ネットワーク IDPS は、特定のホストに対して攻撃が開始されたことを検出することができますが、攻撃の成否はわかりません。 

The analyst may need to examine the host’s logs to determine that information.  
アナリストは、その情報を判断するためにホストのログを調べる必要があるかもしれません。

Correlating events among multiple indicator sources can be invaluable in validating whether a particular incident occurred.  
複数の兆候ソース間のイベントを相関させることは、特定のインシデントが発生したかどうかを検証する上で非常に重要です。

■ **Keep All Host Clocks Synchronized.**  
■ **すべてのホストのクロックを同期**  
Protocols such as the Network Time Protocol (NTP) synchronize clocks among hosts.35  
NTP（Network Time Protocol）などのプロトコルは、ホスト間のクロックを同期させます。 

Event correlation will be more complicated if the devices reporting events have inconsistent clock settings.  
イベントを報告するデバイスのクロック設定が一貫していない場合、イベントの相関関係はより複雑になります。 

From an evidentiary standpoint, it is preferable to have consistent timestamps in logs—for example, to have three logs that show an attack occurred at 12:07:01 a.m., rather than logs that list the attack as occurring at 12:07:01, 12:10:35, and 11:07:06.  
例えば、攻撃が12:07:01、12:10:35、11:07:06に発生したことを示すログよりも、証拠という観点から、攻撃が12:07:01に発生したことを示す3つのログを持つ（一貫したタイムスタンプがある）方が望ましいです。 

■ **Maintain and Use a Knowledge Base of Information.**  
■ **情報のナレッジベースの維持・使用**  
The knowledge base should include information that handlers need for referencing quickly during incident analysis.  
ナレッジベースには、ハンドラーがインシデント分析時に素早く参照するために必要な情報が含まれている必要があります。 

Although it is possible to build a knowledge base with a complex structure, a simple approach can be effective. Text documents, spreadsheets, and relatively simple databases provide effective, flexible, and searchable mechanisms for sharing data among team members.  
複雑な構造のナレッジベースを構築することも可能ですが、シンプルなアプローチが効果的です。。テキスト文書、スプレッドシート、比較的シンプルなデータベースは、チームメンバー間でデータを共有するために効果的かつ柔軟性があり、検索可能なメカニズムを提供します。 

The knowledge base should also contain a variety of information, including explanations of the significance and validity of precursors and indicators, such as IDPS alerts, operating system log entries, and application error codes.  
また、ナレッジベースには、IDPSアラート、オペレーティングシステムのログエントリ、アプリケーションのエラーコードなどの前兆や兆候の重要性や妥当性の説明など、さまざまな情報が含まれていることが望ましいです。 

■ **Use Internet Search Engines for Research.**  
■ **イベントの相関関係処理の実施**  
Internet search engines can help analysts find information on unusual activity.  
インターネット検索エンジンは、アナリストが、異常なアクティビティに関する情報を見つけるのに役立ちます。 

For example, an analyst may see some unusual connection attempts targeting TCP port 22912.  
例えば、TCP ポート 22912 をターゲットにした異常な接続の試みをアナリストが目にすることがあります。

Performing a search on the terms “TCP,” “port,” and “22912” may return some hits that contain logs of similar activity or even an explanation of the significance of the port number.  
「TCP」、「port」、および「22912」という用語で検索すると、類似のアクティビティのログや、ポート番号の重要性についての説明を含むいくつかのヒットが返ってくることがあります。 

Note that separate workstations should be used for research to minimize the risk to the organization from conducting these searches.  
これらの検索を行うことによる組織へのリスクを最小限に抑えるために、調査には別のワークステーションを使用すべきであることに注意してください。 

■ **Run Packet Sniffers to Collect Additional Data.**  
■ **パケットスニファを実行して追加データを収集**  
Sometimes the indicators do not record enough detail to permit the handler to understand what is occurring.  
インジケータは、ハンドラーが何が起こっているのかを理解するのに十分な詳細を記録していないことがあります。

If an incident is occurring over a network, the fastest way to collect the necessary data may be to have a packet sniffer capture network traffic.  
インシデントがネットワーク上で発生している場合、必要なデータを収集する最速の方法は、パケットスニッファーにネットワークトラフィックをキャプチャさせることかもしれません。 

Configuring the sniffer to record traffic that matches specified criteria should keep the volume of data manageable and minimize the inadvertent capture of other information.  
指定された基準に一致するトラフィックを記録するようにスニッファーを設定することで、データ量を管理可能な状態に保ち、他の情報を不用意に取得することを最小限に抑えることができます。 

Because of privacy concerns, some organizations may require incident handlers to request and receive permission before using packet sniffers.  
プライバシーの問題があるため、組織によっては、パケットスニッファーを使用する前にインシデントハンドラーに要求して許可を得ることが必要とする場合があります。

■ **Filter the Data.**  
■ **データのフィルタリング**  
There is simply not enough time to review and analyze all the indicators;  
すべての兆候を確認して分析するには、シンプルに十分な時間はありません。

at minimum the most suspicious activity should be investigated.  
最低限、最も疑わしい活動を調査する必要があります。

One effective strategy is to filter out categories of indicators that tend to be insignificant.  
効果的な戦略の1つは、取るに足らない兆候のカテゴリーをフィルタリングすることです。 

Another filtering strategy is to show only the categories of indicators that are of the highest significance;  
もう一つのフィルタリング戦略は、最も重要度の高い兆候のカテゴリーのみを表示することです。

however, this approach carries substantial risk because new malicious activity may not fall into one of the chosen indicator categories.  
しかしこの方法では、新たな悪意のある活動が、選択した兆候カテゴリのいずれかも該当しない可能性があるため、大きなリスクを伴います。

■ **Seek Assistance from Others.**  
■ **他社の支援を求める**  
Occasionally, the team will be unable to determine the full cause and nature of an incident.  
時として、チームはインシデントの完全な原因と性質を判断できないことがあります。 

If the team lacks sufficient information to contain and eradicate the incident, then it should consult with internal resources (e.g., information security staff) and external resources (e.g., US-CERT, other CSIRTs, contractors with incident response expertise).  
チームがインシデントを封じ込め、根絶するための十分な情報が不足している場合は、内部のリソース（情報セキュリティスタッフなど）や外部のリソース（US-CERT、他のCSIRT、インシデント対応の専門知識を持つ請負業者など）に相談する必要があります。

It is important to accurately determine the cause of each incident so that it can be fully contained and the exploited vulnerabilities can be mitigated to prevent similar incidents from occurring.  
各インシデントの原因を正確に判断して、インシデントを完全に封じ込め、悪用された脆弱性を緩和して、同様のインシデントが発生しないようにすることが重要です。