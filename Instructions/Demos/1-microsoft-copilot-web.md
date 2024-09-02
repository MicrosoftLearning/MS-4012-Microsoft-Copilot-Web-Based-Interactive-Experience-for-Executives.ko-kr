---
Layout: default
demo:
  title: '데모: Microsoft Copilot(웹 범위)'
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot(웹 범위)

## Copilot 및  언어 모델

### 설명 점수

웹의 Microsoft Copilot은 질문에 답변하고 일반적인 작업에 도움을 줄 수 있는 AI 기반 개인 비서를 제공합니다. 질문을 하면 대학 교육을 받은 사람이 할 수 있는 것과 비슷한 대답을 해줍니다.

사용자 또는 조직에서 상용 데이터 보호와 함께 Copilot을 사용하는 경우 채팅이 저장되지 않습니다. 모든 데이터가 암호화되고 Microsoft는 프롬프트 또는 응답을 보관하지 않습니다. 이러한 데이터는 모델을 학습하는 데 사용되지 않으므로 개인 및 조직 정보는 기밀로 유지되므로 안심하고 사용할 수 있습니다.

예를 들어 다음과 같은 일반적인 지식에 대한 질문을 하면 많은 유용한 정보를 얻을 수 있습니다. 질문에 답하는 데 사용할 수 있는 세계의 기본 개념적 모델을 가지고 있다고 생각하면 됩니다.

**예제**:
- **프롬프트:** 코끼리에 대해 무엇을 말씀해 주시겠어요?
- **응답:** (응답에 대해 논의)

Copilot은 Bing 검색 및 결과를 비롯한 방대한 양의 정보에 대해 학습된 LLM(대규모 언어 모델)을 사용합니다. 그러나 Copilot은 단 사실 확인 도구가 아닙니다. Copilot은 질문을 받아 확률적으로 추론할 수 있는 일반 추론 엔진으로 사용할 수 있습니다. 업계에서는 이를 추론이라고 합니다.

**예제**:
- **프롬프트:** 코끼리의 힘에 더 관심이 있습니다. 코끼리와 줄다리기에서 이기려면 몇 명의 인간이 필요할까요? 참고: 지역과 대상 그룹에 따라 '줄다리기'라는 용어를 모르는 사람이 있으므로 그에 맞게 수정해야 할 수도 있습니다. 
- **응답:** (응답에 대해 논의)

Copilot은 가정을 세우고 지식의 조각들을 연결하여 제 질문에 보다 미묘한 답을 줄 수 있었습니다. Copilot을 개선하면서 이러한 LLM에서 작동이 원활한 점과 그렇지 못한 점에 대해 많은 것을 배우고 있으며, 제품을 빌드하면서 이러한 지식을 제품에 반영하고 있습니다.

### 데모 단계

> **참고:** 자신만의 프롬프트를 사용하려면 자신이나 고객이 관심을 가질 만한 일반적인 지식 주제부터 시작하세요.

1. Copilot이 열려 있고 웹 범위를 선택한 상태에서 Edge 탭으로 전환합니다.

    ![Microsoft Copilot의 웹 모드를 보여주는 스크린샷.](../Demos/Media/web_mode.png)

1. **무엇이든 질문...** 텍스트 상자에 프롬프트 라이브러리 문서에서 프롬프트를 복사하여 붙여 넣거나 다음과 같이 입력합니다.

    ```text
    What can you tell me about elephants?
    ```
1. **제출** 단추를 선택합니다.
1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다.

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. **제출** 단추를 선택합니다.

## 접지

### 설명 점수

하지만 이 기능을 한 단계 더 발전시키는 것은 외부 데이터와 지식에 기반한 Copilot 기능입니다. 이를 RAG(검색 증강 생성)라고도 합니다. 이는 현재 작업과 관련된 추가 정보를 언어 모델에 제공하는 프로세스입니다.

예를 들어 노동통계청의 일자리 보고서와 같은 모든 종류의 데이터와 문서에 근거하여 질문을 그라운딩할 수 있습니다. 매년 발간되는 이 보고서는 미국 전역의 일자리와 고용 추세에 대한 데이터로 가득 찬 방대한 문서입니다. Copilot이 해당 정보를 찾아내어 이해하고 실시간으로 질문에 대한 답변을 제공할 수 있습니다. 또한 Copilot이 해당 정보를 어디서 얻었는지 보여주는 참고 자료(예: 노동통계국 웹사이트)도 제공합니다. 즉, Autopilot이 아니라 Copilot이기 때문에 Copilot이 어디서 정보를 얻었는지 확인하고 더 많은 맥락을 파악할 수 있습니다.

