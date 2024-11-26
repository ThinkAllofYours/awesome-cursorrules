# Awesome CursorRules [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <a href="https://patrickjs.com" target="_blank">
    <img src="/cursor-ai-logo.png" alt="Awesome CursorRules" />
  </a>
</p>

## 이 프로젝트는 PatrickJS에서 만든 프로젝트를 fork한 프로젝트입니다

링크는  [여기](https://github.com/PatrickJS/awesome-cursorrules)에서 확인할 수 있습니다.

Cursor AI 경험을 향상시키기 위한 멋진 .cursorrules 파일 모음입니다.

[Cursor AI](https://cursor.sh/)는 AI 기반 코드 에디터입니다. `.cursorrules` 파일은 Cursor AI가 코드를 생성할 때 따라야 할 사용자 정의 규칙을 정의하여 특정 요구사항과 선호도에 맞게 동작을 조정할 수 있게 해줍니다.

## .cursorrules가 필요한 이유?

`.cursorrules`는 개발자가 프로젝트별 지침을 AI에게 정의할 수 있게 해주는 Cursor AI의 강력한 기능입니다. 다음과 같은 이유로 사용하면 좋습니다:

1. **AI 동작 커스터마이징**: `.cursorrules` 파일은 AI의 응답을 프로젝트의 특정 요구사항에 맞게 조정하여 더 관련성 있고 정확한 코드 제안을 보장합니다.

2. **일관성**: `.cursorrules` 파일에서 코딩 표준과 모범 사례를 정의하여 AI가 프로젝트의 스타일 가이드라인에 맞는 코드를 생성하도록 할 수 있습니다.

3. **컨텍스트 인식**: 자주 사용되는 메서드, 아키텍처 결정 또는 특정 라이브러리와 같은 프로젝트에 대한 중요한 컨텍스트를 AI에 제공하여 더 정보에 기반한 코드 생성이 가능합니다.

4. **생산성 향상**: 잘 정의된 규칙을 통해 AI는 수동 편집이 덜 필요한 코드를 생성할 수 있어 개발 프로세스가 빨라집니다.

5. **팀 조율**: 팀 프로젝트의 경우, 공유된 `.cursorrules` 파일을 통해 모든 팀원이 일관된 AI 지원을 받아 코딩 관행의 통일성을 촉진할 수 있습니다.

6. **프로젝트별 지식**: 프로젝트의 구조, 종속성 또는 고유한 요구사항에 대한 정보를 포함하여 AI가 더 정확하고 관련성 있는 제안을 제공하도록 할 수 있습니다.

프로젝트의 루트 디렉토리에 `.cursorrules` 파일을 생성하여 이러한 이점을 활용하고 Cursor AI와의 코딩 경험을 향상시킬 수 있습니다.

## 사용 방법

### 방법 1

1. 아직 설치하지 않았다면 [Cursor AI](https://cursor.sh/)를 설치하세요.
2. 위의 규칙들을 살펴보고 필요에 맞는 `.cursorrules` 파일을 찾으세요.
3. 선택한 `.cursorrules` 파일을 프로젝트의 루트 디렉토리에 복사하세요.
4. 프로젝트의 특정 요구사항에 맞게 규칙을 커스터마이징하세요.

- [Awesome CursorRules ](#awesome-cursorrules-)
  - [Why .cursorrules?](#cursorrules가-필요한-이유)
  - [사용 방법](#사용-방법)
  - [규칙](#방법-1)
    - [프론트엔드 프레임워크와 라이브러리](#프론트엔드-프레임워크와-라이브러리)
    - [백엔드와 풀스택](#백엔드와-풀스택)
    - [모바일 개발](#모바일-개발)
    - [CSS와 스타일링](#css와-스타일링)
    - [상태 관리](#상태-관리)
    - [데이터베이스와 API](#데이터베이스와-api)
    - [테스팅](#테스팅)
    - [빌드 도구와 개발](#빌드-도구와-개발)
    - [언어별](#언어별)
    - [기타](#기타)
  - [디렉토리](#디렉토리)
  - [기여하기](#기여하기)
  - [라이센스](#라이센스)

## 기여하기

기여는 언제나 환영합니다! 공유하고 싶은 훌륭한 `.cursorrules` 파일이 있다면:

1. 이 저장소를 포크하세요.
2. `rules` 디렉토리에 새 폴더를 만드세요. 폴더 이름은 다음 패턴을 따라야 합니다:
   `technology-focus-cursorrules-prompt-file`
   예: `react-typescript-cursorrules-prompt-file`
3. 새 폴더에 `.cursorrules` 파일을 추가하세요.
4. 선택적으로 폴더에 README.md를 포함하여 크레딧과 간단한 설명을 제공하세요.
5. 메인 README.md 파일을 업데이트하고 적절한 카테고리에 기여 내용을 추가하세요.
6. 이 저장소의 루트에 있는 [`.cursorrules`](./.cursorrules) 파일의 가이드라인을 따르는지 확인하세요.
7. 풀 리퀘스트를 제출하세요.

### 프론트엔드 프레임워크와 라이브러리

- [Angular (Novo Elements)](./rules/angular-novo-elements-cursorrules-prompt-file/.cursorrules)
- [Angular (TypeScript)](./rules/angular-typescript-cursorrules-prompt-file/.cursorrules)
- [Astro (TypeScript)](./rules/astro-typescript-cursorrules-prompt-file/.cursorrules)
- [Cursor AI (React, TypeScript, shadcn/ui)](./rules/cursor-ai-react-typescript-shadcn-ui-cursorrules-p/.cursorrules)
- [Next.js 15 (React 19, Vercel AI, Tailwind)](./rules/nextjs15-react19-vercelai-tailwind-cursorrules-prompt-file/.cursorrules)
- [Next.js 14 (Tailwind, SEO)](./rules/cursorrules-cursor-ai-nextjs-14-tailwind-seo-setup/.cursorrules)
- [Next.js (React, Tailwind)](./rules/nextjs-react-tailwind-cursorrules-prompt-file/.cursorrules)
- [Next.js (React, TypeScript)](./rules/nextjs-react-typescript-cursorrules-prompt-file/.cursorrules)
- [Next.js (SEO Development)](./rules/nextjs-seo-dev-cursorrules-prompt-file/.cursorrules)
- [Next.js (Supabase Todo App)](./rules/nextjs-supabase-todo-app-cursorrules-prompt-file/.cursorrules)
- [Next.js (Tailwind, TypeScript)](./rules/nextjs-tailwind-typescript-apps-cursorrules-prompt/.cursorrules)
- [Next.js (TypeScript App)](./rules/nextjs-typescript-app-cursorrules-prompt-file/.cursorrules)
- [Next.js (TypeScript)](./rules/nextjs-typescript-cursorrules-prompt-file/.cursorrules)
- [Next.js (TypeScript, Tailwind)](./rules/nextjs-typescript-tailwind-cursorrules-prompt-file/.cursorrules)
- [Next.js (Vercel, Supabase)](./rules/nextjs-vercel-supabase-cursorrules-prompt-file/.cursorrules)
- [Next.js (Vercel, TypeScript)](./rules/nextjs-vercel-typescript-cursorrules-prompt-file/.cursorrules)
- [Next.js (App Router)](./rules/nextjs-app-router-cursorrules-prompt-file/.cursorrules)
- [Next.js (Material UI, Tailwind CSS)](./rules/nextjs-material-ui-tailwind-css-cursorrules-prompt/.cursorrules)
- [Qwik (Basic Setup with TypeScript and Vite)](./rules/qwik-basic-cursorrules-prompt-file/.cursorrules)
- [Qwik (with Tailwind CSS)](./rules/qwik-tailwind-cursorrules-prompt-file/.cursorrules)
- [React Components Creation](./rules/react-components-creation-cursorrules-prompt-file/.cursorrules)
- [React (Next.js UI Development)](./rules/react-nextjs-ui-development-cursorrules-prompt-fil/.cursorrules)
- [React (TypeScript, Next.js, Node.js)](./rules/react-typescript-nextjs-nodejs-cursorrules-prompt-/.cursorrules)
- [React (TypeScript, Symfony)](./rules/react-typescript-symfony-cursorrules-prompt-file/.cursorrules)
- [Solid.js (Basic Setup)](./rules/solidjs-basic-cursorrules-prompt-file/.cursorrules)
- [Solid.js (TypeScript)](./rules/solidjs-typescript-cursorrules-prompt-file/.cursorrules)
- [Solid.js (Tailwind CSS)](./rules/solidjs-tailwind-cursorrules-prompt-file/.cursorrules)
- [Svelte 5 vs Svelte 4](./rules/svelte-5-vs-svelte-4-cursorrules-prompt-file/.cursorrules)
- [SvelteKit (RESTful API, Tailwind CSS)](./rules/sveltekit-restful-api-tailwind-css-cursorrules-pro/.cursorrules)
- [SvelteKit (Tailwind CSS, TypeScript)](./rules/sveltekit-tailwindcss-typescript-cursorrules-promp/.cursorrules)
- [SvelteKit (TypeScript Guide)](./rules/sveltekit-typescript-guide-cursorrules-prompt-file/.cursorrules)
- [Vue 3 (Nuxt 3 Development)](./rules/vue-3-nuxt-3-development-cursorrules-prompt-file/.cursorrules)
- [Vue 3 (Nuxt 3, TypeScript)](./rules/vue-3-nuxt-3-typescript-cursorrules-prompt-file/.cursorrules)
- [Vue 3 (Composition API)](./rules/vue3-composition-api-cursorrules-prompt-file/.cursorrules)

### 백엔드와 풀스택

- [Deno Integration](./rules/deno-integration-techniques-cursorrules-prompt-fil/.cursorrules)
- [Elixir Engineer Guidelines](./rules/elixir-engineer-guidelines-cursorrules-prompt-file/.cursorrules)
- [Elixir (Phoenix, Docker)](./rules/elixir-phoenix-docker-setup-cursorrules-prompt-fil/.cursorrules)
- [ES Module (Node.js)](./rules/es-module-nodejs-guidelines-cursorrules-prompt-fil/.cursorrules)
- [Go Backend Scalability](./rules/go-backend-scalability-cursorrules-prompt-file/.cursorrules)
- [Go ServeMux REST API](./rules/go-servemux-rest-api-cursorrules-prompt-file/.cursorrules)
- [Go (Basic Setup)](./rules/htmx-go-basic-cursorrules-prompt-file/.cursorrules)
- [Go with Fiber](./rules/htmx-go-fiber-cursorrules-prompt-file/.cursorrules)
- [HTMX (Basic Setup)](./rules/htmx-basic-cursorrules-prompt-file/.cursorrules)
- [HTMX (Flask)](./rules/htmx-flask-cursorrules-prompt-file/.cursorrules)
- [HTMX (Django)](./rules/htmx-django-cursorrules-prompt-file/.cursorrules)
- [Java (Springboot, JPA)](./rules/java-springboot-jpa-cursorrules-prompt-file/.cursorrules)
- [Knative (Istio, Typesense, GPU)](./rules/knative-istio-typesense-gpu-cursorrules-prompt-fil/.cursorrules)
- [Laravel (PHP 8.3)](./rules/laravel-php-83-cursorrules-prompt-file/.cursorrules)
- [Laravel (TALL Stack)](./rules/laravel-tall-stack-best-practices-cursorrules-prom/.cursorrules)
- [Node.js (MongoDB)](./rules/nodejs-mongodb-cursorrules-prompt-file-tutorial/.cursorrules)
- [Node.js (MongoDB, JWT, Express, React)](./rules/nodejs-mongodb-jwt-express-react-cursorrules-promp/.cursorrules)
- [Python (FastAPI)](./rules/py-fast-api/.cursorrules)
- [Python (FastAPI)](./rules/cursorrules-file-cursor-ai-python-fastapi-api/.cursorrules)
- [Python 3.12 (FastAPI Best Practices)](./rules/python-312-fastapi-best-practices-cursorrules-prom/.cursorrules)
- [Python (Django Best Practices)](./rules/python-django-best-practices-cursorrules-prompt-fi/.cursorrules)
- [Python (FastAPI Best Practices)](./rules/python-fastapi-best-practices-cursorrules-prompt-f/.cursorrules)
- [Python (FastAPI Scalable API)](./rules/python-fastapi-scalable-api-cursorrules-prompt-fil/.cursorrules)
- [Python (Flask JSON Guide)](./rules/python-flask-json-guide-cursorrules-prompt-file/.cursorrules)
- [TypeScript (NestJS Best Practices)](./rules/typescript-nestjs-best-practices-cursorrules-promp/.cursorrules)
- [WordPress (PHP, Guzzle, Gutenberg)](./rules/wordpress-php-guzzle-gutenberg-cursorrules-prompt-/.cursorrules)
- [WordPress (macOS)](./rules/cursorrules-cursor-ai-wordpress-draft-macos-prompt/.cursorrules)

### 모바일 개발

- [React Native Expo](./rules/react-native-expo-cursorrules-prompt-file/.cursorrules)
- [SwiftUI Guidelines](./rules/swiftui-guidelines-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Expo, Jest, Detox)](./rules/typescript-expo-jest-detox-cursorrules-prompt-file/.cursorrules)

### CSS와 스타일링

- [Tailwind CSS (Next.js Guide)](./rules/tailwind-css-nextjs-guide-cursorrules-prompt-file/.cursorrules)
- [Tailwind (React, Firebase)](./rules/tailwind-react-firebase-cursorrules-prompt-file/.cursorrules)
- [Tailwind (shadcn/ui Integration)](./rules/tailwind-shadcn-ui-integration-cursorrules-prompt-/.cursorrules)
- [HTML (Tailwind CSS, JavaScript)](./rules/html-tailwind-css-javascript-cursorrules-prompt-fi/.cursorrules)
- [JavaScript (Astro, Tailwind CSS)](./rules/javascript-astro-tailwind-css-cursorrules-prompt-f/.cursorrules)
- [React (Styled Components)](./rules/react-styled-components-cursorrules-prompt-file/.cursorrules)
- [React (Chakra UI)](./rules/react-chakra-ui-cursorrules-prompt-file/.cursorrules)

### 상태 관리

- [React (Redux, TypeScript)](./rules/react-redux-typescript-cursorrules-prompt-file/.cursorrules)
- [React (MobX)](./rules/react-mobx-cursorrules-prompt-file/.cursorrules)
- [React (React Query)](./rules/react-query-cursorrules-prompt-file/.cursorrules)

### 데이터베이스와 API

- [GraphQL (Apollo Client)](./rules/react-graphql-apollo-client-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Axios)](./rules/typescript-axios-cursorrules-prompt-file/.cursorrules)

### 테스팅

- [TypeScript (Expo, Jest, Detox)](./rules/typescript-expo-jest-detox-cursorrules-prompt-file/.cursorrules)

### 빌드 도구와 개발

- [Chrome Extension (JavaScript/TypeScript)](./rules/chrome-extension-dev-js-typescript-cursorrules-pro/.cursorrules)
- [GitHub Code Quality](./rules/github-code-quality-cursorrules-prompt-file/.cursorrules)
- [GitHub Instructions](./rules/github-cursorrules-prompt-file-instructions/.cursorrules)
- [Kubernetes (MkDocs Documentation)](./rules/kubernetes-mkdocs-documentation-cursorrules-prompt/.cursorrules)
- [Linux (NVIDIA CUDA, Python)](./rules/linux-nvidia-cuda-python-cursorrules-prompt-file/.cursorrules)
- [Optimize (DRY, SOLID Principles)](./rules/optimize-dry-solid-principles-cursorrules-prompt-f/.cursorrules)
- [Python Containerization](./rules/python-containerization-cursorrules-prompt-file/.cursorrules)
- [Python (GitHub Setup)](./rules/python-github-setup-cursorrules-prompt-file/.cursorrules)
- [Tauri (Svelte, TypeScript Guide)](./rules/tauri-svelte-typescript-guide-cursorrules-prompt-f/.cursorrules)
- [TypeScript Code Convention](./rules/typescript-code-convention-cursorrules-prompt-file/.cursorrules)

### 언어별

- [JavaScript/TypeScript 코드 품질](./rules/javascript-typescript-code-quality-cursorrules-pro/.cursorrules)
- [JavaScript (Chrome APIs)](./rules/javascript-chrome-apis-cursorrules-prompt-file/.cursorrules)
- [Optimize (Rell Blockchain Code)](./rules/optimize-rell-blockchain-code-cursorrules-prompt-f/.cursorrules)
- [Pandas (scikit-learn Guide)](./rules/pandas-scikit-learn-guide-cursorrules-prompt-file/.cursorrules)
- [Plasticode (Telegram API)](./rules/plasticode-telegram-api-cursorrules-prompt-file/.cursorrules)
- [PyQt6 (EEG Processing)](./rules/pyqt6-eeg-processing-cursorrules-prompt-file/.cursorrules)
- [Python/TypeScript Guide](./rules/python--typescript-guide-cursorrules-prompt-file/.cursorrules)
- [Python Best Practices](./rules/python-cursorrules-prompt-file-best-practices/.cursorrules)
- [Python Developer](./rules/python-developer-cursorrules-prompt-file/.cursorrules)
- [Python Projects Guide](./rules/python-projects-guide-cursorrules-prompt-file/.cursorrules)
- [PyTorch (scikit-learn)](./rules/pytorch-scikit-learn-cursorrules-prompt-file/.cursorrules)
- [Solidity (Hardhat)](./rules/solidity-hardhat-cursorrules-prompt-file/.cursorrules)
- [Solidity (React Blockchain Apps)](./rules/solidity-react-blockchain-apps-cursorrules-prompt-/.cursorrules)
- [TypeScript (LLM Tech Stack)](./rules/typescript-llm-tech-stack-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Node.js, Next.js, AI)](./rules/typescript-nodejs-nextjs-ai-cursorrules-prompt-fil/.cursorrules)
- [TypeScript (Node.js, Next.js, React, UI, CSS)](./rules/typescript-nodejs-nextjs-react-ui-css-cursorrules-/.cursorrules)
- [TypeScript (Node.js, React, Vite)](./rules/typescript-nodejs-react-vite-cursorrules-prompt-fi/.cursorrules)
- [TypeScript (React, Next.js, Cloudflare)](./rules/typescript-react-nextjs-cloudflare-cursorrules-pro/.cursorrules)
- [TypeScript (React, NextUI, Supabase)](./rules/typescript-react-nextui-supabase-cursorrules-promp/.cursorrules)
- [TypeScript (shadcn/ui, Next.js)](./rules/typescript-shadcn-ui-nextjs-cursorrules-prompt-fil/.cursorrules)
- [TypeScript (Vite, Tailwind)](./rules/typescript-vite-tailwind-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Vue.js)](./rules/typescript-vuejs-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Zod, Tailwind, Next.js)](./rules/typescript-zod-tailwind-nextjs-cursorrules-prompt-/.cursorrules)
- [WebAssembly (Z80 Cellular Automata)](./rules/webassembly-z80-cellular-automata-cursorrules-prom/.cursorrules)
- [TypeScript (Next.js)](./rules/typescript-nextjs-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Next.js, React)](./rules/typescript-nextjs-react-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Next.js, React, Tailwind, Supabase)](./rules/typescript-nextjs-react-tailwind-supabase-cursorru/.cursorrules)
- [TypeScript (Next.js, Supabase)](./rules/typescript-nextjs-supabase-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Node.js, Next.js App)](./rules/typescript-nodejs-nextjs-app-cursorrules-prompt-fi/.cursorrules)
- [TypeScript (React)](./rules/typescript-react-cursorrules-prompt-file/.cursorrules)
- [TypeScript (Clasp App Script)](./rules/typescript-clasp-cursorrules-prompt-file/.cursorrules)

### 기타

- [ASCII 시뮬레이션 게임](./rules/ascii-simulation-game-cursorrules-prompt-file/.cursorrules)
- [코드 가이드라인](./rules/code-guidelines-cursorrules-prompt-file/.cursorrules)
- [DragonRuby Best Practices](./rules/dragonruby-best-practices-cursorrules-prompt-file/.cursorrules)
- [Graphical Apps Development](./rules/graphical-apps-development-cursorrules-prompt-file/.cursorrules)
- [Meta-Prompt](./rules/meta-prompt-cursorrules-prompt-file/.cursorrules)
- [Next.js (Type LLM)](./rules/next-type-llm/.cursorrules)
- [Unity (C#)](./rules/unity-cursor-ai-c-cursorrules-prompt-file/.cursorrules)
- [Web App Optimization](./rules/web-app-optimization-cursorrules-prompt-file/.cursorrules)

## 디렉토리

- [CursorList](https://cursorlist.com)
- [CursorDirectory](https://cursor.directory/)

### Cursor에서 CursorRules 추가하기

1. [Cursor AI](https://cursor.sh/)를 설치하세요. 아직 설치하지 않았다면 설치하세요.
2. [vscode-cursor-rules](https://marketplace.visualstudio.com/items?itemName=BeilunYang.cursor-rules) 확장 프로그램을 설치하세요.
3. 명령 팔레트를 엽니다. (Cmd+Shift+P 또는 Ctrl+Shift+P)
4. `Cursor Rules: Add .cursorrules`를 선택하고 다운로드하세요.
5. 프로젝트의 특정 요구사항에 맞게 규칙을 커스터마이징하세요.

기여하는 내용이 원작이거나 기존 작업을 기반으로 한 경우 적절하게 크레딧을 표시해주세요. 기여에 대한 포맷팅, 명명 규칙 및 모범 사례에 대한 자세한 가이드라인은 이 저장소의 루트에 있는 `.cursorrules` 파일을 참조하세요.

---

## 라이센스

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
