### Scenario 8: Telecommuting Compromise
### シナリオ８：在宅勤務の妥協点

On a Saturday night, network intrusion detection software records an inbound connection originating from a watchlist IP address.  
土曜日の夜、ネットワーク侵入検知ソフトウェアは、ウォッチリストのIPアドレスから発信されたインバウンド接続を記録します。  

The intrusion detection analyst determines that the connection is being made to the organization’s VPN server and contacts the incident response team.  
侵入検知アナリストは、その接続が組織のVPN サーバーに行われていると判断し、インシデント対応チームに連絡します。  

The team reviews the intrusion detection, firewall, and VPN server logs and identifies the user ID that was authenticated for the session and the name of the user associated with the user ID.  
チームは、侵入検知、ファイアウォール、および VPN サーバーのログを確認し、セッションで認証されたユーザー ID と、そのユーザー ID に関連付けられたユーザー名を特定します。  

The following are additional questions for this scenario:  
このシナリオの追加質問は以下の通りです。 

1. What should the team’s next step be (e.g., calling the user at home, disabling the user ID, disconnecting the VPN session)? Why should this step be performed first? What step should be performed second?  
チームの次のステップは何ですか? なぜこのステップを最初に実行する必要があるのでしょうか? 次に実行すべきステップは何ですか?

2. How would the handling of this incident differ if the external IP address belonged to an open proxy?  
外部IPアドレスがオープンプロキシに属していた場合、このインシデントの処理はどのように異なるでしょうか?

3. How would the handling of this incident differ if the ID had been used to initiate VPN connections from several external IP addresses without the knowledge of the user?  
ユーザーが知らないうちに、そのIDが複数の外部IPアドレスからVPN接続を開始するために使用されていた場合、このインシデントの処理はどのように異なるでしょうか?

4. Suppose that the identified user’s computer had become compromised by a game containing a Trojan horse that was downloaded by a family member.How would this affect the team’s analysis of the incident? How would this affect evidence gathering and handling? What should the team do in terms of eradicating the incident from the user’s computer?  
特定されたユーザーのコンピュータが、家族のメンバーによってダウンロードされたトロイの木馬を含むゲームによって危険にさらされていたとします。これは、証拠の収集と処理にどのような影響を与えますか？ユーザーのコンピュータからインシデントを根絶するという点で、チームは何をすべきでしょうか?   

5. Suppose that the user installed antivirus software and determined that the Trojan horse had included a keystroke logger. How would this affect the handling of the incident? How would this affect the handling of the incident if the user were a system administrator? How would this affect the handling of the incident if the user were a high-ranking executive in the organization?  
ユーザーがウイルス対策ソフトをインストールし、トロイの木馬にキーストロークロガーが含まれていたと判断したとします。このことは、インシデントの処理にどのような影響を与えますか? ユーザーがシステム管理者であった場合、このことはインシデントの処理にどのような影響を与えますか? ユーザーが組織内の高位幹部であった場合、このことはインシデントの処理にどのような影響を与えるでしょうか?