# 3D 폴리곤 생성기

3D 공간에서 점들을 선택하여 폴리곤을 생성할 수 있는 웹 애플리케이션입니다.

## 주요 기능

- 3D 공간에서 자유롭게 점 선택
- 원근감 있는/없는 카메라 모드 전환
- 직관적인 3D 조작 (회전, 확대/축소, 이동)
- 선택한 점들로 폴리곤 자동 생성
- 모바일 터치 지원

## 사용 방법

1. 점 선택하기
   - PC: 마우스로 점 클릭
   - 모바일: 화면 터치로 점 선택

2. 화면 조작
   - PC
     - 마우스 드래그: 화면 회전
     - 마우스 휠: 확대/축소
     - 마우스 우클릭 드래그: 화면 이동
   - 모바일
     - 한 손가락 드래그: 화면 회전
     - 두 손가락 핀치: 확대/축소
     - 두 손가락 드래그: 화면 이동

3. 폴리곤 생성
   - PC: Enter 키 또는 '생성하기' 버튼 클릭
   - 모바일: '생성하기' 버튼 터치

## 개발 환경 설정

1. 저장소 클론
```bash
git clone https://github.com/yhzion/3d-polygon-poc.git
cd 3d-polygon-poc
```

2. 의존성 설치
```bash
npm install
```

3. 개발 서버 실행
```bash
# 로컬 서버 실행 (예: http-server 사용)
npx http-server
```

## 기술 스택

- Three.js - 3D 그래픽스 라이브러리
- HTML5 Canvas
- ES6+ JavaScript

## 브라우저 지원

- Chrome (권장)
- Firefox
- Safari
- Edge

## 라이선스

MIT License