### 데모 단계

1. **New Topic**을 클릭하여 새 항목을 시작합니다.

    ![Microsoft Copilot의 새 항목을 보여 주는 스크린샷.](../Demos/Media/new_topic.png)

1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다.

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. **제출** 단추를 선택합니다.
1. 응답에서 **자세히 알아보기** 옆의 참고 자료 중 한두 개 위에 마우스를 올려놓습니다.

## 추가 Copilot 기술

### 설명 점수

이것은 훌륭하지만 이 데이터의 그래프를 보고 싶습니다. 안타깝게도 Copilot은 지금 그래프를 그릴 수 없지만, 그렇다고 막혀 있는 것은 아닙니다. Copilot을 구축하면서 다양한 기술을 추가하고 있습니다. 기술은 Copilot이 추론 능력을 활용하여 문제를 해결할 수 있는 방법입니다.

Copilot이 가진 또 다른 능력은 코딩하는 능력입니다. Copilot에게 코딩하는 방법을 알려주고 원하는 그래프에 대한 Python 코드를 작성하도록 할 수 있는지 확인해 보겠습니다.

**예제**:
- **프롬프트:** 지난 5년 동안 노동 통계청의 노동력 참여율 목록을 제공해 주시겠습니까? 코딩도 가능하다고 들었습니다. bls.gov 데이터를 캡처한 다음 제가 찾고 있는 그래프를 생성하는 Python 코드를 작성할 수 있나요?
- **응답:** (응답에 대해 논의)

시간이 지남에 따라 이러한 종류의 프로세스가 더 쉽고 자동화될 것으로 기대합니다.

### 데모 단계

1. **New Topic**을 클릭하여 새 항목을 시작합니다.

    ![Microsoft Copilot의 새 항목을 보여 주는 스크린샷.](../Demos/Media/new_topic.png)

1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다.

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. **제출** 단추를 선택합니다.

## 선택적 데모 단계

### 이미지 인식

먼저 다음을 다운로드합니다. [**What is this image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. **New Topic**을 클릭하여 새 항목을 시작합니다.

    ![Microsoft Copilot의 새 항목을 보여 주는 스크린샷.](../Demos/Media/new_topic.png)

1. 페이지 하단의 **이미지 추가** 아이콘을 선택합니다.

    ![Microsoft Copilot에서 이미지 추가를 보여 주는 스크린샷.](../Demos/Media/add_an_image.png)

1. **이 디바이스에서 업로드**를 선택합니다.
1. 이미지를 다운로드한 위치로 이동하고 **What is this picture.png**를 선택한 다음 **열기**를 선택합니다.
1. **질문하기...** 텍스트 상자에 프롬프트를 입력합니다.

    ```text
    What is this picture?
    ```

1. **제출** 단추를 선택합니다.

### Copilot으로 이미지를 만드는 방법 알아보기

1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다.

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. **제출** 단추를 선택합니다.

### Copilot으로 노래를 쓰는 방법 알아보기

1. 개인 계정에 로그인한 새 브라우저 세션으로 전환합니다.

> **참고:** 이 단계에서는 개인 계정을 사용해야 합니다. 회사 계정은 작동하지 않습니다.

1. 오른쪽 위 모서리에서 **플러그 인**을 선택합니다.

    ![Microsoft Copilot에서 이미지 추가를 보여 주는 스크린샷.](../Demos/Media/copilot_plugins.png)

1. 사용 가능한 플러그 인 목록에서 **Suno**를 사용하도록 설정합니다.

    ![Microsoft Copilot에서 이미지 추가를 보여 주는 스크린샷.](../Demos/Media/copilot_suno.png)

    > **참고:** Suno를 사용하려면 Copilot에서 새 토픽을 시작한 다음 Suno를 사용하도록 설정해야 합니다.

1. **무엇이든 질문...** 텍스트 상자에서 프롬프트를 복사하여 붙여 넣습니다.

    ```text
    Write a country song about Microsoft Copilot, extolling its virtues as an AI companion. Make it catchy, upbeat, and a little quirky.
    ```

1. **제출** 단추를 선택합니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
