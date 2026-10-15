---
version: alpha
name: Celestrial
description: 깊은 네이비와 금색 행동 강조, 가벼운 기하학 서체, 별빛·여명 위 직각 유리 시트와 천체 지도 도해로 구성한 디자인.
colors:
  primary: '#D8B66A'
  secondary: '#B9CCFF'
  gold-light: '#F0DDA5'
  gold-muted: '#8F723D'
  gold-surface: '#262319'
  neutral: '#090F1C'
  surface: '#151F32'
  on-surface: '#EDF2FF'
  on-primary: '#090F1C'
  text-muted: '#9DAAC1'
  border: '#34425C'
  error: '#F0A69D'
  gold-100: '#F6EBCB'
  gold-300: '#F0DDA5'
  gold-500: '#D8B66A'
  gold-700: '#8F723D'
  gold-900: '#262319'
  glass: rgba(255, 255, 255, 0.06)
  glass-raised: rgba(255, 255, 255, 0.10)
  glass-edge: rgba(255, 255, 255, 0.14)
  glass-sidebar: rgba(255, 255, 255, 0.04)
  haze: rgba(177, 145, 234, 0.20)
  dawn: rgba(240, 134, 152, 0.10)
  sky-glow: rgba(99, 111, 239, 0.28)
  atlas-line: rgba(233, 239, 249, 0.07)
typography:
  headline-display:
    fontFamily: Outfit
    fontSize: 78px
    fontWeight: 300
    lineHeight: 1.05
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Outfit
    fontSize: 46px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.028em
  headline-md:
    fontFamily: Outfit
    fontSize: 29px
    fontWeight: 400
    lineHeight: 1.25
  quote:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: 300
    lineHeight: 1.25
  brand:
    fontFamily: Manrope
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0.19em
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.9
  body-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.8
  label-lg:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.6
  label-md:
    fontFamily: Manrope
    fontSize: 10px
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: 0.18em
  caption:
    fontFamily: Manrope
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0.05em
  numeral-lg:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: 300
    lineHeight: 1
    letterSpacing: -0.02em
  data:
    fontFamily: DM Mono
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
  atlas-label:
    fontFamily: Cormorant Garamond
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.2
    fontStyle: italic
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
  section: 65px
  page-margin: 56px
  page-margin-tablet: 32px
  page-margin-mobile: 20px
  content-max: 1280px
components:
  button-primary:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    typography: '{typography.label-lg}'
    rounded: '{rounded.none}'
    height: 48px
    padding: 21px
  button-primary-hover:
    backgroundColor: '{colors.gold-light}'
  button-secondary:
    backgroundColor: transparent
    textColor: '{colors.on-surface}'
    rounded: '{rounded.none}'
    height: 48px
  button-secondary-hover:
    backgroundColor: '{colors.surface}'
  card:
    backgroundColor: '{colors.glass}'
    textColor: '{colors.on-surface}'
    rounded: '{rounded.none}'
    padding: 22px
  input:
    backgroundColor: '{colors.neutral}'
    textColor: '{colors.on-surface}'
    rounded: '{rounded.none}'
    height: 48px
    padding: 13px
  chip:
    backgroundColor: transparent
    textColor: '{colors.secondary}'
    rounded: '{rounded.none}'
  selection-active:
    backgroundColor: '{colors.gold-surface}'
    textColor: '{colors.gold-light}'
    rounded: '{rounded.none}'
    height: 44px
  focus:
    textColor: '{colors.primary}'
  status-error:
    textColor: '{colors.error}'
  sidebar:
    backgroundColor: '{colors.glass-sidebar}'
    textColor: '{colors.on-surface}'
    rounded: '{rounded.none}'
  metric-value:
    typography: '{typography.numeral-lg}'
    textColor: '{colors.on-surface}'
---

# Celestrial

## Overview

Celestrial은 **깊은 네이비, 금색 행동 강조, 가벼운 기하학 서체, 별빛 위의 직각 유리 시트**를 결합한 천체 지도책형 디자인이다. 빛과 투명도로 깊이를 만들고, 독립된 정보 묶음 사이에 밤하늘이 드러나게 한다. 이름은 사용자 지정 표기인 **Celestrial**을 유지한다.

2026-10-15 사용자 선택: **밤의 색조 A / 금색 A / 서체·숫자 B / 밤하늘 B / 재질 B / 모서리 A / 구획 B / 천체 지도 장식 B**. 첨부 문서의 보랏빛 기본 바탕, 보랏빛 주요 버튼, pill 컨트롤과 둥근 패널은 채택하지 않았다. 금색은 가는 장식선뿐 아니라 주요 버튼·선택·진행률에도 사용한다.

이 문서는 여러 화면에 재사용하는 시각 원칙이다. `preview.html`과 `dashboard.html`은 서로 다른 예시이며, 히어로·사이드바·카드 개수·KPI와 차트의 순서를 고정하지 않는다. 천체 지도 장식은 정체성의 일부지만 읽기와 조작을 방해하지 않는 밀도로 적용한다.

### Reference & provenance

