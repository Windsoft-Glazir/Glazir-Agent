# Glazir Agent

**설계자와 BIM 실무자가 도면과 모델을 함께 관리하고 Revit에서 설계·작도·검토 업무를 연결하는 Windsoft 도구입니다.**

## 기능 및 제공 상태

| 기능 | 공식 홈페이지 안내 |
| --- | --- |
| 도면 파일 서버 | 사내 서버에 도면과 BIM 모델을 저장·공유하고 이전 버전과 변경 이력을 관리합니다. Glazir Draft에서 모델을 열고 저장할 수 있습니다. |
| 법규 검토 | 모델의 속성과 치수로 적용 가능한 규칙을 확인합니다. 검토 결과와 측정 근거를 제공하며, 검수된 규칙과 참고 결과를 구분합니다. |
| 외부 AI 연동 | Claude·OpenAI·Gemini를 연결해 자연어로 Revit 모델을 조회하고 작업을 요청하는 구조를 제공합니다. 선택한 AI 환경과 Revit Pilot 연결이 필요합니다. |
| AI 도면 자동 작도 | 벽·바닥·문·창·Room과 뷰를 생성하거나 수정하는 기본 도구가 있습니다. 설계 조건 입력부터 배치·작도·검토·수정까지 연결하는 통합 흐름은 개발 중입니다. |

## 자동 작도 개발 계획

첫 적용 목표는 **단층 주거 세대 1개의 기본 BIM 모델**입니다. 설계 조건과 참고 RVT를 바탕으로 배치안을 검토하고, 작업 계획을 검증한 뒤 기본 요소를 생성합니다. 생성 결과는 계획과 대조하고, 설계자가 선택한 범위만 수정한 뒤 다시 검토하는 흐름을 준비하고 있습니다. 최종 설계와 법규 적합성은 별도 검수가 필요합니다.

- [공식 제품 소개와 개발 계획](https://windsoft.co.kr/glazir-agent.html) · [제품 문의](https://windsoft.co.kr/contact.html)
- [Glazir Draft](https://github.com/Windsoft-Glazir/Glazir-Draft) · [Glazir Exporter](https://github.com/Windsoft-Glazir/Glazir-Exporter)

## English

Glazir Agent connects drawing and model management, regulatory review, and external AI workflows for Revit and BIM teams. The planned end-to-end drafting workflow initially focuses on one single-story residential unit. Check the product page for feature availability, requirements, and the development roadmap.

- [Product overview and roadmap](https://windsoft.co.kr/glazir-agent-en.html)
