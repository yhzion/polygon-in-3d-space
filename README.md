# 3D Polygon Creator

3D 공간에서 점들을 선택하여 폴리곤을 생성하는 웹 애플리케이션입니다.

## 주요 기능

- 3D 공간에서 100개의 무작위 점 생성
- 점 선택을 통한 폴리곤 생성
- 원근감 있는/없는 카메라 모드 전환
- 마우스/터치를 통한 3D 공간 조작
- 선택된 점들의 순서 표시
- 폴리곤 완성 후 선택되지 않은 점들의 반투명 처리
- 전체화면 모드 지원
- 접이식 조작 방법 가이드
- 모바일 기기에서 햅틱 피드백

## 조작 방법

### 데스크톱
- 마우스 드래그: 화면 회전
- 마우스 휠: 확대/축소
- 마우스 우클릭 드래그: 화면 이동
- 점 클릭: 점 선택
- Enter 키: 선택한 점들로 폴리곤 생성
- F11 또는 우측 상단 버튼: 전체화면 전환

### 모바일
- 한 손가락 드래그: 화면 회전
- 두 손가락 핀치: 확대/축소
- 두 손가락 드래그: 화면 이동
- 점 터치: 점 선택
- 하단의 생성하기 버튼: 폴리곤 생성
- 우측 상단 버튼: 전체화면 전환

## 기술 스택

- Three.js: 3D 그래픽 렌더링
- OrbitControls: 카메라 컨트롤
- 반응형 디자인: 모바일/데스크톱 대응

## 특징

- 직관적인 사용자 인터페이스
- 실시간 사용자 가이드 메시지
- 부드러운 애니메이션 효과
- 모바일 터치 최적화
- 고품질 렌더링
  - 안티앨리어싱
  - PCF 소프트 섀도우
  - sRGB 인코딩
  - 다중 조명 시스템 (디렉셔널, 스팟, 포인트 라이트)
- 로딩 화면
- 접이식 조작 가이드
- 모바일 기기 햅틱 피드백

## 사용자 경험 최적화

- 로딩 화면으로 초기 로딩 상태 표시
- 실시간 동작 가이드 메시지
- 모바일에서 더블탭/핀치 줌 방지
- 디바이스별 최적화된 컨트롤 감도
- 반응형 폰트 크기 및 레이아웃

## 브라우저 지원

- 최신 버전의 Chrome, Firefox, Safari, Edge 지원
- WebGL 지원 필요

## 라이선스

MIT License
