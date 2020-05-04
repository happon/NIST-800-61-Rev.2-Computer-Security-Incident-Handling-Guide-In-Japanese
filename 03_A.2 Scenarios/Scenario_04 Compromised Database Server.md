### Scenario 4: Compromised Database Server
### シナリオ４: データベースサーバの危殆化

On a Tuesday night, a database administrator performs some off-hours maintenance on several production database servers.  
火曜日の夜、データベース管理者は、いくつかの本番用データベースサーバのメンテナンスを時間外に行いました。 

The administrator notices some unfamiliar and unusual directory names on one of the servers.  
管理者は、サーバの1つに見慣れない珍しいディレクトリ名があることに気付きました。 

After reviewing the directory listings and viewing some of the files, the administrator concludes that the server has been attacked and calls the incident response team for assistance.  
ディレクトリのリストを確認し、いくつかのファイルを閲覧した後、管理者はサーバが攻撃されたと結論付け、インシデント対応チームに支援を要請しました。

The team’s investigation determines that the attacker successfully gained root access to the server six weeks ago.  
チームの調査では、攻撃者が6週間前にサーバへのルートアクセスに成功したことが判明しました。 

The following are additional questions for this scenario:  
以下は、このシナリオに関する追加の質問です。 

1. What sources might the team use to determine when the compromise had occurred?  
チームはどのような情報源を使用して、侵害がいつ発生したかを判断することができますか?  

2. How would the handling of this incident change if the team found that the database server had been running a packet sniffer and capturing passwords from the network?  
データベースサーバがパケットスニッファーを実行し、ネットワークからパスワードを取得していたことをチームが発見した場合、このインシデントの処理はどのように変わるでしょうか?   
v
3. How would the handling of this incident change if the team found that the server was running a process that would copy a database containing sensitive customer information (including personally identifiable information) each night and transfer it to an external address?  
サーバが毎晩、機密性の高い顧客情報(個人を特定できる情報を含む)を含むデータベースをコピーして外部アドレスに転送するプロセスを実行していたことをチームが発見した場合、このインシデントの処理はどのように変わるでしょうか?   

4. How would the handling of this incident change if the team discovered a rootkit on the server?  
チームがサーバ上にルートキットを発見した場合、このインシデントの処理はどのように変わりますか?