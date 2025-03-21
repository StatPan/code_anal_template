# 코드 구조 분석 템플릿

## 개요

이 프로젝트는 코드 구조 분석을 위한 마크다운 템플릿을 제공합니다. 이 템플릿을 사용하면 코드 구조를 체계적으로 분석하고 문서화할 수 있습니다.

### 주요 기능

- 코드 구조 분석을 위한 마크다운 템플릿 제공
- 프로젝트 목표, 아키텍처, 모듈, 데이터 모델, 코드 스타일, 개선 사항 등 다양한 분석 항목 지원
- Mermaid 다이어그램을 사용한 시각적인 표현 지원
- 협업을 위한 Git 지원

## 사용법

1.  **저장소 복제**: 이 저장소를 복제합니다.
    ```bash
    git clone [저장소 주소]
    ```
2.  **템플릿 작성**: 각 파일에 템플릿에 맞춰 코드 분석 내용을 작성합니다. 각 파일의 목적과 내용을 참고하여 작성하세요.
3.  **Mermaid 다이어그램**: Mermaid 다이어그램을 사용하여 코드 구조를 시각화합니다. 다이어그램 예시는 ARCHITECTURE.md 파일을 참고하세요.
4.  **작업 기록**: `WORKING.log` 파일에 작업 내용을 기록합니다. 작업의 진행 상황과 다음 작업 계획을 명확히 기록하세요.

## LLM, Agent 연동

이 템플릿은 LLM(Large Language Model), Agent와의 연동을 고려하여 설계되었습니다. 각 분석 영역에 대한 내용을 LLM, Agent에게 제공하여 코드 분석을 자동화하거나, 분석 결과를 LLM, Agent를 통해 활용할 수 있습니다.

## 템플릿 구성

각 파일은 다음과 같은 내용을 담고 있습니다.

- **README.md**: 프로젝트 개요, 사용법, 기여 방법 등을 설명합니다.
- **INDEX.md**: 전체 목차 및 파일 목록을 제공합니다.
- **GOAL.md**: 분석 목표 및 범위를 정의합니다.
- **ARCHITECTURE.md**: 시스템 아키텍처를 분석합니다.
- **MODULES/**: 모듈별 분석 내용을 담습니다.
- **DATA/**: 데이터 모델 및 API를 분석합니다.
- **CODE_STYLE.md**: 코드 스타일 및 컨벤션을 분석합니다.
- **IMPROVEMENTS.md**: 개선점 및 확장 가능성을 분석합니다.
- **REFERENCES.md**: 참고 자료 목록을 정리합니다.
- **WORKING.log**: 분석 과정에서 발생한 아이디어, 질문, 문제점 등을 기록합니다.

## 기여 방법

이 프로젝트에 기여하고 싶으시다면, 다음 단계를 따라주세요.

1.  **Fork**: 이 저장소를 Fork합니다.
2.  **Branch**: 새로운 Branch를 생성합니다.
    ```bash
    git checkout -b [브랜치 이름]
    ```
3.  **Commit**: 변경 사항을 Commit합니다.
    ```bash
    git commit -m "[커밋 메시지]"
    ```
4.  **Push**: 변경 사항을 Push합니다.
    ```bash
    git push origin [브랜치 이름]
    ```
5.  **Pull Request**: Pull Request를 생성합니다.
