### 2.3.4.4 Other Outside Parties
### 2.3.4.4 その他の社外第三者団体（サードパーティー）

An organization may want to discuss incidents with other groups, including those listed below.  
組織は、以下に列挙されているグループを含む他のグループとインシデントについて話し合うことを希望する場合があります。  

When reaching out to these external parties, an organization may want to work through US-CERT or its ISAC, as a “trusted introducer” to broker the relationship.  
これらの外部関係者に連絡を取る場合、組織は、US-CERT またはその ISAC を通じて、関係を仲介する「信頼できる紹介者」として活動することを希望する場合があります。  

It is likely that others are experiencing similar issues, and the trusted introducer can ensure that any such patterns are identified and taken into consideration.  
他の組織も同様の問題を経験している可能性が高く、信頼された紹介者は、そのようなパターンが特定され、考慮に入れることができます。  

■ **Organization’s ISP.** An organization may need assistance from its ISP in blocking a major networkbased attack or tracing its origin.  
■ **組織の ISP**  組織は、主要なネットワークベースの攻撃をブロックしたり、その発生源を追跡したりする際に、その ISP からの支援を必要とする場合があります。   

■ **Owners of Attacking Addresses.** If attacks are originating from an external organization’s IP address space, incident handlers may want to talk to the designated security contacts for the organization to alert them to the activity or to ask them to collect evidence.  
■ **攻撃アドレスの所有者**  攻撃が外部組織のIPアドレス空間から発生している場合、インシデントハンドラーは、組織の指定されたセキュリ ティコンタクトに話をして、その活動に注意を喚起したり、証拠を収集するように依頼したりすることをお勧めします。  

It is highly recommended to coordinate such communications with US-CERT or an ISAC. 
US-CERT または ISACとの調整ようなコミュニケーションをすることを強く推奨します。  

■ **Software Vendors.** Incident handlers may want to speak to a software vendor about suspicious activity.  
■ **ソフトウェアベンダ**  インシデント・ハンドラーは、疑わしい活動についてソフトウェア・ベンダーと話をしたいと思う可能性があります。  

This contact could include questions regarding the significance of certain log entries or known false positives for certain intrusion detection signatures, where minimal information regarding the incident may need to be revealed.  
このコンタクトには、インシデントに関する最小限の情報を明らかにする必要がある場合には、特定のログエントリの重要性に関する質問や、特定の侵入検知シグネチャに対する既知の偽陽性に関する質問が含まれる可能性があります。  

More information may need to be provided in some cases—for example, if a server appears to have been compromised through an unknown software vulnerability.  
場合によっては、より多くの情報を提供する必要があるかもしれません。例えば、サーバが未知のソフトウェアの脆弱性によって侵害されたと思われる場合などです。   

Software vendors may also provide information on known threats (e.g., new attacks) to help organizations understand the current threat environment.
また、ソフトウェアベンダは、組織が現在の脅威環境を理解するのに役立つように、既知の脅威（例：新たな攻撃）に関する情報を提供する場合もあります。  

■ **Other Incident Response Teams.** An organization may experience an incident that is similar to ones handled by other teams; proactively sharing information can facilitate more effective and efficient incident handling (e.g., providing advance warning, increasing preparedness, developing situational awareness).  
■ **他のインシデント対応チーム**  情報を積極的に共有することで、より効果的かつ効率的なインシデント対応を促進することができます（例：事前警告の提供、準備態勢の強化、状況認識の向上）。  

Groups such as the Forum of Incident Response and Security Teams (FIRST), the Government Forum of Incident Response and Security Teams (GFIRST), and the Anti-Phishing Working Group (APWG) are not incident response teams, but they promote information sharing among incident response teams.  
FIRST（Forum of Incident Response and Security Teams）、GFIRST（Government Forum of Incident Response and Security Teams）、APWG（Anti-Phishing Working Group）などのグループは、インシデント対応チームではないが、インシデント対応チーム間の情報共有を推進しています。  

■ **Affected External Parties.** An incident may affect external parties directly—for example, an outside organization may contact the organization and claim that one of the organization’s users is attackin it.  
■ **影響を受ける外部関係者**  インシデントは、外部の関係者に直接影響を与えることがあります。例えば、外部の組織が組織に連絡を取り、組織のユーザーの1人が攻撃を受けていると主張することがあります。  

Another way in which external parties may be affected is if an attacker gains access to sensitive information regarding them, such as credit card information.  
外部関係者が影響を受けるもう一つの方法は、攻撃者がクレジットカード情報など、外部関係者に関する機密情報にアクセスできるようになった場合です。  

In some jurisdictions, organizations are required to notify all parties that are affected by such an incident.  
いくつかの管轄区域では、組織は、そのようなインシデントによって影響を受けるすべての当事者に通知することが要求されています。  

Regardless of the circumstances, it is preferable for the organization to notify affected external parties of an incident before the media or other external organizations do so.  
状況にかかわらず、組織は、メディアやその他の外部組織がインシデントを通知する前に、影響を受ける外部関係者にインシデントを通知することが望ましいです。  

Handlers should be careful to give out only appropriate information—the affected parties may request details about internal investigations that should not be revealed publicly.  
影響を受ける関係者は、公開されるべきではない内部調査の詳細を要求することがあります。  

OMB Memorandum M-07-16, Safeguarding Against and Responding to the Breach of Personally Identifiable Information, requires Federal agencies to develop and implement a breach notification policy for personally identifiable information (PII).  
OMB Memorandum M-07-16, Safeguarding Against and Responding to the Breach of Personally Identifiable Information (PII)は、連邦政府機関が個人を特定できる情報（PII）の侵害通知ポリシーを策定し、実施することを要求しています。  

Incident handlers should understand how their incident handling actions should differ when a PII breach is suspected to have occurred, such as notifying additional parties or notifying parties within a shorter timeframe.  
インシデント・ハンドラーは、PII 違反が発生したと疑われる場合、追加の当事者に通知したり、より短い時間枠内で当事者に通知したりするなど、インシデント処理の行動がどのように異なるべきかを理解すべきです。  

Specific recommendations for PII breach notification policies are presented in OMB Memorandum M-07-16.  
PII侵害通知ポリシーに関する具体的な推奨事項は、OMB Memorandum M-07-16に記載されています。  

Also, the National Conference of State Legislatures has a list of state security breach notification laws.  
また、National Conference of State Legislaturesには、州のセキュリティ侵害通知法のリストが掲載されています。  
