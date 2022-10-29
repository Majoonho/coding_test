
![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&text=Welcome!%20&fontSize=60&fontAlignY=40&desc=I'm%20joonho)



### baekjoon_11866 번 요세수스 순열 문제
* check point : 
  * 회전하는 순열 pop(0), pop() 
  * 백준에서 요구하는 답의 형식을 주의할 것 
  * ``` print('<',end='') ```

### baekjoon_2346 번 풍선터뜨리기 문제
* check point :
  * deque 를 사용하면 편리함.
  * ``` from collections import deque```
  * 인덱스 순서를 출력하는 경우, 처음부터 index, val 리스트만들어야 편리함.

### baekjoon_13335 번 트럭(큐) 문제
* check point :
  * 0으로 채운 리스트가 좋을 때가 있음
  * 조건이 있는 pop()을 이용할 때는 0을 append 하는 것도 방법임.
  * ```if bridge:
        if sum(bridge) + trucks[0] <= l:
            bridge.append(trucks.pop(0))
        else:
            bridge.append(0) ```
            
  
