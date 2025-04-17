# 📝 자민 이력서 프로젝트

이 프로젝트는 정적 HTML, TailwindCSS, 그리고 Docker + Nginx를 이용해 만든 **개인 이력서 웹 페이지**입니다.

## 📦 기술 스택

- HTML + TailwindCSS
- 바닐라 JavaScript
- Nginx (정적 파일 서빙)
- Docker (컨테이너 기반 실행)

## 🚀 실행 방법 (Docker)

```bash
docker run --name jahmin-nginx -v $(pwd):/usr/share/nginx/html:ro -p 28181:80 -d nginx
구성

index.html : 메인 이력서 페이지
Docker : 정적 서버 실행 환경
src/ (향후 Spring Boot API 연동 예정)
✨ 앞으로 계획

Spring Boot로 API 연동
DB 연결해서 동적 데이터 제공
도메인 연결 (jahmin.info)
