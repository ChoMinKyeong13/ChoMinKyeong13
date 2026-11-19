<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Cho%20MinKyeong&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=Equipment%20Control%20%C2%B7%20Embedded%20Software%20Developer&descAlignY=58&descSize=18&animation=fadeIn" width="100%">

<img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=600&size=20&duration=3000&pause=900&color=2C5364&center=true&vCenter=true&width=620&lines=%EC%84%BC%EC%84%9C%EC%97%90%EC%84%9C+%EB%AA%A8%ED%84%B0%EA%B9%8C%EC%A7%80%2C+%EC%9E%A5%EB%B9%84%EA%B0%80+%EC%9B%80%EC%A7%81%EC%9D%B4%EB%8A%94+%EC%BD%94%EB%93%9C%EB%A5%BC+%EC%94%81%EB%8B%88%EB%8B%A4;MCU+%E2%86%94+PC+%E2%86%94+DB%2C+%EC%A0%9C%EC%96%B4+%EA%B3%84%EC%B8%B5%EC%9D%84+%EC%9E%87%EB%8A%94+%EA%B0%9C%EB%B0%9C%EC%9E%90;C+%C2%B7+C%2B%2B+%C2%B7+C%23+%C2%B7+Arduino+%C2%B7+MATLAB%2FSimulink" alt="typing">

<br>

<a href="https://github.com/ChoMinKyeong13"><img src="https://komarev.com/ghpvc/?username=ChoMinKyeong13&label=VISITORS&color=2c5364&style=for-the-badge" alt="visitors"></a>
<img src="https://img.shields.io/github/followers/ChoMinKyeong13?label=FOLLOWERS&style=for-the-badge&color=203a43&logo=github" alt="followers">
<img src="https://img.shields.io/badge/OPEN_TO_WORK-장비제어_·_임베디드-5fd4e8?style=for-the-badge&labelColor=0f2027" alt="open to work">

</div>

<br>

## 👋 About Me

<table>
<tr>
<td width="33%" valign="top">

**🎯 지향**

장비 제어 · 임베디드 / 펌웨어 개발자.
하드웨어가 **실제로 안전하게 움직이는** 소프트웨어를 만들고 싶습니다.

</td>
<td width="33%" valign="top">

**🔧 해 온 것**

센서 → MCU → 시리얼 → PC 앱 → DB로 이어지는 **제어 계층 전체**를 직접 연결해 봤습니다.
서보 · 모터 · 긴급정지 · 히스테리시스 · 논블로킹 루프.

</td>
<td width="33%" valign="top">

**🌱 지금**

공주대 미래자동차공학과 4학년
머신비전 기반 AI 첨단제조 **제어SW 개발과정** 수강 중
정보처리기사

</td>
</tr>
</table>

<br>

## 🛠 Tech Stack

<div align="center">

