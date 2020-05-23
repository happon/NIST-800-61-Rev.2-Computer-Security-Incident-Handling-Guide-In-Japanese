### 3.2.1 Attack Vectors
### 3.2.1 攻撃手法

Incidents can occur in countless ways, so it is infeasible to develop step-by-step instructions for handling every incident.  
インシデントは無数の方法で発生する可能性があるため、すべてのインシデントに対処するためのひとつひとつの手順書を作成することは不可能です。 

Organizations should be generally prepared to handle any incident but should focus on being prepared to handle incidents that use common attack vectors.  
組織は、一般的にどのようなインシデントにも対応できるように準備しておくべきですが、一般的な攻撃手法を使用するインシデントに対応できるように準備することに重点を置くべきです。 

Different types of incidents merit different response strategies.  
異なるタイプのインシデントには、異なる対応戦略が必要です。 

The attack vectors listed below are not intended to provide definitive classification for incidents;  
以下に挙げた攻撃手法は、インシデントの決定的な分類を提供することを意図したものではありません。 

rather, they simply list common methods of attack, which can be used as a basis for defining more specific handling procedures.  
むしろ、これらは単に一般的な攻撃方法を列挙したものであり、より具体的な対処方法を定義するための基礎として利用することができます。  


■ **External/Removable Media:**  
■ **外部／リムーバブルメディア**  
An attack executed from removable media or a peripheral device—for example, malicious code spreading onto a system from an infected USB flash drive.  
リムーバブルメディアや周辺機器（例えば、感染したUSBフラッシュドライブからシステムに拡散する悪意のあるコードなど）から実行される攻撃。 

■ **Attrition:**  
■ **消耗**  
An attack that employs brute force methods to compromise, degrade, or destroy systems, networks, or services (e.g., a DDoS intended to impair or deny access to a service or application;  a brute force attack against an authentication mechanism, such as passwords, CAPTCHAS, or digital signatures).  
システム、ネットワーク、またはサービスを危殆化、劣化、または破壊するために、ブルートフォースの手法を用いた攻撃 (例: サービスやアプリケーションへのアクセスを妨害または拒否することを目的とした DDoS、パスワード、CAPTCHAS、デジタル署名などの認証メカニズムに対するブルートフォース攻撃)。 


■ **Web:**  
■ **ウェブ**  
An attack executed from a website or web-based application—for example, a cross-site scripting attack used to steal credentials or a redirect to a site that exploits a browser vulnerability and installs malware.  
WebサイトやWebベースのアプリケーションから実行される攻撃。例えば、資格情報を盗むために使用されるクロスサイトスクリプティング攻撃や、ブラウザの脆弱性を突いてマルウェアをインストールするサイトへのリダイレクトなどが挙げられます。 

■ **Email:**  
■ **Eメール**  
An attack executed via an email message or attachment—for example, exploit code disguised as an attached document or a link to a malicious website in the body of an email message.  
メールメッセージや添付ファイルを介して実行される攻撃。例えば、添付文書を装ったエクスプロイトコードや、メールメッセージの本文にある悪意のあるウェブサイトへのリンクなどが挙げられます。

■ **Impersonation:**  
■ **なりすまし**  
An attack involving replacement of something benign with something malicious— for example, spoofing, man in the middle attacks, rogue wireless access points, and SQL injection attacks all involve impersonation.  
善良なものを悪意のあるものに置き換える攻撃。例えば、なりすまし、中間者攻撃、不正な無線アクセスポイント、SQLインジェクション攻撃などは、すべてなりすましを伴います。

■ **Improper Usage:**  
■ **不適切な使用**  
Any incident resulting from violation of an organization’s acceptable usage policies by an authorized user, excluding the above categories;  
認可されたユーザーによる組織の許容される利用ポリシーの違反に起因するすべてのインシデント（上記のカテゴリーを除く）。 

for example, a user installs file sharing software, leading to the loss of sensitive data; or a user performs illegal activities on a system.   
例えば、ユーザーがファイル共有ソフトウェアをインストールして機密データの損失を招いた場合、またはユーザーがシステム上で違法行為を行った場合。 

■ **Loss or Theft of Equipment:**  
■ **機器の紛失または盗難**  
The loss or theft of a computing device or media used by the organization, such as a laptop, smartphone, or authentication token.  
ノートパソコン、スマートフォン、認証トークンなど、組織が使用しているコンピューティングデバイスやメディアの紛失や盗難。

■ **Other:**  
■ **その他**  
An attack that does not fit into any of the other categories.  
上のどのカテゴリーにも当てはまらない攻撃。

<br/>

This section focuses on recommended practices for handling any type of incident.  
このセクションでは、あらゆるタイプのインシデントに対処するための推奨される実践方法に焦点を当てています。 

It is outside the scope of this publication to give specific advice based on the attack vectors;  
攻撃手法に基づいた具体的なアドバイスの提供は、この出版物の範囲外です。

such guidelines would be provided in separate publications addressing other incident handling topics, such as NIST SP 800-83 on malware incident prevention and handling.  
このようなガイドラインは、マルウェアのインシデント予防と処理に関するNIST SP 800-83のような、他のインシデント処理のトピックを扱う別の出版物で提供されます。