---
demo:
  title: '데모: Microsoft Copilot(작업 범위)'
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot(작업 범위)

## 데모 설정

이 데모는 샘플 문서를 사용하지 않습니다. 대신 동료와 주고받은 기존 커뮤니케이션에 의존합니다. 

아래 프롬프트에서 기밀 정보를 공유하지 않는 사용자를 참조합니다.

## 설명 점수

"작업 범위 내에서 실행되는 Microsoft 365용 Copilot을 사용하면 Copilot은 Microsoft 365 보안을 사용하여 데이터를 보호하고 조직의 규정 준수 경계 내에서 모든 서비스를 실행합니다.

여기서는 작업 범위에서 Microsoft Graph의 정보를 사용하여 Copilot을 향상합니다. 몇 가지 기본적인 참조 자료 관리부터 시작해 보겠습니다. 어디서 누구로부터 정보를 얻을 수 있는지 파악하는 것은 참조 자료 관리의 고질적인 과제입니다. 조직에서 누가 그라운딩과 LLM에 대해 알려줄 수 있는지 살펴보겠습니다.

이제 Copilot에게 커뮤니케이션을 요약하고 동료 중 한 명과 함께 작업해 달라고 요청하겠습니다. 전자 메일, 채팅 및 문서로 응답을 구성하도록 요청합니다. 작업 범위에서 Copilot은 내 전자 메일 메시지, 일정, 채팅 및 문서를 볼 수 있습니다.

Copilot은 일정에 대해 생각하는 방법을 배우고 있습니다. 그 정보를 처리하고 요약해 유용한 정보를 제공할 수 있었습니다. 그리고 참조가 포함되어 있어 해당 정보를 보거나 확인하거나 자세한 정보를 얻을 수 있습니다.

우리는 항상 프롬프트를 살펴보고 더 복잡한 정보 검색 및 자동화를 통해 Copilot의 작동하는 방식을 개선하는 방법을 찾고 있습니다."

## 데모 단계

> **중요:** 프롬프트를 추가로 사용자 지정하려면 기밀이 아닌 전자 메일 또는 모임을 찾고 Copilot에 요약하거나 작업 항목을 나열하도록 요청합니다. 중요: 사람을 선택할 때 기밀 정보를 공유하지 않는 사용자를 선택하세요!

1. 왼쪽 위에서 토글을 **작업**으로 전환합니다.

1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다. 

    ```text
    What is "grounding" for an LLM and how does it work? If I wanted to know more about it, who would be able to help me?
    ```

1. **제출** 단추를 선택합니다.

1. **무엇이든 질문...** 텍스트 상자에 다음을 복사하여 붙여 넣거나 입력합니다. 

    ```text
    Can you summarize the last five emails from “/”.
    ```
    > **참고:** 슬래시 기호를 포함해야 합니다.

1. 동료의 이름을 입력합니다.

    > **중요:** 기밀 정보를 공유하지 않는 사람을 선택합니다.

1. 이름이 나타나면 선택합니다.
1. 프롬프트의 나머지 부분을 복사하여 붙여 넣거나 입력합니다.

    ```text
    To be specific, look for the last five emails from this person over the last few days and stack rank them in order of most important to least important, based on your analysis of the contents.
    ```

1. **제출**을 선택합니다.

1. **선택 사항:** **질문하기...** 텍스트 상자에서 프롬프트를 복사하여 붙여넣습니다.

    ```text
    Can you summarize the last five emails from my boss? To be specific, look for the last five emails from my boss over the last few days and stack rank them in order of most important to least important, based on your analysis of the contents.
    ```

    그런 다음, **제출**을 선택합니다.

1. **선택 사항:** **질문하기...*" 텍스트 상자에서 프롬프트를 복사하여 붙여넣습니다.

    ```text
    Review my meetings this week and create 5-7 categories that describe how I am spending my time. For each category, provide a short description and give me an approximate percentage of time I spent there.
    ```

    그런 다음, **제출**을 선택합니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
