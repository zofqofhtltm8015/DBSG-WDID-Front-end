# What did i do?




#  서비스 개요 
##  배경과 개발목표
---

    우리는 인터넷을 하루 평균 4시간 47분 정도 사용합니다.
특히 소프트웨어마이스터고등학교에 다니는 전 하루에 6, 7시간 정도 인터넷을 사용하는 거 같습니다.
<br><br>
주로 인터넷을 사용할때 웹 서비스를 사용하는 사람들의 비율이 가장 높았습니다.<br><br>
어느 날, 방문기록을 정리하려고 방문기록을 보니 쓸모없이 들어간 웹 사이트들이 너무 많았습니다. <br><br>
1분 - 10분 짜리 동영상들을 유튜브를 통해 하루에 3~4시간씩 보는 것을 보고 Facebook에도 하루에 1 - 2시간씩 쓰는 걸 보고 정말 충격먹었습니다.<br><br> 왜냐하면 유튜브나 페이스북을 얼마 사용하지 않았던 것 같은데 너무 많은 시간을 낭비했기 때문입니다. <br><br>
이 문제를 바탕으로 전 
 방문기록을 토대로 유튜브 사용시간, 페이스북 사용시간 등
   어느 시간대에 무엇을 했는지를 정리해주는 기능과 <br><br>
   사이트 이용 시간을 사용자가 직접 설정하고 설정한 시간 이상으로 시간이 초과된다면 그 웹사이트에 못들어가게 차단해주는 서비스를 만들 계획입니다.
   <br><br>




##  서비스 개념
---
고객 : Chrome엔진을 기반으로 만든 웹 브라우저 사용하는 모든 사람들

제공 가치 : 인터넷 사용시간을 알려주고 사용시간을 조정 및 차단할 수 있기에 일에 몰입하는데 도움을 줄 수 있음.
 기술구현 :  
	웹 프론트엔드 : HTML, CSS, JS, React, Axios
백엔드 : MS SQL, Node.js(Express)
다른 기술들 : Chrome History API
 제공 방법 : 웹(Web), 확장앱(네이버 웨일 한정)
 
다. 주요 타겟 고객
※ 이 서비스는 누가 쓸 것인가? 사용자에게 어떤 가치(혜택)를 줄 수 있는가?
Chrome 및 네이버 웨일을 쓰는 모든 사람들
 	웹 사이트 이용시간을 보고 동기부여 및 특정 사이트 시간 조절 및 차단 기능으로 인해 능률 향상
 

 
## 주요 서비스 내용 ※ (최대한 구체적으로 기술)
<br><br>
1) 주요 서비스 기능<br>
    ① 구글 계정으로 로그인 하면 그 계정으로 된 방문기록을 시계그림으로 요약해서 보여줌<br><br>
      ② 웹 사이트에 낭비한 총 시간을 옆에서 보여줌 (1일, 1주일, 1달)
      <br><br>
    ③ 특정 웹사이트에 대해 1일 또는 1주일 또는 1달을 기준으로 몇시간을 볼 것인지를 정함 만약 그 시간을 넘었다면 바로 차단됨. 하지만 원하는 시간을 선택해 
    10분씩 열어줌. (이 기능은 ON/OFF 가능)
    <br><br>
    ④ 또 다른 휴식시간 대를 정함. 이때 시간 조절한 웹사이트에 들어가도 시간 카운트가 되지 않음. 하지만 차단 되었다면 그 시간에도 얄짤없이 못봄(동기부여).
    <br><br>


    **밑 부턴 미구현**
2) 서비스 시나리오



2. 서비스 경쟁력/차별화 ※ (1~3페이지로 작성)
가. 경쟁(유사) 서비스 현황
※ (유사한 서비스 현황, 기존 시장 규모 및 확장 가능성)
 
나. 경쟁(유사) 서비스 대비 차별화 요소
※ 고객이 느끼는 타 서비스 대비 차별화 요소 (예시)
        - 기존 서비스 대비 고객의 시간을 줄여 준다.
        - 사용자 편의성을 획기적으로 개선 했다.(UI/UX 등)
        - 아주 편리하고 새로운 기술을 적용했다.
           (저작권/특허가 있는 경우 명기)
 
3. 개발 계획
가. 개발 팀 구성*
     *개발 팀은 4명으로 구성
     **개발시 역할(예 : 디자인, 기획, 임베디드 개발, 클라이언트 개발, 서버 개발 등)
 
나. 프로젝트 수행 방법
- 해당 과제 수행 일정
(제안한 팀원들이 어떻게 어떤 일정으로 서비스를 만들어 갈 것인지 설명)
