### 3.1.1 Preparing to Handle Incidents 
### 3.1.1 インシデントハンドリングの準備

The lists below provide examples of tools and resources available that may be of value during incident handling.  
以下のリストは、インシデントハンドリング中に価値があると思われる利用可能なツールとリソースの例を提供しています。 

These lists are intended to be a starting point for discussions about which tools and resources an organization’s incident handlers need.  
これらのリストは、組織のインシデント・ハンドラーがどのようなツールやリソースを必要としているかを議論するための出発点となることを意図しています。 

For example, smartphones are one way to have resilient emergency communication and coordination mechanisms.  
例えば、スマートフォンは、回復力のある緊急通信と調整メカニズムを持つための一つの方法です。 

An organization should have multiple (separate and different) communication and coordination mechanisms in case of failure of one mechanism.  
組織は、1つのメカニズムが故障した場合に備えて、複数の（別々の、異なる）通信および調整メカニズムを持つべきです。 

#### Incident Handler Communications and Facilities:  
#### インシデントハンドラーの通信と設備について  

■ **Contact information** for team members and others within and outside the organization (primary and backup contacts), such as law enforcement and other incident response teams;  
■ チームメンバー、および法執行機関やその他のインシデント対応チームなど、組織内外のその他の人（プライマリーコンタクトおよびバックアップコンタクト）の**連絡先情報**

information may include phone numbers, email addresses, public encryption keys (in accordance with the encryption software described below), and instructions for verifying the contact’s identity  
電話番号、電子メールアドレス、公開暗号化キー（以下に説明する暗号化ソフトウェアに準拠）、および連絡先の身元を確認するための指示などが含まれます。 


■ **On-call information** for other teams within the organization, including escalation information  
エスカレーション情報を含む組織内の他チームの**オンコール情報**

■ **Incident reporting mechanisms,** such as phone numbers, email addresses, online forms, and secure instant messaging systems that users can use to report suspected incidents; at least one mechanism should permit people to report incidents anonymously   
■ 電話番号、電子メールアドレス、オンラインフォーム、ユーザーが疑わしいインシデントを報告するために使用できる安全なインスタントメッセージングシステムなどの**インシデント報告メカニズム**。

■ **Issue tracking system** for tracking incident information, status, etc.  
インシデント情報やステータスなどを追跡するための、**問題追跡システム**

■ **Smartphones** to be carried by team members for off-hour support and onsite communications  
■ 時間外のサポートや現場でのコミュニケーションのために、チームメンバーが携帯する**スマートフォン**

■ **Encryption software** to be used for communications among team members, within the organization and with external parties; for Federal agencies, software must use a FIPS-validated encryption algorithm  
■ **暗号化ソフトウェア**は、チームメンバー間、組織内、および外部の関係者との通信に使用されるもので、連邦政府機関の場合、ソフトウェアはFIPS140-2認証済みの暗号化アルゴリズムを使用する必要があります。

■ **War room** for central communication and coordination; if a permanent war room is not necessary or practical, the team should create a procedure for procuring a temporary war room when needed  
■ 連絡調整のための**作戦室**。常設の作戦室が必要ない場合や現実的でない場合は、チームは必要に応じて一時的な戦闘室を調達するための手順を作成すべきです。 

■ **Secure storage facility** for securing  
■ evidence and other sensitive materials  
証拠品などの機密性の高いものを確保するための**安全な保管手段**  

#### Incident Analysis Hardware and Software:  
#### インシデント分析のハードウェアとソフトウェア

■ **Digital forensic workstations21 and/or backup** devices to create disk images, preserve log files, and save other relevant incident data  
■ ディスクイメージを作成し、ログファイルを保存し、その他の関連するインシデントデータを保存するための**デジタル・フォレンジック・ ワークステーション※１ および/またはバックアップ装置**  
※１ A digital forensic workstation is specially designed to assist incident handlers in acquiring and analyzing data.These workstations typically contain a set of removable hard drives that can be used for evidence storage. 
デジタル・フォレンジック・ワークステーションは、インシデント・ハンドラーがデータを取得して分析するのを支援するために特別に設計されています。これらのワークステーションには、通常、証拠保管に使用できるリムーバブルハードドライブのセットが含まれています。  

■ **Laptops** for activities such as analyzing data, sniffing packets, and writing reports  
■ データ分析、パケットの盗聴、レポート作成などの活動に使用する**ノートパソコン**

■ **Spare workstations, servers, and networking equipment,** or the virtualized equivalents, which may be used for many purposes, such as restoring backups and trying out malware  
■ **ワークステーション、サーバ、ネットワーク機器**、または仮想化されたものをスペアとして、バックアップの復元やマルウェアの試用など、様々な目的で使用することができます。 

■ **Blank removable media**  
■ **空のリムーバブルディスク**

■ **Portable printer** to print copies of log files and other evidence from non-networked systems  
■ ネットワークに接続されていないシステムからログファイルなどの証拠品のコピーを印刷するための**携帯型プリンタ**

■ **Packet sniffers and protocol analyzers** to capture and analyze network traffic  
■ ネットワークトラフィックをキャプチャして分析するための**パケットスニファーとプロトコルアナライザ**

