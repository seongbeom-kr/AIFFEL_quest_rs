# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 임성범
- 리뷰어 : 홍사빈


# PRT(Peer Review Template)
- [0]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/17d18633-8655-48bd-860c-df05f8367d84)
        - loss 시각화!
        - ![image](https://github.com/user-attachments/assets/c91e2d50-0b2a-4dc8-aa70-c1b2e6901592)
        - 추상적 요약!
        - ![image](https://github.com/user-attachments/assets/aa66108c-4392-486b-84f4-f461bbec79a8)
        - 추출적 요약!
        - ![image](https://github.com/user-attachments/assets/291835e9-7ea6-4c32-8135-e18b5e24d16b)
        - 실제 데이터와 만든 데이터 인덱스 비교!

- [0]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/ad210cbb-8d3c-4ec3-a296-9170b87cde27)
        - 리뷰어가 이해하지 못한 부분을 말로 잘 설명했다. 기존에 만들었던 Seq2text, Seq2summary, decoder seq, summa_summary 네 가지를 비교하는 코드이다.

- [0]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/ee5e4be4-7c13-4b40-b2ee-422c34869660)
        - 사진은 완성본. 전처리된 문장은 영어로 인식하지 못해 요약 불가 에러가 발생했다. 그래서 전처리를 하지 않고 summary를 진행하여 에러를 수정했다.
        
- [0]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/a710feab-990b-4927-93db-8a8928409444)
        - 생각이 잘 드러난 회고!

- [0]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
      - ![image](https://github.com/user-attachments/assets/d127d062-5386-4957-a42e-7d7e4b188556)
      - for문이 아닌 lambda 함수로 구현!


# 회고(참고 링크 및 코드 개선)
```
리뷰어가 완성하지 못한 부분을 깔끔하게 정리하여 시도했다.
추가적인 실험을 각 진행사항마다 추가한 모습이 인상적이다.
비전공자임에도 뛰어난 코딩 실력을 보인다.
```
