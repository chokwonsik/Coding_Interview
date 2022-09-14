# 비선형 자료구조



* 그래프
  * [Leetcode 200 섬의 개수](https://leetcode.com/problems/number-of-islands/)(Array, Depth-First Search, Breadth-First Search, Union Find, Matrix )
    * [DFS로 그래프 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/32_200_Number-of-Islands/32_200_DFS.py)
  * [Leetcode 17 전화 번호 문자 조합](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) (Hash Table, String, Backtracking)
    * [모든 조합 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/33_17_Letter-Combinations-of-a-Phone-Number/33_17_backtracking.py)
  * [Leetcode 46 순열](https://leetcode.com/problems/permutations/) (Array, Backtracking)
    * [DFS를 활용한 순열 생성](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/34_46_Permutations/34_46_DFS.py)
    * [itertools 모듈 사용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/34_46_Permutations/34_46_itertools.py)
  * [LeetCode 77 조합](https://leetcode.com/problems/combinations/) (Backtracking)
    * [DFS로 K개 조합 생성](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/35_77_Combinations/35_77_DFS.py)
    * [itertools 모듈 사용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/35_77_Combinations/35_77_itertools.py)
  * [LeetCode 39 조합의 합](https://leetcode.com/problems/combination-sum/) (Array, Backtracking)
    * [DFS로 중복 조합 그래프 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/36_39_Combination-Sum/36_39_DFS.py)
  * [LeetCode 78 부분 집합](https://leetcode.com/problems/subsets/) (Array, Backtracking, Bit Manipulation)
    * [트리의 모든 DFS 결과](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/37_78_Subsets/37_78_DFS.py)
  * [LeetCode 332 일정 재구성](https://leetcode.com/problems/reconstruct-itinerary/) (Depth-First Search, Graph, Eulerian Circuit)
    * [DFS로 일정 그래프 구성](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_DFS.py)
    * [스택 연산으로 쿠 연산 최적화 시도](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_stack.py)
    * [일정 그래프 반복](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/38_332_Reconstruct-Itinerary/38_332_repeat.py)
  * [LeetCode 207 코스 스케줄](https://leetcode.com/problems/course-schedule/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
    * [가지치기를 이용한 최적화](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/12_graph/39_207_Course-Schedule/39_207_backtracking.py)


* 최단 경로 문제
  * [LeetCode 743 코스 스케줄](https://leetcode.com/problems/network-delay-time/)  (Depth-First Search, Breadth-First Search, Graph, Heap(Priority Queue), Shortest Path)
    * [DFS로 순환 구조 판별](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/13_shortest-path-problem/40_743_Network-Delay-Time/40_743_DFS.py)
  * [LeetCode 787 K경유지 내 가장 저렴한 항공권](https://leetcode.com/problems/cheapest-flights-within-k-stops/) (Dynamic Programming, Depth-First Search, Breadth-First Search, Graph, Heap(Priority Queue), Shortest Path)
     * [다익스트라 알고리즘 응용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/13_shortest-path-problem/41_787_Cheapest-Flights-Within-K-Stops/41_787_Dijkstra.py)


* 트리 
  * [LeetCode 104 이진 트리의 최대 깊이](https://leetcode.com/problems/maximum-depth-of-binary-tree/) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
    * [반복 구조로 BFS 풀이](https://github.com/chokwonsik/Coding_Interview/blob/Data_Structure/Non_Linear/14_Tree/42_104_Maximum-Depth-of-Binary-Tree/42_104_BFS.py)
  * [LeetCode 543 이진 트리의 직경](https://leetcode.com/problems/diameter-of-binary-tree/) (Tree, Depth-First Search, Binary Tree)
    * [상태값 누적 트리 DFS](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/43_543_Diameter-of-Binary-Tree/43_543_DFS.py)
  * [LeetCode 687 가장 긴 동일 값의 경로](https://leetcode.com/problems/longest-univalue-path/) (Tree, Depth-First Search Binary Tree)
    * [상태값 거리 계산 DFS](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/44_687_Longest-Univalue-Path/44_687_DFS.py)
  * [LeetCode 226 이진 트리 반전](https://leetcode.com/problems/invert-binary-tree/) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
    * [Pythonic](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_Pythonic.py)
    * [DFS](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_DFS.py)
    * [DFS2](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_DFS2.py)
    * [Post-Order](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/45_226_Invert-Binary-Tree/45_226_Post-Order.py)
  * [LeetCode 617 두 이진 트리 병합](https://leetcode.com/problems/merge-two-binary-trees/)
    * [재귀 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/46_617_Merge-Two-Binary-Trees/46_617_recursion.py) (Tree, Depth-First Search, Breadth-First Search, Binary Tree)
  * [LeetCode 297 이진 트리 직렬화 & 역직렬화](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) (String, Tree, Depth-First Search, Breadth-First Search, Design, Binary Tree)
    * [렬화 & 역직렬화 구현](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/47_297_Serialize-and-Deserialize-Binary-Tree/47_297_Serialize%26Deserialize.py)
  * [LeetCode 110 균형 이진 트리](https://leetcode.com/problems/balanced-binary-tree/) (Tree, Depth-First Search, Binary Tree)
    * [재귀 구조로 높이 차이 계산](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/48_110_balanced-binary-tree/48_110_recursion.py)
  * [LeetCode 310 최소 높이 트리 ](https://leetcode.com/problems/minimum-height-trees/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
    * [단계별 리프 노드 제거](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/49_310_Minimum-Height-Trees/49_310_bianry-search-tree.py)
  * [LeetCode 310 최소 높이 트리 ](https://leetcode.com/problems/minimum-height-trees/) (Depth-First Search, Breadth-First Search, Graph, Topological Sort)
    * [단계별 리프 노드 제거](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/49_310_Minimum-Height-Trees/49_310_bianry-search-tree.py)
  * [LeetCode 1038 이진 탐색 트리를 더 큰 수 합계 트리로](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) (Tree, Depth-First Search, Binary Search Tree, binary Tree)
    * [중외 순회로 노드 값 누적](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/51_1038_Binary-Search-Tree-to-Greater-Sum-Tree/51_1038_BST.py)
  * [LeetCode 938 이진 탐색 트리 합의 범위](https://leetcode.com/problems/range-sum-of-bst/) (Tree, Depth-First Search, Binary Search Tree, Binary Tree)
    * [재귀 구조 DFS로 부르트 포스 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_brute-force.py)
    * [DFS 가지치기로 필요한 노드 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_branch-pruning.py)
    * [반복 구조 DFS로 필요한 노드 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_DFS.py)
    * [반복 구조 DFS로 필요한 노드 탐색 (큐)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/52_938_Range-Sum-of-BST/52_938_DFS-queue.py)
  * [LeetCode 783 이진탐색트리(BST) 노드간 최소 거리](https://leetcode.com/problems/minimum-distance-between-bst-nodes/) (Tree, Depth-First Search, Breadth-First Search, Binary Search Tree, Binary Tree)
    * [재귀 구조로 중위 순회](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/53_783_Minimum-Distance-Between-BST-Nodes/53_783_recursion.py)
    * [반복 구조로 중위 순회](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/53_783_Minimum-Distance-Between-BST-Nodes/53_783_repeat.py)
  * [LeetCode 105 전위, 중위 순회 결과로 이진 트리 구축](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) (Array, Hash Table, Divide and Conquer, Tree, Binary Tree)
    * [전위 순회 결과로 중위 순회 분할 정복](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/14_Tree/54_105_Construct-Binary-Tree-from-Preorder-and-Inorder-Traversal/54_105_pre-order%26in-order.py)


* 힙
  * [LeetCode 215 배열의 K번째 큰 요소](https://leetcode.com/problems/kth-largest-element-in-an-array/) (Array, Divide and Conquer, Sorting, Heap (Priority Queue), Quickselect)
    * [heapq 모듈 이용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heqpq.py)
    * [heapq 모듈의 heqpify 이용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heapq-heapify.py)
    * [heqpq 모듈의 nlargest 이용](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_heapq-nlargest.py)
    * [정렬을 이용한 풀이](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/15_Heap/55_215_Kth-Largest-Element-in-an-Array/55_215_sorted.py)


* 트라이
  * [LeetCode 208 트라이 구현](https://leetcode.com/problems/implement-trie-prefix-tree/) (Hash Table, String, Design, Trie)
    * [딕셔너리를 이용해 간결한 트라이 구현](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/56_208_%20Implement-Trie-(Prefix-Tree)/56_208_dict.py)
  * [LeetCode 336 팰린드롬 페어](https://leetcode.com/problems/palindrome-pairs/)
    * [팰린드롬을 브루트 포스로 계산](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/57_336_palindrome-pairs/57_336_brute-force.py)
    * [트라이 구현](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/16_Trie/57_336_palindrome-pairs/57_336_trie.py)


>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.316-475.
> >pythaac, 코드 (다익스트라 알고리즘 응용), https://github.com/onlybooks/algorithm-interview/issues/104 