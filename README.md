# Coding_Interview
## LeetCode 문제 풀이

* 개발 언어 및 도구
  * "Python 3.7+" , 리트코드, 파이참 커뮤니티 에디션
  
---------------------------------------

### [문자열 조작](https://github.com/chokwonsik/Coding_Interview/tree/main/6_String_Manipulation)
  * [LeetCode 125 유효한 팰린드롬](https://leetcode.com/problems/valid-palindrome/) (Two Pointers, String)
    * [코드 (slicing)](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/1_LeetCode_125_Valid-Palindrome/1_leetcode_125_slicing.py),
      [코드 (deque)](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/1_LeetCode_125_Valid-Palindrome/1_leetcode_125_deque.py), 
      [코드 (list)](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/1_LeetCode_125_Valid-Palindrome/1_leetcode_125_list.py)
  * [LeetCode 344 문자열 뒤집기](https://leetcode.com/problems/reverse-string/) (Two Pointers, String, Recursion)
    * [코드 (pytonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/2_LeetCode_344_Reverse-String/2_leetcode_344_pytonic.py), 
      [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/2_LeetCode_344_Reverse-String/2_leetcode_344_two-pointer.py)
  * [LeetCode 937 로그 파일 재정렬](https://leetcode.com/problems/reorder-data-in-log-files/) (Array, String, Sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/3_LeetCode_937_Reorder-Log-Files/3_leetcode_937.py)
  * [LeetCode 819 가장 흔한 단어](https://leetcode.com/problems/most-common-word/) (Hash Table, String, Counting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/4_LeetCode_819_Most-Common-Word/4_leetcode_819.py)
  * [LeetCode 49 그룹 애너그램](https://leetcode.com/problems/group-anagrams/) (Hash Table, String, Sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/5_LeetCode_49_Group-Anagrams/5_leetcode_49.py)
  * [LeetCode 5 가장 긴 팰린드롬 부분 문자열](https://leetcode.com/problems/longest-palindromic-substring/) (String, Dynamic Programming)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/6_String_Manipulation/6_LeetCode_5_Longest-Palindromic-Substring/6_leetcode_5.py)
  
---------------------------------------
### [선형 자료구조](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/README.md)
* 배열
  * [LeetCode 1 두 수의 합](https://leetcode.com/problems/two-sum/) (Array, Hash Table)
    * [코드 (dict)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_LeetCode_1_Two-Sum/7_leetcode_1_dict.py),
      [코드 (dict2)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_LeetCode_1_Two-Sum/7_leetcode_1_dict-2.py),
      [코드 (in)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_LeetCode_1_Two-Sum/7_leetcode_1_in.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/7_LeetCode_1_Two-Sum/7_leetcode_1_brute-force.py)
  * [LeetCode 42 빗물 트래핑](https://leetcode.com/problems/trapping-rain-water/) (Array, Two Pointers, Dynamic Programming, Stack, Monotonic Stack)
    * [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_LeetCode_42_Trapping-Rain-Water/8_leetcode_42_two-pointer.py),
      [코드 (stack)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/8_LeetCode_42_Trapping-Rain-Water/8_leetcode_42_stack.py)
  * [LeetCode 15 세 수의 합](https://leetcode.com/problems/3sum/) (Array, Two Pointers, Sorting)
    * [코드 (two-pointer)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_LeetCode_15_3Sum/9_leetcode_15_two-pointer.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/9_LeetCode_15_3Sum/9_leetcode_15_brute-force.py)
  * [LeetCode 561 배열 파티션 1 ](https://leetcode.com/problems/array-partition-i/) (Array, Greedy, Sorting, Counting Sort)
    * [코드 (pytonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_LeetCode_561_Array-Partition-I/10_leetcode_561_pytonic.py),
      [코드 (even-number)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_LeetCode_561_Array-Partition-I/10_leetcode_561_even-number.py),
      [코드 (even-number)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/10_LeetCode_561_Array-Partition-I/10_leetcode_561_ascending.py)
  * [LeetCode 238 자신을 제외한 배열의 곱](https://leetcode.com/problems/product-of-array-except-self/) (Array, Prefix Sum)
    * [코드 (mul)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/11_LeetCode_238_Product-of-Array-Except-Self/11_leetcode_238.py)
  * [LeetCode 121 주식을 사고팔기 가장 좋은 시점](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) (Array, Dynamic Programming)
    * [코드 (min&max)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_LeetCode_121_Best%20Time-to-Buy-and-Sell-Stock/12_leetcode_121_min%26max.py),
      [코드 (brute-force)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/7_Array/12_LeetCode_121_Best%20Time-to-Buy-and-Sell-Stock/12_leetcode_121_brute-force.py)
  
      
* 연결리스트
  * [LeetCode 234 팰린드롬 연결 리스트](https://leetcode.com/problems/palindrome-linked-list/) (Linked List, Two Pointers, Stack, Recursion)
    * [코드 (runner)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_LeetCode_234_Palindrome-Linked-List/13_leetcode_234_runner.py),
      [코드 (deque)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_LeetCode_234_Palindrome-Linked-List/13_leetcode_234_deque.py),
      [코드 (list)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/13_LeetCode_234_Palindrome-Linked-List/13_leetocde_234_list.py)
  * [LeetCode 21 두 정렬 리스트의 병합](https://leetcode.com/problems/merge-two-sorted-lists/) (Linked List, Recursion)
    * [코드 (recursive)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/14_LeetCode_21_Merge-Two-Sorted-Lists/14_leetcode_21_recursive.py)
  * [LeetCode 206 역순 연결리스트](https://leetcode.com/problems/reverse-linked-list/) (Linked List, Recursion)
    * [코드 (lterative)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_LeetCode_206_Reverse-Linked-List/15_leetcode_206_lterative.py),
    [코드 (recursive)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/15_LeetCode_206_Reverse-Linked-List/15_leetcode_206_recursive.py)
  * [LeetCode 2 두 수의 덧셈](https://leetcode.com/problems/add-two-numbers/) (Linked List, Math, Recursion)
    * [코드 (casting)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_Leetcode_2_Add-Two-Numbers/16_leetcode_2_casting.py), 
    [코드 (full-adder)](https://github.com/chokwonsik/Coding_Interview/blob/main/Data_Structure/Linear/8_Linked-List/16_Leetcode_2_Add-Two-Numbers/16_leetcode_2_casting.py)




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
    - [코드 (pythonic)](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/78_LeetCode_122_Best-Time-to-Buy-and-Sell-Stock-II/78_leetcode_122_pythonic.py),
      [코드 2](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/78_LeetCode_122_Best-Time-to-Buy-and-Sell-Stock-II/78_leetcode_122.py)
  * [LeetCode 455 쿠키 부여](https://leetcode.com/problems/assign-cookies/) (Array, Greedy, sorting)
    * [코드](https://github.com/chokwonsik/Coding_Interview/blob/main/Algorithm/21_Greedy-Algorithm/82_LeetCode_455_Assign-Cookies/82_leetcode_455.py)
 
* 분할 정복 
* 다이나믹 프로그래밍


---------------------------------------

>Sang.Kil. Park, _파이썬 알고리즘 인터뷰_, 책만, 2020, pp.14-35.