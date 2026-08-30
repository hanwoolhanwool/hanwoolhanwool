

<div align="center">

### 핵심 재미를 빠르게 구현하고 검증하며,<br/>유저가 다시 플레이할 이유를 만드는

**게임 클라이언트 개발자 이한울**입니다.

</div>

<br/>

- 직관적이고 **단순한 규칙에서 참신한 재미**가 만들어지는 게임을 설계합니다.
- **기획부터 개발, 아트까지 직접** 수행하며 아이디어를 플레이 가능한 게임으로 구현합니다.
- **협동 멀티플레이**, **생존·전투 루프 설계**, **안정적인 입력 시스템** 구현에 강점이 있습니다.
- 프로젝트 초기 설계부터 개발 계획, 구현, QA, 문서화, 출시까지 **전 과정을 체계적으로** 운영합니다.
- **SOLID 원칙과 객체지향 설계**를 일관되게 적용해 **확장성과 유지보수성**이 뛰어난 게임을 개발합니다.


<br/>

# 💪 강점

## 기획 · 아트 · 개발을 혼자 완주합니다

게임 하나가 굴러가려면 필요한 세 축을 **전부 직접** 만듭니다. 외주나 팀원을 기다려서 막히는 구간이 없습니다.

| | 직접 하는 일 | 확인할 수 있는 곳 |
|---|---|---|
| **기획** | 코어 루프 · 세계관 · 밸런스를 **기획서로 확정하고** 구현을 시작한다 | Train Survival 기획서 · 세계관 · 비주얼/UIUX · 오디오 · 아트 예산 [문서 6종](https://github.com/hanwoolhanwool/Train-Survival/tree/main/docs/design) |
| **아트** | Blender 와 생성형 3D 도구로 에셋을 직접 만들고 다듬어 **URP 에 얹는다** | [Mecha Survivor 리그 · 히어로 포즈 문서](https://github.com/hanwoolhanwool/Mecha-Survivor/tree/main/Docs) · Train Survival 열차 · 지형 아트 패스 |
| **개발** | 클라이언트 · 네트워크 · UI · 에디터 툴까지 **전부 직접 쓴다** | Train Survival 스크립트 308개 · Netcode 1~4인 멀티플레이 |

**Train Survival** 은 이 셋을 혼자 돌려 만들고 있는 프로젝트이고,
**카피바라 몸짱 만들기** 는 2인 팀에서 기획 · 개발 총괄과 아트를 맡아 **출시까지** 끌고 간 결과물입니다.

<br/>

## 맡은 역할에 최선을 다합니다

팀의 작업 흐름을 이해하고 담당 역할을 끝까지 책임감을 가지고 구현합니다.
지금까지 참여한 팀 프로젝트에서 역할 분담을 분명하게 하고, 맡은 역할은 **끝까지 구현하거나 막히면 대책을 마련해** 마무리했습니다.

| 프로젝트 | 맡은 일 | 확인할 수 있는 곳 |
|---|---|---|
| **카피바라 몸짱 만들기**<br/><sub>2인 · 2025.10 – 12</sub> | 기획 · 개발 총괄 · 리듬 판정 로직 · 리더보드 연동 · WebGL / AAB 빌드와 배포 · 출시 후 라이브 개선 | [케이스 문서](https://hanwoolhanwool.github.io/portfolio/capybara-portfolio.html) |
| **열받는 게임**<br/><sub>3인 · 2026.05 – 06</sub> | MediaPipe 손동작 **입력 파이프라인 5레이어 전 구간** · 플레이어 · 몬스터 · 보스 · 레벨 디자인 | [케이스 문서](https://hanwoolhanwool.github.io/portfolio/sam-i-bang-portfolio.html) |
| **Trophy Hunter : Wizard War**<br/><sub>4인 · 2025.10 – 11</sub> | **매칭 시스템** 설계 · 구현 · 룸 진행 · 방장 교체 · 이탈 복구 등 세션 흐름 · 기획 · QA 겸임 | [케이스 문서](https://hanwoolhanwool.github.io/portfolio/wizard-war-portfolio.html) |

**막히면 우회로를 만들어서라도 약속한 기능을 남깁니다.**

- **Wizard War** — 방장이 로딩 중 이탈하면 시작 판정을 내릴 주체가 사라져 전원이 로딩 화면에 갇혔습니다. 새 마스터가 판정을 승계하게 만들어 세션을 이어 붙였습니다.
- **열받는 게임** — 웹캠 인식은 흔들림 자체를 없앨 수 없어, 신뢰도 게이트로 나쁜 프레임을 버리고 필터로 남은 떨림을 눌러 **조작 가능한 입력만 게임에 넘겼습니다.**

<sub>담당이 아닌 영역과 팀원이 구현한 부분은 케이스 문서에 구분해 적어 두었습니다.</sub>

<br/>

## 혼자여도 팀처럼 굴립니다

1인 개발이라고 절차를 건너뛰지 않습니다. 기능 하나가 **초기 세팅 → 구현 계획 → 구현 · QA → 문서화** 를 순서대로 통과하고,
그 흔적이 전부 저장소에 남아 **결과물뿐 아니라 과정도 열어 볼 수 있습니다.**

| 단계 | 하는 일 | 남는 것 |
|---|---|---|
| **1 · 초기 세팅** | 어셈블리 계층 · 폴더 배치 · 코드 컨벤션 · 테스트 러너 · 커밋 규약을 **코드 한 줄 쓰기 전에** 고정한다 | [`docs/conventions`](https://github.com/hanwoolhanwool/Train-Survival/tree/main/docs/conventions) |
| **2 · 구현 계획** | 마일스톤을 기능 단위로 쪼개 **구현 계획서**를 먼저 쓴다 — 범위 · 순서 · 완료 조건을 문서에서 확정하고 시작한다 | [`docs/plans`](https://github.com/hanwoolhanwool/Train-Survival/tree/main/docs/plans) |
| **3 · 구현 · QA** | 구현과 함께 **플레이 검증 항목**을 만들어 직접 돌리고, 나온 문제는 후속 수정으로 계획서에 다시 적는다. 회귀는 **EditMode 테스트**가 막는다 | [플레이 검증 항목](https://github.com/hanwoolhanwool/Train-Survival/tree/main/docs/plans/M8) · [EditMode 753개](https://github.com/hanwoolhanwool/Train-Survival/tree/main/Assets/_Project/Tests) |
| **4 · 문서화** | 완성된 기능은 **as-built 명세**로 남겨, 다음 기능이 추측이 아니라 그 문서 위에서 시작하게 한다 | [`docs/specs`](https://github.com/hanwoolhanwool/Train-Survival/tree/main/docs/specs) |

<sub>같은 방식을 Idle Game 에도 적용해, Player 도메인 하나에 <a href="https://github.com/hanwoolhanwool/Idle-Game/tree/main/docs/specs/player">기술 명세 10편</a>이 남아 있습니다.</sub>

<br/>

# 🛠 Tech Stack

<p>
<img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white">
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white">
<img src="https://img.shields.io/badge/URP-2C2C2C?style=flat-square&logo=unity&logoColor=white">
<img src="https://img.shields.io/badge/Netcode_for_GameObjects-1B4B72?style=flat-square&logo=unity&logoColor=white">
<img src="https://img.shields.io/badge/Photon_PUN2-0B7AC7?style=flat-square&logoColor=white">
<img src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white">
<img src="https://img.shields.io/badge/Android_AAB-3DDC84?style=flat-square&logo=android&logoColor=white">
&nbsp;
<img src="https://img.shields.io/badge/Rider-000000?style=flat-square&logo=rider&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
&nbsp;
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white">
<img src="https://img.shields.io/badge/Codex-412991?style=flat-square&logoColor=white">
<img src="https://img.shields.io/badge/Meshy_AI-A855F7?style=flat-square&logoColor=white">
<img src="https://img.shields.io/badge/Tripo-14B8A6?style=flat-square&logoColor=white">
</p>

설계 · 최적화 &nbsp;—&nbsp; `FSM` `ScriptableObject` `Event Bus` `Service Locator` `Object Pooling` `Addressables` `async/await`

<br/>

# 🚀 Projects

## 진행 중 · 1인 개발

### 🚂 Train Survival

<img src="https://img.shields.io/badge/MAIN-D9402A?style=for-the-badge" alt="메인 프로젝트"> &nbsp; [🔗 저장소](https://github.com/hanwoolhanwool/Train-Survival)

<img width="500" alt="Train Survival 타이틀 화면" src="./assets/train.jpg" />

<br/>

**Overview** : 1~4인 협동 생존 크래프팅  
2026.07 – 진행중

<br/>

**역할**
- 기획 · 클라이언트 · 네트워크 · 아트 파이프라인 **전 구간 1인 담당**
- Netcode for GameObjects 기반 **1~4인 세션 · 소유권 · 상태 동기화** 설계
- 낮/밤 사이클과 지역 전환에 맞춘 **몬스터 웨이브 · 생존 자원 루프** 구현
- 스폰 · 이벤트 · 전역 접근을 **인프라 계층으로 분리** (PoolManager · EventBus · ServiceLocator)

**성과**
- 배경 FBX **27종에 Mesh LOD 3단** 적용 — 침엽수 `3,130 → 1,664 → 832 tris`, **원거리 73% 감소**를 임포터 플래그만으로 확보 (Blender 왕복·에셋 재제작 없음)
- 기관차 · 칸 모듈 · 차륜 · 선로 · 구조물 등 **정적 모델 10종도 LOD 3단** 생성 — 단계당 tris 절반
- 숲 팔레트 실측으로 예산 검증 — 타일당 오브젝트 **28.4개**(목표 30 이하 충족) · 타일당 **59,496 tris**, 프레임 합계 **~1.7M tris**로 타깃(2~4M) 내 유지
- 병목이 개수가 아니라 **개당 tris**임을 실측으로 특정 — 감축 에셋 세그먼트 39k vs 미감축 87k
- 스폰 · 소멸을 **PoolManager 경유로 통일**(27개 스크립트) — 런타임 `Instantiate`/`Destroy` 제거
- **EditMode 통과**로 최적화 후 회귀 차단

<br/>

### 🤖 Mecha Survivor

[🔗 저장소](https://github.com/hanwoolhanwool/Mecha-Survivor)

<img width="500" alt="Mecha Survivor 리그 실험실 툴 화면" src="./assets/mecha.jpg" />

<br/>

**Overview** : 3D 공중전 메카 뱀서라이크  
2026.07 – 진행중

<br/>

**역할**
- 뱀서라이크에서 **성장 구조만** 빌려오고 전투를 액션 슈터로 재설계
- **쿨다운 로테이션 무기 시스템** — A가 쿨다운에 들어가면 B·C로 압박을 잇는다
- Y축을 쓰는 **3D 공중 이동 · 수동 조준** 컨트롤
- Core · Systems · Gameplay · UI · Utilities **단방향 어셈블리** 구성

**성과**
- "손이 놀지 않게 한다"는 설계 목표를 쿨다운 로테이션이라는 장치로 구체화
- 무기 · 난이도 · 업그레이드를 문서로 분리 → 밸런스 수정 비용 절감

<br/>

### 💤 Idle Game

[🔗 저장소](https://github.com/hanwoolhanwool/Idle-Game)

<img width="500" alt="Idle Game 플레이 화면" src="./assets/idle.jpg" />

<br/>

**Overview** : 방치형 어드벤처  
2026.03 – 진행중

<br/>

**역할**
- Player 도메인을 **상태 머신 · 스탯 · 스킬 · 전투 · 입력 등 10개 시스템으로 분리**
- 기능마다 **설계 근거와 다이어그램을 기술 명세로 고정**
- 문서 폴더를 코드의 `Features/<도메인>` 구조와 그대로 미러링

**성과** — 분리한 구조가 실제로 돌려준 것
- 이동 입력을 `IMoveInputSource` 하나로 추상화해 **방치형 자동 전투와 조이스틱 수동 조작이 같은 경로로 흐릅니다** — `PlayerInputRouter` 가 모드만 갈아 끼우고, 상태 머신과 이동 코드는 입력이 어디서 오는지 모릅니다
- 스킬 · 상태 머신의 계약을 **`Contracts` 폴더로 격리**(`ISkillEffect` · `ICastGate` · `IDamageable` · `IPlayerState` …) → 새 스킬은 **기존 코드를 고치지 않고 구현체 추가만으로** 붙습니다
- 저장을 `ISaveRepository` · `ISaveable` · `ISaveMigration` 으로 나눠 **저장 위치와 세이브 포맷을 게임 코드에서 떼어냈습니다** — 실제로 `SaveMigration_V1ToV2` 로 **기존 세이브를 깨지 않고** 스키마를 올렸습니다
- 보상을 `IExpReceiver` · `IGoldReceiver` 로 받게 해, **적은 누가 보상을 받는지 모른 채** 처치 사실만 발행합니다
- 스탯 소비자에게는 `IReadOnlyStats` 만 노출해 **읽기와 쓰기 권한을 구조로 갈랐습니다**
- 문서 폴더를 코드 구조 그대로 미러링 — 스크립트 145개 · **기술 명세 11편**이 폴더와 1:1로 대응합니다

<br/>

## 출시 · 팀 프로젝트

### 🦫 카피바라 몸짱 만들기

[🔗 케이스 문서](https://hanwoolhanwool.github.io/portfolio/capybara-portfolio.html)

<img width="300" alt="카피바라 몸짱 만들기 캐릭터 도감 화면" src="./assets/capybara.jpg" />

<br/>

**Overview** : 토스 앱인에 출시한 WebGL 리듬 게임 — **인기 순위 87위**  
2인 팀 · 2025.10 – 12 · **2026.04.10 출시**

<br/>

**역할**
- **기획 · 개발 총괄**
- 리듬 **판정 로직**과 리더보드 연동
- WebGL 성능 최적화, **WebGL · AAB 빌드와 배포**
- 출시 후 유저 피드백 기반 **버그 · 밸런스 · 편의 기능 라이브 개선**

**성과**
- 초당 여러 개 생기고 사라지던 **노트 · 판정 파티클을 오브젝트 풀로 전환** — `Instantiate`/`Destroy` 반복이 만들던 **WebGL GC 프레임 튐 제거** (WebGL은 GC가 멈추면 곧바로 프레임이 튄다)
- 풀 반납에 **세대 토큰**을 걸어 이중 반납 차단, 정적 버퍼 재사용으로 갱신 경로의 할당 제거
- `Debug.Log` 전량을 **`GameLogger` + `Conditional` 스트립**으로 교체 — 릴리즈 빌드에서 로깅 비용 자체를 제거
- 리듬 판정을 시간이 아닌 **UI 좌표 겹침**으로 계산 — **프레임레이트가 흔들려도 화면에 보이는 것과 판정이 어긋나지 않음**
- 토스 앱인 **인기 순위 87위**

<br/>

### ✋ 열받는 게임

[🔗 케이스 문서](https://hanwoolhanwool.github.io/portfolio/sam-i-bang-portfolio.html)

<img width="500" alt="열받는 게임 플레이 화면" src="./assets/gesture.jpg" />

<br/>

**Overview** : 키보드 대신 웹캠 앞의 손동작으로 조작하는 3D 액션  
3인 팀 · 2026.05 – 06 · `Unity 6` · `MediaPipe`

<br/>

**역할**
- MediaPipe 추론이 게임 명령이 되기까지 **5레이어 입력 파이프라인 전 구간 설계**
- 워커 스레드 → 메인 스레드 **경계 처리** (ConcurrentQueue · 큐 상한 30 · 객체 풀링)
- **좌표 정제** (OneEuroFilter · 신뢰도 게이트 · handedness 안정화)
- 플레이어 · 몬스터 · 보스와 레벨 디자인

**성과**
- 손 데이터 객체 풀링으로 **프레임당 할당 제거**
- 큐 상한과 오래된 프레임 폐기로 **입력 지연 누적 차단**
- 룰 매칭과 시간 디바운스의 주기 분리로 **연산 낭비 제거**
- 종횡비 캐시 · 신뢰도 게이트 · OneEuroFilter로 **떨림과 반응 지연을 한 필터로 동시 해결**

<br/>

### 🧙 Trophy Hunter : Wizard War

[🔗 케이스 문서](https://hanwoolhanwool.github.io/portfolio/wizard-war-portfolio.html)

<img width="500" alt="Trophy Hunter : Wizard War 플레이 화면" src="./assets/wizard.jpg" />

<br/>

**Overview** : Photon PUN2 기반 1인칭 4인 마법 배틀  
4인 팀 · 2025.10 – 11 · `Unity` · `Photon PUN2`

<br/>

**역할**
- **매칭 시스템** 설계 · 구현
- **룸 진행 · 방장 교체 · 이탈 복구** 등 세션 흐름 처리
- 기획 + 클라이언트 + QA 겸임

**성과** — 끊기지 않는 세션을 만든 것들
- 매칭을 `JoinOrCreateRoom` 하나로 통일 — "매칭 중인 방이 있으면 참가, 없으면 생성"을 **서버가 원자적으로 판정**하게 해 **클라이언트 간 경합 자체를 제거**
- 버튼을 연속으로 눌러 방이 중복 생성되던 문제를 시작 · 취소 **코루틴 1초 래치**와 진입 조건으로 차단
- 준비 완료를 **룸 프로퍼티 단일 소스**에 기록 → 4인이 같은 값을 읽어 시작 판정이 갈리지 않습니다
- 방장이 로딩 중 나가면 시작 조건을 검사할 주체가 사라져 **전원이 로딩 화면에 갇히던 문제**를, `OnMasterClientSwitched` 에서 **새 마스터가 판정을 승계**하도록 해 해결
- 강제 종료 경로에서 생존자 수가 이중 감소하던 버그를, **로컬 삭제 없이 원격에만 통지하는 경로**를 따로 만들어 종료 시나리오에서 분리
- 커서 잠금이 UI가 닫히는 프레임과 어긋나 클릭이 월드로 새던 문제를 `WaitForEndOfFrame` 으로 정렬

<br/>

<sub>팀 프로젝트의 기여 수치는 저장소를 클론해 <code>git log --author</code> 와 <code>git blame --line-porcelain</code> 으로 직접 집계했고, 담당이 아닌 영역도 케이스 문서에 함께 적어 두었습니다.</sub>

<br/>

# 🏃 Career

- **[인턴십] 멋쟁이사자처럼 × 검은토끼흰토끼** — 게임 클라이언트 개발 · 2026.04 – 05
- **멋쟁이사자처럼 유니티 게임 개발 5기** · 2025.05 – 12
- **전북 글로벌게임센터 게임 콘텐츠 전문인력 양성과정 (UE5)** · 2024.07 – 08 — 🏆 우수상
- **원광대학교 게임콘텐츠학과** · 2019.03 – 2026.03 — 🏆 성적 우수 표창 (아너스 클럽)
- **유튜브 채널 운영** · 2022 — 기획 · 편집 · 업로드 전 과정, 누적 24만 조회

<br/>

# 📫 Contact

- **Portfolio** : [hanwoolhanwool.github.io/portfolio](https://hanwoolhanwool.github.io/portfolio/)
- **GitHub** : [github.com/hanwoolhanwool](https://github.com/hanwoolhanwool)

<sub>더 자세한 기여 수치와 문제 해결 기록은 포트폴리오 각 케이스 문서에 있습니다.</sub>
