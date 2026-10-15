---
version: alpha
name: Botanica
description: 숲색과 연두, 풍부한 펄프 종이, 직각의 겹친 종잇장으로 만드는 식물 기록지 디자인. Fraunces 제목·숫자, Instrument Sans UI, JetBrains Mono 데이터.
colors:
  primary: '#163A2A'
  secondary: '#376347'
  tertiary: '#D6E8A4'
  neutral: '#F5F3E8'
  surface: '#E9EDDE'
  on-surface: '#163A2A'
  on-primary: '#F5F3E8'
  text-muted: '#5B695C'
  border: '#C4CCB8'
  error: '#A13D2D'
  forest-100: '#E3ECE5'
  forest-300: '#ACC5B2'
  forest-500: '#648F73'
  forest-700: '#376347'
  forest-900: '#163A2A'
  leaf-100: '#EDF2DF'
  leaf-300: '#CEDDA8'
  leaf-500: '#9AB66B'
  leaf-700: '#617F3B'
  leaf-900: '#344B25'
  sage-100: '#E9EDDE'
  sage-300: '#C4CCB8'
  sage-500: '#98A58B'
  sage-700: '#6B7C60'
  sage-900: '#3E5038'
  sprout-100: '#F0F5DA'
  sprout-300: '#D6E8A4'
  sprout-500: '#B5D36A'
  sprout-700: '#7B9A34'
  sprout-900: '#465F1E'
  paper-stock: '#F3F0E3'
  kraft: '#E4E0D0'
  on-kraft: '#17261A'
  kraft-muted: '#4A5A4D'
  rule-line: '#A8CBA7'
  mesh-line: rgba(62, 124, 66, 0.11)
  mesh-fine: rgba(62, 124, 66, 0.07)
  margin-line: rgba(176, 81, 57, 0.35)
typography:
  headline-display:
    fontFamily: Fraunces
    fontSize: 78px
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: -0.055em
  headline-lg:
    fontFamily: Fraunces
    fontSize: 42px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: -0.035em
  headline-md:
    fontFamily: Fraunces
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: -0.02em
  brand:
    fontFamily: Fraunces
    fontSize: 33px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.045em
  body-lg:
    fontFamily: Instrument Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Instrument Sans
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.8
  body-sm:
    fontFamily: Instrument Sans
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.8
  label-lg:
    fontFamily: Instrument Sans
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.6
  label-md:
    fontFamily: Instrument Sans
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: 0.16em
  caption:
    fontFamily: Instrument Sans
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0.05em
  numeral-lg:
    fontFamily: Fraunces
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -0.02em
  data:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
rounded:
  none: 0px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  section: 72px
  page-margin: 56px
  page-margin-tablet: 32px
  page-margin-mobile: 20px
  content-max: 1280px
  sheet: 20px
  mesh: 24px
  plot-mesh: 20px
components:
  button-primary:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    typography: '{typography.label-lg}'
    rounded: '{rounded.none}'
    height: 44px
    padding: 24px
  button-primary-hover:
    backgroundColor: '{colors.secondary}'
  button-secondary:
    backgroundColor: transparent
    textColor: '{colors.primary}'
    rounded: '{rounded.none}'
    height: 44px
  button-secondary-hover:
    backgroundColor: '{colors.surface}'
  card:
    backgroundColor: '{colors.neutral}'
    textColor: '{colors.primary}'
    rounded: '{rounded.none}'
    padding: '{spacing.sheet}'
  input:
    backgroundColor: transparent
    textColor: '{colors.primary}'
    rounded: '{rounded.none}'
    height: 48px
    padding: 13px
  chip:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.primary}'
    rounded: '{rounded.none}'
  focus:
    textColor: '{colors.secondary}'
  status-error:
    textColor: '{colors.error}'
  sidebar:
    backgroundColor: '{colors.kraft}'
    textColor: '{colors.on-kraft}'
    typography: '{typography.body-sm}'
    rounded: '{rounded.none}'
  nav-item-active:
    backgroundColor: '{colors.neutral}'
    textColor: '{colors.on-kraft}'
    rounded: '{rounded.none}'
  metric-value:
    textColor: '{colors.primary}'
    typography: '{typography.numeral-lg}'
---

# Botanica

## Overview

Botanica는 **숲색과 연두, 풍부한 펄프 종이, 직각으로 정리한 식물 기록지**를 시각 언어로 삼는다. 종이의 표면과 가장자리는 유기적이고, 조작 요소와 정보 정렬은 반듯하다. 크라프트색 탐색 영역, 겹친 종잇장, 세리프 숫자가 따뜻함을 만들며 작은 식물 표식이 정체성을 드러낸다.

