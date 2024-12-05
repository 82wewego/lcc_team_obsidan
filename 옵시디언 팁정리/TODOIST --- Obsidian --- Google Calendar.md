


---



#### Todoist


Tasks 관리 일정을 등록할 때, 빠르게, 어디서든 가능해야한다.  
  
Todoist의 처리 과정은 아래와 같다.  
  
할 일이 메일함에 들어오 듯이, 할일 또는 일정들을 inbox라는 곳에 등록한다.  
  
이 곳에 할일을 쌓아두고, 메모를 생성하듯이 관리할 수 있다. 또한, Gmail에서 Todoist로 바로 할일을 만들어주는 플러그인도 존재한다.  
  
Todoist에 존재하는 Project 개념을 통해서 inbox에 담긴 할일 및 일정들을 본인이 수행하는 목적에 맞게 사전에 분류해둔 대로 넣어두고 이를 관리하는 것이 가능하다.  
  
추가로, Deadline, 우선순위, 레이블, Description을 할일에 작성하는 것이 가능하다.  
  
알람과 Location도 설정할 수 있지만 이는 유료이다.  
  
Task에 SubTask를 만들어서 계층적으로 Tasks를 관리하는 것이 가능하다.  
  
Todoist의 **일정 처리 프로세스** 자체가 좋아 보이고, 프로젝트와 레이블을 색으로 구분할 수 있어서 개밌어 보였다.  
  
가장 중요한 점은, **Google Calender 간의 연동성인데, 양방향 연동이 잘 되고, UI도 깔끔**해서 마음에 들었다.


---


##### Todoist를 위한 통합을 설정할 경우, API 토큰을 입력해야 합니다. 방법:

