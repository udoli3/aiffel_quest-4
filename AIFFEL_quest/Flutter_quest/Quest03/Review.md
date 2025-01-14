코더: 임상운, 김기홍 리뷰어: 김원영 

<aside>
🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 기능이 정상적으로 작동하는지?
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부

앱이 시작될 때 FirstPage를 표시하고 ‘/second’ 라우트로 이동하여 SecondPage를 표시하도록 설정하여 나중에 Navigator.pushNamed(context, '/second')와 같은 코드를 사용하여 생성된 두 페이지 사이를 자유롭게 이동할 수 있도록 구현했습니다. 

  ![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/5a2fdd47-2b6c-4987-adc3-584aefffadcc)
  ![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/6e8ec196-2008-4b7d-a03a-23a1b8821899)


    
- [x]  **2. 핵심적이거나 복잡하고 이해하기 어려운 부분에 작성된 설명을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation/markdown이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
          
모든 핵심 코드들에 주석들이 잘 달려있고 하기의 주석들처럼 어떤 방식을 사용하여 다시 첫번째 화면으로 보내는지 쉽게 이해할 수 있었습니다. 

![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/0b6b1430-b844-437c-a9a8-f721f8f4dbb8)

        
- [x]  **3.** 에러가 난 부분을 디버깅하여 “문제를 해결한 기록”을 남겼나요? 또는
   “새로운 시도 및 추가 실험”을 해봤나요? ****
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
          
pop()함수 관련하여 발생했던 문제의 원인 및 해결 과정을 주석과 Peer Review를 통해 구체적으로 잘 설명하였습니다.
  
![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/1879fd2a-e87a-4459-9496-520d029a2524)

        
- [x]  **4. 회고를 잘 작성했나요?**
    - 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 상세히 기록 되어 있나요?
      
금일 프로젝트를 통해 배운 점, 아쉬었던 점, 느낀 점이 회고에 솔직하고 담백하게 기록되어 있습니다. 

![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/ac4073eb-84e3-4cc2-991b-b6ee9bba053b)


- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
          
페이지 간 이동, 데이터 전달, 그리고 페이지 스택 관리를 효과적으로 구현하였으며 사용자 인터페이스도 직관적이고 사용하기 편리하게 설계하였습니다. 

하기 코드는 Flutter에서 페이지 간 데이터 전달을 효과적으로 구현하는 좋은 예입니다. 
‘SecondPage’ 위젯이 생성될 때 이전 페이지에서 전달된 is_cat 변수를 받아와서 사용하고 있는데 이 실행을 통해 페이지 간 상태 공유를 가능하게 하였습니다.

![image](https://github.com/chocoelf/aiffel_quest/assets/168173100/27fb2d6d-b388-4e47-a4ed-0af6ad108f5c)

  
    

