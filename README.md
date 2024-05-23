# 지역 기반 뉴스 플랫폼

## 프로젝트 정의

**지역 기반 뉴스 플랫폼**은 위치 서비스 시스템을 기반으로 지역 시민들이 뉴스를 직접 작성하여 정보와 이슈를 공유하고 지역의 유니크한 뉴스 커뮤니티 시스템을 제공합니다.

- **지역 기반 뉴스 플랫폼**은 지역 시민들의 정보와 이슈를 공유하는데 필요한 도구와 커뮤니티를 제공합니다.
- 지역을 기반으로 개개인이 기사를 올릴 수 있는 시스템으로 기사의 기본적인 템플릿, 카테고리, 실시간 소통 기능(커뮤니티)을 제공합니다.
- 업로드 된 기사는 사용자의 선택에 따라 실시간 기사와 정형화된 기사로 노출되며, 추천수에 따라 상위 노출이 가능하며, 사용자의 레벨에 따른 지역의 유니크 하고 소통 가능한 뉴스 커뮤니티 시스템을 제공합니다.

<br>

## 팀원 구성

<div align="center">

|                                                          **박준**                                                           |                                                         **이동혁**                                                          |                                                           **김수민**                                                            |                                                         **박현성**                                                          |                                                                    **지혜민**                                                                    |
| :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars.githubusercontent.com/u/157086374?v=4" height=150 width=150> <br/>](https://github.com/mutajune) | [<img src="https://avatars.githubusercontent.com/u/89085298?v=4" height=150 width=150> <br/>](https://github.com/LfromTheE) | [<img src="https://avatars.githubusercontent.com/u/95954000?s=64&v=4" height=150 width=150> <br/>](https://github.com/ssuminii) | [<img src="https://avatars.githubusercontent.com/u/170388640?v=4" height=150 width=150> <br/>](https://github.com/Haley513) | [<img src="https://www.catholicpress.kr/data/cheditor4/1509/2001159622_9fjrpOFA_1.png" height=150 width=150> <br/>](https://github.com/ssuminii) |
|                                                            팀장                                                             |                                                       플로우차트 작성                                                       |                                                        GitHub, 문서 작성                                                        |                                                      리서치, 문서 작성                                                      |                                                                       팀원                                                                       |

</div>

<br>

## 설치

급여 및 업무 관리 플랫폼은 서버와 클라이언트 시스템으로 구성되며 Javascript 와 Nodejs 기반으로 구성되어있습니다.<br>
프로젝트 저장소를 다음 설명에 따라 개발자 컴퓨터에 복사하고 설치 명령을 입력하여 설치를 할 수 있습니다.

```bash
git clone https://github.com/ibare/devcamp-onboarding-template.git my-project

cd my-project

npm install
```

프로젝트를 다운로드하고 설치하기 위해선 사용자의 컴퓨터에 Git 과 Nodejs가 설치되어있어야합니다.
만약 설치되어있지 않은 도구가 있다면 다음 링크를 통해 사용자 환경에 맞는 버전을 설치해주세요.

- [Git - Downloads](https://git-scm.com/downloads)
- [Node.js — Download Node.js®](https://nodejs.org/en/download/current)

## 실행

개발자 로컬 환경에서 개발 모드로 실행하기 위해선 프로젝트 루트 디렉토리에서 다음의 명령을 실행하세요.

```bash
npm run dev
```

## 배포

프로젝트의 배포 버전을 생성하기 위해 빌드 스크립트를 실행합니다.

```bash
npm run build:production
```

개발 환경 배포 빌드는 build:develop 스크립트를 사용해주세요.
운영 환경 빌드는 build:production 스크립트를 사용해주세요.

## 문서

프로젝트 설계 문서는 design 디렉토리에 마크다운 파일로 기록되어있습니다.
각각의 설계 문서는 다음과 같습니다.

- [요구사항 정의서](https://github.com/ssuminii/devcamp-onboarding-template/blob/main/design/%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EC%A0%95%EC%9D%98%EC%84%9C.md)
  - 제품이 제공해야되는 기능 요구 정의서입니다.
  - 요구사항 정의서에 기술된 기능은 최소 기능 요구사항이며 추상적일 수 있으며 기능의 구체화는 제품 구현 단계에서 이루어집니다.
- [프로젝트 설계서](https://github.com/ssuminii/devcamp-onboarding-template/blob/main/design/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%A0%95%EC%9D%98%EC%84%9C.md)
  - 요구사항 정의서를 기반으로 프로젝트를 설계합니다.
- [기능 정의서](https://github.com/ssuminii/devcamp-onboarding-template/blob/main/design/%EA%B8%B0%EB%8A%A5%EC%A0%95%EC%9D%98%EC%84%9C.md)
  - 사용자 스토리 기반으로 세부 기능을 정의합니다.
