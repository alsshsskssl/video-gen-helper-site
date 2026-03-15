# Video Gen Helper

YouTube 영상 제작 워크플로우를 자동화하는 웹 기반 도구입니다.

## 주요 기능

- **자막 추출**: YouTube 영상에서 자막을 자동으로 추출합니다.
- **스크립트 작성**: AI를 활용하여 영상 스크립트를 자동 생성합니다.
- **이미지 생성**: 스크립트에 맞는 이미지를 AI로 생성합니다.
- **모션 적용**: 생성된 이미지에 자동으로 모션 효과를 적용합니다.
- **TTS 생성**: 스크립트를 음성으로 변환합니다.
- **영상 합성**: 이미지, 모션, TTS를 조합하여 최종 영상을 생성합니다.
- **썸네일 제작**: AI 기반 썸네일 디자인 및 제안 기능을 제공합니다.
- **YouTube 업로드**: 완성된 영상을 YouTube에 직접 업로드합니다.
- **채널 분석**: YouTube 채널의 조회수, 시청 시간, 구독자 등 분석 데이터를 제공합니다.

## 기술 스택

- **Backend**: Python, FastAPI
- **Frontend**: HTML, JavaScript
- **AI/ML**: Google Gemini API, WhisperX (음성 인식)
- **YouTube 연동**: YouTube Data API v3, YouTube Analytics API v2
- **영상 처리**: OpenCV, FFmpeg

## YouTube API 사용

이 애플리케이션은 YouTube Data API v3와 YouTube Analytics API v2를 사용하여 다음 기능을 제공합니다:

- 사용자의 YouTube 채널에 영상 업로드
- 영상 썸네일 설정
- 채널 분석 데이터 조회 (조회수, 시청 시간, 구독자 변화 등)
- 시청자 인구통계 분석

모든 YouTube 관련 작업은 사용자의 명시적 동의(OAuth 2.0 인증)를 통해 수행되며, 사용자 본인의 채널에 대해서만 작동합니다.

## 연락처

- 이메일: alsshsskssl@gmail.com
- GitHub: [alsshsskssl](https://github.com/alsshsskssl)
