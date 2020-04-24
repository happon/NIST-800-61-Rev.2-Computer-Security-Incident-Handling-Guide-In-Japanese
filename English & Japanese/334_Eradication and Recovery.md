### 3.3.4 Eradication and Recovery
### 3.3.4 根絶と回復

After an incident has been contained, eradication may be necessary to eliminate components of the incident, such as deleting malware and disabling breached user accounts, as well as identifying and mitigating all vulnerabilities that were exploited.  
インシデントが収束した後、マルウェアの削除や破られたユーザーアカウントの無効化など、インシデントの構成要素を排除するために根絶が必要になる場合がありますが、悪用されたすべての脆弱性を特定して緩和することもできます。  

During eradication, it is important to identify all affected hosts within the organization so that they can be remediated.  
根絶の際には、組織内の影響を受けるすべてのホストを特定し、それらを修復できるようにすることが重要です。 

For some incidents, eradication is either not necessary or is performed during recovery.  
インシデントによっては、根絶が必要ない場合もあれば、回復の最中に実行される場合もあります。 

<br/>

In recovery, administrators restore systems to normal operation, confirm that the systems are functioning normally, and (if applicable) remediate vulnerabilities to prevent similar incidents.  
回復では、管理者はシステムを正常な動作に戻し、システムが正常に機能していることを確認し、（該当する場合には）脆弱性を修正して同様のインシデントを防止します。  

Recovery may involve such actions as restoring systems from clean backups, rebuilding systems from scratch, replacing compromised files with clean versions, installing patches, changing passwords, and tightening network perimeter security (e.g., firewall rulesets, boundary router access control lists).  
回復には、クリーンなバックアップからのシステムの復元、ゼロからのシステムの再構築、感染したファイルのクリーンなバージョンへの置き換え、パッチのインストール、パスワードの変更、ネットワークの境界セキュリティの強化（例：ファイアウォールのルールセット、境界ルータのアクセス制御リスト）などのアクションが含まれる場合があります。  

Higher levels of system logging or network monitoring are often part of the recovery process.  
より高度なレベルのシステムロギングやネットワーク監視は、回復プロセスの一部であることが多いです。  

Once a resource is successfully attacked, it is often attacked again, or other resources within the organization are attacked in a similar manner.  
一度攻撃に成功すると、リソースが再び攻撃されたり、組織内の他のリソースが同様の方法で攻撃されたりすることがよくあります。  

<br/>

Eradication and recovery should be done in a phased approach so that remediation steps are prioritized.  
根絶と回復は、修復手順に優先順位が付けられるように、段階的なアプローチで行う必要があります。  

For large-scale incidents, recovery may take months;  
大規模なインシデントの場合、回復には数ヶ月かかることもあります。  

the intent of the early phases should be to increase the overall security with relatively quick (days to weeks) high value changes to prevent future incidents.  
初期の段階では、将来のインシデントを防ぐために、比較的迅速（数日から数週間）に価値の高い変更を行い、全体的なセキュリティを向上させることを目的とすべきです。  

The later phases should focus on longer-term changes (e.g., infrastructure changes) and ongoing work to keep the enterprise as secure as possible.  
後の段階では、長期的な変更（インフラの変更など）と、企業のセキュリティを可能な限り維持するための継続的な作業に焦点を当てるべきです。

<br/>

Because eradication and recovery actions are typically OS or application-specific, detailed recommendations and advice regarding them are outside the scope of this document.  
根絶と回復のためのアクションは、一般的に OS やアプリケーション固有のものであるため、それらに関する詳細な推奨事項やアドバイスは、本書の範疇外です。