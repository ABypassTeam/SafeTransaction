*This project has reached the end. You should find another project to replace this project.*

# Safe Transaction

여러분의 거래를 안전하게 지켜드리는 Safe Transaction 브라우저 확장 프로그램입니다.  

표준 브라우저 확장을 따르도록 설계되어, 별도 프로그램 설치 없이 한국 산업 표준 암호화를 이용하여  
안전하게 아무 작업도 하지 않기 때문에 더욱 편리하게 사용할 수 있습니다. 물론 무슨 암호화인지는 모릅니다.  

이 확장 프로그램을 설치하면 전자 금융 사기 예방 서비스가 가능하기 때문에 **무조건 설치**해야 합니다.  
설치하고 싶지 않으세요? 그렇다면 대체 프로그램 설치 방법을 해당 사이트가 안내할 것입니다.  
대체 프로그램과 행복한 시간이 되시길 바랍니다.

> **경쟁 연구소로 부터 인정 받은 보안 기술**
> 
> ![Approved by competitor](https://user-images.githubusercontent.com/27724108/221333588-dcbc68ab-b003-45e4-a049-d459187b8bc2.png)

# 사용 전 확인하세요.
이 확장 프로그램이 사용하는 서버는 KT, SK, LG U+ 등 국내 ISP에서 제공하는 DNS 서버에서 차단되었습니다.
[한국인터넷진흥원의 DNS 간섭에 대해 조사하고 있습니다. #8](https://github.com/Baw-Appie/SafeTransaction/issues/8)  
![DNS 차단](https://github.com/Baw-Appie/SafeTransaction/assets/15670271/fce775d6-575d-4cb0-8df0-9f7fa1160f75)  
개발자는 정부의 차단 시도에 대해 유감을 표합니다.  

## 왜 차단되었을까요?
KISA는 Safe Transaction 확장 프로그램이 보안 프로그램을 우회하기 때문에 공공의 위협을 초래할 수 있다고 합니다.  

## 사실은 이렇습니다
KISA의 주장과는 다르게 Safe Transaction은 보안 프로그램을 우회하지 않습니다.  
아니 그렇다면 왜 이 확장 프로그램을 설치하면 보안 프로그램을 설치하라고 하지 않는 것일까요?  
Safe Transaction은 보안 프로그램보다 사용자 편의 중심의 보안 알고리즘을 사용한 
더 강력한 보안 프로그램으로 대체하기 때문입니다.  
**여러분의 보안은 기존과 동일, 혹은 그 이상으로 안전하게 유지됩니다.**

내 컴퓨터에 프로그램을 설치하면 해당 프로그램은 컴퓨터의 권한을 모두 가져가게 됩니다.  
하지만 Safe Transaction은 어떤가요? 브라우저 컨텍스트 안에서 격리되어 브라우저 밖을 빠져나올 수 없게 됩니다.  
누군가 보안 프로그램의 취약점을 활용하여 내 컴퓨터를 해킹하는 이상한 사태가 발생할 수는 있어도,
Safe Transaction의 취약점을 활용하여 해킹이 가능한 범위는 브라우저 탭, 그 이상은 불가합니다.

이러한 브라우저 격리 기술은 [WebKit](https://webkit.org), [Chromium](https://chromium.org), [Gecko](https://firefox-source-docs.mozilla.org/overview/gecko.html) 등을 통해 구현되어 [Apple](https://apple.com), [Google](https://google.com), [Microsoft](https://microsoft.com), [Mozilla](https://mozilla.org) 등
다양한 회사와 수 많은 자원 봉사자의 지원에 의하여 검증되었습니다.  
그렇지만 보안 프로그램이라고 주장하는 것은 대체 누가 그 보안을 검증하였나요?  
저는 모르겠습니다.

## 그래서 어떻게 할까요?
이 문제는 사실 개발자가 해결해야 할 문제입니다.  
하지만 이러한 차단을 우회한다 하더라도 다시 차단된다면 불법 사이트가 도메인 바꾸는 것 마냥 저도 도메인 수백개를 사서 사용해야 하게 될 것입니다.  
하지만 이 글을 보시고 계신 이용자님께서는 저에게 돈을 주지 않을 것을 알고 있습니다.  
그렇기에 사용자 분들에게 근본적인 문제 해결이 가능한 [DNS 변경]을 권장드립니다. 

위의 사유로 인하여 이 확장 프로그램을 사용하고자 한다면 네트워크의 DNS를 [Cloudflare DNS Resolver (1.1.1.1)](https://1.1.1.1) 또는 [Google Public DNS (8.8.8.8)](https://dns.google/) 등의 해외 서비스가 제공하는 DNS 서버로 변경하세요.  
차단된 주소는 다음과 같습니다:
 - astx2-emulator.appie.dev
 - ipinside-emulator.appie.dev

# 설치

Chrome: https://chrome.google.com/webstore/detail/safe-transaction/hlknngdmefboagppfcddkbnnphbhdngk  
Firefox: https://addons.mozilla.org/addon/safe-transaction  
Whale: https://store.whale.naver.com/detail/fennejhonlpdndgjkhpgojjlnfbcjakk

# 지원 현황

|         | 조회 | 거래(이체) | 비고                                                   |
| ------- | -- | ------ | ---------------------------------------------------- |
| 국민은행    | ✔️ | ✔️ | KB국민인증서 로그인 |
| 하나은행    | ✔️ | ✔️ | 하나인증서 로그인 |
| 신한은행    | ✔️ | ✔️ | 신한인증서 로그인 |
| 우리은행    | ❓  | ❓    | 확인 필요 |
| 농협은행    | ✔️ | ✔️ | 금융인증서 로그인 |
| 기업은행    | ✔️  | ✔️  | 금융인증서 로그인, 24.09.26 확인 |
| SC제일은행  | ✔️ | ❌ | 금융인증서 로그인, INISAFE CrossWeb EX 설치시 이체 가능 |
| 케이뱅크 기업 | ✔️  | ✔️ | 공동인증서 로그인, 25.05.22 케뱅비즈 전용 패치로 우회  |
| OK저축은행  | ✔️ | ❌ | 금융인증서 로그인, 이체 시도시 NOS 통신 오류 (NOS E2E 필요) / 24.09.26 확인 |
| 삼성증권[^삼성증권]    | ✔️ | ❌ | 클라우드 인증서 로그인, SignKorea NA Certification Tool Kit 설치 필요 |
[^삼성증권]: 클라우드 인증서 사용시 SignKorea NA Certification Tool Kit 설치가 되었음을 나타내는 Tampermonkey 스크립트로 로그인 가능함을 확인하였으나, 거래시 ASTx2의 E2E가 필요하여 거래 불가

# 기능 및 특징

 - 안전한 거래를 강력하게 지원합니다.
 - IP 안에 무엇이 있을지 생각해보신 적 있으세요? 아무것도 없답니다.
 - 온라인 보안을 해드립니다


# 외부 서버 이용 안내

이 확장 프로그램은 외부 서버를 이용합니다. 그러므로 인터넷 없이는 작동하지 않습니다.  
왜 개발자는 굳이 돈 주고 서버와 도메인을 구매한 뒤 외부 서버를 이용하도록 만들었을까요? 그 이유는 사용되는 암호화 알고리즘은 각 언어마다 사용 방법이 매우 다르며 기본 동작 마저 달라 구현을 옮기는 것이 쉽지 않기 때문입니다.  
Java 공화국, 대한민국인 만큼 구현에 사용한 암호화 PoC는 Kotlin JVM으로 작성되었으며 이러한 코드를 JavaScript로 다시 작성하는 것보다는, 암호화하는 서버를 만드는 것이 더욱 간단하고 쉬우며 개인 정보 유출에 더 큰 도움이 됩니다.  
하지만 걱정할 필요가 없습니다. 이 확장 프로그램은 여러분의 개인정보를 수집하지 않습니다. 개발자는 여러분의 개인 정보를 존중하며 이 확장 프로그램이 사용하는 외부 서버는 여러분의 개인 정보를 저장하지 않습니다.  
못 믿으시겠나요? 다시 생각해보세요. 이용자의 개인정보는 이미 공공재이므로 다른 곳에서 쉽게 구할 수 있는데 제가 뭐하러 수집을 하나요? 오히려 저장공간 낭비가 될 것입니다.

누군가는 저에게 그 정도 코드 옮기는 것은 그냥 AI로 '딸깍'하면 된다고 말하고는 합니다.  
하지만 AI는 BouncyCastle이 얼마나 강력한 라이브러리인지 알고나 있을까요?  
저는 BouncyCastle 없이 다시 구현하기가 두렵습니다.


# 외부 서버의 소스 코드

이 개발자는 굳이 외부 서버를 사용하면서 외부 서버의 소스 코드를 공개하지 않았습니다.  
왜일까요? 개발자의 입장에서 생각해봅시다. 이 확장 프로그램을 본 어떤 연구소는 이 확장 프로그램을 가만히 두지 않을 가능성이 높습니다. 그러므로 이 개발자는 나중에 이 확장 프로그램이 문제가 되었을 경우 도망가기 위하여 외부 서버를 공개하지 않았습니다. 개발자가 외부 서버를 닫아버리면 이 확장 프로그램은 고장나기 때문에 외부 서버는 킬 스위치의 역할을 할 수 있습니다.  
하지만 개발자가 소스 코드를 공개했다면 어떨까요? 개발자가 서버를 닫더라도 누군가 서버를 다시 만들면 그만입니다. 저는 도망가야하기 때문에 공개하지 않겠습니다. 물론 도망가면 병역 면탈 또는 탈영으로 잡혀갑니다. 감사합니다.


# 알고 있는 문제

## 1. 나는 MacOS 안쓰는데요?
보안 거래가 작동하면 그 사이트는 내가 macOS를 사용 중이라고 인식하여 이상한 파일을 던져주거나, 오작동하는 문제가 있을 수 있습니다.  
이는 대부분의 사이트가 Windows에는 합법인척 하는 키로깅<sup>[1]</sup>, 언제 터질지 모르는 커널 후킹 등 바이러스인지 뭔지 모를 괴랄한 짓을 하는 것에 비해 macOS는 간단한 짓만 하기 때문에 그런 것이니 참으시고 사용하세요.  

## 2. 설치 후 유해 사이트라고 뜸
경쟁 제품에서 Safe Transaction이 사용하는 도메인을 피싱 사이트로 지정하여 발생하는 문제입니다.  
왜 Safe Transaction과 경쟁 제품을 동시에 사용하시려고 하는지는 잘 모르겠지만, 해당 제품은 Safe Transaction를 보고 배가 아파서 정상 작동하지 못하도록 유해 사이트라는 거짓 작동을 하게 만든 것이 아닐까요?  
위에서도 한번 언급했지만, Safe Transaction은 여러분의 민감한 데이터를 훔치치지 않습니다. 귀찮아서 끄지 않은 Nginx에 로깅되는 데이터에는 Cloudflare의 IP만 찍힐 뿐입니다.  
저는 어떤 프로그램을 사용하는지는 사용하는 사람의 선택이니 어떤 것을 선택하도록 강요하지 않습니다. 그러므로 아래 몇 가지 해결 방법이 있습니다.  

### 해결 방법 1: Safe Transaction 삭제
키로깅 기능부터, 사용중인 PC 정보 수집, 사용자 핑거프린팅, 접속 사이트 감청<sup>[1: 대한민국 해석 기준으로는 아님]</sup> 등 세계 최고 기능이 한 번에 포함된 프로그램을 Safe Transaction를 대신하여 사용하는 방법입니다.  
수집을 동의하지 않으신거 같다고요? 걱정마세요. 경쟁사 개인정보 수집방침 깊숙한 곳에 숨겨져 있고, 따로 동의하라는 팝업을 띄우지도 않았거든요.<sup>[2]</sup>  

이 글을 보는 사람이 이 방법을 사용하실 분은 없을 것이라고 생각합니다만, 아무튼 Safe Transaction을 지우면 문제가 해결됩니다.  
(Safe Transaction은 경쟁 제품과 달리 삭제시 클릭 한번으로 제거됩니다)

### 해결 방법 2: 경쟁 제품 삭제
누군지도 모르는 개발자가 적어둔 개인정보 수집하지 않는다는 글을 믿으시는 분에게 추천하는 방법입니다.  
경쟁 제품을 삭제하면 해결됩니다. ([구라 제거기](https://teus.me/862?category=836336)를 활용하면 좋습니다)  

### 해결 방법 3: ECH 사용
경쟁 제품은 http에서는 Host 헤더를, https에서는 [SNI 필드를 체크하여 유해 사이트 여부](https://brunch.co.kr/@searphiel9/46)를 확인합니다.   
https에서 이러한 감청을 막기 위한 여러가지의 시도들이 있었고 그 중 한 가지 방법으로 ECH(Encrypted Client Hello, [관련 링크](https://blog.cloudflare.com/encrypted-client-hello/))를 사용하는 방법입니다.  
Firefox에서 DoH를 활성화 한 뒤, about:config 로 이동하여 ```network.dns.echconfig.enabled```를 ```true```로 변경하면 됩니다.  
대신 이 방법은 기본적으로 비활성화되어 있는 기능인 만큼 실험적이고 항상 잘 작동하진 않습니다.  

# 님만 모르는 문제

저는 착한 개발자이니 Safe Transaction을 사용함으로써 발생하는 모든 문제는 여러분에게 무상으로 제공하겠습니다. 사양하지 않으셔도 됩니다.  

<sub>[1] 대한민국 <a href="https://twitter.com/actualpolicy_kr/status/1095918718436048898">(유사) 유권해석 기준</a>으로 처음부터 단대단 암호화가 아닌 제3자가 디코딩 후 열람 할 수 있는 사항을 보는 것은 "감청"에 해당되지 않으므로, 키로거는 "감청" 이 아닙니다.</sub><br>
<sub>[2] 경쟁사 개발사인 모 연구소에서는 이런 프로그램을 PUP (Potentially Unwanted Program) 이라고 부르는 것 같아요.</sub>
