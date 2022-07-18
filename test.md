안녕하세요 :-) 반갑습니다~
이것은 테스트 파일이에요.
이 파일을 수정해볼 것이에요😎

2022년 6월 2일 
- 한번 더 수정!
-  이번에는 Stash를 보고 있어요~
2022년 7월 18일 
- 한번 더 수정!
- 이번에는 PR 후 merge 시fast-forward에 대해 테스트해보고 있어요. 아래와 같은 절차로 테스트할 예정입니다.
  1. branch를 하나 만든다.✅
  2. 1차 수정을 진행하고 PR 올린다.✅
  3. 2차 수정을 진행하고 push한다.✅
  4. PR을 merge한다.✅
- 현재 브랜치는 main 브랜치로부터 파생됐기 때문에 merge시 main 브랜치의 head만이동시키는 fast-forward merge가 발생할 거라고 예상합니다.  
- 위 과정으로 push를 진행했을 때 PR을 들어가보면 방금 추가한 commit이 보이네요.
- branch와 branch를 merge하는 것이기 때문에 당연한 것일수도..?
- ~~이번에는 fast-forward 옵션을 끄고 push 진행해보겠습니다.~~  
- 아 근데, fast-forward는 merge와 관련이 있는 것인데..? 
  - github PR을 merge할 때는 `-no-ff` 옵션을 사용할 수 없는 것인가?
  - fast-forward 옵션을 꺼야하는 경우는 언제이지? 해당 옵션의 용도를 잘못 이해하고 있는 것 같다.
  - PR의 목적은 무엇일까? -> 왜 PR merge는 -no-ff 옵션이 없는지 궁금해서.
  - PR을 올리고 나서 commit, push 진행했는데 이건 PR merge에 합져지지 않았으면 좋겠다! 이 경우 어떻게 해야할까?

