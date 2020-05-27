### Scenario 5: Unknown Exfiltration 
#### シナリオ５：不明な流出

On a Sunday night, one of the organization’s network intrusion detection sensors alerts on anomalous outbound network activity involving large file transfers.  
日曜日の夜、組織のネットワーク侵入検知センサーの1つが、大規模なファイル転送を含む異常なアウトバウンドネットワークアクティビティを警告しました。 

The intrusion analyst reviews the alerts; it appears that thousands of .RAR files are being copied from an internal host to an external host, and the external host is located in another country.  
侵入アナリストがアラートを確認すると、何千もの .RAR ファイルが内部ホストから外部ホストにコピーされており、外部ホストは別の国に位置していることがわかりました。

The analyst contacts the incident response team so that it can investigate the activity further.  
アナリストは、インシデント対応チームに連絡して、その活動をさらに調査できるようにします。

The team is unable to see what the .RAR files hold because their contents are encrypted.  
.RAR ファイルの内容は暗号化されているため、チームは .RAR ファイルが何を保持しているかを見ることができません。

Analysis of the internal host containing the .RAR files shows signs of a bot installation.  
.RARファイルを含む内部ホストを分析すると、ボットのインストールの兆候が見られます。

The following are additional questions for this scenario:  
このシナリオに関する追加の質問は以下の通りです。

1. How would the team determine what was most likely inside the .RAR files? Which other teams might assist the incident response team?  
. RARファイルの内部にある可能性の高いものをチームはどのように判断するのでしょうか？他のどのチームがインシデント対応チームを支援しますか？ 

2. If the incident response team determined that the initial compromise had been performed through a wireless network card in the internal host, how would the team further investigate this activity?  
インシデント対応チームが、最初の侵害が内部ホストのワイヤレスネットワークカードを介して行われたと判断した場合、チームはこの活動をどのようにしてさらに調査しますか? 

3. If the incident response team determined that the internal host was being used to stage sensitive files from other hosts within the enterprise, how would the team further investigate this activity?  
インシデント対応チームが、内部ホストが企業内の他のホストからの機密ファイルのステージングに使用されていると判断した場合、チームはどのようにしてこの活動をさらに調査しますか?