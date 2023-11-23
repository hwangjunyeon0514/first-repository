# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박준
- 리뷰어 : 이승제


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**  
    [O] 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
    - [O] 1) 캐글 데이터분석 전과정이 성공적으로 진행되었는가?  

        **-> 전체적으로 과정이 성공적으로 진행되었고, 파일 생성 후 캐글에 제출까지 완료**
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/63c08ac8-cf35-46c4-9be0-5be35be968b0)


    - [O] 2) 전처리, 학습과정 및 결과에 대한 설명이 시각화를 포함하여 체계적으로 진행되었는가?  

        **-> 시각화를 통해 테이터의 분포 등을 파악할 수 있다.**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/7e69e5de-72bb-43c0-b427-d5c77473ac02)


        **-> score, rmsle이 계산된 결과를 한 눈에 확인 할 수 있다.**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/ca20e816-2ae6-4c6e-a238-580f43e960ef)  

    - [O] 3) 회귀모델 예측정확도가 기준 이상 높게 나왔는가? 

        **-> 108829로 11만 보다 낮게 잘 나왔다.**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/578b6191-acc9-4cbb-920c-fa7e6ce6128b)
---
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
 
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인  
        **-> my_GridSearch라는 메서드가 어떻게 작동하는지, 주석을 보고 파악할 수 있다.**
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/23848616-7ef8-4dd1-a888-715aec0fb390)

---

- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?**

   - [O] 문제 원인 및 해결 과정을 잘 기록하였는지 확인  
        **-> 치우친 노드를 log 적용하여 조정**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/7b27d22d-08e8-4c4b-9add-ca032974e3de)
       
    
   - [O] 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인  
        **-> 속성값을 바꿔주면서 테스트를 진행**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/5f3130c4-a3b7-4d15-aeec-163cfe570b7c)

---
        
- [O]  **4. 회고를 잘 작성했나요?**
    [O] 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해  
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
        **-> 프로젝트를 진행하면서 느낀점이 회고를 통해서 작성 되어있다**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/3aa653a5-14e4-46b5-8623-7bb62cb91640)

    [O] 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인  
        **-> 코드를 실행한 후에 정렬하여 값이 잘 출력되는지 확인.**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/e8e4f86c-b0c4-457d-a8c1-e0e720088f8d)

---
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    [O] 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인  
        **-> 아래 사진처럼 snake 형식으로 잘 작성이 되어있으며 변수 사이에 x, y처럼 띄어쓰기가 잘 작성이 됨**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/08fa849a-72fc-483b-bdfe-5fbcd42ffefd)


    [O] 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지  
        **-> def를 선언해서 코드가 잘 정리가 되었다**  
        ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/6c4d5aa7-b30c-404c-be87-b9a2be0d6121)

      
    [O] 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지  
        **->  def를 선언해서 코드가 잘 정리가 되었다**  
         ![image](https://github.com/happybin2013/first-repository_jun/assets/85716670/c0c7fdc9-5385-4f49-8ee6-1fe7d12d15fb)



# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.

### 참고! 해당 대회에서 캐글 데이터를 상세하게 분석하신 분의 링크  
https://www.kaggle.com/code/bluepinetree/57-of-415-eda-stacking-modeling

### pep8 style guide  
https://peps.python.org/pep-0008/
```

