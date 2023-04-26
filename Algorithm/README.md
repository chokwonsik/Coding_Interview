# 알고리즘

* 정렬
  * [LeetCode 148 리스트 정렬](https://leetcode.com/problems/sort-list/) (Linked List, Two Pointers, Divide and Conquer, Sorting, Merge Sort)
    * [병합정렬](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/58_148_Sort-List/58_148_merge-sort.py)
    * [내장 함수를 이용하는 실용적인 방법](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/58_148_Sort-List/58_148_sort.py)
  * [LeetCode 56 구간 병합](https://leetcode.com/problems/merge-intervals/) (Array, Sorting)
    * [정렬하여 병합](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/59_56_Merge-Intervals/59_56_merge-sorted.py)
  * [LeetCode 147 삽입 정렬 리스트](https://leetcode.com/problems/insertion-sort-list/) (Linked List, Sorting) 
    * [삽입 정렬](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/60_147_Insertion-Sort-List/60_147_insertion.py)
    * [삽입 정렬의 비교 조건 개선](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/60_147_Insertion-Sort-List/60_147_insertion_Improving.py)
  * [LeetCode 179 가장 큰 수](https://leetcode.com/problems/largest-number/) (String, Greedy, Sorting)
    * [삽입 정렬](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/61_179_Largest-Number/61_179_insertion.py)
  * [LeetCode 242 유효한 애너그램](https://leetcode.com/problems/valid-anagram/) (Hash Table, String, Sorting)
    * [정렬을 이용한 비교](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/62_242_Valid-Anagram/62_242_Pythonic.py)
  * [LeetCode 75 색 정렬](https://leetcode.com/problems/sort-colors/) (Array, Two Pointers, Sorting)
    * [네덜란드 국기 문제를 응용한 풀이](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/63_75_Sort-Colors/63_75_Dutch-National-Flag-Problem.py)
  * [LeetCode 973 원점에 K번째로 가까운 점](https://leetcode.com/problems/k-closest-points-to-origin/) (Array, Math, Divide and Conquer, Geometry, Sorting, Heap(Priority Queue), Quickselect)
    * [유클리드 거리의 우선순위 큐 순서](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Sorting/64_973_K-Closest-Points-to-Origin/64_973_Euclidean-Distanc.py)
    

* 이진검색 
  * [LeetCode 704 이진 검색](https://leetcode.com/problems/binary-search/) (Array, Binary Search)
      * [재귀 풀이](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/65_704_Binary-Search/65_704_recursion.py)
      * [반복 풀이](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/65_704_Binary-Search/65_704_repeat.py)
      * [이진 검색 모듈](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/65_704_Binary-Search/65_704_bisect.py)
      * [이진 검새을 사용하지 않는 index 풀이](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/65_704_Binary-Search/65_704_index.py)
  * [LeetCode 33 회전 정렬된 배열 검색](https://leetcode.com/problems/search-in-rotated-sorted-array/) (Array, Bianry, Search)
    * [피벗을 기준으로 한 이진 검색](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/66_33_Search-in-Rotated-Sorted-Array/66_33_pivot.py)
  * [LeetCode 349 두 배열의 교집합](https://leetcode.com/problems/intersection-of-two-arrays/) (Array, Hashtable, Two Pointers, Binary Search, Sorting)
    * [부르트 포스로 계산](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/67_349_Intersection-of-Two-Arrays/67_349_Brute-Force.py)
    * [이진 검색으로 일치 여부 판별](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/67_349_Intersection-of-Two-Arrays/67_349_binary-search.py)
    * [투 포인터로 일치 여부 판별](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/67_349_Intersection-of-Two-Arrays/67_349_two-pointer.py)
  * [LeetCode 167 두 수의 합 II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) (Array, Two Pointers, Binary Search)
    * [투 포인터](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/68_167_Two%20Sum-II-Input-Array-Is-Sorted/68_167_two-pointers.py)
    * [이진 검색](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/68_167_Two%20Sum-II-Input-Array-Is-Sorted/68_167_binary-serach.py) 
    * [bisect 모듈 + 슬라이싱](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/68_167_Two%20Sum-II-Input-Array-Is-Sorted/68_167_bisect%26slicing.py)
    * [bisect 모듈 + 슬라이싱 최소화](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/68_167_Two%20Sum-II-Input-Array-Is-Sorted/68_167_bisect%26slicing-minimization.py)
    * [bisect 모듈 + 슬라이싱 제거](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/68_167_Two%20Sum-II-Input-Array-Is-Sorted/68_167_bisect.py)
  * [LeetCode 240 2D 행렬 검색 II](https://leetcode.com/problems/search-a-2d-matrix-ii/)
    * [첫 행의 맨 뒤에서 탐색](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Binary-Search/69_240_Search-a-2D-Matrix-II/69_240_binary-serach.py)
* 비트 조작 


* 슬라이딩 윈도우 


* 그리디 알고리즘  
  * [LeetCode 122 주식을 사고팔기 가장 좋은 시점 2](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) (Array, Dynamic Programming, Greedy)
    * [그리디 알고리즘](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122_greedy.py)
    * [Pythonic](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122_pythonic.py)
  * [LeetCode 406 키에 따른 대기열 재구성](https://leetcode.com/problems/queue-reconstruction-by-height/) (Array, Greedy, Binary Indexed Tree, Segment Tree, Sorting)
    * [우선순위 큐 이용](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/79_406_Queue-Reconstruction-by-Height/79_406_priority-queue.py)
  * [LeetCode 621 태스크 스케줄러](https://leetcode.com/problems/task-scheduler/) (Array, Hash Table, Greedy, Sorting, Heap(Priority Queue), Counting)
    * [우선순위 큐 이용](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/80_621_Task-Scheduler/80_621_priority-queue.py)
  * [LeetCode 134 주유소](https://leetcode.com/problems/gas-station/) (Array, Greedy)
    * [모두 방문](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/81_134_Gas-Station/81_134_a-visit.py)
    * [한 번 방문](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/81_134_Gas-Station/81_134_visit-all.py)
  * [LeetCode 455 쿠키 부여](https://leetcode.com/problems/assign-cookies/) (Array, Greedy, sorting)
    * [그리디 알고리즘](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/82_455_Assign-Cookies/82_455_greedy.py)
    * [이진 검색](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/Greedy-Algorithm/82_455_Assign-Cookies/82_455_binary-search.py) 
 
* 분할 정복 


* 다이나믹 프로그래밍

>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.478-646.