■ **Digital forensic software** to analyze disk images  
■ ディスクイメージを解析する**デジタルフォレンジックソフトウェア**

■ **Removable media** with trusted versions of programs to be used to gather evidence from systems  
■ 信頼のおけるバージョンのプログラムを入れておき、システムから証拠を集める際に使用する**リムーバブルメディア**

■ **Evidence gathering accessories,** including hard-bound notebooks, digital cameras, audio recorders, chain of custody forms, evidence storage bags and tags, and evidence tape, to preserve evidence for possible legal actions  
■ **証拠収集アクセサリー**：法的行動の可能性に備えて証拠を残しておくための、堅表紙のノート、デジタルカメラ、オーディオレコーダ、証拠・記録の保管フォーム、証拠保管バッグとタグ、証拠テープなど。

#### Incident Analysis Resources:  
#### インシデント分析リソース

■ **Port lists,** including commonly used ports and Trojan horse ports  
■ 一般に使用されるポートとトロイの木馬のポートの**ポートリスト**

■ **Documentation** for OSs, applications, protocols, and intrusion detection and antivirus products  
■ OS、アプリケーション、プロトコル、侵入検知とアンチウイルスシグネチャなどの**ドキュメント**

■ **Network diagrams and lists of critical assets**, such as database servers  
■ **ネットワーク図と重要な資産の一覧**  
例）データベースサーバー

■ Current baselines of expected network, system, and application activity  
■ 期待されるネットワーク、システム、アプリケーションの活動の現在の**基準**  

■ Cryptographic hashes of critical files22 to speed incident analysis, verification, and eradication  
■ インシデントの分析、検証、および撲滅を迅速に行うための重要ファイルの**暗号化ハッシュ**

#### Incident Mitigation Software:  
#### インシデント軽減ソフトウェア  

■ Access to images of clean OS and application installations for restoration and recovery purposes  
復元やリカバリーのためのクリーンなOSやアプリケーションのインストールイメージへのアクセス

<br/>

Many incident response teams create a jump kit, which is a portable case that contains materials that may be needed during an investigation.  
多くのインシデント対応チームは、調査中に必要となる可能性のある資材が入った携帯用ケースであるジャンプキットを作成しています。

The jump kit should be ready to go at all times.   
ジャンプキットは、いつでも持ち運べるようにしておく必要があります。

Jump kits contain many of the same items listed in the bulleted lists above. 
ジャンプキットには、上記の箇条書きのリストに記載されているものと同じものが多く含まれています。

For example, each jump kit typically includes a laptop, loaded with appropriate software (e.g., packet sniffers, digital forensics).  
例えば、各ジャンプキットには通常、適切なソフトウェア（例：パケットスニッファー、デジタルフォレンジック）を搭載したノートパソコンが含まれています。 

Other important materials include backup devices, blank media, and basic networking equipment and cables.  
その他の重要な材料には、バックアップデバイス、ブランクメディア、および基本的なネットワーク機器とケーブルが含まれています。

Because the purpose of having a jump kit is to facilitate faster responses, the team should avoid borrowing items from the jump kit.  
ジャンプキットを持つ目的は、迅速な対応を容易にすることですので、チームはジャンプキットからのアイテムの借用を避けるべきです。 

<br/>

Each incident handler should have access to at least two computing devices (e.g., laptops).  
各インシデント担当者は、少なくとも2台のコンピューティングデバイス（ノートパソコンなど）にアクセスできるようにしておくべきです。

One, such as the one from the jump kit, should be used to perform packet sniffing, malware analysis, and all other actions that risk contaminating the laptop that performs them.  
1台は、ジャンプキットからのものなど、パケットスニッフィング、マルウェア解析、およびそれらを実行するノートパソコンを汚染する危険性のあるその他のすべてのアクションを実行するために使用してください。 

This laptop should be scrubbed and all software reinstalled before it is used for another incident.  
このノートパソコンは、別のインシデントに使用する前に、スクラブし、すべてのソフトウェアを再インストールする必要があります。 

Note that because this laptop is special purpose, it is likely to use software other than the standard enterprise tools and configurations, and whenever possible the incident handlers should be allowed to specify basic technical requirements for these specialpurpose investigative laptops.  
このノートパソコンは特別な目的のため、標準的なエンタープライズツールや設定以外のソフトウェアを使用する可能性が高いことに注意してください。 

In addition to an investigative laptop, each incident handler should also have a standard laptop, smart phone, or other computing device for writing reports, reading email, and performing other duties unrelated to the hands-on incident analysis.  
調査用ノートパソコンに加えて、各インシデントハンドラーは、報告書を書いたり、電子メールを読んだり、実地でのインシデント分析とは無関係の他の業務を行ったりするために、標準的なノートパソコン、スマートフォン、または他のコンピューティングデバイスを持っているべきです。 

<br/>

Exercises involving simulated incidents can also be very useful for preparing staff for incident handling; see NIST SP 800-84 for more information on exercises23 and Appendix A for sample exercise scenarios.  
模擬インシデントを含む演習も、インシデントハンドリングのためのスタッフの準備に非常に有用です。