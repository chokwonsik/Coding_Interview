# Coding_Interview
## LeetCode 문제 풀이

* 개발 언어 및 도구
  * "Python 3.7+" , 리트코드, 파이참 커뮤니티 에디션
  
---------------------------------------

### [문자열 조작](https://github.com/chokwonsik/Coding_Interview/tree/main/String-Manipulation)
  * [LeetCode 125 유효한 팰린드롬](https://leetcode.com/problems/valid-palindrome/) (Two Pointers, String)
    * [코드 (slicing)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_slicing.py),
      [코드 (deque)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_deque.py), 
      [코드 (list)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/1_125_Valid-Palindrome/1_125_list.py)
  * [LeetCode 344 문자열 뒤집기](https://leetcode.com/problems/reverse-string/) (Two Pointers, String, Recursion)
    * [코드 (pytonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/2_344_Reverse-String/2_344_pytonic.py), 
      [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/2_344_Reverse-String/2_344_two-pointer.py)
  * [LeetCode 937 로그 파일 재정렬](https://leetcode.com/problems/reorder-data-in-log-files/) (Array, String, Sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/3_937_Reorder-Log-Files/3_937.py)
  * [LeetCode 819 가장 흔한 단어](https://leetcode.com/problems/most-common-word/) (Hash Table, String, Counting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/4_819_Most-Common-Word/4_819.py)
  * [LeetCode 49 그룹 애너그램](https://leetcode.com/problems/group-anagrams/) (Hash Table, String, Sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/5_49_Group-Anagrams/5_49.py)
  * [LeetCode 5 가장 긴 팰린드롬 부분 문자열](https://leetcode.com/problems/longest-palindromic-substring/) (String, Dynamic Programming)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/String-Manipulation/6_5_Longest-Palindromic-Substring/6_5.py)
  
---------------------------------------
### [선형 자료구조](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/README.md)
* 배열
  * [LeetCode 1 두 수의 합](https://leetcode.com/problems/two-sum/) (Array, Hash Table)
    * [코드 (dict)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_dict.py),
      [코드 (dict2)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_dict-2.py),
      [코드 (in)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_in.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_1_Two-Sum/7_1_brute-force.py)
  * [LeetCode 42 빗물 트래핑](https://leetcode.com/problems/trapping-rain-water/) (Array, Two Pointers, Dynamic Programming, Stack, Monotonic Stack)
    * [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_42_Trapping-Rain-Water/8_42_two-pointer.py),
      [코드 (stack)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_42_Trapping-Rain-Water/8_42_stack.py)
  * [LeetCode 15 세 수의 합](https://leetcode.com/problems/3sum/) (Array, Two Pointers, Sorting)
    * [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_15_3Sum/9_15_two-pointer.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_15_3Sum/9_15_brute-force.py)
  * [LeetCode 561 배열 파티션 1 ](https://leetcode.com/problems/array-partition-i/) (Array, Greedy, Sorting, Counting Sort)
    * [코드 (pytonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_pytonic.py),
      [코드 (even-number)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_even-number.py),
      [코드 (even-number)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_561_Array-Partition-I/10_561_ascending.py)
  * [LeetCode 238 자신을 제외한 배열의 곱](https://leetcode.com/problems/product-of-array-except-self/) (Array, Prefix Sum)
    * [코드 (mul)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/11_238_Product-of-Array-Except-Self/11_238.py)
  * [LeetCode 121 주식을 사고팔기 가장 좋은 시점](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) (Array, Dynamic Programming)
    * [코드 (min&max)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_121_Best%20Time-to-Buy-and-Sell-Stock/12_121_min%26max.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_121_Best%20Time-to-Buy-and-Sell-Stock/12_121_brute-force.py)
  
      
* 연결리스트
  * [LeetCode 234 팰린드롬 연결 리스트](https://leetcode.com/problems/palindrome-linked-list/) (Linked List, Two Pointers, Stack, Recursion)
    * [코드 (runner)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_234_runner.py),
      [코드 (deque)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_234_deque.py),
      [코드 (list)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_234_Palindrome-Linked-List/13_leetocde_234_list.py)
  * [LeetCode 21 두 정렬 리스트의 병합](https://leetcode.com/problems/merge-two-sorted-lists/) (Linked List, Recursion)
    * [코드 (recursive)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/14_21_Merge-Two-Sorted-Lists/14_21_recursive.py)
  * [LeetCode 206 역순 연결리스트](https://leetcode.com/problems/reverse-linked-list/) (Linked List, Recursion)
    * [코드 (lterative)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_206_Reverse-Linked-List/15_206_lterative.py),
    [코드 (recursive)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_206_Reverse-Linked-List/15_206_recursive.py)
  * [LeetCode 2 두 수의 덧셈](https://leetcode.com/problems/add-two-numbers/) (Linked List, Math, Recursion)
    * [코드 (casting)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_2_Add-Two-Numbers/16_2_casting.py), 
    [코드 (full-adder)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_2_Add-Two-Numbers/16_2_casting.py)
  * [LeetCode 24 페어의 노드스왑](https://leetcode.com/problems/swap-nodes-in-pairs/) (Linked List, Recursion)
    * [코드 (값만 교환)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_value-exchange.py),
      [코드 (반복 구조로 스왑)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_repeat-swap.py),
      [코드 (recursive) ](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/17_24_Swap-Nodes-in-Pairs/17_24_recursion.py)
  * [LeetCode 328 홀짝 연결 리스트](https://leetcode.com/problems/odd-even-linked-list/) (Linked List)
     * [코드 (반복 구조로 홀짝 노드 처리)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/18_328_Odd-Even-Linked-List/18_328_repeat.py)
  * [LeetCode 92 역순 연결 리스트](https://leetcode.com/problems/reverse-linked-list-ii) (Linked List)
     * [코드 (반복 구조로 노드 뒤집기)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/19_92_Reverse-Linked-List-II/19_92_repeat.py)
  * [LeetCode 20 유호한 괄호](https://leetcode.com/problems/valid-parentheses/) (String, Stack)
      * [코드 (스택 일치 여부 판별)](https://github.com/onlybooks/algorithm-interview/blob/master/3-linear-data-structures/ch09/20-1.py)
  * [LeetCode 316 중복 문자 제거](https://leetcode.com/problems/remove-duplicate-letters/) (String, Stack, Greedy, Monotonic Stack)
      * [코드 (재귀를 이용한 분리)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/21_316_Remove-Duplicate-Letters/21_316_recursion.py), 
      [코드 (스택을 이용한 문자 제거)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/21_316_Remove-Duplicate-Letters/21_316_stack.py)
  * [LeetCode 739 일일온도](https://leetcode.com/problems/daily-temperatures/) (Array, Stack, Monotonic Stack)
      * [코드 (스택 값 비교)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/22_739_Daily-Temperatures/22_739_stack.py)
  * [LeetCode 225 큐를 이용한 스택 구현](https://leetcode.com/problems/implement-stack-using-queues/) (Stack, Design, Queue)
      * [코드 (push() 할 때 큐를 이용해 재정렬)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/23_225_Implement-Stack-using-Queues/23_225_push.py)
  * [LeetCode 232 스택을 이용한 큐 구현](https://leetcode.com/problems/implement-queue-using-stacks/) (Stack, Design, Queue)
    * [코드 (스택 2개 사용)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/24_232_Implement-Queue-using-Stacks/24_232_stack.py)
  * [LeetCode 622 원형 큐 디자인](https://leetcode.com/problems/design-circular-queue/) (Array, Linked List, Design, Queue)
    * [코드 (배열을 이용한 풀이)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/9_Stack%26Queue/25_622_Design-Circular-Queue/25_622_array.py)
  * [LeetCode 641 원형 테크 디자인](https://leetcode.com/problems/design-circular-deque/) (Array, Linked List, Design, Queue)
    * [코드 (이중 연결 리스트)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/10_Dequq%26Priority-queue/26_641_Design-Circular-Deque/26_641_Doubly-linked-list.py)




* 스택, 큐
* 데크, 우선 순위 큐 
* 해시 테이블

---------------------------------------------

### [비선형 자료구조](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Non_Linear/README.md)
  * 그래프 
  * 최단 경로 문제 
  * 트리 
  * 힙 
  * 트라이

---------------------------------------

### [알고리즘](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/README.md)
* 정렬 
* 이진검색 
* 비트 조작 
* 슬라이딩 윈도우 
* 그리디 알고리즘  
  * [LeetCode 122 주식을 사고팔기 가장 좋은 시점 2](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) (Array, Dynamic Programming, Greedy)
    - [코드 (pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122_pythonic.py),
      [코드 2](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/78_122_Best-Time-to-Buy-and-Sell-Stock-II/78_122.py)
  * [LeetCode 455 쿠키 부여](https://leetcode.com/problems/assign-cookies/) (Array, Greedy, sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/82_455_Assign-Cookies/82_455.py)
 
* 분할 정복 
* 다이나믹 프로그래밍


---------------------------------------

>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.14-35.