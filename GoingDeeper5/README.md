# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 진민준
- 리뷰어 : 박연우


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

열심히 과정을 수행하셨지만 결과가 나오지 않아 아쉽게도 루브릭 기준을 만족한다고 할 수 없다. 
![image](https://github.com/user-attachments/assets/d45741bd-8dff-480f-8e7d-28679ccf2d94)


    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

주석이 잘 달려있다고 보기는 어렵지만, 노드의 내용과는 다르게 데이터 타입을 바꾸어 진행하는 등의 과정 부분에서 주석을 달아두셨다. 
딕셔너리 객체를 그대로 두어도 프로젝트 자체를 진행하는 데에는 문제가 없는데, 데이터프레임으로 바꾸어 진행하신 이유가 있으셨다면 그 내용도 회고나 주석으로 간단하게나마 언급이 되었다면 조금 더 친절한 노트북 파일이 되었을 것 같다. 
![image](https://github.com/user-attachments/assets/8f6c1694-318f-4f7f-a7eb-0ac535e7c5cf)


        
- [v]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**

노드와는 다른 코드를 시도하셨다. 
디버깅을 위해 여러 코드를 작성하여 중간중간 결과를 확인하며 프로젝트를 수행하셨다. 

TrainingArguments()의 경우, 
노드에서 제공하는 코드는 배치 크기를 8로 해두었는데, 코더님은 32까지 늘려 진행하셨고, warmup_steps 등의 인자를 추가하셨다. 

에러 발생 및 프로젝트 수행 시간 때문에 GPU 정보를 출력하는 등의 과정을 겪으신 것 같다. 


![image](https://github.com/user-attachments/assets/e833bbc5-bae4-4858-91de-7c94e2871302)

![image](https://github.com/user-attachments/assets/980e499c-22a2-4796-942a-5b357f9d7eaf)
![image](https://github.com/user-attachments/assets/78ef9247-cf06-4b5e-9259-f34f20049ebb)
![image](https://github.com/user-attachments/assets/b38550f2-3c8a-4ec7-a2d6-d397adb32da6)
![image](https://github.com/user-attachments/assets/6da6c142-52c0-46ac-96a7-d9a7cec735d2)

        
- [v]  **4. 회고를 잘 작성했나요?**

회고 작성을 잘 해주셨다. 
![image](https://github.com/user-attachments/assets/25503b31-0558-46fa-9913-f88cb32194dd)

        
- [v]  **5. 코드가 간결하고 효율적인가요?**

코드가 간결하고 효율적이다.
![image](https://github.com/user-attachments/assets/2870a9bc-9815-4830-9c0c-57a816140ccf)
![image](https://github.com/user-attachments/assets/d12d67a1-dca4-45b1-ae41-f005c99c3ecf)


# 회고(참고 링크 및 코드 개선)
```
노드와는 다른 시도를 하신 부분들이 있어 그 부분을 유의하며 리뷰하였다. 노드 코드를 그대로 가져다 쓰는 것보다, 내 코드로 시도해보는 것이 좋다고 생각은 하였지만 그러면 시간이 부족해지는 경우가 많으니 그렇게는 다들 잘 하지 않는데, 코더님은 시간이 좀 부족해질 수는 있어도 코더님 본인만의 코드로 프로젝트를 진행하려고 하신 것 같아 인상 깊다.

고생하셨습니다, 민준님 !!!
```

