<p align="center">
<img width="100px" src="https://i.ibb.co/MZVkxm8/fur-icon.png" align="center" alt="GitHub Readme Stats" />
<h1 align="center">Fur-Fact</h1>
<h3 align="center">펫 모발을 이용한 생체 정보 분석 레포트와 사료 추천 서비스</h3>
</p>

## Medium

[Fur-Fact Medium](https://medium.com/@ickim1218/펫-모발을-이용한-생체-정보-분석-레포트와-사료-추천-서비스-3ba691bf1b24)

## Core Features

1. 데이터 결과가 들어간 xml 파일을 업로드하여 데이터베이스에 저장
2. 데이터의 결과를 쉽게 알아볼 수 있도록 **시각화**된 차트 제공
3. 검사 결과에 알맞은 **사료 추천**

## Demo

- 메인 페이지
- 레포트 페이지
- 수의사 페이지
- 등…..

## System Architecture

![fur-arc.png](https://github.com/user-attachments/assets/869f760a-2d13-402f-a9d0-5a54074ad62e)

## Tech Stack

|                                                                                                                                                                                                                                                   Frontend                                                                                                                                                                                                                                                   |                                                                                                                                              Backend                                                                                                                                              |                                                                                                                                                                                                                                                                   DevOps                                                                                                                                                                                                                                                                    |                                                                                                 Monitoring                                                                                                 |                                                                                                                                                                                                                                                    ETC                                                                                                                                                                                                                                                     |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"/><br><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white"/><br><img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/><br><img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=Vite&logoColor=white"/><br><img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat&logo=PWA&logoColor=white"/> | <img src="https://img.shields.io/badge/Node.js-FA04E?style=flat&logo=Node.js&logoColor=white"/><br><img src="https://img.shields.io/badge/mysql-4479A1?style=flat&logo=mysql&logoColor=white"><br><img src="https://img.shields.io/badge/Express-000000?style=flat&logo=Express&logoColor=white"> | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white"/><br><img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white"/><br><img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=Amazon S3&logoColor=white"/><br><img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=amazonrds&logoColor=white"/><br><img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat&logo=GitHub Actions&logoColor=white"/> | <img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=Grafana&logoColor=white"/><br><img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=Prometheus&logoColor=white"/> | <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white"/><br><img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white"/><br><img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white"/><br><img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=Postman&logoColor=white"/><br><img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=white"/><br> |

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

## Team Members

<table width="1000">
<thead>
</thead>
<tbody>
<tr>
<th>Pictures</th>
<td width="100" align="center">
<a href="https://github.com/BellYun">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U079CFQMZ8S-04a4ab3dbfe9-512" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Kiminni">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U079F0EASMS-6caf86eabacd-512" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/kimich1218">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U079F0E88UC-5135de681c7a-512" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/egg-silver">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U0799JKBWGM-7d358d7bbea8-512" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Ajeong-Im">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U079CFQNKV0-c7b754406a4b-512" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/nagosu">
<img src="https://ca.slack-edge.com/T079H2P7R5E-U0799JK841K-56b691470586-512" width="60" height="60">
</a>
</td>
</tr>
<tr>
<th>Name</th>
<td width="100" align="center">정종윤</td>
<td width="100" align="center">이민기</td>
<td width="100" align="center">김인철</td>
<td width="100" align="center">이지은</td>
<td width="100" align="center">임아정</td>
<td width="100" align="center">박진우</td>
</tr>
<tr>
<th>Position</th>
<td width="150" align="center">
Leader<br>
Frontend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
</td>
<td width="150" align="center">
Frontend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
</td>
<td width="150" align="center">
Frontend<br>
</td>
</tr>
<tr>
<th>GitHub</th>
<td width="100" align="center">
<a href="https://github.com/BellYun">
<img src="http://img.shields.io/badge/BellYun-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Kiminni">
<img src="http://img.shields.io/badge/Kiminni-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/kimich1218">
<img src="http://img.shields.io/badge/kimich1218-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/egg-silver">
<img src="http://img.shields.io/badge/eggsilver-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Ajeong-Im">
<img src="http://img.shields.io/badge/AjeongIm-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/nagosu">
<img src="http://img.shields.io/badge/nagosu-green?style=social&logo=github"/>
</a>
</td>
</tr>
</tbody>
</table>
