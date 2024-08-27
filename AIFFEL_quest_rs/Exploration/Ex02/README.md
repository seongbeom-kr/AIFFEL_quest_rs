# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 임성범
- 리뷰어 : 김소희


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 나오지 않았습니다. grid search를 다양한 parameter에 대해 다양한 값으로 수행하다 보니 시간이 오래 걸려 결과가 아직 나오지 않았습니다.

    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - ![image](https://github.com/user-attachments/assets/ea71947a-b8ed-4f5f-a57e-e4e4701ba826) : grid search를 사람마다 다른 파라미터에 대해 수행할 수 있기 때문에 해당 블럭에 주석이 필요하다고 봅니다.
    - 해당 코드 블럭에 doc string/annotation이 간결하게 적혀 있지만, 각 하이퍼파라미터의 의미 등을 기술하면 더욱 좋겠습니다.
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술하면 좋습니다.
    - 주석을 보고 코드 이해가 잘 되었는지
        - ![image](https://github.com/user-attachments/assets/2af1e711-ea93-4999-ad3f-10aa9a10f6b2) : 함수의 기능, 입력값과 출력을 설명하는 주석을 포함했습니다.

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있습니다.
        - ![image](https://github.com/user-attachments/assets/2ddbcb76-1bb6-4b4b-9171-1c26a33c9e01) : EDA를 광범위하고 상세하게 수행하여 각 feature의 특성을 깊게 파악했습니다. Grid search를 4*4가지 이상의 하이퍼파라미터에 대해 수행하여 모델 성능을 높이려는 시도가 보였습니다.

        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등을 기록해 주세요.
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있습니다.
        - ![image](https://github.com/user-attachments/assets/f6df5cff-05ca-42ae-88df-25530a026d47) : 중간중간 수정된 그래프를 출력하여 이해를 도왔습니다.

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했습니다.
        - ![image](https://github.com/user-attachments/assets/c7419069-0cfc-4dbe-b13b-992e5b70b9f0) : 로그 변환을 하는 코드를 함수로 작성하여 반복을 줄였습니다.



# 회고(참고 링크 및 코드 개선)
```
# 다양한 그리드 서치 시도, 깊은 EDA 분석, 함수화 등이 돋보였습니다.
# 개선할 만한 부분은 보이지 않았습니다.
```