- 2026-10-14 확인한 [Stellarium Web](https://stellarium-web.org/)에서 어두운 하늘 위 가는 연결선과 레이블의 대비를 참고했다. 코드·로고·이미지는 사용하지 않았다.
- 2026-10-15 사용자 제공 Celestial 문서의 유리·별빛·서체·천체 지도 표현을 비교하고 위 선택 조합을 반영했다.
- 별 지도와 도해는 직접 그린 SVG다. 배경의 좌표선과 가상 별자리는 장식이며 실제 관측 결과가 아니다. 소개 화면의 별자리도 시각적 도식이다.
- Outfit, Manrope, DM Mono 및 도해용 Cormorant Garamond와 OFL 라이선스를 로컬 `assets/`에 포함한다.
- 기존 [Google DESIGN.md alpha 명세](https://github.com/google-labs-code/design.md/blob/main/docs/spec.md)의 frontmatter와 본문 구조를 유지한다.

## Colors

기존 깊은 네이비와 금색 계열을 유지한다. `neutral` #090F1C는 바탕, `surface` #151F32는 불투명 폴백 면, `on-surface` #EDF2FF는 본문, `text-muted` #9DAAC1은 보조 글자, `border` #34425C는 읽을 수 있는 경계다.

**주요 행동은 Gold #D8B66A와 Ink #090F1C 글자다.** 선택은 `gold-surface` #262319와 `gold-light` #F0DDA5, 명확한 선택선을 조합한다. 보랏빛은 배경의 빛 번짐에만 쓰며 기본 버튼 색을 대체하지 않는다. 차가운 보조색 `secondary` #B9CCFF도 유지한다.

| Gold 단계 | 색 | 역할 |
| --- | --- | --- |
| 100 | #F6EBCB | 가장 밝은 작은 강조 |
| 300 | #F0DDA5 | 호버와 강조 레이블 |
| 500 | #D8B66A | 주요 행동·선택·진행률 |
| 700 | #8F723D | 장식 경계, 작은 본문에는 사용하지 않음 |
| 900 | #262319 | 선택된 영역의 어두운 금색 면 |

별빛 배경의 보라·라일락·장밋빛은 낮은 불투명도로 제한한다. 유리 면은 `glass` 6%, 사이드바는 `glass-sidebar` 4%, 더 높은 면은 `glass-raised` 10%의 밝은 층이다. 이 값은 배경에 합성되므로 고정 HEX 면과 동일하지 않다. 색 견본은 원래 토큰 값을 보여주며 유리 효과를 씌우지 않는다.

상태는 색뿐 아니라 문구·아이콘으로 구분한다. 오류는 기존 `error` #F0A69D를 사용한다. 필수 상태를 장식선의 낮은 불투명도로 표현하지 않는다. 실제 유리와 배경 조합에서 글자 대비를 확인하고, 부족하면 불투명 면이나 더 진한 바탕으로 보완한다.

## Typography

- **Outfit 300**: 큰 제목과 큰 KPI 숫자. 가벼운 기하학 형태가 밤하늘의 여유를 만든다. 작은 제목은 400/500으로 조절한다.
- **Manrope 400/500/600**: 본문·탐색·버튼·일반 UI. 본문은 14–16px, 정보가 많은 영역은 12–13px부터 조정한다.
- **DM Mono 400/500**: 표의 숫자, 시간, ID, 축 값과 짧은 메타데이터. 긴 문장에는 사용하지 않는다.
- **Cormorant Garamond italic 400**: 지도 제목판·가상 별자리 이름·도해 번호 같은 짧은 천체 지도 레이블에 한정한다. 본문이나 기본 큰 제목 서체가 아니다.

큰 숫자는 약 40px Outfit 300, 단위는 작은 데이터 서체로 분리한다. 크기와 줄바꿈은 문장 길이·가용 폭·정보 밀도에 맞춘다. 한글은 설치된 Noto Sans KR 또는 시스템 산세리프로 대체하며 영문 서체의 한글 지원을 가정하지 않는다. 한글에는 과도한 음수 자간을 적용하지 않는다.

## Layout

1. **작업 목적이 화면 순서를 결정한다.** 읽기·탐색·비교·입력 흐름에 맞춰 배치한다. 특정 천문 도구의 구조를 강제하지 않는다.
2. **독립된 정보 묶음은 떨어진 시트로 표현한다.** 관련 행은 하나의 시트에 두고, 프로젝트·작업·차트 등 다른 묶음 사이에는 밤하늘이 보이는 간격을 둔다.
3. **밝기를 행동과 중요 정보에 모은다.** 금색 버튼, 선택선, 데이터가 지도 장식보다 먼저 읽혀야 한다.
4. **데이터 정렬은 정확하게 유지한다.** 곡선 장식이 있어도 입력·행·열은 안정적으로 정렬한다.
5. **좁은 화면에서는 읽는 순서와 조작 공간을 보존한다.** 열을 줄이고, 넓은 제목 도해는 숨길 수 있다. 실제 데이터는 크기만 줄여 해결하지 않는다.

간격은 4/8/16/24/32/48/64px 계열이다. 독립 시트 사이는 약 24px, 내부는 20–22px를 시작값으로 쓴다. 사이드바 폭·섹션 순서·카드 개수·최대 폭은 사용 목적에 맞춘다.

## Elevation & Depth

깊이는 **별빛 배경 위의 반투명 유리**로 표현한다. 기본 유리는 밝은 색 6%와 `backdrop-filter: blur(18px)`를 조합하고, 1px 경계와 약한 안쪽 하이라이트로 표면을 구분한다. 사이드바도 같은 재질을 사용한다. 드롭 섀도보다 투명도·경계·빛을 우선한다.

블러를 지원하지 않는 환경은 `surface` #151F32 계열의 불투명한 면으로 대체한다. 표 헤더·입력·읽기 영역은 필요한 경우 더 안정적인 불투명 면을 쓴다. 글자 자체에 블러나 발광을 적용하지 않는다.

배경은 깊은 네이비 위 낮은 강도의 보라·라일락·여명색 번짐과 드문 별점이다. 별점은 고정된 시드의 로컬 SVG로 제공하며 자동 점멸이나 회전이 없어도 정체성이 유지된다. `prefers-reduced-motion`을 존중한다.

천체 지도 장식은 별빛 위, 콘텐츠 아래에 놓는다. 극좌표 형태의 원호와 방사선, 좌표 레이블, 점선 황도와 하나의 가상 별자리로 표현한다. 선은 배경으로 물리고, 데이터 선과 혼동되지 않게 실제 도표의 축·레이블은 별도로 표시한다.

## Shapes

**버튼·입력·칩·패널·탐색 영역은 0px 직각**을 기준으로 한다. 유리 재질이 둥근 모서리를 뜻하지 않는다. pill 컨트롤과 20px 둥근 카드는 기본값에서 제외한다.

천체 도해의 원·반구·궤도·별점은 의미에 필요한 곡선을 유지한다. 이 원형 도해를 카드나 버튼의 모서리에 확장하지 않는다. 제목 도해의 프레임도 직각으로 처리한다.

## Components

### Actions and selection

주요 행동은 금색 바탕과 Ink 글자, 보조 행동은 투명 면과 밝은 글자·가는 경계다. 44–48px 이상의 조작 높이를 확보한다. 호버는 Gold 300, 포커스는 명확한 금색 외곽선으로 표시한다. 금색은 장식에만 제한되지 않으며 선택·진행률에도 사용할 수 있다.

### Glass sheets

독립된 정보 묶음은 직각 유리 시트와 간격으로 구분한다. 표·목록은 같은 시트 안에서 행으로 묶는다. 헤더와 본문을 가는 선으로 나누고 작은 글자 뒤의 배경을 안정적으로 유지한다. 큰 지표는 Outfit 숫자와 Manrope 설명으로 표현한다.

### Navigation and input

사이드바는 반투명 밤색 면, 현재 위치는 어두운 금빛 면과 선·밝은 글자로 표시한다. 탐색 방식 자체는 링크·탭·사이드바 중 목적에 맞게 정한다. 탭은 방향키·Home·End 및 `tablist/tab/tabpanel` 관계를 지원한다.

입력에는 항상 보이는 레이블, 읽을 수 있는 경계, 키보드 포커스와 가까운 오류 설명을 제공한다. 저장·복사·완료 결과는 문구로 알린다. placeholder는 레이블을 대신하지 않는다.

### Atlas details

넓은 화면의 제목 도해는 이중 금색 프레임, 작은 반구 그림, 짧은 지도 제목과 예시임을 알리는 문구를 조합한다. 좁은 화면에서는 생략할 수 있다. 섹션에는 로마 숫자, 차트에는 `Fig. 1`처럼 읽는 순서에 따른 도해 번호를 사용할 수 있다.

배경 좌표·황도·가상 별자리는 장식임을 표시한다. 실제 관측값이나 업무 상태처럼 제시하지 않는다. 도해는 평면 SVG이며, 행성 사진·3D 광택·굵은 장식이 필수 요소는 아니다. 실제 관계를 나타내는 차트에는 단위·축·레이블을 제공한다.

## Do's and Don'ts

- 깊은 네이비와 금색 주요 행동을 유지한다.
- Outfit 제목·숫자, Manrope UI, DM Mono 데이터를 구분한다.
- Cormorant 이탤릭은 짧은 지도 레이블에 한정한다.
- 별빛·여명 위의 독립된 유리 시트도 모서리는 직각으로 유지한다.
- 가는 지도 장식과 실제 데이터의 위계를 분명히 한다.
- 배경과 합성된 유리 면에서 작은 글자와 포커스 대비를 확인한다.
- 블러 미지원 환경에서는 안정적인 불투명 면을 제공한다.
- 금색 버튼을 보랏빛으로 바꾸거나 금색을 장식 전용으로 제한하지 않는다.
- 모든 페이지에 같은 제목판·사이드바·도표 순서를 강제하지 않는다.
- 자동 점멸·과도한 광륜·텍스트 블러를 추가하지 않는다.
- 이름을 임의로 Celestial로 바꾸지 않는다.
- 토큰과 원칙을 바꾸면 소개 화면과 대시보드도 함께 갱신한다.
