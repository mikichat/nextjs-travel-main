# Next.js Travel Management System

이 프로젝트는 Next.js 14, TypeScript, Tailwind CSS를 사용하여 구축된 여행 관리 시스템 대시보드입니다.

## 🚀 기술 스택

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Database**: [SQLite](https://www.sqlite.org/index.html) (via `sqlite` & `sqlite3`)
- **State Management**: React Context API

## 📂 프로젝트 구조

```
├── app/                # Next.js App Router 페이지 및 레이아웃
├── components/         # 재사용 가능한 UI 컴포넌트
│   ├── pages/          # 대시보드 등 페이지별 컴포넌트
│   └── ...
├── context/            # 전역 상태 관리를 위한 Context
├── lib/                # 데이터베이스 연결 및 유틸리티 (db.ts)
├── types/              # TypeScript 타입 정의
├── public/             # 정적 파일
└── ...
```

## ✨ 주요 기능

- **대시보드**: 주요 지표 및 현황 파악
- **사이드바 네비게이션**: 예약, 고객, 상품, 견적, 알림 등 주요 메뉴 접근
- **알림 시스템**: 읽지 않은 알림 카운트 표시
- **SQLite 연동**: 로컬 데이터베이스를 통한 데이터 관리

## 🛠️ 설치 및 실행 방법

1. **의존성 설치**

   ```bash
   npm install
   ```

2. **개발 서버 실행**

   ```bash
   npm run dev
   ```

   브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어 확인하세요.

3. **빌드 및 시작 (프로덕션)**

   ```bash
   npm run build
   npm start
   ```

## 📝 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.
