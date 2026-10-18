# NestJS 기반 미니 게시판

NestJS와 Prisma를 직접 학습하고 활용하기 위해 개발한 간단한 CRUD 게시판 프로젝트입니다.

**배포 URL**: https://nestjs-test-web.vercel.app/

**Frontend Repository:** https://github.com/bestallround/nestjs-test-web

## 기술 스택

| 구분 | 기술 | 배포 환경 |
|---|---|---|
| Frontend | Next.js, TypeScript | Vercel |
| Backend | NestJS, TypeScript | AWS EC2 |
| Database | PostgreSQL | AWS RDS |
| ORM | Prisma | - |
| Local DB | PostgreSQL, Docker | Local |

## 주요 기능

- 게시글 CRUD (작성, 목록·상세 조회, 수정, 삭제)

## 아키텍처

```text
Browser
   │
   ▼
Next.js (Vercel)
   │
   ▼
NestJS (AWS EC2)
   │
   ▼
Prisma ORM
   │
   ▼
PostgreSQL (AWS RDS)
```

로컬 개발 환경에서는 Docker 기반 PostgreSQL을 사용합니다.
