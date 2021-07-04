### Appendix G Crisis Handling Steps 
### 付録Ｇ 危機対応のステップ

This is a list of the major steps that should be performed when a technical professional believes that a serious incident has occurred and the organization does not have an incident response capability available.  
これは技術専門家が重大なインシデントが発生し、組織にインシデント対応能力がないと考えた場合に実行すべき主な手順のリストです。  

This serves as a basic reference of what to do for someone who is faced with a crisis and does not have time to read through this entire document.  
これは危機に直面したときに、この文書全体を読み通す時間がない人のために何をすべきかの基本的な参考資料としての役割を果たします。   

1. **Document everything.** This effort includes every action that is performed, every piece of evidence, and every conversation with users, system owners, and others regarding the incident.  
**すべてを文書化する。** この取り組みには、実行されたすべてのアクション、すべての証拠の断片、ユーザー、システム所有者、およびインシデントに関するその他の人とのすべての会話が含まれます。

2. **Find a coworker who can provide assistance.** Handling the incident will be much easier if two or more people work together. For example, one person can perform actions while the other documents them.  
**援助してくれる同僚を見つける。** 例えば、一人が行動を行い、もう一人がそれを文書化するなどです。 

3. **Analyze the evidence to confirm that an incident has occurred.** Perform additional research as necessary (e.g., Internet search engines, software documentation) to better understand the evidence. Reach out to other technical professionals within the organization for additional help.  
**証拠を分析して、インシデントが発生したことを確認する。** 必要に応じて、証拠をよりよく理解するために追加の調査(インターネットの検索エンジン、ソフ トウェアの文書など)を行います。組織内の他の技術専門家に連絡を取り、追加の支援を求めます。 

4. **Notify the appropriate people within the organization.** This should include the chief information officer (CIO), the head of information security, and the local security manager. Use discretion when discussing details of an incident with others; tell only the people who need to know and use communication mechanisms that are reasonably secure. (If the attacker has compromised email services, do not send emails about the incident.)  
**組織内の適切な担当者に通知する。** これには最高情報責任者（CIO）、情報セキュリティ責任者、現地のセキュリ ティ管理者が含まれるべきです。インシデントの詳細を他の人に話す場合は慎重に行い、知る必要のある人だけに伝え、合理的に安全なコミュニケーションメカニズムを使用します(攻撃者が電子メールサービスに侵入した場合は、インシデントに関する電子メールを送信しないこと)  
。

5. **Notify US-CERT and/or other external organizations** for assistance in dealing with the incident.   
**US-CERT および/またはその他の外部組織に通知**し、インシデントへの対応を支援してもらう。

6. **Stop the incident if it is still in progress.** The most common way to do this is to disconnect affected systems from the network. In some cases, firewall and router configurations may need to be modified to stop network traffic that is part of an incident, such as a denial of service (DoS) attack.  
**インシデントがまだ進行中の場合はインシデントを停止する。** 最も一般的な方法は、影響を受けたシステムをネットワークから切断することです。場合によっては、サービス拒否（DoS）攻撃など、インシデントの一部であるネットワークトラフィックを停止するために、 ファイアウォールおよびルーターの構成を変更する必要があります。 

7. **Preserve evidence from the incident.** Make backups (preferably disk image backups, not file system backups) of affected systems. Make copies of log files that contain evidence related to the incident.  
**インシデントの証拠を保存する。** 影響を受けたシステムのバックアップ（ファイルシステムのバックアップではなく、ディスクイメージのバックアップが望ましい）を作成します。インシデントに関連する証拠を含むログファイルのコピーを作成します。 

8. **Wipe out all effects of the incident.** This effort includes malware infections, inappropriate materials (e.g., pirated software), Trojan horse files, and any other changes made to systems by incidents. If a system has been fully compromised, rebuild it from scratch or restore it from a known good backup.  
**インシデントのすべての影響を一掃する。** この作業には、マルウェア感染、不適切な素材（海賊版ソフトウェアなど）、トロイの木馬ファイル、およびインシデントによってシステムに加えられたその他の変更が含まれます。システムが完全に侵害されている場合は、ゼロからシステムを再構築するか、既知の良好なバックアップから復元します。 

9. **Identify and mitigate all vulnerabilities that were exploited.** The incident may have occurred by taking advantage of vulnerabilities in operating systems or applications. It is critical to identify such vulnerabilities and eliminate or otherwise mitigate them so that the incident does not recur.   
**悪用されたすべての脆弱性を特定し緩和する。** インシデントは、オペレーティングシステムやアプリケーションの脆弱性を利用して発生した可能性があります。そのような脆弱性を特定し、インシデントが再発しないように排除するか、または緩和することが重要です。  

10. **Confirm that operations have been restored to normal.** Make sure that data, applications, and other services affected by the incident have been returned to normal operations.  
**操作が正常に復旧したことを確認する。** インシデントの影響を受けたデータ、アプリケーション、およびその他のサービスが通常の運用に戻ったことを確認してください。

11. **Create a final report.** This report should detail the incident handling process. It also should provide an executive summary of what happened and how a formal incident response capability would have helped to handle the situation, mitigate the risk, and limit the damage more quickly.  
**最終報告書を作成する。** この報告書には、インシデント処理プロセスの詳細を記載する必要があります。また、何が起こったのか、正式なインシデント対応能力があれば、どのように状況を処理し、リスクを軽減し、被害をより迅速に限定することができたのかについての要約を提供する必要があります。 
