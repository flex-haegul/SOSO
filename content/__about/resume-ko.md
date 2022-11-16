---
title: 'about'
date: 2022-07-16 16:21:13
lang: 'ko'
---

<h1 class='title'>
안녕하세요, 이소영 입니다.
</h1>

**저는 이런 것들에 가치를 두고 있습니다.**

- 좋은 설계와 코드
- 테스트와 안정성
- 자동화와 생산성
- 지식과 경험 공유
- 큰 가치를 전달할 수 있는 일

|            |                              |
| :--------: | ---------------------------- |
| **Blog** | <https://so-so.dev> |
| **GitHub** | <https://github.com/SoYoung210> |
| **E-mail** | <ethdud1@gmail.com>            |


<h2>
<span class='highlight'>Work Experiences</span>
</h2>

<h3 class='no-border' style='margin-top: 1em;'>
  <a target='_blank' href='https://flex.team/'>플렉스</a>
  <div class='period'>(2021.02 ~ 현재)</div>
</h3>

|              |                                                         |
| -----------: | ------------------------------------------------------- |
| **position** | FE Platform, Design Platform, Core Squad |
| **projects** | Design System, flex2.0개편, Core HR관련 서비스  |

#### Design Platform

**flex Design System 3.0(linear) 설계 및 개발**

Design System 2.0의 문제를 해결하고 장기적으로 제품의 좋은 재료가 될 새로운 디자인 시스템 구축했습니다. 공통 영역이 보장해야 하는 범위를 정의하고 UX와 DX를 고려하여 구현하였습니다.

- 표현의 제약을 줄이면서 동작의 일관성을 보장하는 [디자인 시스템 설계](https://so-so.dev/react/design-system-decision-record/)
  - 다양한 컴포넌트 용례를 효율적으로 지원하기 위한 추상 컴포넌트 정의
  - 동작의 일관성을 보장하는 Headless 컴포넌트 구성
- 확장성을 보장하는 레이어의 문제를 반복되는 UI Pattern을 지원할 수 있도록 linear-extension 패키지 운영
- 컴포넌트 시나리오 기반의 테스트 구성

**디자이너와 개발자의 생산성을 높일 수 있는 도구 기획 및 개발**

- 디자인 리소스 변경에 필요한 커뮤니케이션 비용을 줄이기 위해 figma와 코드를 동기화하는 스크립트 제작
- 디자이너의 한글 컨텐츠에 대한 고민을 줄여주는 [Lorem ipsum Figma plugin](https://www.figma.com/community/plugin/1097438299470908389/Lorem-ipsum-universal) 제작
- 실제 디자인 시안과 일치하는 스켈레톤 컴포넌트 코드를 자동 생성해주는 [Skeleton Code generator Figma Plugin](https://www.figma.com/community/plugin/1072079296344464088/figeleton) 제작

#### flex2.0 개편

다양한 인사정책, 규모를 가진 고객사에서도 사용할 수 있는 제품으로 도약하기 위한 개편을 진행했습니다.

- 2.0 프로젝트 설계 및 기반 패키지 제작
  - [react-query](https://tanstack.com/query/v4)를 사용할 때 고유함이 보장되어야 하는 queryKey를 개발자가 직접 판단하지 않아도 되도록 api 요청정보 기반으로 자동생성 해주는 hook package 개발
  - stitches.js, react-hook-form등 flex1.0에서 사용하지 않던 라이브러리 도입, 팀 내 사용 가이드 전파
  - antd기반의 Design System2.0 개발 및 이후 유지보수
  - Framer 코드 컴포넌트 구성을 통해 디자인과 개발 단계에서 하나의 구현체를 사용할 수 있도록 개선
- 유저 프로필, 구성원 추가/초대
  - 복잡한 Form을 Uncontrolled, Controlled의 조합으로 설계 및 개발
  - 권한을 단순하게 처리할 수 있도록 설계

#### Core HR

- 정보를 대량으로 변경할 때 Excel과 유사한 변경 편의성을 제공하기 위해 ag-grid를 활용한 Editable Table을 공통 모듈화 하고, 이를 활용하여 [인사/계약 정보 대량변경](https://userguide.flex.team/de413145-ae7a-4643-a7dd-a41e0d61870d#3927052f-651a-457e-926e-71925c9a9bbe) 기능 개발
- 회사별 구성원 초대 템플릿을 관리할 수 있는 형태로 온보딩 기능 개선

<h3 class='no-border'>
  <a href='https://www.banksalad.com/' target='_blank'>뱅크샐러드</a>
  <div class='period'>(2018.12 ~ 2021.02)</div>
</h3>

|              |                                                         |
| -----------: | ------------------------------------------------------- |
| **position** | Engineering Foundation |
| **projects** | Design System, 카드/대출/투자 추천 서비스 2.0 개편 |

#### Design System

디자인 일관성과 생산성을 높이기 위한 [BPL(Banksalad Product Language)](https://blog.banksalad.com/tech/banksalad-product-language-design/) 을 설계 및 구현했습니다.

- 2.0 첫 버전의 컴포넌트 개발 및 문서와 Storybook등 환경 구성
- [rollup 설정 개선](https://so-so.dev/tool/rollup/rollupjs-config/)으로 번들 사이즈 30% 감소

#### 공통 패키지 운영

- 각 프로젝트에서 중복으로 만들어 사용하고 있던 공통 함수들을 monorepo 멀티 패키지 구조로 변경 ([관련 설정](https://so-so.dev/pattern/mono-repo-config/))
- 프로젝트 스캐폴딩 cli, 유틸 함수 등을 추가

#### 대출 추천 재개발

- View와 Data를 분리하고 모든 비즈니스 로직을 redux middleware에서 처리.
  - redux, redux-saga 적용 및 가이드 공유
- [msw](https://github.com/mswjs/msw)와 [testing-library](https://testing-library.com/)를 사용하여 Integration Test진행. 팀 내 테스트 코드 작성 가이드 작성
  - 테스트 커버리지 10%에서 70%로 상승

#### Webview TTI 개선

- LightHouse기준(Slow 4G)40점에서 87점으로 향상.
  - TTI 2.5초에서 1.5초로 상승
- SSR 가이드 공유
  - [관련 저장소](https://github.com/SoYoung210/react-ssr-code-splitting)

<h2>
<span class='highlight'>Communities</span>
</h2>

#### Presentations

- [디자인 시스템, 형태를 넘어서](https://speakerdeck.com/soyoung210/dijain-siseutem-hyeongtaereul-neomeoseo) @FEConf2022 (22.10.08)
- [절망 드리븐 성장: 함께 일하고 싶은 개발자가 되기까지](https://speakerdeck.com/soyoung210/jeolmang-deuribeun-seongjang-hamgge-ilhago-sipeun-gaebaljaga-doegiggaji) @한빛데브그라운드 (19.12.13)
- [헌집줄게, 새집다오](https://speakerdeck.com/soyoung210/heonjibjulge-saejibdao-riaegteu-peurojegteu-gujojojeong) @FEConf2019 (19.10.26)
- [Clean Architecture in Banksalad](https://speakerdeck.com/soyoung210/clean-architecture-in-banksalad) @XXIT Tech Talk (19.10.05)
- [인턴상륙작전](https://speakerdeck.com/soyoung210/inteonsangryugjagjeon) @GDG Lightning Talk (19.02.19)

#### Activities

- [FEConf Organizer](https://feconf.kr/) (20.03 ~ current)
- [커넥트재단 부스트캠프 리뷰어](https://boostcamp.connect.or.kr/) (20.08 ~ 20.10)
