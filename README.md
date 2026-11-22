# 연금건보 체크: 5060 연금, 건보료 계산기

정적 사이트. 빌드 과정 없이 Vercel에 그대로 올립니다.

## 폴더 구성
- index.html: 계산기 3종 (CSS, JS 인라인)
- guide.html, guide/*.html: 해설 글 목록과 9편
- about.html, privacy.html, terms.html: 소개와 문의, 개인정보처리방침, 이용약관
- assets/site.css: 하위 페이지 공용 스타일
- sitemap.xml, robots.txt, vercel.json(cleanUrls), ads.txt(승인 후 사용), og-image.png

## 배포
1. Vercel: Add New, Project, Framework Preset Other, Build Command 비움
2. 배포 주소: https://pension-care-web.vercel.app (canonical, og:url, sitemap.xml, robots.txt에 반영 완료)
3. 구글 서치콘솔, 네이버 서치어드바이저에 sitemap.xml 제출

## 애드센스 신청 순서
1. 자체 도메인 연결 (vercel.app 주소로는 신청하지 않기)
2. 서치콘솔에서 가이드 글 색인 확인 후 신청
3. 승인 후 head에 애드센스 코드 추가, ads.txt의 pub 번호 입력 후 맨 앞 # 삭제

## 해마다 손볼 곳
- index.html 스크립트의 A_VALUE, A_PLUS_200, CAP
- 화면 글, FAQ, 기준표, 가이드 글의 같은 숫자
