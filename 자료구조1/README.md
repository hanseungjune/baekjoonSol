# Data Structre (자료구조)

[메인으로 돌아가기](https://github.com/tony9402/baekjoon)

이 자료구조에서는 큐, 스택, 덱을 익히는 문제들로 뽑았습니다.

풀어보면 좋을 문제는 추천 문제에 체크(✔) 해놨습니다.

<br>

**_❗️❗️꼭 문제를 순서대로 안풀어도 됩니다.❗️❗️_**

[백준 문제집](https://www.acmicpc.net/workbook/view/6779)
| 순번 | 추천 문제 | 문제 번호 | 문제 이름 | 난이도 | 풀이 여부 | 비고 |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| 00 | ✔ | <a href="https://www.acmicpc.net/problem/10828" target="_blank">10828</a> | <a href="https://www.acmicpc.net/problem/10828" target="_blank">스택</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | - |
| 01 | ✔ | <a href="https://www.acmicpc.net/problem/9012" target="_blank">9012</a> | <a href="https://www.acmicpc.net/problem/9012" target="_blank">괄호</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | 괄호 갯수로 비교해서 풀기 |
| 02 | ✔ | <a href="https://www.acmicpc.net/problem/18258" target="_blank">18258</a> | <a href="https://www.acmicpc.net/problem/18258" target="_blank">큐 2</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | deque로 풀자 |
| 03 | ✔ | <a href="https://www.acmicpc.net/problem/1158" target="_blank">1158</a> | <a href="https://www.acmicpc.net/problem/1158" target="_blank">요세푸스 문제</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | `%` 로 인덱스 순회 |
| 04 | ✔ | <a href="https://www.acmicpc.net/problem/2164" target="_blank">2164</a> | <a href="https://www.acmicpc.net/problem/2164" target="_blank">카드2</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | remove 대신에 popleft |
| 05 | ✔ | <a href="https://www.acmicpc.net/problem/10866" target="_blank">10866</a> | <a href="https://www.acmicpc.net/problem/10866" target="_blank">덱</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | sys.stdin.readline |
| 06 | ✔ | <a href="https://www.acmicpc.net/problem/1935" target="_blank">1935</a> | <a href="https://www.acmicpc.net/problem/1935" target="_blank">후위 표기식2</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | Good | stack, ord() |
| 07 | ✔ | <a href="https://www.acmicpc.net/problem/1966" target="_blank">1966</a> | <a href="https://www.acmicpc.net/problem/1966" target="_blank">프린터 큐</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | Good | 로직이 헷갈렸던 부분이 많은데 쓰면서 해야할 듯 |
| 08 | ✔ | <a href="https://www.acmicpc.net/problem/2346" target="_blank">2346</a> | <a href="https://www.acmicpc.net/problem/2346" target="_blank">풍선 터뜨리기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | Good | 음수 % 양수 = 양수+음수 개념인듯 |
| 09 | ✔ | <a href="https://www.acmicpc.net/problem/1874" target="_blank">1874</a> | <a href="https://www.acmicpc.net/problem/1874" target="_blank">스택 수열</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> | Good | 스택수열 자체를 이해 못한듯 |
| 10 | ✔ | <a href="https://www.acmicpc.net/problem/10799" target="_blank">10799</a> | <a href="https://www.acmicpc.net/problem/10799" target="_blank">쇠막대기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> | Good | /: 자름, (: 스택, ):+1 |
| 11 | ✔ | <a href="https://www.acmicpc.net/problem/2504" target="_blank">2504</a> | <a href="https://www.acmicpc.net/problem/2504" target="_blank">괄호의 값</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/> | Good | i-1 일때만 계산, 더해주는 값을 스택 정리하면서 같이 초기화 |
| 12 | ✔ | <a href="https://www.acmicpc.net/problem/2800" target="_blank">2800</a> | <a href="https://www.acmicpc.net/problem/2800" target="_blank">괄호 제거</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> | Good | combination으로 [start, end] 인덱스 구해주고, "(, )"을 ""로 바꿔준다. |
| 13 | ✔ | <a href="https://www.acmicpc.net/problem/2493" target="_blank">2493</a> | <a href="https://www.acmicpc.net/problem/2493" target="_blank">탑</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> | Good | 메모이제이션 사용 |
| 14 | ✔ | <a href="https://www.acmicpc.net/problem/22942" target="_blank">22942</a> | <a href="https://www.acmicpc.net/problem/22942" target="_blank">데이터 체커</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/> | Good | 양 끝의 원의 x좌표와 해당하는 원의 번호를 비교해서 괄호 느낌으로 문제를 풀면 쉽다 |
| 15 | ✔ | <a href="https://www.acmicpc.net/problem/1918" target="_blank">1918</a> | <a href="https://www.acmicpc.net/problem/1918" target="_blank">후위 표기식</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/> | Good | 후위표기법 개념을 다시 이해하게됨. |
| 16 | | <a href="https://www.acmicpc.net/problem/10845" target="_blank">10845</a> | <a href="https://www.acmicpc.net/problem/10845" target="_blank">큐</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | queue == [] 대신에 len(queue) == 0 |
| 17 | | <a href="https://www.acmicpc.net/problem/4949" target="_blank">4949</a> | <a href="https://www.acmicpc.net/problem/4949" target="_blank">균형잡힌 세상</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | 크게 어려운건 없는데 예외처리를 잘해야할 듯 |
| 18 | | <a href="https://www.acmicpc.net/problem/3986" target="_blank">3986</a> | <a href="https://www.acmicpc.net/problem/3986" target="_blank">좋은 단어</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | Good | 'A', 'B'만 비교하자 |
| 19 | | <a href="https://www.acmicpc.net/problem/1021" target="_blank">1021</a> | <a href="https://www.acmicpc.net/problem/1021" target="_blank">회전하는 큐</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | Good | 어디 위치하냐에 따라서 왼쪽인지 오른쪽인지 정한다. |
| 20 | | <a href="https://www.acmicpc.net/problem/18115" target="_blank">18115</a> | <a href="https://www.acmicpc.net/problem/18115" target="_blank">카드 놓기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | Good | stack 처럼 꺼내려면 반복문을 거꾸로 돌려야지 |
| 21 | | <a href="https://www.acmicpc.net/problem/5397" target="_blank">5397</a> | <a href="https://www.acmicpc.net/problem/5397" target="_blank">키로거</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> | Bad | stack을 2개로 나눠서 사용하고, insert 보다는 그냥 append, pop가 좋음 |
| 22 | | <a href="https://www.acmicpc.net/problem/5430" target="_blank">5430</a> | <a href="https://www.acmicpc.net/problem/5430" target="_blank">AC</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> | Good | join()와 strip(), split()를 잘써야함 |
| 23 | | <a href="https://www.acmicpc.net/problem/1863" target="_blank">1863</a> | <a href="https://www.acmicpc.net/problem/1863" target="_blank">스카이라인 쉬운거</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> | Good | 스카이라인 문제 이해 잘해두기 |
| 24 | | <a href="https://www.acmicpc.net/problem/22866" target="_blank">22866</a> | <a href="https://www.acmicpc.net/problem/22866" target="_blank">탑 보기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/> | Bad | 시간초과를 해결한 방도가 보이지 않는다. |
