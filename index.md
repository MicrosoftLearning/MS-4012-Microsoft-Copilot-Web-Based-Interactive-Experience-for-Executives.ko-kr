---
title: 온라인 호스팅 지침
permalink: index.html
layout: home
---

# 콘텐츠 디렉터리

이 과정의 데모는 액셀러레이터 키트 [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG) 데모를 기반으로 합니다.

이 교육을 제공하기 전에 데모를 숙지하는 것이 중요합니다. 여러 랩의 경우 샘플 문서와 미리 만든 Teams 모임 및 전자 메일을 활용합니다.

- [여기](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles)에서 모든 샘플 문서를 미리 다운로드합니다.
- [여기](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)에 있는 지침에 따라 Teams 모임 및 전자 메일 스레드를 설정합니다.
- [여기](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf)에 있는 상호 작용 환경을 숙지합니다.

    > **참고:** 상호 작용 환경 PDF 파일은 디바이스에 직접 다운로드됩니다(다운로드 폴더).

- [여기](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx)에서 최신 교육 데크를 검토합니다.

## 과정 설명

Microsoft Copilot의 혁신적인 잠재력과 조직 효율성에 미치는 영향을 살펴봅니다. Copilot 라이선스가 없는 임원 및 비즈니스 리더를 위해 설계된 이 환경은 효과적인 프롬프트를 만드는 기술을 탐구하고, 상호 작용 환경을 제공하며, Microsoft 365용 Microsoft Copilot이 일상적인 비즈니스 워크플로에 원활하게 통합되어 생산성과 혁신을 향상하는 방법을 보여줍니다.

이 전달의 주요 목표는 다음과 같습니다.

- 효과적인 프롬프트를 만드는 방법 교육
- Microsoft Copilot(웹 범위)을 시연하고 상호 작용 환경을 통해 참가자를 안내합니다.
- Microsoft 365용 Microsoft Copilot 시연 - Microsoft Copilot(작업 범위), Word, Outlook 및 Teams
- 참가자를 초대하여 모바일용 Microsoft Copilot을 다운로드 및 사용해 보도록 합니다.

## 과정 소요 시간(미완료) 

| # | 항목                                 | 세부 정보                                                                                          | 총 시간      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Microsoft 365용 Copilot에서 효과적인 프롬프트 작성하기 | - 프롬프트 슬라이드의 기술 <br> - 프롬프트 빌딩 슬라이드 <br> - Copilot 랩 슬라이드 | 5~10분    |
| 2 | 웹 기반 Microsoft Copilot          | - 데모 Microsoft Copilot(웹 모드) <br> - 상호 작용 환경  <br> - 사용자 경험 공유 슬라이드 | 35분      |
| 3 | Microsoft 365용 Copilot 작동 방식     | - Microsoft Graph 슬라이드 <br> - Word의 데모 Copilot, Microsoft Copilot(작업 모드), Outlook의 Copilot 및 Teams의 Copilot <br> - 평가 슬라이드 <br> - 모바일 슬라이드의 Microsoft Copilot | 25분      |
|   |                                       |                                                                                                  | **총 시간은 70분을 초과할 수 있습니다.** |


아래에는 각 데모의 하이퍼링크 목록이 나와 있습니다.

## 데모

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 데모 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
