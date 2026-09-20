# HYUN Converter v1.0.0

HYUN Converter의 첫 정식 버전입니다.

## 주요 기능

- 프로그램 본체의 중복 설명 문구를 정리해 더 간결한 UI로 개선
- Windows x64 / macOS Apple Silicon 지원
- 문서, 영상, 오디오, 이미지 로컬 변환
- PDF, DOC, DOCX, HWP, HWPX, PPT, PPTX, TXT, RTF 문서 처리
- DOCX → HWP / HWPX / PPTX
- HWP → HWPX / PPTX
- HWPX → HWP / PPTX
- PDF → HWPX
- PPT / PPTX → HWPX
- PPTX ↔ DOCX
- 기존 PDF / Word / PowerPoint 변환 경로 유지
- 변환 진행률, 취소, 저장 위치 변경, 결과 파일 열기 지원

## 문서 변환 엔진

문서 형식에 따라 ONLYOFFICE x2t, HYUN document bridge, HWP writer를 조합해 로컬에서 처리합니다. 업로드 서버 없이 사용자 PC에서 변환합니다.

서로 구조가 크게 다른 문서 형식 간 변환에서는 복잡한 레이아웃, SmartArt, 고급 도형, 일부 서식이 재구성될 수 있습니다.
