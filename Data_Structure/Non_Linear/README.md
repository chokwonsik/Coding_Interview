# 비선형 자료구조



* 그래프
  * [Leetcode 200 섬의 개수](https://leetcode.com/problems/number-of-islands/)(Array, Depth-First Search, Breadth-First Search, Union Find, Matrix )
    * [코드 (DFS로 그래프 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/32_200_Number-of-Islands/32_200_DFS.py)
  * [Leetcode 17 전화 번호 문자 조합](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) (Hash Table, String, Backtracking)
    * [코드 (모든 조합 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/33_17_Letter-Combinations-of-a-Phone-Number/33_17_backtracking.py)
  * [Leetcode 46 순열](https://leetcode.com/problems/permutations/) (Array, Backtracking)
    * [코드 (DFS를 활용한 순열 생성)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/34_46_Permutations/34_46_DFS.py)
    * [코드 (itertools 모듈 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/34_46_Permutations/34_46_itertools.py)
  * [LeetCode 77 조합](https://leetcode.com/problems/combinations/) (Backtracking)
    * [코드 (DFS로 K개 조합 생성)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/35_77_Combinations/35_77_DFS.py)
    * [코드 (itertools 모듈 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/35_77_Combinations/35_77_itertools.py)
  * [LeetCode 39 조합의 합](https://leetcode.com/problems/combination-sum/) (Array, Backtracking)
    * [코드 (DFS로 중복 조합 그래프 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/36_39_Combination-Sum/36_39_DFS.py)
  * [LeetCode 78 부분 집합](https://leetcode.com/problems/subsets/) (Array, Backtracking, Bit Manipulation)
    * [코드 (트리의 모든 DFS 결과)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/37_78_Subsets/37_78_DFS.py)
  * [LeetCode 332 일정 재구성](https://leetcode.com/problems/reconstruct-itinerary/) (Depth-First Search, Graph, Eulerian Circuit)
    * [코드 (DFS로 일정 그래프 구성)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_DFS.py)
    * [코드 (스택 연산으로 쿠 연산 최적화 시도)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_stack.py)
    * [코드 (일정 그래프 반복)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_repeat.py)
  * [LeetCode 207 코스 스케줄](https://leetcode.com/problems/course-schedule/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
    * [코드 (가지치기를 이용한 최적화)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/39_207_Course-Schedule/39_207_backtracking.py)

* 최단 경로 문제
  * [LeetCode 743 코스 스케줄](https://leetcode.com/problems/network-delay-time/)  (Depth-First Search, Breadth-First Search, Graph, Heap(Priority Queue), Shortest Path)
    * [코드 (DFS로 순환 구조 판별)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/13_shortest-path-problem/40_743_Network-Delay-Time/40_743_DFS.py)
  * [LeetCode 787 K경유지 내 가장 저렴한 항공권](https://leetcode.com/problems/cheapest-flights-within-k-stops/) (Dynamic Programming, Depth-First Search, Breadth-First Search, Graph, Heap(Priority Queue), Shortest Path)
    * [코드 (다익스트라 알고리즘 응용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/13_shortest-path-problem/41_787_Cheapest-Flights-Within-K-Stops/41_787_Dijkstra.py)

* 트리
  * [LeetCode 104 이진 트리의 최대 깊이](https://leetcode.com/problems/maximum-depth-of-binary-tree/) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
    * [코드 (반복 구조로 BFS 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/Data_Structure/Non_Linear/14_Tree/42_104_Maximum-Depth-of-Binary-Tree/42_104_BFS.py)
  * [LeetCode 543 이진 트리의 직경](https://leetcode.com/problems/diameter-of-binary-tree/) (Tree, Depth-First Search, Binary Tree)
    * [코드 (상태값 누적 트리 DFS)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/43_543_Diameter-of-Binary-Tree/43_543_DFS.py)
* 힙 
* 트라이


>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.316-475.
> >pythaac, 코드 (다익스트라 알고리즘 응용), https://github.com/onlybooks/algorithm-interview/issues/104 