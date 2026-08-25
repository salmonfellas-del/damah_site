# DAMAH site

초간단 정적 웹사이트입니다.

## 파일
- index.html : HOME
- damah.html : DAMAH
- style.css : 전체 스타일
- images/ : 사진 폴더

## 사진 넣는 법
images 폴더에 아래 이름으로 사진을 넣으세요.

HOME
- home-01.jpg
- home-02.jpg
- home-03.jpg
- home-04.jpg

DAMAH
- damah-01.jpg
- damah-02.jpg
- damah-03.jpg

기존 파일명을 유지하면 HTML 수정 없이 바로 표시됩니다.

## Cloudflare Pages 배포
가장 빠른 방법:
1. 이 폴더 전체를 GitHub 새 Repository에 업로드
2. Cloudflare Dashboard → Workers & Pages
3. Create → Pages → Connect to Git
4. GitHub Repository 선택
5. Framework preset: None
6. Build command: 비워두기
7. Build output directory: /
8. Deploy
9. Custom domains → damah.haus 추가

Cloudflare에서 도메인을 구매했다면 DNS 연결은 대부분 자동으로 처리됩니다.

## 텍스트 수정
damah.html의 소개문과 footer의 이메일 주소만 원하는 내용으로 바꾸면 됩니다.
