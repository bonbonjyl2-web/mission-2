# BAS 캠페인 스토리보드 기획 문서

프로젝트명 : BAS (Berry Airy Skin) 브랜드 숏폼 광고

형식 :  9:16 세로형( 숏폼 플랫폼 타겟이 20~30대이므로 세로형 선택) / 총 10초 / 제품 광고

문서 목적  : 브랜드 아이덴티티 기반 숏폼 광고 제작 가이드 및 씬별 생성/편집 기준 정리


## 1. 브랜드 아이덴티티

* 브랜드명  
BAS (Berry Airy Skin)

* 타겟  
20~30대 / 갓생 / 시성비 / 가심비 중시 소비자

* 톤앤매너  
- 미니멀리즘(Minimalism) 중심
- 텍스트는 짧고 명확하게 사용
- 여백을 살린 깔끔한 레이아웃
- 자연 유래 성분을 연상시키는 차분한 얼씨(Earthy) 톤
- 현대적인 메탈릭 포인트를 더해 ‘과학적 비건’ 무드 강화
- 담백하지만 자신감 있는 태도
- 감성 과장보다 객관적이고 단정한 화법 사용
- 예: “어려 보이세요”가 아니라 “오늘 당신의 피부는 어제보다 탄탄합니다.”

* USP  
복잡한 스킨케어 레이어링 대신, 핵심 성분 하나로 멀티 케어가 가능한 ‘Layering-free’ 솔루션 제공


## 2. 캠페인 목표 / 핵심 메시지

* 캠페인 목표  
- 복잡한 루틴에 피로를 느끼는 타겟에게 BAS의 간결하고 효율적인 스킨케어 철학을 전달
- 짧은 시간 안에 브랜드명, 제품, 슬로건을 명확히 인지시키기
- 제품 중심의 미니멀한 비주얼로 신뢰감과 프리미엄 무드 형성

* 핵심 메시지  
“Berry Efficient (베리 에피션트) 0.1%의 과학”

* 전달 가치  
- 누구에게: 바쁜 20~30대, 효율을 중시하는 소비자
- 어떤 가치: 하나로 충분한 멀티 케어, 덜어낼수록 선명해지는 루틴

* 서사 구조  
기승전결 구조
- 기: 복잡한 루틴의 피로
- 승: 불필요한 것을 비움
- 전: BAS 하나로 충분한 과학적 솔루션 제안
- 결: 브랜드 인지 + 슬로건 + CTA


## 3. 제작 원칙 및 고정 파라미터

* 전 컷 공통 스타일 블록  
minimalist product photography, earthy beige and sage green palette, brushed metallic accents, soft natural light, negative space, clean vegan aesthetic

* 전 컷 공통 고정 파라미터  
--ar 9:16 --seed 4270 --style raw

* 레퍼런스 / 제어 고정 설명  
- sref 고정: 첫 승인컷의 스타일 레퍼런스를 모든 컷에 동일 적용하여 색감, 질감, 조명 톤 일관성 유지
- seed 4270 고정: 제품 형태와 전체 무드 편차 최소화
- style raw 고정: 과도한 스타일 왜곡을 줄이고 제품 중심의 현실적 결과 확보
- 제품 일관성 유지: 제품 패키지 정면 이미지를 Image Reference 또는 ControlNet Reference로 활용하여 병 비율, 캡 형태, 라벨 위치가 컷마다 달라지지 않도록 관리
- 본 영상은 인물 중심이 아닌 제품 중심 광고이므로 캐릭터 reference보다 제품 reference 고정이 우선


## 4. 사용 도구 목록

* 이미지 생성  
- Flux Nano banana use ai
- 목적: 제품 연출 컷, 매크로 컷, 배경/무드 이미지 생성

* 스타일 일관성 유지  
- Image Reference / ControlNet
- 목적: 제품 및 톤앤매너 고정

* 이미지-비디오 변환  
- Runway / Kling 
- 목적: 줌인, 디졸브, 라이트 스윕, 슬로모션 구현

* 오디오 생성  
- Suno
- 목적: 로파이 미니멀 피아노 BGM 생성

* SFX  
- freesound 또는 직접 편집
- 목적: 복잡한 루틴의 잡음, 전환 효과음, 드롭 포인트 사운드

