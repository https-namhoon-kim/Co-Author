## 조금 더 명확히 알아보는 Stream의 정의

### 1. Stream이란 무엇인가?

인지적 관점에서의 Stream이란?
- 강물 (Flow의 함정에 빠진 거 아닐까?)
- 절벽 투신론

#### 1.1. JVM에서 언급하는 Stream

#### 1.2. Reactive에서 언급하는 Stream

#### 1.3. Corotuines에서 언급하는 Stream

### 2. 좀 더 명확한 Cold / Hot의 구분

어떤 단어 혹은 Keyword에 대해서 일상생활에 빗대어 명세를 한다.
- 프로그래밍언어적 관점에서 해석했을 때, 인지적 관점에서 추론이 되어야하는 함.
- Keyword : 상호 약속된 단어 (=예약어)

- 왜 하필 Cold인가?
- 무엇이 차갑길래?
- 그렇다면 왜 또 하필 Hot인가?
- 무엇이 뜨겁길래?

인지적 관점에서 명확하게 차갑다. 혹은 뜨겁다. 라고 해석되어야하는 관념을 찾아야 함.


#### PoV (Point of View)
**1. 데이터가 어디서 만들어지는가?**
- 데이터가 어디서 소비되는 가의 관점
- 그리고 소비되지않은 데이터는 어떻게 되는가? 

**2. emit되는 타이밍. 데이터 방출되는 시점(Hot-Trigger)**

**3. 관계성 (1:1, 1:N N:M… )**

#### 2.1. Cold

구독자 등판하면 값을 줘용

없으면 안줘용

프로그래밍적으로 접근하는 것.

#### 2.1. Hot