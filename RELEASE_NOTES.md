# HYUN Converter v0.2.0

**Windows와 macOS에서 동일한 변환 기능을 제공합니다.**

v0.2.0은 영상·오디오·이미지 변환에 문서 변환을 추가하고, Apple Silicon macOS 배포판을 함께 제공하는 버전입니다.

## 다운로드

- Windows x64: `HYUN-Converter-Setup.exe`
- macOS Apple Silicon: `HYUN-Converter-macOS-arm64.dmg`

## 주요 기능

- PDF / DOCX / HWP / HWPX / TXT / RTF 문서 입력 지원
- 문서를 DOCX / PDF / TXT / RTF로 변환
- 영상 파일에서 MP3 / WAV / M4A / FLAC / AAC 오디오 추출
- 영상 화질: 최고 화질 / 균형 / 용량 절약
- 영상 해상도: 원본 / 4K / 1080p / 720p
- 영상 코덱: H.264 / H.265
- WEBM 출력: VP9
- 드래그 앤 드롭
- 변환 진행률, 처리 속도, 예상 남은 시간 표시
- 결과 파일 및 폴더 바로 열기
- 기존 파일을 덮어쓰지 않고 새 이름으로 저장
- 외부 서버 업로드 없이 사용자 PC에서 로컬 처리

## macOS 배포판

- Apple Silicon(M1 / M2 / M3 / M4 계열) arm64 지원
- FFmpeg / ffprobe 및 필요한 런타임 라이브러리 내장
- ONLYOFFICE 기반 문서 변환 엔진 내장
- Homebrew나 별도 변환 프로그램 설치 불필요
- DMG 내부 설치본에서 미디어 변환과 문서 변환 동작 검증 완료

## 지원 형식

- 영상 입력: MP4 · MOV · MKV · AVI · WEBM · M4V
- 영상 출력: MP4 · MOV · MKV · WEBM
- 오디오 입력: MP3 · WAV · M4A · FLAC · AAC · OGG
- 오디오 출력: MP3 · WAV · M4A · FLAC · AAC
- 이미지 입력: JPG · JPEG · PNG · WEBP · HEIC · HEIF
- 이미지 출력: JPG · PNG · WEBP
- 문서 입력: PDF · DOCX · HWP · HWPX · TXT · RTF
- 문서 출력: DOCX · PDF · TXT · RTF

문서 출력은 입력 형식에 따라 지원 가능한 형식이 달라질 수 있습니다.

## 설치파일 무결성

- Windows: 177,458,629 bytes
  - SHA-256: `75abdbbf94eb0121a55fe38d77311813da6c91a6531fa42f8ba02016ed2cc225`
- macOS arm64: 110,915,275 bytes
  - SHA-256: `c969070d6a1277b8e4b6d8af9a5b84eaeb8092ce69d8aa1bc92a833f8947d653`

현재 테스트 배포판은 정식 코드 서명 및 공증이 적용되지 않았습니다.

---

**HYUN Converter**  
Made by **HYUN IT LABS**