* 영상 편집  
- CapCut
- 목적: 컷 편집, 텍스트 오버레이, BGM/SFX 믹싱, 최종 출력

* 문서화  
- Google Docs 
- 목적: 스토리보드 정리 및 PDF 내보내기


#  씬 구성

## [씬 1]

씬 번호  
01

씬 길이  
0–2초

목표 메시지  
복잡한 스킨케어 루틴은 피로를 만든다.

화면 구성  
- 구도: 탑뷰(top view)
- 피사체: 화장품 병 7~8개가 어지럽게 쌓인 구성
- 배경: 베이지 톤 대리석
- 움직임: 카메라 미세 흔들림 + 슬로우 푸시인
- 텍스트 유무: 없음 (여백 유지)

내레이션(또는 화면 카피)  
“7단계 루틴, 진짜 필요한가요?”

사용 도구와 사용 목적  
- 이미지 생성: Midjourney/Flux
  → 어수선한 루틴의 문제 상황 시각화
- 비디오 생성: Runway/Pika/Kling
  → 미세 흔들림과 줌인 모션 추가
- 오디오/SFX
  → 여러 잡음이 겹치는 듯한 피로감 연출

입력 프롬프트(원문)  
cluttered skincare bottles, top view, slow push-in, beige marble surface, 7 to 8 cosmetic bottles scattered in a visually busy arrangement, soft natural light, slight camera shake, no text on screen, minimalist product photography, earthy beige and sage green palette, brushed metallic accents, soft natural light, negative space, clean vegan aesthetic --ar 9:16 --sref [첫 승인컷의 sref 코드] --seed 4270 --style raw

출력 결과 요약  
베이지 대리석 위 복잡하게 놓인 병들을 탑뷰로 보여주며 루틴 피로를 즉시 전달하는 오프닝 컷

생성 결과 파일명 또는 링크 표기  
BAS_SC01_IMG_v01.png  
BAS_SC01_MV_v01.mp4


## [씬 2]

씬 번호  
02

씬 길이  
2–4초

목표 메시지  
불필요한 단계를 덜어내면 핵심만 남는다.

화면 구성  
- 구도: 중앙 정렬
- 피사체: 기존 병들이 사라지고 BAS 세럼 1병만 남음
- 배경: 동일한 베이지 계열 공간, 더 정리된 화면
- 움직임: 디졸브 매치컷
- 텍스트 유무: 있음 / 하단 텍스트 “Layering-free.”

내레이션(또는 화면 카피)  
Layering-free.

사용 도구와 사용 목적  
- 이미지 생성
  → BAS 제품 중심 정면 컷 생성
- 비디오 생성
  → 병들이 사라지는 디졸브 전환 구현
- 오디오
  → BGM 시작, 정돈된 무드 전환

입력 프롬프트(원문)  
bottles fade away, single serum bottle remains centered, clean composition, balanced negative space, beige neutral background, minimal motion, elegant dissolve transition feeling, single vegan serum hero object, modern metallic cap, minimalist product photography, earthy beige and sage green palette, brushed metallic accents, soft natural light, negative space, clean vegan aesthetic --ar 9:16 --sref [첫 승인컷의 sref 코드] --seed 4270 --style raw

출력 결과 요약  
복잡함이 정리되고 BAS 세럼 하나만 남으며 ‘Layering-free’ 메시지가 선명해지는 전환 컷

생성 결과 파일명 또는 링크 표기  
BAS_SC02_IMG_v01.png  
BAS_SC02_MV_v01.mp4


## [씬 3]

씬 번호  
03

씬 길이  
4–7초

목표 메시지  
핵심 성분 0.1%의 과학으로 하나로 충분한 케어를 제안한다.

화면 구성  
- 구도: 매크로 클로즈업
- 피사체: 스포이드, 세럼 한 방울, 손등
- 배경: 흐린 뉴트럴 배경, 제품 메탈릭 포인트 강조
- 움직임: 슬로모션 드롭
- 텍스트 유무: 있음 / “0.1%” 숫자 페이드인

내레이션(또는 화면 카피)  
“핵심 성분 0.1%. 하나로 충분합니다.”

사용 도구와 사용 목적  
- 이미지 생성
  → 제품/스포이드/손등의 매크로 비주얼 생성
