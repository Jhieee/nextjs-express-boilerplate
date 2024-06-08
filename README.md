
# node express 와 nextjs 로 FRONTEND, BACKEND 구성

```json
  "dependencies": {
    "antd": "^5.18.0",
    "express": "^4.19.2",
    "next": "14.2.3",
    "react": "^18",
    "react-dom": "^18"
}
```

## 라이브러리 설치
```bash
npm install
```

## 실행
```json
"scripts": {
    "dev": "npm-run-all --parallel dev:**",
    "dev:client": "next dev",
    "dev:server": "node server/app.js",
    "build": "next build",
    "start": "npm-run-all --parallel start:**",
    "start:client": "next start",
    "start:server": "node server/app.js",
    "lint": "next lint"
},
```

```bash
npm run dev
```