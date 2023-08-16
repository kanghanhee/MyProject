# BBangMap Server
> 🥐 당신의 후회없는 빵 선택을 도와줄 브레드 맵, 지도기반 **빵집 추천** 앱 서비스
- 앱 출시 [iOS](https://apps.apple.com/kr/app/%EB%B9%B5%EB%8F%99%EC%97%AC%EC%A7%80%EB%8F%84/id1595032110), [AOS](https://play.google.com/store/apps/details?id=bbangmap.com&pli=1)


![표지](https://user-images.githubusercontent.com/76844556/168022567-8200bb68-92b7-43f3-8143-2ee08b0591be.png)
<p float="left">
<image width=30% src="https://user-images.githubusercontent.com/76844556/168022804-1b3722c8-d7ca-48f8-81c8-ff178610d4f5.png">
<image width=30% src="https://user-images.githubusercontent.com/76844556/168022793-794c37c6-6e03-4418-a4fa-53885c6a9ce9.png">
<image width=30% src="https://user-images.githubusercontent.com/76844556/168022777-a56d8304-1e3a-4cf8-967d-7ef61f6a2ec3.png">
</p>
<p float="left">
<image width=30% src="https://user-images.githubusercontent.com/76844556/168022696-e6fc9d6b-74f0-4a19-8c60-ac5a6ffe8a8e.png">
<image width=30% src="https://user-images.githubusercontent.com/76844556/168022672-4f089eb8-0ab7-42f1-81e2-3787843466e2.png">
</p>

---
# Server
- REST ful API
- Admin Service

# Development Environment
- Express 4.17.1
- Node.js 12
- Mysql2 2.3.2
- JsonWebToken
- Sequelize 6.11.0
- AWS EC2, RDS, S3
- Git Actions
- Slack Webhook

# ERD
![bbang_map_erd](https://user-images.githubusercontent.com/76844556/168024339-ecc7f962-78f0-410b-ab13-97252f9bc00b.png)

# Foldering
```
🗂 BBangMap-Server
    🗂 api
        🗂 routes
            🗂 auth
            🗂 bakery
            🗂 curation
            🗂 mission
            🗂 review
            🗂 user
            - index.js
        - index.js
    🗂 src
        🗂 auth
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 bakery
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 curation
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 mission
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 review
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 user
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        - index.js
    🗂 models
        🗂 modelUtil
        - index.js
    🗂 modules
        🗂 multer
        🗂 uuidUtil
        - definition.js
        - jwt.js
        - responseMessage.js
        - statusCode.js
        - util.js
    🗂 config
        - config.json
        - s3.js
        - secretJwtKey.js
    🗂 other
        - slackAPI.js
        - slackSender.js
        - jwt.js
        - relationStatus.js
        - reportReason.js
        - responseMessage.js
        - slackMessage.js
        - statusCode.js
    🗂 middlewares
        - authUtil.js
```

# Convention
- [Commit Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Commit-Convention)
- [Coding Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Coding-Convention)
- [Git Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Git-Convention)

# Communication
- Github
- Asana
- Notion
- Slack
- Figma

# Team
- Server 강한희 이솔 이현종