- 비디오 생성
  → 방울 낙하, 퍼짐, 광 반사 슬로모션 구현
- 오디오/SFX
  → 미세한 드롭 효과음으로 집중감 강화

입력 프롬프트(원문)  
macro shot, single serum drop falling on hand, slow motion, metallic dropper reflecting soft light, clean skin texture, scientific yet natural skincare mood, precise composition, 0.1 percent efficacy impression, premium vegan serum detail, minimalist product photography, earthy beige and sage green palette, brushed metallic accents, soft natural light, negative space, clean vegan aesthetic --ar 9:16 --sref [첫 승인컷의 sref 코드] --seed 4270 --style raw

출력 결과 요약  
세럼 한 방울의 집중감을 통해 ‘0.1%의 과학’과 멀티 케어 효율을 감각적으로 보여주는 핵심 컷

생성 결과 파일명 또는 링크 표기  
BAS_SC03_IMG_v01.png  
BAS_SC03_MV_v01.mp4


## [씬 4]

씬 번호  
04

씬 길이  
7–10초

목표 메시지  
BAS의 브랜드명, 슬로건, CTA를 명확하게 각인시킨다.

화면 구성  
- 구도: 정면 고정형 제품 히어로 샷
- 피사체: BAS 제품 1병 + 로고
- 배경: 세이지 그린 단색 배경
- 움직임: 카메라 고정, 빛만 은은하게 이동
- 텍스트 유무: 있음
  - 로고: BAS
  - 슬로건: Berry Efficient. 0.1%의 과학
  - CTA: @bas_official

내레이션(또는 화면 카피)  
“오늘 당신의 피부는 어제보다 탄탄합니다. BAS.”

사용 도구와 사용 목적  
- 이미지 생성
  → 브랜드 히어로 팩샷 제작
- 비디오 생성
  → 라이트 스윕으로 고급감 강화
- 오디오
  → BGM 페이드아웃으로 브랜드 엔딩 집중
- 편집 도구
  → 로고, 슬로건, CTA 삽입

입력 프롬프트(원문)  
static product hero shot, sage green background, subtle light sweep, front-facing serum bottle, premium minimalist layout, logo area reserved, clean vegan beauty campaign, modern metallic highlight, calm and confident branding finish, minimalist product photography, earthy beige and sage green palette, brushed metallic accents, soft natural light, negative space, clean vegan aesthetic --ar 9:16 --sref [첫 승인컷의 sref 코드] --seed 4270 --style raw

출력 결과 요약  
세이지 그린 배경 위 제품과 로고를 정면으로 제시해 브랜드 인지와 CTA를 마무리하는 엔딩 컷

생성 결과 파일명 또는 링크 표기  
BAS_SC04_IMG_v01.png  
BAS_SC04_MV_v01.mp4


# 오디오 구성 요약

* BGM  
- 스타일: 로파이 미니멀 피아노
- 도구: Suno
- 목적: 불필요한 감정 과잉 없이, 정제되고 효율적인 브랜드 인상 형성

* SFX  
- 씬 1: 겹치는 짧은 잡음 / 복잡함 표현
- 씬 2: 정적 한 박자 / 비움의 전환
- 씬 3: 드롭 포인트 강조 / 집중감 강화
- 씬 4: 잔향 최소화 / 브랜드 집중

* 나레이션 톤  
- 차분함
- 자신감
- 과장 없는 객관적 문장
- 예: “오늘 당신의 피부는 어제보다 탄탄합니다.”


# 파일명 규칙

권장 파일명 규칙  
BAS_[SCENE번호]_[타입]_[버전]

예시  
BAS_SC01_IMG_v01.png  
BAS_SC03_MV_v01.mp4  
BAS_BGM_v01.wav  
BAS_STORYBOARD_v01.pdf


# 최종 산출물 목록

1) 스토리보드 기획 문서 PDF  
- BAS_STORYBOARD_v01.pdf

2) 씬별 생성 소스  
- SC01 이미지 / 비디오
- SC02 이미지 / 비디오
- SC03 이미지 / 비디오
- SC04 이미지 / 비디오

3) 오디오 소스  
- BGM 1종
- SFX 묶음
- 나레이션 녹음본

4) 최종 편집본  
- 9:16 숏폼 광고 10초 완성본

---