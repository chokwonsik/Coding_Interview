# 선형 자료구조


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



>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.168-313.