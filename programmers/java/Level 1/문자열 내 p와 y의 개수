###24.04.22 문자열 내 p와 y의 개수
[문제 링크](https://school.programmers.co.kr/learn/courses/30/lessons/12916)

##문제 설명
대문자와 소문자가 섞여있는 문자열 s가 주어집니다. s에 'p'의 개수와 'y'의 개수를 비교해 같으면 True, 다르면 False를 return 하는 solution를 완성하세요. 'p', 'y' 모두 하나도 없는 경우는 항상 True를 리턴합니다. 단, 개수를 비교할 때 대문자와 소문자는 구별하지 않습니다.

예를 들어 s가 "pPoooyY"면 true를 return하고 "Pyy"라면 false를 return합니다.

##제한사항
문자열 s의 길이 : 50 이하의 자연수
문자열 s는 알파벳으로만 이루어져 있습니다.

##풀이
```java
import java.util.*;

class Solution {
    boolean solution(String s) {
        boolean answer = true;
        String[] str = s.split("");
        int p = 0;
        int y = 0;
        
        System.out.println(Arrays.toString(str));

       for(int i=0; i<str.length; i++){
           if(str[i].equals("p")|| str[i].equals("P")){
               p ++;
           }else if(str[i].equals("y") || str[i].equals("Y")){
               y ++;
           }
       }
        return p == y ? true : false;
    }
}
```

##성능 요약
	통과 (0.38ms, 72.3MB)

##기록
0단계 이후 첫 1단계 문제라 걱정이 있었지만 연습 문제라 그런지 큰 어려움이 없었다.
