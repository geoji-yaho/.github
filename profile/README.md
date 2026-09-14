<div align="center">

<img src="https://raw.githubusercontent.com/geoji-yaho/.github/main/profile/assets/banner.png" alt="거지야호" width="100%">

<br>

[![데모](https://img.shields.io/badge/데모_보러가기-떼거지-2b2520?style=for-the-badge&labelColor=f5d95c)](https://geoji-yaho.github.io/geoji-web/)
[![대회](https://img.shields.io/badge/원티드_AI_Championship-2026-c4553f?style=for-the-badge&labelColor=2b2520)](https://www.wanted.co.kr/)
[![팀](https://img.shields.io/badge/팀원-5명-2a5c4a?style=for-the-badge&labelColor=2b2520)](#팀)

</div>

<br>

## 돈은 혼자 아끼면 괴롭고 같이 아끼면 게임이 됩니다

가계부는 사흘을 넘기기 어렵습니다. 혼자 쓰는 반성문이라 그렇습니다.

**떼거지**는 그 반성문을 공개 재판으로 바꿉니다. 배달 24,000원을 결제한 날, 그 지출은 조용히 기록되는 대신 친구들 앞에 피고인석으로 끌려 나옵니다. 친구들이 배심원이 되어 유죄와 무죄에 표를 던지고, AI 판사가 그 표 위에서 형량과 판결문을 씁니다. 유죄면 무지출 며칠이 선고됩니다.

절제를 혼자 견디는 일에서 같이 노는 일로 옮기는 것, 그게 이 서비스가 하려는 전부입니다.

<br>

<div align="center">
<img src="https://raw.githubusercontent.com/geoji-yaho/.github/main/profile/assets/preview.png" alt="떼거지 화면" width="100%">
</div>

<br>

## 이렇게 돌아갑니다

| | 단계 | 하는 일 |
|:---:|---|---|
| 1 | **자진 신고** | 쓴 돈을 직접 올립니다. 계좌 연동은 없습니다. 변명 한 줄을 붙일 수 있습니다 |
| 2 | **배심원 투표** | 같은 방 친구들이 유죄와 무죄에 투표합니다. 마감은 방장이 30분부터 12시간까지 정합니다 |
| 3 | **AI 판사 선고** | 표를 받아 형량과 판결문을 씁니다. 방의 강도에 따라 순한맛부터 지옥맛까지 말투가 바뀝니다 |
| 4 | **형 집행** | 유죄면 무지출 N일. 버티면 방어 금액이 쌓이고 거지력이 오릅니다 |

판결은 유죄, 무죄, 동의, 기각, 각하 다섯 가지이고 낙관 도장으로 찍힙니다. 참은 날은 재판 없이 바로 칭송받습니다.

<br>

## 저장소

<table>
<tr>
<td width="33%" valign="top">

### [geoji-web](https://github.com/geoji-yaho/geoji-web)

피고인이 서는 자리. 화면 열넷과 판결 연출, 카카오 로그인.

`React 19` `TypeScript` `Vite`
`TanStack Query` `Tailwind 4`

</td>
<td width="33%" valign="top">

### [geoji-server](https://github.com/geoji-yaho/geoji-server)

법원 서기. 방과 지출, 재판, 투표, 랭킹의 정본.

`Java` `Spring Boot` `JPA`
`Supabase Postgres` `OAuth2`

</td>
<td width="33%" valign="top">

### [geoji-agent](https://github.com/geoji-yaho/geoji-agent)

판사석. 표를 읽고 형량과 판결문, 짤을 정합니다.

`Python` `FastAPI` `LangGraph`
`Pydantic` `SQLAlchemy`

</td>
</tr>
</table>

<br>

## 팀

팀명 **거지야호**. 전원 재직자라 평일 저녁과 주말에 모입니다.

<table>
<tr>
<td align="center" width="20%">
<a href="https://github.com/leesoyuun"><img src="https://avatars.githubusercontent.com/u/51051548?v=4" width="90" style="border-radius:50%"></a><br>
<b>이소윤</b><br>
<sub>팀장, 프론트엔드</sub><br>
<a href="https://github.com/leesoyuun"><sub>@leesoyuun</sub></a>
</td>
<td align="center" width="20%">
<a href="https://github.com/chan9yu"><img src="https://avatars.githubusercontent.com/u/80776262?v=4" width="90" style="border-radius:50%"></a><br>
<b>여찬규</b><br>
<sub>프론트엔드</sub><br>
<a href="https://github.com/chan9yu"><sub>@chan9yu</sub></a>
</td>
<td align="center" width="20%">
<a href="https://github.com/gamgam330"><img src="https://avatars.githubusercontent.com/u/48207536?v=4" width="90" style="border-radius:50%"></a><br>
<b>규민</b><br>
<sub>백엔드, DB 설계</sub><br>
<a href="https://github.com/gamgam330"><sub>@gamgam330</sub></a>
</td>
<td align="center" width="20%">
<a href="https://github.com/mhjoon99"><img src="https://avatars.githubusercontent.com/u/70474860?v=4" width="90" style="border-radius:50%"></a><br>
<b>마혜준</b><br>
<sub>AI 에이전트, 로고</sub><br>
<a href="https://github.com/mhjoon99"><sub>@mhjoon99</sub></a>
</td>
<td align="center" width="20%">
<a href="https://github.com/imhyun132"><img src="https://avatars.githubusercontent.com/u/55345254?v=4" width="90" style="border-radius:50%"></a><br>
<b>김미현</b><br>
<sub>AI 에이전트, 짤 생성</sub><br>
<a href="https://github.com/imhyun132"><sub>@imhyun132</sub></a>
</td>
</tr>
</table>

<br>

## 일하는 방식

- **기준 문서가 하나입니다.** 화면과 동작의 정본은 팀 위키이고 각 저장소의 `docs/`는 그 요약입니다. 위키에 없는 기능은 만들지 않고, 미결정 값을 코드에 박아야 하면 먼저 묻습니다
- **에이전트 하네스를 씁니다.** 룰을 하나씩 소유한 리뷰어와 빌더, QA 에이전트를 두고 씁니다. 기계가 판정할 수 있는 규칙은 검사 스크립트로 내려 커밋과 CI에서 막습니다
- **게이트를 치우지 않습니다.** 타입 검사와 빌드, 린트, 포맷 검사를 전부 통과해야 커밋입니다. 통과시키려고 테스트를 건너뛰거나 룰을 끄지 않습니다
- **한국어로 씁니다.** 문서와 커밋 메시지, 리뷰가 한국어이고 코드 식별자만 영어입니다

<br>

## 일정

| 시기 | 무엇 |
|---|---|
| 8/31 | 팀 결성. 5인 |
| 9/2 | MVP 범위와 판결 구조 확정 |
| 9/6 | 디자인 파운데이션, 공통 컴포넌트 |
| 9/14 | 화면 열넷 API 연결, 카카오 로그인 |
| **9/20** | **제출 마감** |
| 9/21 ~ 10/5 | 예선 심사와 온라인 투표 |

<br>

<div align="center">
<sub>지출은 자진 신고입니다. 계좌 연동은 하지 않습니다.</sub>
</div>
