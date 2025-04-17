# 🧑‍💻 자민 이력서 프로젝트 (Resume Web Project)

> **Nginx + HTML + Docker** 조합으로 만든 나만의 이력서 웹사이트  
> 터미널 기반 개발에 재미를 느끼며 한 줄씩 쌓아가는 개발자의 성장기

---

## 📸 Preview

![screenshot](https://via.placeholder.com/800x400?text=Resume+Preview+Here)

> *(원하면 실제 이력서 스크린샷을 올리고 링크 교체 가능)*

---

## 🚀 프로젝트 소개

- 정적 HTML 기반 이력서 웹페이지
- TailwindCSS로 빠르고 깔끔한 디자인
- Docker + Nginx 조합으로 어디서든 실행 가능
- Vanilla JavaScript로 향후 API 연동 준비 중

---

## 🛠 기술 스택

| 역할 | 기술 |
|------|------|
| 프론트 | HTML, TailwindCSS, JavaScript |
| 서버 | Nginx (정적 웹서버) |
| 개발환경 | Docker, VSCode, 터미널, iTerm2 |
| 향후 예정 | Spring Boot, MySQL, GitHub Actions |

---

## 🧪 실행 방법

```bash
# 현재 디렉토리에 index.html 존재 시 아래 명령어 실행
docker run --name jahmin-nginx -v $(pwd):/usr/share/nginx/html:ro -p 28181:80 -d nginx

# 브라우저에서 접속
http://localhost:28181

