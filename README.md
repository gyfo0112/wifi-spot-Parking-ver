# wifi-spot(Parking-ver) 📍

공공 주차장 데이터를 카카오맵 위에 표시해주는 앱입니다.

## 📌 프로젝트 소개
장소 검색 / 지도 마커 표시 / 즐겨찾기 기능을 제공하며
localStorage로 즐겨찾기를 저장합니다.

## ⚙️ 주요 기능
- 카카오맵 마커 표시 및 인포윈도우
- 키워드 실시간 검색 및 필터링
- 즐겨찾기 추가 / 제거 / 토글
- localStorage 즐겨찾기 영구 저장
- Context API 전역 상태 관리

## 🛠 사용 기술
- React (useState, useEffect, useRef, useMemo, useCallback)
- React Router DOM
- Kakao Maps API
- Tailwind CSS
- Vite

## 🚀 실행 방법
```bash
npm install
npm run dev
```

## 🔑 환경 변수 설정
프로젝트 루트에 `.env` 파일 생성 후 아래 내용 추가

```
VITE_KAKAO_MAP_KEY=발급받은_API_KEY
```
