# HYUN Converter v0.3.0

**문서 변환 범위를 Word와 PowerPoint까지 확장한 업데이트입니다.**

Windows와 macOS에서 동일한 변환 규칙을 사용하며, 지원되지 않는 조합은 선택지에 노출하지 않습니다.

## 주요 변경

- `PPT`, `PPTX` PowerPoint 파일 입력 지원
- `DOC` 구형 Word 파일 입력 지원
- 기존 `HWP`, `HWPX`, `DOCX`, `PDF`, `TXT`, `RTF` 문서 변환 유지 및 정리
- 입력 파일 형식에 맞춰 실제 가능한 출력만 표시
- Windows x64 / macOS Apple Silicon 설치본 동시 제공

## 문서 변환 지원표

- PDF → DOCX / RTF / TXT
- DOC → DOCX / PDF / RTF / TXT
- DOCX → PDF / RTF / TXT
- HWP / HWPX → DOCX / PDF / RTF / TXT
- PPT → PPTX / PDF
- PPTX → PDF / TXT
- TXT → DOCX / PDF / RTF
- RTF → DOCX / PDF / TXT

> HWP/HWPX는 입력 및 다른 문서 형식으로의 변환을 지원합니다. 현재 내장 엔진에서는 HWP/HWPX 자체를 출력 형식으로 생성하지 않습니다.

## 기존 기능

- 영상 / 오디오 / 이미지 변환
- 영상에서 오디오 추출
- 영상 화질, 해상도, 코덱 설정
- 드래그 앤 드롭
- 변환 진행률 / 처리 속도 / 예상 남은 시간
- 결과 파일 및 폴더 바로 열기
- 기존 파일을 덮어쓰지 않고 새 이름으로 저장
- 외부 서버 업로드 없이 로컬 처리

## 다운로드

- Windows x64: `HYUN-Converter-Setup.exe`
- macOS Apple Silicon: `HYUN-Converter-macOS-arm64.dmg`
- 무결성 정보: `SHA256SUMS.txt`

현재 테스트 배포판은 정식 코드 서명 및 공증이 적용되지 않았습니다.

---

**HYUN Converter**  
Made by **HYUN IT LABS**
