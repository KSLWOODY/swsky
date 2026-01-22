# 우리방 조회 페이지 (GitHub Pages)

## 구성
- `index.html` : 조회/검색/필터 페이지
- `admin.html` : 관리자 업로드(엑셀/CSV) → 공유 링크 생성
- `data.csv` : 기본 데이터(영구 반영용)
- `bg.png` : 배경 이미지

## 배포 (GitHub Pages)
1. 이 폴더 내용을 그대로 GitHub repo 루트에 업로드
2. GitHub → Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
3. 생성된 URL로 접속

## 데이터 업데이트
- 영구 반영: `data.csv`를 교체
- 임시 공유: `admin.html`에서 파일 업로드 → 생성된 링크 공유