2026-10-15 사용자 A/B 선택을 기준으로 확정한 조합이다: **색상 A / 서체·숫자 B / 질감 B / 모서리 A / 구획 B / 사이드바 B / 모눈·노트선 B / 장식 A**. Instrument Sans와 JetBrains Mono를 채택하고, 초기 DM Sans 및 실험용 IBM Plex 조합과 pill 버튼은 기본값에서 제외한다.

이 문서는 재사용하는 디자인 원칙이다. 소개 화면, 작업 도구, 데이터 화면, 읽기, 설정과 입력 흐름에 적용한다. `preview.html`과 `dashboard.html`은 서로 다른 적용 예시이며, 사진·도감 번호·히어로·사이드바 유무·섹션 순서를 필수 구성으로 정하지 않는다.

### Reference & provenance

- 2026-10-14 확인한 [Royal Botanic Gardens, Kew](https://www.kew.org/)의 식물 사진과 여유로운 텍스트 공간의 관계를 참고했다. 로고·카피·사진·코드는 사용하지 않았다.
- 2026-10-15 사용자가 제공한 paper-and-moss 문서에서 종이 질감·종잇장 구획·크라프트 탐색 면·모눈과 노트선·서체 역할을 비교했고, 위 A/B 선택만 채택했다. Moss/Pollen 팔레트, 둥근 카드, 고정된 화면 순서는 채택하지 않았다.
- 식물 이미지는 내장 이미지 생성 도구로 만든 예시 자산이다. [생성 기록](assets/README.md).
- Fraunces, Instrument Sans, JetBrains Mono와 OFL 라이선스를 로컬 `assets/`에 포함한다. 종이 질감은 로컬 SVG로 표현한다.
- 기존 [Google DESIGN.md alpha 명세](https://github.com/google-labs-code/design.md/blob/main/docs/spec.md)의 frontmatter와 본문 구조를 유지한다.

## Colors

**Forest·Leaf·Sage·Sprout의 기존 네 계열을 유지한다.** Forest는 글자와 행동의 중심, Leaf는 올리브 기운의 보조 강조, Sage는 중립적인 면과 경계, Sprout은 밝은 연두색 포인트다. Moss 계열이나 황색 포인트로 교체하지 않는다.

| 계열 | 100 | 300 | 500 | 700 | 900 |
| --- | --- | --- | --- | --- | --- |
| Forest | #E3ECE5 | #ACC5B2 | #648F73 | #376347 | #163A2A |
| Leaf | #EDF2DF | #CEDDA8 | #9AB66B | #617F3B | #344B25 |
| Sage | #E9EDDE | #C4CCB8 | #98A58B | #6B7C60 | #3E5038 |
| Sprout | #F0F5DA | #D6E8A4 | #B5D36A | #7B9A34 | #465F1E |

`primary`는 Forest 900, `secondary`는 Forest 700, `tertiary`는 Sprout 300, `surface`는 Sage 100, `border`는 Sage 300이다. 밝은 단계는 면, 중간 단계는 차트와 강조, 어두운 단계는 글자와 행동에 쓴다. 한 화면에서는 Forest를 중심으로 1–2개 보조 계열의 강도를 조절한다.

종이 바탕은 `paper-stock` #F3F0E3, 종잇장은 `neutral` #F5F3E8, 보조 면은 `surface` #E9EDDE다. 탐색 면의 `kraft` #E4E0D0는 따뜻한 중립색이며 강조색이 아니다. 크라프트 위에는 `on-kraft` #17261A 또는 `kraft-muted` #4A5A4D를 쓴다.

`mesh-line`과 `mesh-fine`은 희미한 녹색 모눈, `rule-line`은 목록 행 구분, `margin-line`은 붉은 노트 여백선이다. 붉은 여백선은 문구용 선에만 한정하며 오류 의미와 혼동되는 강조 면으로 쓰지 않는다. 오류에는 기존 `error` #A13D2D를 쓴다.

권장 글자/바탕은 `primary/neutral`, `text-muted/neutral`, `on-primary/primary`, `primary/tertiary`다. 밝은 연두색을 작은 본문으로 쓰지 않는다. 상태는 색뿐 아니라 텍스트·아이콘·선택선으로 구분한다. 차트 계열도 색만으로 구분하지 않는다.

## Typography

- **Fraunces 400**: 성격을 드러내는 제목과 큰 KPI 숫자. 큰 숫자는 고정폭 서체가 아닌 부드러운 세리프로 표현한다. 이탤릭은 짧은 강조에 한정한다.
- **Instrument Sans 400/500/600**: 본문, 버튼, 탐색과 조작 레이블. 기본 본문은 15–16px, 정보 밀도가 높은 화면은 12–13px부터 조절한다.
- **JetBrains Mono 400**: 항목 ID, 시간, 정렬해야 하는 표의 숫자, 축 값과 짧은 기록용 메타데이터. 긴 문장에는 사용하지 않는다.

큰 제목 토큰은 넓은 화면의 기준값이다. 실제 크기와 줄바꿈은 문장 길이와 가용 폭에 맞춘다. 큰 숫자는 약 40px, 단위는 작은 산세리프 또는 데이터 서체로 구분한다. 표의 숫자와 KPI 숫자는 역할이 다르다.

한글 제목은 설치된 `Noto Serif KR` 또는 시스템 세리프, 본문은 `Noto Sans KR` 또는 시스템 산세리프로 대체한다. 영문 서체의 한글 지원을 가정하지 않으며 한글에 과도한 음수 자간을 적용하지 않는다. 프리뷰에 포함된 영문 서체는 네트워크 없이 로컬에서 로드한다.

## Layout

### Composition principles

1. **목적이 구성을 결정한다.** 읽기·탐색·입력·작업의 순서와 정보 관계를 먼저 정한다. KPI → 차트 → 표 같은 한 가지 순서를 강제하지 않는다.
2. **독립된 정보 묶음은 종잇장으로 표현한다.** 서로 다른 프로젝트·작업·기록 영역에는 간격과 약한 깊이를 둔다. 한 그룹 안의 항목마다 카드를 만들지 않는다.
3. **직선 정렬을 유지한다.** 제목, 데이터 열, 입력과 반복 행동을 안정적으로 정렬한다. 종이 가장자리의 미세한 불규칙성은 콘텐츠 정렬을 바꾸지 않는다.
4. **구조와 장식의 밀도를 구분한다.** 모눈은 바탕에서, 노트선은 반복 행에서, 식물 표식은 소수의 브랜드 지점에서 역할을 갖는다.
5. **형태보다 읽는 순서를 우선한다.** 좁은 화면에서는 열을 줄이고 보조 정보를 다음 흐름으로 보내며, 탐색이 필요하면 사이드바를 상단 탐색으로 바꾼다.

### Spacing and adaptation

간격은 기존 4/8/16/24/32/48/64px 계열을 사용한다. 종잇장 내부의 시작값은 20px, 독립된 종잇장 사이도 약 20px다. 배경 모눈은 24px, 차트의 가는 모눈은 20px다. 데이터 행 간격은 내용과 조작 크기에 따라 조절하며 텍스트를 모눈에 억지로 맞추지 않는다.

사이드바 폭, 열 수, 콘텐츠 최대 폭과 섹션 순서는 화면 목적에 맞춘다. 사진·히어로·특정 카드 개수·모든 화면의 사이드바를 필수로 만들지 않는다.

## Elevation & Depth

깊이는 **바탕 위에 놓인 직각 종잇장**으로 표현한다. 크림색 면과 1px 경계, 낮고 부드러운 그림자, 미세하게 불규칙한 종이 가장자리를 조합한다. 모서리는 둥글게 깎지 않지만 가장자리 자체는 종이처럼 조금 흔들릴 수 있다.

### Paper material

풍부한 질감은 긴 섬유, 미세 입자, 드문 펄프 반점, 약한 표면 요철, 가장자리 음영의 다섯 요소다. `assets/paper-rich.svg`가 앞의 네 요소를 한 장의 반복 질감으로 제공하고, 화면 바탕의 약한 방사형 음영이 마지막 요소를 맡는다.

질감은 바탕과 종잇장 배경에 적용한다. 텍스트·아이콘·차트 데이터·입력 위에 필터를 덮지 않는다. 같은 면에 입자를 여러 번 중첩하지 않으며, 색상 견본은 정확한 토큰 색을 보여주기 위해 질감을 제외한다. 요철은 재료의 성격을 드러낼 정도로 보이되 반짝임이나 두꺼운 입체감이 되지 않게 한다.

종잇장 가장자리에는 배경 레이어에만 작은 SVG displacement를 적용한다. 프리뷰의 기준은 scale 4px이며, 내용과 포커스 표시에는 적용하지 않는다. 기본 그림자는 `0 1px 2px rgba(23,38,28,.08), 0 6px 18px rgba(23,38,28,.06)` 정도로 제한한다. 버튼과 입력에는 종잇장 그림자를 반복하지 않는다.

### Stationery lines

바탕 모눈은 종잇장 사이와 여백에 드러난다. 불투명한 종잇장 위로 바탕 모눈이 비치지 않게 한다. 차트에는 더 가는 20px 모눈을 쓰되 실제 데이터 축과 레이블이 우선이다.

목록·표·일정의 노트선은 실제 행 경계를 따라간다. 작업 목록이나 기록에는 시간·선택 칸과 본문 사이에 붉은 세로 여백선을 둘 수 있다. 줄바꿈한 문장을 선이 가로지르지 않게 한다. KPI 면에는 노트선을 넣지 않는다.

색 전환은 약 180ms 이내로 차분하게 표현하고, 불필요한 반복 움직임은 사용하지 않는다. `prefers-reduced-motion`을 존중한다.

## Shapes

**버튼·입력·칩·패널·사진 프레임의 기본 모서리는 0px 직각이다.** `rounded.none`을 공통으로 사용한다. 이전 pill 버튼이나 둥근 카드, 아치 사진 프레임을 기본으로 사용하지 않는다.

종잇장의 작은 가장자리 변형과 컨트롤의 정확한 직각을 구분한다. 원형 상태 점이나 식물 선화는 기능·상징에 필요한 예외이며 둥근 카드 스타일로 확장하지 않는다. 선택은 왼쪽 또는 아래쪽 선, 면의 명도 차이, 텍스트를 함께 사용한다.

## Components

### Actions and selection

주요 행동은 Forest 바탕과 Paper 글자, 보조 행동은 투명하거나 Sage 면으로 표현한다. 버튼은 0px 모서리와 최소 44px 조작 높이를 기준으로 한다. 호버·눌림·포커스·선택·비활성을 구분한다. 포커스는 주변과 구별되는 Forest/Canopy 외곽선으로 표시한다.

### Information sheets

독립된 정보 묶음은 크림색 종잇장, 약한 경계, 낮은 그림자와 20px 안쪽 여백을 사용한다. 헤더와 내용의 위계를 분명히 한다. 관련 행은 한 종잇장 안의 목록이나 표로 유지한다. 큰 지표는 Fraunces 숫자와 Instrument Sans 설명을 조합한다.

### Navigation

사이드바를 사용하는 경우 밝은 크라프트 바탕과 어두운 녹색 글자를 쓴다. 현재 위치는 더 밝은 종이 면과 왼쪽 선택선으로 표시한다. 짙은 초록 사이드바는 기본값이 아니다. 작은 잎 로고와 절제된 선형 표식을 허용한다.

탐색의 깊이와 빈도에 따라 링크·탭·사이드바를 선택한다. 탭은 `tablist/tab/tabpanel` 관계 및 방향키·Home·End 탐색을 지원한다.

### Input and feedback

입력에는 항상 보이는 레이블, 충분한 높이, 명확한 포커스와 가까운 오류 설명을 둔다. 입력은 직각이며 기본 높이는 48px다. placeholder는 레이블을 대신하지 않는다. 저장·완료·복사 뒤에는 결과를 알린다.

### Tables, charts and media

반복 데이터는 JetBrains Mono로 필요한 숫자 열과 시간을 정렬한다. 표의 노트선과 차트 모눈은 데이터보다 약해야 한다. 차트는 축·단위·레이블을 갖추고 여러 계열은 범례나 직접 레이블로 구분한다.

식물 사진·잎 아이콘·표식은 허용하며 소수의 지점에 둔다. 추상적인 녹색 번짐을 기본 장식으로 강제하지 않는다. 식물 사진이 없어도 색·서체·종이와 직각 구획으로 Botanica가 드러나야 한다.

## Do's and Don'ts

- Forest·Leaf·Sage·Sprout의 기존 색 계열을 유지한다.
- 제목과 큰 숫자는 Fraunces, 일반 UI는 Instrument Sans, 정렬 데이터는 JetBrains Mono로 구분한다.
- 풍부한 종이 재료와 반듯한 정보 정렬을 함께 유지한다.
- 겹친 종잇장도 모서리는 직각으로 유지한다.
- 탐색 면은 밝은 크라프트, 주요 행동은 짙은 Forest로 역할을 나눈다.
- 모눈은 바탕·차트에, 노트선은 실제 반복 행에 맞춘다.
- 키보드 포커스와 상태, 작은 글자의 대비를 지킨다.
- 질감과 가장자리 필터를 글자나 데이터 위에 덮지 않는다.
- pill CTA, 둥근 카드, 강한 광택·네온·유리 효과를 섞지 않는다.
- 모든 화면에 같은 사진·사이드바·카드 개수·섹션 순서를 요구하지 않는다.
- 토큰·원칙을 바꾸면 소개 화면과 대시보드의 대응 표현도 함께 갱신한다.