1. [https://todoist.com](https://app.todoist.com/app/)에서 웹 앱을 통해 Todoist 계정에 로그인하세요.
2. 좌측 상단에 **당신의 아바타**를 클릭하세요.
3. **설정**을 선택하세요.
4. 좌측에 **통합**을 선택하세요.
5. **개발자** 탭을 선택하세요.
6. **클립보드에 복사**를 클릭하여 API 토큰을 받으세요.

![api-token-developer.png](https://res.cloudinary.com/imagist/image/fetch/q_auto,f_auto,c_scale,w_2624/https%3A%2F%2Fget.todoist.help%2Fhc%2Farticle_attachments%2F17075602779292)



---

#### 아이젠하워 매트릭스

![etc-image-0](https://blog.kakaocdn.net/dn/nDjYq/btsA3RfIvDI/VqlkIXpkg377KJIUx5ovi1/img.png)

https://medium.com/nextunicorn/%EC%8A%A4%ED%83%80%ED%8A%B8%EC%97%85-%EB%8C%80%ED%91%9C%EC%97%90%EA%B2%8C-%EA%B0%80%EC%9E%A5-%ED%95%84%EC%9A%94%ED%95%9C-%EC%9D%98%EC%82%AC%EA%B2%B0%EC%A0%95-%EB%8F%84%EA%B5%AC-%EC%95%84%EC%9D%B4%EC%A0%A0%ED%95%98%EC%9B%8C-%EB%A7%A4%ED%8A%B8%EB%A6%AD%EC%8A%A4-f7eb3a8c7148

해당 동영상에서 접할 수 있었던, Tasks 관리법이다.  
중요성과 긴급성을 기준으로 4분위로 나누어서 일정을 관리하는 방식이다.  
  
PARA처럼 좋은 체계화법임을 확인할 수 있었고, 실제 적용은 하지 않는 방향으로 결정했다.  
  
나중에 회사에 들어가서는 이 방식을 사용해서 일정을 체계적으로 관리해보면 될 것 같다.

---

### Obsidian과의 연동성

Custom frames 플러그인을 통해서 웹사이트를 Obsidian에서 접속 가능하게 만들 수 있다.  
따라서, Todoist와 Google Calender 자체를 연동 시켜두는 것이 가능하다.  
  
다만, 웹 페이지에 직접 들어가서 설정하는 것은 의미가 없다.  
  
Todoist 관련 플러그인을 통해서 **Obsidian과 Todoist 간의 앙방향 동기화**가 가능하도록 설정할 수 있다.

- Todoist Plugin
- Ultimate Todoist Sync

'Todoist Plugin'을 사용해서 Todoist의 할 일들을 동기화 해서, 이를 대시보드 형태로 가지고 올 수 있다.

`Ultimate Todoist Sync` 을 사용해서 Obsidian의 Task를 생성하면 Todoist에 이를 연결해준다.

todoist 태그가 붙은 Task에 한에서, Todoist로 넘어간다. Todoist에 넘어간 할일의 Description에 해당 .md 파일이 포함되고, 이를 열면 로컬 Obsidian이 열린다.  
  
이를 통해서, **Obsidian & Todoist & Google Calender를 동기화하여 할일 및 일정 관리 환경을 세팅**할 수 있음을 확인했다.

---

## # 세팅 시작

순서는 다음과 같다.

1. Todoist 가입 및 세팅
2. Todoist & Google Calender 연동
3. Obsidian Custom Frame
4. Todoist & Obisdian 연동

목표는 다음과 같다.

**일정 생성 및 관리**

- Desktop: Todoist, Obisidian
- Mobile: Google Calender & Todoist

**일정 확인**

- Desktop: Obsidian
- Mobile: Google Calender & Todoist

**Todoist에 일정을 생성하면, Obsidian과 Google Calender에 동기화**를 시킨다.  
또한, **Obsidian에서 Todoist 일정을 생성**한다. 위 동기화 설정이 끝나면 Google Calender에도 동기화됨  
  
모바일에서는 Obsidian을 구글 드라이브 Vault를 걸 수 없어서, **일정에 대한 관리는 Todoist, 캘린더로 관리하는 것 Google Calender를 사용**한다.  
  
데스크탑은 Obsidian으로 모든 관리가 가능하고, Custom Frame을 사용해서 웹 브라우저 없이 옵시디언에서 모든 처리를 수행하는 것이 가능하다.

> **Obsidian -- Todoist -- Google Calender**  
> 구조로 동기화를 수행하면 된다.

---

### 1. Todoist 가입 및 세팅

![Pasted image 20231128022649.png](https://blog.kakaocdn.net/dn/ehaLMo/btsA4dpiyje/mzajzyhMKfNkIwvY0gXPWK/img.png)

Google로 소셜 SignUp을 수행

![Pasted image 20231128022724.png](https://blog.kakaocdn.net/dn/vp6EE/btsA2ZyjxPS/Rkbqf0AES5EvnRvbFQGBzk/img.png)

가입 1단계

![Pasted image 20231128022754.png](https://blog.kakaocdn.net/dn/dVTCoR/btsA3RUld9r/BuYKHWmm4TYwsTaoUf1nr0/img.png)

가입 2단계

![Pasted image 20231128022911.png](https://blog.kakaocdn.net/dn/bFqZnX/btsAYIjANYl/69qAPJD1l07zco9kGXWW0k/img.png)

기본 환경 - 영어로 설정한 상태

- Inbox는 할일들을 쌓아놓는 창구
- Today는 오늘까지 수행할 작업
- Upcoming은 앞으로 남은 작업을 확인할 수 있다.

![Pasted image 20231128023047.png](https://blog.kakaocdn.net/dn/bdUtgh/btsAZ74AGzf/PxYrgJIwK5tiuW1xySNEUK/img.png)

Upcoming

- Filter & Labels은 쿼리를 통한 필터링을 수행해서 원하는 작업들을 골라 볼 수 있는 기능을 제공한다.
- Assist를 통해서 AI 서비스를 제공하고 있고, Filter는 최대 3개, 레이블은 제한은 크게 없는 듯 하다.

---

#### **Project 생성**

프로젝트 단위로 일정들을 분류해서 관리가 가능하다.

  
Inbox에서 할일 관리를 수행하는 것이 아니라, **할일을 Project에 할당함으로써, 세부적으로 관리하는 것이 가능**하다.

![Pasted image 20231128023323.png](https://blog.kakaocdn.net/dn/eEsg0c/btsA7TKtv3x/NYYinz8lF9k5hXU8A5vlI0/img.png)

Dev&nbsp;프로젝트&nbsp;생성&nbsp;-&nbsp;색도&nbsp;붙일&nbsp;수&nbsp;있어서&nbsp;마음에&nbsp;든다.

Dev Project 생성 후 할일 생성해보면, # 을 통해서 텍스트로 붙일수도 있고, 아래 버튼을 통해서 Project를 선택하는 것이 가능하다.

![Pasted image 20231128023538.png](https://blog.kakaocdn.net/dn/deC4ob/btsA8sMDtYp/SHEKXKFiaMKMduKN0ehNQ1/img.png)

또한, 프로젝트 내에서 파티션처럼 하위 섹션을 구분하는 것이 가능하다. 제한이 몇개까지 될련지는 모르겠지만 굉장히 좋다.

![Pasted image 20231128023743.png](https://blog.kakaocdn.net/dn/clfZml/btsA4TK0l2F/YpWwnAe4uZSXX20QTmmu01/img.png)

Section 구분

---

### 2. Todoist & Google Calender 연동

이제 Todoist와 Google Calender와 동기화를 걸어보자.

![Pasted image 20231128024305.png](https://blog.kakaocdn.net/dn/cUl7As/btsA3Q83az0/czL4MphAJwWalIUBRhWKQK/img.png)

Todist의 환경설정 > 통합에서 Google Calender와의 연동 안내를 바로 볼 수 있다.

![Pasted image 20231128024351.png](https://blog.kakaocdn.net/dn/cx4UjT/btsA20qsKNj/2KJzd3E5EFbj05BTkkkaG0/img.png)

구글 로그인을 수행하면 바로 가져오는 것이 가능하다.

![Pasted image 20231128024445.png](https://blog.kakaocdn.net/dn/CYAs7/btsA4RsUvQ3/IFTIeP5rupnXwXOToIb710/img.png)

Google Calender와의 상세 연결

연동이 되고 나면, Google Calender와의 연결에 대한 상세 설정을 하게 된다.  
기존에 덮어씌워버리면 정신없을 것 같아, 그냥 새로운 캘린더로 설정하고 나머지를 설정했다.

---

#### Tip

Google Calender에서는 일정을 **이벤트와 할 일**로 관리하는데, 이는 시작 시간과 종료 시간의 유무에 따라 구분된다.

Todoist에서는 할일을 만들 때, 시작 시간은 설정할 수 있지만, 종료 시간을 설정하려면 구독권이 필요해서 이 점이 좀 아쉬웠다.

다만, **Todoist에서 시작 시간을 걸어두면 Google Calender에서 이를 한 시간으로 잡아서 이벤트에 할당**하기 때문에, 할 일과 이벤트를 구분해서 연동하는 것이 가능하다.

상세한 일정은 Google Calender에서 추가적으로 수정해주어야 한다.

![Pasted image 20231128030142.png](https://blog.kakaocdn.net/dn/cimoXp/btsA4TjZCnf/vC3GiqRvKmbkXJweu0mf80/img.png)

Todoist에서 Start 시간만 정했을 때

![Pasted image 20231128030321.png](https://blog.kakaocdn.net/dn/xyTnB/btsA7SLAVik/0feKO21gsSCPuyfwWNDbJK/img.png)

Google Calender에서 이벤트로 반영됨

또한, **Todoist에서 Start 시간을 넣었다가 제거해도 Google Calender의 할 일로 업데이트**되므로 사용하기 편리하다.

---

### 3. Obsidian Custom Frames 세팅

Custom Frames 플러그인은 **Obsidian 내에서 별도의 웹 페이지를 임베딩**할 수 있게 만들어준다.

별도의 브라우저 없이, Obsidian에서 모든 관리가 가능해진다고 보면 된다.

Todoist와 Google Calender 홈페이지를 등록해서 사용하자.

![Pasted image 20231128030922.png](https://blog.kakaocdn.net/dn/eFkIpe/btsAYIw8U2i/jxotfun7KmL29d97qL1yB1/img.png)

Custom Frames 설치&nbsp; 세팅

설치는 커뮤니티 플러그인에서 바로 수행이 가능하고, Add Frame을 눌러 내가 사용할 프레임을 하나씩 추가하면 된다.

추가 이후 **Obsidian 재시작을 해줘야지 설정 사항이 반영**된다.

![Pasted image 20231128031519.png](https://blog.kakaocdn.net/dn/baIZiZ/btsA0bsrpzX/9civNX1zYNy31U0E3KASY1/img.png)

아이콘도 설정할 수 있고, 이는 Lucide icons 페이지에서 검색해서 가지고오면 된다.

Ribbon 아이콘과 Open in Center는 추가해주는 것이 편하다.

![Pasted image 20231128032157.png](https://blog.kakaocdn.net/dn/u3e3Y/btsAYHyhXGp/cvhhLBdlLCHkYyruEhSuKK/img.png)

세팅 이후, 이렇게 옵시디언에서 사용이 가능해진다.

---

### 4. Todoist & Obsidian 연동

마지막으로 Todoist와 Obsidian을 연동해보자.

- Todoist Plugin
- Ultimate Todoist Sync

위의 두 가지 플러그인을 설치한다.

Todoist Plugin는 **Obsidian에서 캔버스로 TodoList Dash Board를 생성하기 위함**이고, Ultimate Todoist Sync는 **옵시디언에서 Todoist로 할일 생성**을 할 수 있기 위함이다.

설치 후, 이를 나누어서 세팅해본다.

![Pasted image 20231128032637.png](https://blog.kakaocdn.net/dn/ugGiL/btsA7TjqHJ1/CGlpNy2xcTCIJ4XDl0XWN1/img.png)

---

#### Todoist Plugin

![Pasted image 20231128032734.png](https://blog.kakaocdn.net/dn/dQn9Fz/btsAZ92sRip/USNa7VsVvGJcLrTua9t23K/img.png)

플러그인 소

Todoist 내의 프로젝트 또는 할일을 Obsidian으로 불러올 수 있는 플러그인이다.

Todoist에 생성하는 것 또한 가능하긴 한데, 별도의 모달 창에서 이를 수행해야 한다.

이 플러그인을 사용하기 위해서 Todoist의 API Token이 필요한데, 이를 가지고 오자.

![Pasted image 20231128032821.png](https://blog.kakaocdn.net/dn/DGevO/btsA7Mq54Ph/W7qlLji1LICEiYEL9KhDE0/img.png)

Todoist 환경설정 > 통합 > Developer

![Pasted image 20231128033002.png](https://blog.kakaocdn.net/dn/cftYRI/btsA7QUy5oR/B7I28C1sLJDOcA9fUKDmrk/img.png)

Todoist 플러그인 세팅

플러그인 소개 페이지에서 확인할 수 있는 예제를 살펴보면 아래와 같이 사용이 가능하다.

마크다운 코드블럭을 통해서 불러오기가 가능하고, 예시는 아래와 같다.

![Pasted image 20231128033556.png](https://blog.kakaocdn.net/dn/dbvGld/btsA30wSJih/5R8dlu1y1DcM0JJ1hITJq1/img.png)

옵시디언에 추가된 모습

````bash
```todoistname: Highest Priority & Datefilter: "today | overdue"sorting:    - date   - prioritygroup: true```
````

여기에서도 클릭을 통해서 할일을 관리하는 것이 가능하다.

  
group: true를 통해서 Todoist의 section 정보를 가지고 올 수 있다.

이제 이를 통해서 Custom DashBoard를 구성해보자.

1. 새 캔버스를 생성  
2. 전체 할일 대시보드 생성  
3. ~~완료 목록 대시보드 생성~~ - 완료 작업은 현재 불가능하다고 한다!  
4. 상세 할일 대시보드 생성

![Pasted image 20231128034802.png](https://blog.kakaocdn.net/dn/bmr4NK/btsA7AEiIXG/36TMGk5mNBDHCGIrPDW26k/img.png)

이렇게 대시보드를 통해서 Todoist 웹 UI가 아닌 옵시디언에서 별도로 확인이 가능하다.

 [필터

공통 질문과 답변을 찾아 당신의 팀과 Todoist를 이용하는 방법에 대해 알아보세요.

todoist.com](https://todoist.com/ko/help/articles/introduction-to-filters-V98wIH)

여기에서 todoist 필터링 기준을 확인할 수 있다.

---

#### Ultimate Todoist Sync

![Pasted image 20231128035007.png](https://blog.kakaocdn.net/dn/puY42/btsA3PI1EEN/1bERaQR7CHv0EZwqWPL8gk/img.png)

해당 플러그인에서 제공하는 기능이 아직 부족해 보이지만, 여러가지가 존재한다.

Obsidian에서 Todoist로 할일을 생성하고, 수정하고 하는 것들이 가능하다고 한다.

여기에서 사용할 기능은, Obsidian의 Task를 생성했을 때, 이를 Todoist에 반영하도록만 하면 된다.

![Pasted image 20231128035218.png](https://blog.kakaocdn.net/dn/cw5GKt/btsA7p3QZSJ/UK3NmLgaN1IuLc9H1myM8k/img.png)

설정은 마찬가지로 API Token이 필요하고, 주의할 점은 Full Vault Sync를 걸어버리면, Obsidian에 존재하는 모든 Tasks들이 Todoist에 넘어간다.

기본 값으로는 #todoist 태그를 Task에 붙임으로서 트리거가 되는 듯 하다.

자동 싱크 타임은 5분으로 설정되어 있다. 실제로 사용할 때는 옵시디언에서 할일들을 쭉 뽑고, 나중에 todoist에서 관리를 하면 된다고 생각해서 충분하다고 생각했다.

이를 테스트해보면,

![Pasted image 20231128035541.png](https://blog.kakaocdn.net/dn/cQ21GL/btsA3Rtgm3B/ckZMSA262JPb9RygRKhA51/img.png)

옵시디언에서 만든 Task가 todoist에 반영되었음을 알 수 있다. 만약, 옵시디언에서 해당 Task를 삭제하면 이 또한 반영된다!

추가로, Todoist의 Description에 해당 Task가 작성된 옵시디언 페이지 URI를 걸어준다. 클릭하면 옵시디언 소프트웨어가 열린다.  
이는 브라우저에선 리다이렉션이 동작하지만, Obsidian 내부에서는 동작하지 않는다.  
  
이제 모든 세팅은 끝났다.

---

## # 결론

이전에는 휴대폰에서 Timetree, PC 환경에선 Obsidian으로 따로 일정관리를 수행하고 있었다.

불편하고 동기화가 안되서, 이를 걷어내고 옵시디언을 기준으로 PC에서도 작업하고 모바일에서도 확인 및 관리가 가능하게 스마트한 일정 및 할일 관리를 수행하고 싶었다.

이를 위해서 Todoist & Google Calander 를 사용했다.

**Obsidian --- Todoist --- Google Calander**  
  
이렇게 A - B, B - C 구조로 최종적으로 A - C의 양방향 연동이 가능하다.

Todoist를 기준으로 이런 자동화된 일정 및 할일 관리 파이프라인이 구성되었다.

별도로 대시보드도 만들고 해서, 굉장히 마음에 든다. 옵시디언을 더 잘 활용하게 된 것 같아 뿌듯하다.

이런 과정을 매시업이라고 하는지 정확하게는 모르겠지만, 이렇게 연동성이 좋아서 사용자들에게 편리함을 제공할 수 있는 그런 서비스를 설계하고 개발하고 싶다는 생각을 하게된 경험이였다.

![Pasted image 20231128142417.png](https://blog.kakaocdn.net/dn/mOJRC/btsA4dbNqIw/ATWQsugSQWuknIs6NhM510/img.png)

현재는 이렇게 관리 중이다.