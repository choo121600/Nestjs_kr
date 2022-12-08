---
description: Nest.js 소개 페이지 입니다.
---

# Introduction

### 소개

Nest(NestJS)는 효율적이고 확장 가능한 **`Node.js`**서버 측 애플리케이션을 구축하기 위한 프레임워크입니다.\
진보적인 JavaScript를 사용하고 **`TypeScript`**로 구축되어 완벽하게 지원하며(그래도 개발자는 pure JavaScript로 코딩할 수 있습니다.) OOP(Object Oriented Programming), FP(Functional Programming) 및 FRP(Function Reactive Programming) 요소를 결합합니다.

Nest는 내부적으로 **`Express`**(기본값)와 같은 강력한 HTTP 서버 프레임워크를 사용하며 선택적으로 **`Fastify`**도 사용하도록 구성할 수 있습니다.

Nest는 이러한 일반적인 Node.js프레임워크(Express, Fastify) 이상의 추상화 수준을 제공하지만 API를 개발자에게 직접 노출하기도 합니다. 이를 통해 개발자는 기본 플랫폼에서 사용할 수 있는 수많은 타사 모듈을 자유롭게 사용할 수 있습니다.

### 철학

최근 몇 년간 Node.js덕분에 JavaScript는 Frontend 및 Backend 애플리케이션 모두에서 웹의 "공통어"가 되었습니다. 이는 개발자 생산성을 향상시키고 빠르고 테스트 가능하며 확장 가능한 프런트엔드 애플리케이션을 생성할 수 있는 **`Angular`**, **`React`** 및 **`Vue`**와 같은 멋진 프로젝트를 탄생 시켰습니다. 그러나 Node(및 server-side JavaScript)를 위한 우수한 libraries, helpers 및 tools가 많이 존재하지만 그 중 어느 것도 _**아키텍처**_의 주요 문제를 효과적으로 해결하지 못합니다.

Nest는 개발자와 팀이 테스트 가능하고 확장 가능하며 느슨하게 결합되고 쉽게 유지 관리할 수 있는 애플리케이션을 만들 수 있는 즉시 사용 가능한 애플리케이션 아키텍처를 제공합니다. 아키텍처는 Angular에서 크게 영감을 받았습니다.

### 설치

시작하려면, Nest CLI를 사용하여 프로젝트를 스케폴드하거나 시작 프로젝트를 클론을 떠서 시작할 수 있습니다. (둘 다 같은 결과를 생성합니다.)

Nest CLI로 프로젝트를 스케폴딩하려면 아래와 같은 명령어를 실행하세요. 이렇게 하면 새 프로젝트 디렉토리가 생성되고 초기 핵심 Nest파일 및 지원 모듈로 디렉토리가 채워져 프로젝트의 기본 구조가 생성됩니다. 처음 사용하는 사용자에게는 NestCLI로 새 프로젝트를 만드는 것이 좋습니다. First Steps에서 이 접근 방식으로 계속 진행할 것입니다.

```
$ npm i -g @nestjs/cli
$ nest new project-name
```

#### **Hint**

TypeScript의 엄격 모드를 활성화 하여 새 프로젝트를 생성 하려면 명령에 \
`--strict`플래그를 전달합니다.`nest new`

### **대안**

또는 **Git** 을 사용하여 TypeScript 시작 프로젝트를 설치하려면 다음을 수행하십시오 .

```bash
$ git clone https://github.com/nestjs/typescript-starter.git project
$ cd project
$ npm install
$ npm run start
```

#### **Hint**

git 기록 없이 저장소를 복제하려면 degit을 사용할 수 있습니다 .



브라우저를 열고 로 이동합니다 [`http://localhost:3000/`](http://localhost:3000/).

시작 프로젝트의 JavaScript 특징을 설치하려면 `javascript-starter.git`위의 명령 시퀀스에서 사용하십시오.

**npm** (또는 **yarn** ) 으로 코어 및 지원 파일을 설치하여 처음부터 수동으로 새 프로젝트를 생성할 수도 있습니다 . 물론 이 경우 프로젝트 상용구 파일을 직접 만들어야 합니다.

```bash
$ npm i --save @nestjs/core @nestjs/common rxjs reflect-metadata
```
