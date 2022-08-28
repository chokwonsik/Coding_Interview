₩# Coding_Interview
## LeetCode 문제 풀이

* 개발 언어 및 도구
  * "Python 3.7+" , 리트코드, 파이참 커뮤니티 에디션
  
---------------------------------------

### [문자열 조작](https://github.com/chokwonsik/Coding_Interview/tree/main/String-Manipulation)
  * [LeetCode 125 유효한 팰린드롬](https://leetcode.com/problems/valid-palindrome/) (Two Pointers, String)
    * [코드 (리스트로 변환)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_list.py)
    * [코드 (데크 자료형을 이용한 최적화)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_deque.py)
    * [코드 (슬라이싱 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_slicing.py)
  * [LeetCode 344 문자열 뒤집기](https://leetcode.com/problems/reverse-string/) (Two Pointers, String, Recursion)
    * [코드 (투 포인터를 이용한 스왑)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/2_344_Reverse-String/2_344_two-pointer.py)
    * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/2_344_Reverse-String/2_344_pythonic.py)
  * [LeetCode 937 로그 파일 재정렬](https://leetcode.com/problems/reorder-data-in-log-files/) (Array, String, Sorting)
    * [코드 (람다와 +연산자를 이용)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/3_937_Reorder-Log-Files/3_937.py)
  * [LeetCode 819 가장 흔한 단어](https://leetcode.com/problems/most-common-word/) (Hash Table, String, Counting)
    * [코드 (리스트 컴프리헨션, Counter 객체 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/4_819_Most-Common-Word/4_819.py)
  * [LeetCode 49 그룹 애너그램](https://leetcode.com/problems/group-anagrams/) (Hash Table, String, Sorting)
    * [코드 (정렬하여 딕셔너리에 추가)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/5_49_Group-Anagrams/5_49.py)
  * [LeetCode 5 가장 긴 팰린드롬 부분 문자열](https://leetcode.com/problems/longest-palindromic-substring/) (String, Dynamic Programming)
    * [코드 (중앙을 중심으로 확장하는 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/6_5_Longest-Palindromic-Substring/6_5.py)
  
---------------------------------------
### [선형 자료구조](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/README.md)
* 배열
  * [LeetCode 1 두 수의 합](https://leetcode.com/problems/two-sum/) (Array, Hash Table)
    * [코드 (브루트 포스로 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_brute-force.py)
    * [코드 (in을 이용한 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_in.py)
    * [코드 (첫 번쨰 수를 뺀 결과 키 조회)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_dict.py) 
    * [코드 (조회 구조 개선)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_dict-2.py)
  * [LeetCode 42 빗물 트래핑](https://leetcode.com/problems/trapping-rain-water/) (Array, Two Pointers, Dynamic Programming, Stack, Monotonic Stack)
    * [코드 (스택 쌓기)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_42_Trapping-Rain-Water/8_42_stack.py)
    * [코드 (투 포인터를 최대로 이동)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_42_Trapping-Rain-Water/8_42_two-pointer.py) 
  * [LeetCode 15 세 수의 합](https://leetcode.com/problems/3sum/) (Array, Two Pointers, Sorting)
    * [코드 (브루트 포스로 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_15_3Sum/9_15_brute-force.py)
    * [코드 (투 포인터로 합 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_15_3Sum/9_15_two-pointer.py)
  * [LeetCode 561 배열 파티션 1 ](https://leetcode.com/problems/array-partition-i/) (Array, Greedy, Sorting, Counting Sort)
    * [코드 (오름차순 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_ascending.py)
    * [코드 (짝수 번째 값 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_even-number.py)
    * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_pythonic.py)
  * [LeetCode 238 자신을 제외한 배열의 곱](https://leetcode.com/problems/product-of-array-except-self/) (Array, Prefix Sum)
    * [코드 (왼쪽 곱셈 결과에 오르쪽 값을 차례대로 곱셈)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/11_238_Product-of-Array-Except-Self/11_238.py)
  * [LeetCode 121 주식을 사고팔기 가장 좋은 시점](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) (Array, Dynamic Programming)
    * [코드 (브루트 포스로 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_121_Best%20Time-to-Buy-and-Sell-Stock/12_121_brute-force.py)
    * [코드 (저점과 현재 값과의 차이 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_121_Best%20Time-to-Buy-and-Sell-Stock/12_121_min%26max.py)

      
* 연결리스트
  * [LeetCode 234 팰린드롬 연결 리스트](https://leetcode.com/problems/palindrome-linked-list/) (Linked List, Two Pointers, Stack, Recursion)
    * [코드 (리스트 변환)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_234_list.py)
    * [코드 (데크를 이용한 최적화)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_234_deque.py)
    * [코드 (런너를 이용한 우아한 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_234_runner.py)
  * [LeetCode 21 두 정렬 리스트의 병합](https://leetcode.com/problems/merge-two-sorted-lists/) (Linked List, Recursion)
    * [코드 (재귀 구조로 연결)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/14_21_Merge-Two-Sorted-Lists/14_21_recursive.py)
  * [LeetCode 206 역순 연결리스트](https://leetcode.com/problems/reverse-linked-list/) (Linked List, Recursion)
    * [코드 (재귀 구조로 뒤집기)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_206_Reverse-Linked-List/15_206_recursive.py)
    * [코드 (반복 구조로 뒤집기)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_206_Reverse-Linked-List/15_206_lterative.py)
  * [LeetCode 2 두 수의 덧셈](https://leetcode.com/problems/add-two-numbers/) (Linked List, Math, Recursion)
    * [코드 (자료형 변환)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_2_Add-Two-Numbers/16_2_casting.py)
    * [코드 (전가산기 구현)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_2_Add-Two-Numbers/16_2_casting.py)
  * [LeetCode 24 페어의 노드스왑](https://leetcode.com/problems/swap-nodes-in-pairs/) (Linked List, Recursion)
    * [코드 (값만 교환)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_value-exchange.py)
    * [코드 (반복 구조로 스왑)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_repeat-swap.py)
    * [코드 (재귀 구조로 스왑) ](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_recursion.py)
  * [LeetCode 328 홀짝 연결 리스트](https://leetcode.com/problems/odd-even-linked-list/) (Linked List)
     * [코드 (반복 구조로 홀짝 노드 처리)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/18_328_Odd-Even-Linked-List/18_328_repeat.py)
  * [LeetCode 92 역순 연결 리스트](https://leetcode.com/problems/reverse-linked-list-ii) (Linked List)
     * [코드 (반복 구조로 노드 뒤집기)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/19_92_Reverse-Linked-List-II/19_92_repeat.py)


* 스택, 큐
  * [LeetCode 20 유호한 괄호](https://leetcode.com/problems/valid-parentheses/) (String, Stack)
      * [코드 (스택 일치 여부 판별)](https://github.com/onlybooks/algorithm-interview/blob/master/3-linear-data-structures/ch09/20-1.py)
  * [LeetCode 316 중복 문자 제거](https://leetcode.com/problems/remove-duplicate-letters/) (String, Stack, Greedy, Monotonic Stack)
      * [코드 (재귀를 이용한 분리)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/21_316_Remove-Duplicate-Letters/21_316_recursion.py)
      * [코드 (스택을 이용한 문자 제거)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/21_316_Remove-Duplicate-Letters/21_316_stack.py)
  * [LeetCode 739 일일온도](https://leetcode.com/problems/daily-temperatures/) (Array, Stack, Monotonic Stack)
      * [코드 (스택 값 비교)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/22_739_Daily-Temperatures/22_739_stack.py)
  * [LeetCode 225 큐를 이용한 스택 구현](https://leetcode.com/problems/implement-stack-using-queues/) (Stack, Design, Queue)
      * [코드 (push() 할 때 큐를 이용해 재정렬)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/23_225_Implement-Stack-using-Queues/23_225_push.py)
  * [LeetCode 232 스택을 이용한 큐 구현](https://leetcode.com/problems/implement-queue-using-stacks/) (Stack, Design, Queue)
    * [코드 (스택 2개 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/24_232_Implement-Queue-using-Stacks/24_232_stack.py)
  * [LeetCode 622 원형 큐 디자인](https://leetcode.com/problems/design-circular-queue/) (Array, Linked List, Design, Queue)
    * [코드 (배열을 이용한 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/25_622_Design-Circular-Queue/25_622_array.py)


* 데크, 우선 순위 큐
  * [LeetCode 641 원형 테크 디자인](https://leetcode.com/problems/design-circular-deque/) (Array, Linked List, Design, Queue)
    * [코드 (이중 연결 리스트)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/10_Dequq%26Priority-queue/26_641_Design-Circular-Deque/26_641_Doubly-linked-list.py)
  * [LeetC0de 23 k개 정렬 리스트 병합](https://leetcode.com/problems/merge-k-sorted-lists/) (Linked List, Divide and Conquer, Heap(Priority Queue), Merge Sort) 
    * [코드 (우선순위 큐를 이용한 리스트 병합)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/10_Dequq%26Priority-queue/27_23_Merge-k-Sorted-Lists/27_23_Priority-queue.py)


* 해시 테이블
  * [LeetCode 706 해시맵 디자인](https://leetcode.com/problems/design-hashmap/) (Array, Hash Table, Linked List, Design, Hash Function)
    * [코드 (개별 체이닝 방식을 이용한 해시 테이블 구현)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/28_706_Design-HashMap/28_706_Individual-chaining.py)
  * [LeetCode 771 보석과 돌](https://leetcode.com/problems/jewels-and-stones/) (Hash Table, String)
    * [코드 (해시 테이블을 이용한 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/29_771_Jewels-and-Stones/29_771_hash-table.py) 
    * [코드 (defaultdict를 이용한 비교 생략)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/29_771_Jewels-and-Stones/29_771_defaultdict.py)
    * [코드 (Counter로 계산 생략)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/29_771_Jewels-and-Stones/29_771_counter.py)
    * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/29_771_Jewels-and-Stones/29_771_pythonic.py)
  * [LeetCode 3 중복 문자 없는 가장 긴 부분 문자열](https://leetcode.com/problems/longest-substring-without-repeating-characters/) (Hash Table, String, Sliding Window)
    * [코드 (슬라이딩 윈도우와 투 포인터로 사이즈 조절)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/30_3_Longest-Substring-Without-Repeating-Characters/30_3_sliding-window&two-pointer.py)
  * [LeetCode 347 상위 K 빈도 요소](https://leetcode.com/problems/top-k-frequent-elements/) (Array, Hash Table, Divide and Conquer, Sorting, Heap(Priority Queue), Bucket Sort, Counting, Quickselect)
    * [코드 (Counter를 이용한 음수 순 추출)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/31_347_Top-K-Frequent-Elements/31_347_counter.py)
    * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/11_hash-table/31_347_Top-K-Frequent-Elements/31_347_Pythonic.py)


---------------------------------------------

### [비선형 자료구조](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/README.md)
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
    * [LeetCode 687 가장 긴 동일 값의 경로](https://leetcode.com/problems/longest-univalue-path/) (Tree, Depth-First Search Binary Tree)
      * [코드 (상태값 거리 계산 DFS)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/44_687_Longest-Univalue-Path/44_687_DFS.py)
    * [LeetCode 226 이진 트리 반전](https://leetcode.com/problems/invert-binary-tree/) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
      * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_Pythonic.py)
      * [코드 (DFS)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_DFS.py)
      * [코드 (DFS2)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_DFS2.py)
      * [코드 (Post-Order)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_Post-Order.py)
    * [LeetCode 617 두 이진 트리 병합](https://leetcode.com/problems/merge-two-binary-trees/)
      * [코드 (재귀 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/46_617_Merge-Two-Binary-Trees/46_617_recursion.py) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
    * [LeetCode 297 이진 트리 직렬화 & 역직렬화](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) (String, Tree, Depth-First Search, Breadth-First Search, Design, Binary Tree)
      * [코드 직렬화 & 역직렬화 구현](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/47_297_Serialize-and-Deserialize-Binary-Tree/47_297_Serialize%26Deserialize.py)
    * [LeetCode 110 균형 이진 트리](https://leetcode.com/problems/balanced-binary-tree/) (Tree, Depth-First Search, Binary Tree)
      * [코드 (재귀 구조로 높이 차이 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/48_110_balanced-binary-tree/48_110_recursion.py)
    * [LeetCode 310 최소 높이 트리 ](https://leetcode.com/problems/minimum-height-trees/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
      * [코드 (단계별 리프 노드 제거)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/49_310_Minimum-Height-Trees/49_310_bianry-search-tree.py)
    * [LeetCode 310 최소 높이 트리 ](https://leetcode.com/problems/minimum-height-trees/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
      * [코드 (단계별 리프 노드 제거)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/49_310_Minimum-Height-Trees/49_310_bianry-search-tree.py)
    * [LeetCode 1038 이진 탐색 트리를 더 큰 수 합계 트리로](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) (Tree, Depth-First Search, Binary Search Tree, binary Tree)
      * [코드 (중외 순회로 노드 값 누적)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/51_1038_Binary-Search-Tree-to-Greater-Sum-Tree/51_1038_BST.py)
    * [LeetCode 938 이진 탐색 트리 합의 범위](https://leetcode.com/problems/range-sum-of-bst/) (Tree, Depth-First Search, Binary Search Tree, Binary Tree)
      * [코드 (재귀 구조 DFS로 부르트 포스 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_brute-force.py)
      * [코드 (DFS 가지치기로 필요한 노드 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_branch-pruning.py)
      * [코드 (반복 구조 DFS로 필요한 노드 탐색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_DFS.py)
      * [코드 (반복 구조 DFS로 필요한 노드 탐색 (큐))](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_DFS-queue.py)
    * [LeetCode 783 이진탐색트리(BST) 노드간 최소 거리](https://leetcode.com/problems/minimum-distance-between-bst-nodes/) (Tree, Depth-First Search, Breadth-First Search, Binary Search Tree, Binary Tree)
      * [코드 (재귀 구조로 중위 순회)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/53_783_Minimum-Distance-Between-BST-Nodes/53_783_recursion.py)
      * [코드 (반복 구조로 중위 순회)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/53_783_Minimum-Distance-Between-BST-Nodes/53_783_repeat.py)
    * [LeetCode 105 전위, 중위 순회 결과로 이진 트리 구축](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) (Array, Hash Table, Divide and Conquer, Tree, Binary Tree)
      * [코드 (전위 순회 결과로 중위 순회 분할 정복)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/54_105_Construct-Binary-Tree-from-Preorder-and-Inorder-Traversal/54_105_pre-order%26in-order.py)

  * 힙
    * [LeetCode 215 배열의 K번째 큰 요소](https://leetcode.com/problems/kth-largest-element-in-an-array/) (Array, Divide and Conquer, Sorting, Heap (Priority Queue), Quickselect)
      * [코드 (heapq 모듈 이용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heqpq.py)
      * [코드 (heapq 모듈의 heqpify 이용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heapq-heapify.py)
      * [코드 (heqpq 모듈의 nlargest 이용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heapq-nlargest.py)
      * [코드 (정렬을 이용한 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_sorted.py)

  * 트라이
    * [LeetCode 208 트라이 구현](https://leetcode.com/problems/implement-trie-prefix-tree/) (Hash Table, String, Design, Trie)
      * [코드 (딕셔너리를 이용해 간결한 트라이 구현)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/56_208_%20Implement-Trie-(Prefix-Tree)/56_208_dict.py)
    * [LeetCode 336 팰린드롬 페어](https://leetcode.com/problems/palindrome-pairs/)
      * [코드 (팰린드롬을 브루트 포스로 계산)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/57_336_palindrome-pairs/57_336_brute-force.py)
      * [코드 (트라이 구현)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/57_336_palindrome-pairs/57_336_trie.py)

---------------------------------------

### [알고리즘](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/README.md)
* 정렬
  * [LeetCode 148 리스트 정렬](https://leetcode.com/problems/sort-list/) (Linked List, Two Pointers, Divide and Conquer, Sorting, Merge Sort)
    * [코드 (병합정렬)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/58_148_Sort-List/58_148_merge-sort.py)
    * [코드 (내장 함수를 이용하는 실용적인 방법)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/58_148_Sort-List/58_148_sort.py)
  * [LeetCode 56 구간 병합](https://leetcode.com/problems/merge-intervals/) (Array, Sorting)
    * [코드 (정렬하여 병합)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/59_56_Merge-Intervals/59_56_merge-sorted.py)
  * [LeetCode 147 삽입 정렬 리스트](https://leetcode.com/problems/insertion-sort-list/) (Linked List, Sorting) 
    * [코드 (삽입 정렬)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/60_147_Insertion-Sort-List/60_147_insertion.py)
    * [코드 (삽입 정렬의 비교 조건 개선)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/60_147_Insertion-Sort-List/60_147_insertion_Improving.py)
  * [LeetCode 179 가장 큰 수](https://leetcode.com/problems/largest-number/) (String, Greedy, Sorting)
    * [코드 (삽입 정렬)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/61_179_Largest-Number/61_179_insertion.py)
* 이진검색 
* 비트 조작 
* 슬라이딩 윈도우 
* 그리디 알고리즘  
  * [LeetCode 122 주식을 사고팔기 가장 좋은 시점 2](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) (Array, Dynamic Programming, Greedy)
    * [코드 (그리디 알고리즘)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122_greedy.py)
    * [코드 (Pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122_pythonic.py)
  * [LeetCode 455 쿠키 부여](https://leetcode.com/problems/assign-cookies/) (Array, Greedy, sorting)
    * [코드 (그리디 알고리즘)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/82_455_Assign-Cookies/82_455_greedy.py)
    * [코드 (이진 검색)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/82_455_Assign-Cookies/82_455_binary-search.py) 
 
* 분할 정복 
* 다이나믹 프로그래밍


---------------------------------------

>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.14-35.
> >pythaac, 코드 (다익스트라 알고리즘 응용), https://github.com/onlybooks/algorithm-interview/issues/104