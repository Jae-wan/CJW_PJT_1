
<h2> MBTI 너랑콜 프로젝트 / CJW_Project_1 </h2>
<br>

> <b> 프로젝트 명 : MBTI 너랑콜 <br> </b>
> 프로젝트 설명 : MBTI 성향을 가지고 내가 궁금했던 MBTI 성향을 파악할 수도 있고, 따듯한 대화도 할 수 있는 외롭고 심심한 감성 젖는 밤을 달래주는 앱

> <b> 개발 환경 : Android Studio </b>
> * minSdk : 26
> targetSdk : 31

> * <b> 요구사항 정의서 (초안) </b>  <br>
> <table>
  <tr>
    <td><img alt="" src="https://user-images.githubusercontent.com/57258381/166427342-b400f909-fa50-4522-bce3-656d89a55ed6.png" height="700" width="1000"> </td>
  </tr>
</table>




---



(22.05.03)
이전에 간단한 프로젝트를 시작했을때는 조금 더 체계적으로 하고싶은 마음에 욕심이 커져서 잘 모르더라도 요구사항정의서, ERD, Design (feat.Figma) 까지 했었는데 혼자서 많은것을 하려다보니 막상 앱 구현보다는 기획에만 의존하는 경우가 많아져버려서 구현에 조금 더 신경쓰고자 기획적인 부분보다 구현 부분에 조금 더 신경을 쓰고자 이번에는 요구사항 정의서를 최대한 정확하게 만들고, 간단한 MVP 모델부터 만들어보려고 한다.


(22.05.04)
https://huiung.tistory.com/160
https://duckssi.tistory.com/42
https://velog.io/@k906506/Error-android.content.pm.ApplicationInfo-android.content.Context.getApplicationInfo-on-a-null-object-reference
https://dtuto.com/questions/822/failed-to-open-qemu-pipe-qemud-network-invalid-argument
https://copycoding.tistory.com/352?category=1013954
https://doitddo.tistory.com/88
https://material.io/components/bottom-navigation/android#theming-a-bottom-navigation-bar

(22.05.18)
> Bottom Navigation - Fragment - Navigation Host 연결 완료

* 주로 참고한 사이트
https://kumgo1d.tistory.com/73

* 참고하면 좋을 것 같은 사이트
https://youngest-programming.tistory.com/274
https://codechacha.com/ko/android-navigation-basic/

전화 기능을 어떻게 구현하면 좋을 것인가?
https://greensky0026.tistory.com/207
https://developer.android.com/guide/topics/connectivity/telecom/selfManaged?hl=ko

(22.05.22)
텔레콤 프레임워크 (전화)
https://developer.android.com/guide/topics/connectivity/telecom?hl=ko

RemonCall을 이용한 단순 통화 앱 만들기(Android) 초안
https://devguide.remotemonster.com/drafts/drafts/inside-remoncall-sdk/remoncall
https://devguide.remotemonster.com/drafts/drafts/simplevideocall-code-android

* InCallService : 대부분의 스펙이 구현되어있고, 구현된 항목을 선언하고 요청만 해 주면 구현할 수 있다.

* ConnectionService : VOIP개발에 더 적합함.
GSM 통화를 개발하기 위해 각종 편의사항이 제공되는 InCallService와는 다르게,
  연결을 직접 받아 등록하고 통화의 시작, 종료까지 모두 구현 해 주어야 함.
  그래서 VOIP 구현에는 Open Source 라이브러리를 주로 사용함. (카톡 보이스톡도 그렇다.)
  
youtube 및 구글링을 통해 나오는 다양한 Calling App 구현을 일단 따라해보기로 결정.


