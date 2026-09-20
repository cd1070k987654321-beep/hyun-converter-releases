# HYUN Converter

영상, 오디오, 이미지, 문서 파일을 한 곳에서 변환하는 HYUN IT LABS의 데스크톱 유틸리티입니다.

현재 최신 버전은 **v0.3.0**이며 Windows x64와 Apple Silicon Mac을 지원합니다.

## 다운로드

### Windows
➡️ **[HYUN Converter for Windows](https://github.com/cd1070k987654321-beep/hyun-converter-releases/releases/latest/download/HYUN-Converter-Setup.exe)**

### macOS · Apple Silicon
➡️ **[HYUN Converter for macOS](https://github.com/cd1070k987654321-beep/hyun-converter-releases/releases/latest/download/HYUN-Converter-macOS-arm64.dmg)**

macOS 배포판은 M1 / M2 / M3 / M4 계열 Apple Silicon용입니다.

## v0.3.0 주요 변경

- PowerPoint `PPT`, `PPTX` 입력 지원 추가
- 구형 Word `DOC` 입력 지원 추가
- HWP / HWPX / DOC / DOCX / PPT / PPTX / PDF 문서 변환 흐름 확장
- 입력 형식에 따라 실제 지원되는 출력 형식만 자동 표시
- Windows와 macOS에서 동일한 문서 변환 규칙 적용
- 모든 파일은 외부 서버 업로드 없이 사용자 PC에서 로컬 처리

## 문서 변환

| 입력 | 선택 가능한 출력 |
| --- | --- |
| PDF | DOCX · RTF · TXT |
| DOC | DOCX · PDF · RTF · TXT |
| DOCX | PDF · RTF · TXT |
| HWP / HWPX | DOCX · PDF · RTF · TXT |
| PPT | PPTX · PDF |
| PPTX | PDF · TXT |
| TXT | DOCX · PDF · RTF |
| RTF | DOCX · PDF · TXT |

현재 내장 문서 엔진은 HWP/HWPX **입력**을 지원하지만 HWP/HWPX 파일로 다시 저장하는 출력은 제공하지 않습니다.

## 전체 지원 형식

- 영상 입력: MP4 · MOV · MKV · AVI · WEBM · M4V
- 영상 출력: MP4 · MOV · MKV · WEBM
- 오디오 입력: MP3 · WAV · M4A · FLAC · AAC · OGG
- 오디오 출력: MP3 · WAV · M4A · FLAC · AAC
- 이미지 입력: JPG · JPEG · PNG · WEBP · HEIC · HEIF
- 이미지 출력: JPG · PNG · WEBP
- 문서 입력: PDF · DOC · DOCX · HWP · HWPX · PPT · PPTX · TXT · RTF

## 주요 기능

- 파일 드래그 앤 드롭 및 파일 선택
- 파일 종류에 맞는 출력 형식 자동 추천
- 변환 진행률, 처리 속도, 예상 남은 시간 표시
- 영상 화질 설정: 최고 화질 / 균형 / 용량 절약
- 영상 해상도: 원본 / 4K / 1080p / 720p
- 영상 코덱: H.264 / H.265, WEBM은 VP9
- 영상에서 MP3 / WAV / M4A / FLAC / AAC 오디오 추출
- 변환 완료 후 파일 또는 폴더 바로 열기
- 기존 파일을 덮어쓰지 않고 새 이름으로 저장
- FFmpeg / ffprobe 및 문서 변환 엔진 내장

## 설치 안내

- Windows: Windows 10 / 11 x64
- macOS: Apple Silicon(M1 이상) arm64

현재 테스트 배포판은 정식 코드 서명 및 공증이 적용되지 않았습니다. Windows에서는 SmartScreen 경고가, macOS에서는 개발자 확인 경고가 표시될 수 있습니다.

Windows는 **추가 정보 → 실행**, macOS는 앱을 한 번 실행한 뒤 **시스템 설정 → 개인정보 보호 및 보안 → 확인 없이 열기** 또는 Finder에서 앱을 우클릭해 **열기**를 사용할 수 있습니다.

## 무결성 확인

`SHA256SUMS.txt`에서 최신 설치파일의 SHA-256 해시를 확인할 수 있습니다.

## 피드백

버그, 변환되지 않는 파일, 설치 문제, 개선 의견은 GitHub **Issues**에 남겨주세요.

---

Made by **HYUN IT LABS**
