<p align="center">
<img width="100px" src="https://i.ibb.co/MZVkxm8/fur-icon.png" align="center" alt="GitHub Readme Stats" />
<h1 align="center">Fur-Fact</h1>
<h3 align="center">펫 모발을 이용한 생체 정보 분석 레포트와 사료 추천 서비스</h3>
</p>

## Medium

[Fur-Fact Medium](https://medium.com/@ickim1218/펫-모발을-이용한-생체-정보-분석-레포트와-사료-추천-서비스-3ba691bf1b24)

## Demo

- 메인 페이지
- 레포트 페이지
- 수의사 페이지
- 등…..

## System Architecture

![fur-arc.png](https://github.com/user-attachments/assets/869f760a-2d13-402f-a9d0-5a54074ad62e)

## Tech Stack

**frontend**: react, typescript, vite, tailwind css, PWA

**backend**: node.js, express, mysql

**devops**: docker, amazon s3, amazon ec2, github actions

**etc**: github, slack, notion, figma

## ERD

![fur-Erd.png](https://github.com/user-attachments/assets/f7e06453-836b-4ce5-8566-1ac93045ef39)

## API

![Untitled](https://github.com/user-attachments/assets/57121182-e8ec-4008-89b4-b5c60fbfe25c)

## File Directory

<details>
<summary>Frontend</summary>
    
    📦Frontend
     ┣ 📂.github
     ┣ 📂dev-dist
     ┣ 📂node_modules
     ┣ 📂public
     ┃ ┣ 📜firebase-messaging-sw.js
     ┃ ┣ 📜manifest.json
     ┃ ┣ 📜maskable-icon-512x512.png
     ┃ ┣ 📜pwa-192x192.png
     ┃ ┣ 📜pwa-512x512.png
     ┃ ┣ 📜pwa-64x64.png
     ┃ ┗ 📜vite.svg
     ┣ 📂src
     ┃ ┣ 📂api
     ┃ ┃ ┗ 📜config.ts
     ┃ ┣ 📂apis
     ┃ ┃ ┗ 📜patchDeviceToken.ts
     ┃ ┣ 📂assets
     ┃ ┃ ┣ 📜Alarm.png
     ┃ ┃ ┣ 📜Alarm_Filled.png
     ┃ ┃ ┣ 📜Alarm_Focus.png
     ┃ ┃ ┣ 📜Dog.jpg
     ┃ ┃ ┣ 📜Home.png
     ┃ ┃ ┣ 📜Home_Focus.png
     ┃ ┃ ┣ 📜MyPage.png
     ┃ ┃ ┣ 📜MyPage_Focus.png
     ┃ ┃ ┣ 📜logo.png
     ┃ ┃ ┣ 📜react.svg
     ┃ ┃ ┗ 📜setting.png
     ┃ ┣ 📂components
     ┃ ┃ ┣ 📂alarm
     ┃ ┃ ┃ ┗ 📜NotificationItem.tsx
     ┃ ┃ ┣ 📂common
     ┃ ┃ ┃ ┣ 📂Navigation
     ┃ ┃ ┃ ┃ ┣ 📜NavLink.tsx
     ┃ ┃ ┃ ┃ ┗ 📜Navigation.tsx
     ┃ ┃ ┃ ┣ 📜AddInput.tsx
     ┃ ┃ ┃ ┣ 📜FullButton.tsx
     ┃ ┃ ┃ ┣ 📜Input.tsx
     ┃ ┃ ┃ ┣ 📜MoblieLayout.tsx
     ┃ ┃ ┃ ┗ 📜PCLayout.tsx
     ┃ ┃ ┣ 📂main
     ┃ ┃ ┃ ┣ 📂Carousel
     ┃ ┃ ┃ ┃ ┣ 📜Carousel.tsx
     ┃ ┃ ┃ ┃ ┣ 📜CarouselDotButton.tsx
     ┃ ┃ ┃ ┃ ┗ 📜carousel.css
     ┃ ┃ ┃ ┣ 📜AddCard.tsx
     ┃ ┃ ┃ ┣ 📜Modal.tsx
     ┃ ┃ ┃ ┣ 📜PetCard.tsx
     ┃ ┃ ┃ ┣ 📜PetInfoCard.tsx
     ┃ ┃ ┃ ┗ 📜PetInspectionCard.tsx
     ┃ ┃ ┣ 📂result
     ┃ ┃ ┃ ┗ 📜ResultItem.tsx
     ┃ ┃ ┗ 📂selectBox
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┣ 📂pages
     ┃ ┃ ┣ 📂alarm
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┣ 📂login
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┣ 📂main
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┣ 📂result
     ┃ ┃ ┃ ┣ 📂mobile
     ┃ ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┃ ┗ 📜index.ts
     ┃ ┃ ┣ 📂signup
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┣ 📂vetList
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┃ ┗ 📂vetResult
     ┃ ┃ ┃ ┗ 📜index.tsx
     ┃ ┣ 📂store
     ┃ ┃ ┣ 📜useAuthStore.ts
     ┃ ┃ ┗ 📜useEditModeStore.ts
     ┃ ┣ 📂types
     ┃ ┃ ┗ 📜index.ts
     ┃ ┣ 📂utils
     ┃ ┃ ┗ 📂notification
     ┃ ┃ ┃ ┗ 📜index.ts
     ┃ ┣ 📜App.css
     ┃ ┣ 📜firebase.ts
     ┃ ┣ 📜index.css
     ┃ ┣ 📜main.tsx
     ┃ ┣ 📜router.tsx
     ┃ ┗ 📜vite-env.d.ts
     ┣ 📜.eslintrc.cjs
     ┣ 📜.gitignore
     ┣ 📜README.md
     ┣ 📜index.html
     ┣ 📜package-lock.json
     ┣ 📜package.json
     ┣ 📜postcss.config.js
     ┣ 📜sw.js
     ┣ 📜tailwind.config.js
     ┣ 📜tsconfig.app.json
     ┣ 📜tsconfig.json
     ┣ 📜tsconfig.node.json
     ┣ 📜vite.config.ts
     ┗ 📜yarn.lock
  </details>
    
<details>
<summary>Backend</summary>

    📦Backend
     ┣ 📂.idea
     ┣ 📂node_modules
     ┣ 📂db
     ┣ 📂uploads
     ┣ 📂src
     ┃ ┣ 📂api
     ┃ ┃ ┣ 📂furdata
     ┃ ┃ ┃ ┣ 📜controller.js
     ┃ ┃ ┃ ┣ 📜model.js
     ┃ ┃ ┃ ┗ 📜repository.js
     ┃ ┃ ┣ 📂pet
     ┃ ┃ ┃ ┣ 📜controller.js
     ┃ ┃ ┃ ┣ 📜model.js
     ┃ ┃ ┃ ┗ 📜repository.js
     ┃ ┃ ┣ 📂test
     ┃ ┃ ┃ ┣ 📜controller.js
     ┃ ┃ ┃ ┣ 📜model.js
     ┃ ┃ ┃ ┗ 📜repository.js
     ┃ ┃ ┗ 📂user
     ┃ ┃ ┃ ┣ 📜controller.js
     ┃ ┃ ┃ ┣ 📜jwt.js
     ┃ ┃ ┃ ┣ 📜model.js
     ┃ ┃ ┃ ┗ 📜repository.js
     ┃ ┣ 📂data
     ┃ ┃ ┣ 📜initDatabase.js
     ┃ ┃ ┗ 📜sequelize.js
     ┃ ┣ 📂middleware
     ┃ ┃ ┣ 📜jwtVerify.js
     ┃ ┃ ┣ 📜logging.js
     ┃ ┃ ┗ 📜s3Upload.js
     ┃ ┣ 📂swagger
     ┃ ┃ ┣ 📜swagger-furData.yaml
     ┃ ┃ ┣ 📜swagger-pet.yaml
     ┃ ┃ ┣ 📜swagger-test.yaml
     ┃ ┃ ┣ 📜swagger-user.yaml
     ┃ ┃ ┗ 📜swagger.js
     ┃ ┗ 📜router.js
     ┣ 📜.env
     ┣ 📜.gitignore
     ┣ 📜docker-compose.yml
     ┣ 📜Dockerfile
     ┣ 📜index.js
     ┣ 📜init.sql
     ┣ 📜package-lock.json
     ┣ 📜package.json
     ┣ 📜README.md
     ┗ 📜wait-for-it.sh

</details>
