# NutrifyMe Front-End
- 메인 레포지토리 : https://github.com/NutrifyMe/NutrifyMe.git

## 프로젝트 소개
영양제 먹느랴 정신없는데 막상 사고싶은 영양제를  찾다보니 기존 영양제와 중복되는 영양제들이 많아서 (일부성분 복합적으로 나오는 영양제들) 내 권장섭취량을 파악해서 남용 및 오용하지 않고 적정량만 섭취하기 위해 찾던 과정이 번거로워서 만드는김에 시스템 만들면 어떨까 ? 라는 생각에 시작한 프로젝트

## 팀원 구성
| 한기선(FE) | 김인철(BE) | 
|----------|-----------|
| <img src ="https://avatars.githubusercontent.com/u/176655935?v=4" width=200> <br /> @kiseon77 |  <img src ="https://avatars.githubusercontent.com/u/176651866?v=4" width=200> <br /> @incheolhit | 

##  1. 개발환경
Front : HTML, React, styled-components
Back-end : 
버전 및 이슈관리 : Github, Github Issues
협업 툴 : Discord, Notion
디자인 : Figma


##  2. 채택한 개발 기술과 브랜치 전략
### React, styled-component
* React
  - 컴포넌트화를 통해 추후 유지보수와 재사용성을 고려했습니다.
  - 유저 배너, 상단과 하단 배너 등 중복되어 사용되는 부분이 많아 컴포넌트화를 통해 리소스 절약이 가능했습니다.
* styled-component
  - props를 이용한 조건부 스타일링을 활용하여 상황에 알맞은 스타일을 적용시킬 수 있었습니다.
  - 빌드될 때 고유한 클래스 이름이 부여되어 네이밍 컨벤션을 정하는 비용을 절약할 수 있었습니다.
  - S dot naming을 통해 일반 컴포넌트와 스타일드 컴포넌트를 쉽게 구별하도록 했습니다.

## 3. 프로젝트 프론트엔드 구조

## 4. 역할분담
### 한기선
- 기획
- 디자인
- 프론트엔드 구현
### 김인철
- 기획
- 백엔드 구현