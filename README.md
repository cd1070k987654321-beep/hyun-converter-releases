# HYUN Converter

영상, 오디오, 이미지, 문서 파일을 한 곳에서 변환하는 HYUN IT LABS의 데스크톱 유틸리티입니다.

현재 최신 버전은 **v0.2.0**이며 Windows x64와 Apple Silicon Mac을 지원합니다.

## 다운로드

### Windows
➡️ **[HYUN Converter for Windows](https://github.com/cd1070k987654321-beep/hyun-converter-releases/releases/latest/download/HYUN-Converter-Setup.exe)**

### macOS · Apple Silicon
➡️ **[HYUN Converter for macOS](https://github.com/cd1070k987654321-beep/hyun-converter-releases/releases/latest/download/HYUN-Converter-macOS-arm64.dmg)**

macOS 배포판은 M1 / M2 / M3 / M4 계열 Apple Silicon용입니다.

## v0.2.0 주요 기능

- 영상 / 오디오 / 이미지 / 문서 파일 변환
- PDF, DOCX, HWP, HWPX, TXT, RTF 문서 입력 지원
- 영상 파일에서 MP3, WAV, M4A, FLAC, AAC 오디오 추출
- 파일 드래그 앤 드롭 및 파일 선택
- 파일 종류에 맞는 출력 형식 자동 추천
- 변환 진행률, 처리 속도, 예상 남은 시간 표시
- 영상 화질 설정: 최고 화질 / 균형 / 용량 절약
- 영상 해상도 설정: 원본 / 4K / 1080p / 720p
- 영상 코덱 선택: H.264 / H.265, WEBM은 VP9 사용
- 변환 완료 후 파일 또는 폴더 바로 열기
- 기존 파일을 덮어쓰지 않고 새 파일로 저장
- 미디어 및 문서 변환 엔진 내장
- 파일은 외부 서버로 업로드하지 않고 PC에서 로컬 처리

## 지원 입력 형식

- 영상: MP4, MOV, MKV, AVI, WEBM, M4V
- 오디오: MP3, WAV, M4A, FLAC, AAC, OGG
- 이미지: JPG, JPEG, PNG, WEBP, HEIC, HEIF
- 문서: PDF, DOCX, HWP, HWPX, TXT, RTF

## 지원 출력 형식

- 영상: MP4, MOV, MKV, WEBM
- 오디오: MP3, WAV, M4A, FLAC, AAC
- 이미지: JPG, PNG, WEBP
- 문서: DOCX, PDF, TXT, RTF

문서 출력 형식은 입력 파일 종류에 따라 선택 가능한 형식이 달라질 수 있습니다.

## 설치 안내

- Windows: Windows 10 / 11 x64
- macOS: Apple Silicon(M1 이상) arm64
- Windows 설치파일: 약 170MB
- macOS DMG: 약 106MB

현재 테스트 배포판은 정식 코드 서명 및 공증이 적용되지 않았습니다. Windows에서는 SmartScreen 경고가, macOS에서는 개발자 확인 경고가 표시될 수 있습니다.

Windows는 **추가 정보 → 실행**, macOS는 앱을 한 번 실행한 뒤 **시스템 설정 → 개인정보 보호 및 보안 → 확인 없이 열기** 또는 Finder에서 앱을 우클릭해 **열기**를 사용할 수 있습니다.

미디어 변환용 FFmpeg / ffprobe와 문서 변환 엔진이 설치파일에 포함되어 있어 별도 변환 프로그램이나 Homebrew 설치가 필요하지 않습니다.

## 무결성 확인

`SHA256SUMS.txt`에서 최신 설치파일의 SHA-256 해시를 확인할 수 있습니다.

```text
75abdbbf94eb0121a55fe38d77311813da6c91a6531fa42f8ba02016ed2cc225  HYUN-Converter-Setup.exe
c969070d6a1277b8e4b6d8af9a5b84eaeb8092ce69d8aa1bc92a833f8947d653  HYUN-Converter-macOS-arm64.dmg
```

## 피드백

버그, 변환되지 않는 파일, 설치 문제, 개선 의견은 GitHub **Issues**에 남겨주세요.

---

Made by **HYUN IT LABS**
