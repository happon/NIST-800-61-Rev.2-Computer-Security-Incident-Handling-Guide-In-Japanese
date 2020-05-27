### Scenario 1: Domain Name System (DNS) Server Denial of Service (DoS) 
### シナリオ１：ドメインネームシステム(DNS)サーバのDoS(サービス拒否) 

On a Saturday afternoon, external users start having problems accessing the organization’s public websites.  
土曜日の午後、外部のユーザーが組織の公開ウェブサイトにアクセスする際に問題が発生します。

Over the next hour, the problem worsens to the point where nearly every access attempt fails.  
その後1時間ほどで問題は悪化し、ほぼすべてのアクセスが失敗するまでになりました。 

Meanwhile, a member of the organization’s networking staff responds to alerts from an Internet border router and determines that the organization’s Internet bandwidth is being consumed by an unusually large volume of User Datagram Protocol (UDP) packets to and from both the organization’s public DNS servers.  
一方、組織のネットワーキング担当者の一人がインターネットとの境界ルーターからの警告に応答し、組織のインターネット帯域幅が、組織のパブリックDNSサーバーとの間のユーザー・データグラム・プロトコル(UDP)パケットの異常に大量のパケットによって消費されていると判断しました。 

Analysis of the traffic shows that the DNS servers are receiving high volumes of requests from a single external IP address.  
トラフィックを分析すると、DNSサーバーは1つの外部IPアドレスから大量のリクエストを受信していることがわかります。

Also, all the DNS requests from that address come from the same source port.  
また、そのアドレスからのDNSリクエストはすべて同じソースポートから来ています。 

<br/>

The following are additional questions for this scenario: 
このシナリオに関する追加の質問は以下の通りです。


1. Whom should the organization contact regarding the external IP address in question?  
問題の外部IPアドレスに関して、組織は誰に連絡すべきか? 

2. Suppose that after the initial containment measures were put in place, the network administrators detected that nine internal hosts were also attempting the same unusual requests to the DNS server.  
初期の封じ込め対策を実施した後、ネットワーク管理者が、9 台の内部ホストが DNS サーバーに同じ異常な要求を試みていることを検出したとします。  
How would that affect the handling of this incident?  
そのことは、このインシデントの処理にどのような影響を与えますか?  


3. Suppose that two of the nine internal hosts disconnected from the network before their system owners were identified. How would the system owners be identified?  
9台の内部ホストのうち2台が、システムの所有者が特定される前にネットワークから切断されたとします。システム所有者はどのようにして特定されますか? 
