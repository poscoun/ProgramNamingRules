# 프로그램 네이밍 규칙
1. 클래스나 메소드명은 파스칼 표기법을 따른다.
- 모든 단어에서 첫 번째 문자가 대문자이며 나머지는 소문자로 표기.
ex) 
public class HelloWorld{             // 클래스명
  public void HelloCity(){           // 메소드명
  }
}

2. 변수, 파라미터 등은 카멜 표기법을 따른다.
- 최초에 사용된 단어를 제외한 모든 단어의 첫 문자가 대문자이며, 나머지는 소문자로 표기.
ex) 
int totalCost = 0;               // 변수명
String fullName = "";

public void HelloCity(String familyName){};          // 파라미터명

3. 변수에 모든 의미를 충분히 담을것 (접두사 제외)
- 가능하면 모든 축약어를 사용하지 않고, 의미를 바로 알 수 있도록 합니다.
- 위의 변수명 중에서 totalCost 같은 경우, total을 tot 라고 축약어를 사용하는 경우도 많이 있습니다.
- 하지만 예외의 경우도 있습니다. 접두사를 사용하여 변수명을 지을 때 접두사는 축약어를 사용하는 편이 좋습니다.

![image](https://user-images.githubusercontent.com/75350944/118422247-d1eec780-b6fd-11eb-862a-0cafe3be2818.png)
