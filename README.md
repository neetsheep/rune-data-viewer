# 룬 정보 데이터 뷰어

게임 룬 정보를 효율적으로 조회할 수 있는 웹 애플리케이션입니다.

## 주요 기능

- **반응형 디자인**: 모바일과 데스크톱 모든 환경에서 최적화된 UI
- **다중 필터링**: 종류, 등급, 효과 카테고리별 필터링
- **정렬 기능**: 모든 컬럼에 대한 오름차순/내림차순 정렬
- **모바일 최적화**: 모바일에서 설명 컬럼 토글 기능
- **크로스 브라우저 호환**: ES5 문법으로 구형 브라우저까지 지원

## 지원 데이터

- **무기 룬**: 전설, 신화 등급
- **방어구 룬**: 전설, 신화 등급  
- **앰블럼 룬**: 전설 등급
- **효과 카테고리**: 공격력 증가, 피해 증가, 치명타 확률, 추가타 확률, 유틸, 기타

## 배포

이 프로젝트는 Vercel에 배포되어 있습니다.

### 로컬 실행

```bash
# 정적 서버로 실행
npx serve .

# 또는 Python으로 실행
python -m http.server 8000
```

### Vercel 배포

```bash
# Vercel CLI 설치 (처음만)
npm install -g vercel

# 배포
vercel

# 프로덕션 배포
vercel --prod
```

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 반응형 디자인, Flexbox
- **Vanilla JavaScript**: ES5 문법으로 최대 호환성 확보
- **Vercel**: 정적 사이트 호스팅

## 브라우저 지원

- Chrome, Firefox, Safari (최신 버전)
- Edge (최신 버전)
- iOS Safari (iOS 10+)
- Android WebView (Android 5+)
- Internet Explorer 11+ 