| 분야 | 스택 |
|:---:|:---|
| **Languages** | <img src="https://skillicons.dev/icons?i=c,cpp,cs,py" height="40"> |
| **Embedded · Control** | <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,matlab" height="40"> |
| **Desktop · DB** | <img src="https://skillicons.dev/icons?i=dotnet,mysql" height="40"> &nbsp; ![WinForms](https://img.shields.io/badge/WinForms-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![MFC](https://img.shields.io/badge/MFC-5C2D91?style=flat-square) ![SFML](https://img.shields.io/badge/SFML-8CC445?style=flat-square&logo=sfml&logoColor=white) ![NAudio](https://img.shields.io/badge/NAudio-FF5500?style=flat-square) |
| **Tools** | <img src="https://skillicons.dev/icons?i=visualstudio,git,github" height="40"> |
| **Interfaces** | ![UART](https://img.shields.io/badge/UART_Serial-F97316?style=flat-square) ![PWM](https://img.shields.io/badge/PWM_Servo%2FDC-0EA5E9?style=flat-square) ![REST](https://img.shields.io/badge/REST_API-1E90FF?style=flat-square) |

</div>

<br>

## ✨ Featured

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/ChoMinKyeong13/CrazyArcade-SFML"><img src="https://raw.githubusercontent.com/ChoMinKyeong13/CrazyArcade-SFML/main/docs/images/gameplay.gif" width="100%"></a>
<br><b>CrazyArcade-SFML</b>
<br><sub>C++ · SFML · 5인 팀 부팀장 — 타일 이동 + 보간 렌더링, 콜백 기반 모듈 분리</sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/ChoMinKyeong13/DJing"><img src="https://raw.githubusercontent.com/ChoMinKyeong13/DJing/main/docs/images/dj_deck.gif" width="100%"></a>
<br><b>DJing</b>
<br><sub>C# · MySQL — DB 설계 · SQL 전담, 6테이블 ERD · 상관 서브쿼리</sub>
</td>
</tr>
</table>

<br>

## 🎓 Graduation Research

### EV6 구동계 모델링 및 노면 예측 기반 슬립 방지 토크 제어
<sub>공주대학교 미래자동차공학과 졸업논문 · MATLAB / Simulink</sub>

전기차 구동계와 차량 종방향 동역학을 모델링하고, **노면 마찰을 실시간으로 추정**해
바퀴 미끄러짐이 커지면 **모터 토크를 줄여 헛돎을 막는** 제어기를 설계 · 검증했습니다.

```mermaid
flowchart LR
    D["운전자 토크 요구<br>1800 Nm"] --> C
    subgraph CTRL["슬립 방지 제어기"]
      E["노면 마찰 추정<br>Dry · Wet · Ice 분류"] --> C["목표 슬립 추종<br>토크 저감"]
    end
    C -- "토크 지령" --> M["EV6 구동계<br>350 Nm × 10.65 × η0.95"]
    M --> V["차량 종방향 동역학<br>1985 kg · r 0.359 m"]
    V -- "휠 속도 · 차속 → 슬립" --> E
```

**시나리오** — 같은 가속 요구로 `건조(μ 0.9) → 0~4 s` · `젖은 노면(μ 0.5) → 4~7 s` · `빙판(μ 0.2) → 7~12 s` 를 주행

<br>

#### 📊 결과 요약 (EV6 제원 기반 모델)

| 항목 | 제어 없음 | 슬립 제어 | 비고 |
|---|:---:|:---:|---|
| **빙판 구간 최대 슬립** | 0.783 | **0.139** | **약 82% 감소** |
| 최종 차속 (12 s) | 27.30 m/s | **27.66 m/s** | 헛돌지 않아 오히려 더 빠름 |
| 모터 출력 제한(168 kW) 적용 시 최대 슬립 | 0.458 | **0.139** | 제어 없으면 출력 한계에 포화 |
| 모터 출력 제한 적용 시 최대 출력 | 168 kW (포화) | **129 kW** | 불필요한 출력 낭비 감소 |

| 강건성 검증 | 조건 | 빙판 최대 슬립 범위 |
|---|---|:---:|
| 9-case | 질량 ±5% × 타이어 반경 ±3% | 0.128 ~ 0.150 |
| 27-case | 질량 × 반경 × 빙판 마찰계수(0.18~0.22) | 0.094 ~ 0.177 |
| 구현 일치성 | Simulink 모델 vs MATLAB RK4(0.002 s) 독립 구현 | 두 결과 곡선 일치 |

<br>

<table>
<tr>
<td width="50%"><img src="assets/thesis/Fig1_speed_slip.png"><br><sub><b>차속 · 슬립</b> — 빙판 진입(7 s) 후 제어 없음은 슬립 0.8까지 발산, 제어 시 0.15 부근 유지 (기준 모델)</sub></td>
<td width="50%"><img src="assets/thesis/Fig2_torque_force.png"><br><sub><b>휠 토크 · 타이어 구동력</b> — 토크를 1800 → 약 1230 Nm로 낮췄는데도 구동력은 오히려 더 큼</sub></td>
</tr>
<tr>
<td><img src="assets/thesis/Fig3_road_estimate.png"><br><sub><b>노면 추정 · 분류</b> — 마찰계수 변화를 추정해 Dry → Wet → Ice로 분류</sub></td>
<td><img src="assets/thesis/Fig7_adaptive_control_comparison.png"><br><sub><b>고정 목표 vs 노면 적응 목표</b> — 노면에 맞춰 목표 슬립을 바꾸면 빙판 슬립이 더 낮게 유지</sub></td>
</tr>
<tr>
<td><img src="assets/thesis/Fig11_power_limited_control.png"><br><sub><b>모터 출력 제한 모델</b> — 제어 없음은 168 kW 한계에 붙고 슬립 0.46, 제어 시 0.14</sub></td>
<td><img src="assets/thesis/Fig13_robustness.png"><br><sub><b>27-case 파라미터 민감도</b> — 질량 · 반경 · 마찰계수가 달라도 빙판 슬립 0.18 이하</sub></td>
</tr>
<tr>
<td colspan="2" align="center"><img src="assets/thesis/Fig14_MATLAB_Simulink_comparison.png" width="60%"><br><sub><b>Simulink vs MATLAB RK4</b> — 같은 방정식을 두 방식으로 구현해 모델 구현 오류가 없는지 교차 확인</sub></td>
</tr>
</table>

> ⚠️ 모든 결과는 EV6 공개 제원을 바탕으로 한 **시뮬레이션 값**이며 실차 측정 데이터가 아닙니다.
> 타이어 모델 · 출력 한계는 가정값을 사용했고, 그래서 파라미터를 흔들어 보는 강건성 검증을 함께 수행했습니다.

<br>

## 📂 Projects

### ⚙️ 제어 · 임베디드

| 프로젝트 | 설명 | 핵심 | 기술 | 형태 |
|---|---|---|---|:---:|
| [**Moble-2nd-Team-Project**](https://github.com/smlee11-hash/Moble-2nd-Team-Project) | 스마트 컨베이어 AI 품질검사 · 자동 분류 라인 | **불량분류 컨베이어** 서보 · 모터 · 센서 · 긴급정지 제어, MFC 담당 | Arduino · C++ · MFC | 팀 6인 |
| [**SmartHouseControl**](https://github.com/ChoMinKyeong13/SmartHouseControl) | 날씨를 읽고 스스로 지붕을 닫는 스마트홈 모형 | MCU/PC 제어 계층 분리 · `millis()` 논블로킹 · 히스테리시스 · 시리얼 프레이밍 | Arduino · C# · Open-Meteo | 개인 |

### 🖥 데스크톱 · 데이터베이스

| 프로젝트 | 설명 | 핵심 | 기술 | 형태 |
|---|---|---|---|:---:|
| [**DJing**](https://github.com/ChoMinKyeong13/DJing) | SoundCloud 스타일 음악 공유 + 2덱 DJ 믹서 | **DB 설계 · SQL 전담** — ERD, 상관 서브쿼리 + `EXISTS`, 좋아요 집계 전략, UNIQUE 제약 버그 해결 ([팀 저장소](https://github.com/dragon1894-lab/moble2)) | C# · MySQL · NAudio | 팀 |
| [**Kiosk**](https://github.com/ChoMinKyeong13/Kiosk) | 회원 인증 → 장바구니 → 카드/포인트 결제 키오스크 | 화면/데이터(Store) 분리 · `Tag` 바인딩 · `DialogResult` 흐름 제어 | C# WinForms | 개인 |

### 🎮 게임 · 그래픽스

| 프로젝트 | 설명 | 핵심 | 기술 | 형태 |
|---|---|---|---|:---:|
| [**CrazyArcade-SFML**](https://github.com/ChoMinKyeong13/CrazyArcade-SFML) | 2인용 물풍선 대전 게임 | **부팀장 · 플레이어 파트** — 타일 이동 보간, 상자 밀기, 동시 입력, HSV 팔레트 교체 | C++17 · SFML 3 | 팀 5인 |
| [**WMgame**](https://github.com/ChoMinKyeong13/WMgame) | 수박게임 클론 | 물리 엔진 없이 중력 · 원 충돌 반복 해소 · 합체 판정 직접 구현 | C# · GDI+ | 개인 |

<br>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=ChoMinKyeong13&theme=nord&no-frame=true&no-bg=true&margin-w=6&column=7" width="95%">

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=ChoMinKyeong13&show_icons=true&include_all_commits=true&bg_color=0f2027&title_color=5fd4e8&text_color=e2e8f0&icon_color=5fd4e8&hide_border=true&border_radius=12" height="170">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChoMinKyeong13&layout=compact&langs_count=8&bg_color=0f2027&title_color=5fd4e8&text_color=e2e8f0&icon_color=5fd4e8&hide_border=true&border_radius=12" height="170">

<img src="https://streak-stats.demolab.com?user=ChoMinKyeong13&background=0f2027&ring=5fd4e8&fire=f97316&currStreakLabel=5fd4e8&sideLabels=e2e8f0&currStreakNum=ffffff&sideNums=ffffff&dates=94a3b8&stroke=203a43&hide_border=true&border_radius=12" width="70%">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChoMinKyeong13&bg_color=0f2027&color=e2e8f0&line=5fd4e8&point=f97316&area=true&area_color=5fd4e8&hide_border=true&radius=12" width="100%">

</div>

<br>

## 🧭 Education & Certificates

| 기간 | 내용 |
|---|---|
| ~ 2027.02 (졸업 예정) | **공주대학교 미래자동차공학과** · 졸업논문: EV6 구동계 모델링 및 노면 예측 슬립 방지 토크 제어 |
| 2026.06 ~ 2027.01 | **모블 · 융합_머신비전을 활용한 AI 기반 첨단제조 분야 제어SW 개발과정** · 1차 팀 프로젝트 DJing, 2차 팀 프로젝트 스마트 컨베이어 라인 |
| 자격 | **정보처리기사** |

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=110&section=footer" width="100%">

</div>
