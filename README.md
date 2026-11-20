# 🚀 Data Structures & Algorithms (DSA) Training Tracker

> A clean, comprehensive, and well-structured repository tracking daily Data Structures and Algorithms (DSA) problem-solving, algorithmic patterns, classroom exercises, and homework assignments implemented in Python.

---

## 📌 Summary Dashboard

| Metric | Details |
| :--- | :--- |
| **Total Days Covered** | **8 Days** |
| **Total Problems Solved** | **49 Problems** |
| 🏫 **Classroom Problems** | 21 Problems |
| 🏠 **Homework & Practice** | 28 Problems |
| 💻 **Primary Language** | Python 3 |
| 🎯 **Focus Areas** | Arrays, Two Pointers, Hashing, Frequency Maps, Matrices, Running State ($O(1)$ Space), $k$-Sum Patterns |

---

## 📊 Daily Curriculum & Progress

| Day | Primary Topics Covered | Class | Home | Total | Key Algorithmic Patterns |
| :---: | :--- | :---: | :---: | :---: | :--- |
| **Day 01** | Array Fundamentals & Basic Operations | 3 | 1 | **4** | Min/Max scanning, Odd/Even filtering, 1st & 2nd largest |
| **Day 02** | Sets & Hashing Fundamentals | 1 | 1 | **2** | Set membership, Deduplication, Unique ID extraction |
| **Day 03** | Complexity Analysis & Subarray / Pairs | 1 | 5 | **6** | Big-O time & space, Fibonacci analysis, Pair generation ($O(N^2)$) |
| **Day 04** | Two Pointers, Array Reversal & Rotations | 5 | 8 | **13** | Converging pointers, Cyclic rotations, In-place reversal, Array partitioning |
| **Day 05** | In-Place Modification & Character Encoding | 2 | 2 | **4** | ASCII conversions, In-place element shifting, Move zeroes |
| **Day 06** | Hash Maps, Frequencies & Duplicates | 3 | 5 | **8** | Dictionary frequency counting, Duplicate detection, LeetCode patterns |
| **Day 07** | Running State, Prefix Extrema & Strings | 3 | 3 | **6** | Running min/max in $O(1)$ space, Stock profit (LC 121), First unique char |
| **Day 08** | Two Pointers, 2D Matrices & $k$-Sum | 3 | 3 | **6** | Matrix diagonal summation, Two Sum, 3Sum, 4Sum, Bound pair sums |
| **Total** | **Comprehensive 8-Day DSA Program** | **21** | **28** | **49** | **Foundational to Intermediate Mastery** |

---

## 📂 Detailed Day-by-Day Breakdown

### [Day 01] Array Fundamentals & Basic Operations
*Focus: Linear traversal, single-pass extrema tracking, and condition-based aggregation.*

- **🏫 In-Class Problems (3):**
  - [`array_min_max.py`](problems_solved_in_class/day_01/array_min_max.py) — Finding minimum and maximum values in a single pass ($O(N)$ time, $O(1)$ space).
  - [`average_of_odd_and_even_numbers.py`](problems_solved_in_class/day_01/average_of_odd_and_even_numbers.py) — Segregating and computing running averages for odd and even elements.
  - [`first_and_second_largest.py`](problems_solved_in_class/day_01/first_and_second_largest.py) — Optimal tracking of first and second largest numbers without full sorting.
- **🏠 Homework Problems (1):**
  - [`input_output_format_and_validation.py`](problems_solved_in_home/day_01/input_output_format_and_validation.py) — Competitive programming I/O parsing and constraint validation.

---

### [Day 02] Sets & Hashing Fundamentals
*Focus: Utilizing hash sets for $O(1)$ lookups, deduplication, and presence marking.*

- **🏫 In-Class Problems (1):**
  - [`attendance_marker.py`](problems_solved_in_class/day_02/attendance_marker.py) — Tracking attendee presence and verifying unique roll calls via hash sets.
- **🏠 Homework Problems (1):**
  - [`unique_employee_id.py`](problems_solved_in_home/day_02/unique_employee_id.py) — Extracting distinct employee identifiers and removing duplicates.

---

### [Day 03] Complexity Analysis & Subarrays / Pairs
*Focus: Time & space complexity evaluation, recurrence relations, and multi-pass traversal.*

- **🏫 In-Class Problems (1):**
  - [`fibonacci_time_space_complexity.py`](problems_solved_in_class/day_03/fibonacci_time_space_complexity.py) — Comparative analysis of recursive $O(2^N)$ vs iterative $O(N)$ Fibonacci.
- **🏠 Homework Problems (5):**
  - [`01_exam_score_statistics.py`](problems_solved_in_home/day_03/01_exam_score_statistics.py) — Statistical distribution of exam scores (mean, min, max, cutoff analysis).
  - [`02_placement_cutoff_count.py`](problems_solved_in_home/day_03/02_placement_cutoff_count.py) — Counting students satisfying specific eligibility criteria.
  - [`03_first_last_occurrence.py`](problems_solved_in_home/day_03/03_first_last_occurrence.py) — Boundary search for first and last occurrences of an element.
  - [`04_reverse_student_id.py`](problems_solved_in_home/day_03/04_reverse_student_id.py) — Digit extraction and numeric sequence reversal.
  - [`05_print_all_pairs.py`](problems_solved_in_home/day_03/05_print_all_pairs.py) — Generating and analyzing all pairwise combinations ($O(N^2)$).

---

### [Day 04] Two Pointers, Array Reversal & Rotations
*Focus: Converging pointer mechanics, in-place array manipulation, and cyclic rotation algorithms.*

- **🏫 In-Class Problems (5):**
  - [`first_last_occurrence_two_pointer.py`](problems_solved_in_class/day_04/first_last_occurrence_two_pointer.py) — Bidirectional two-pointer search for element boundary indices.
  - [`reverse_array.py`](problems_solved_in_class/day_04/reverse_array.py) — Basic array reversal mechanisms.
  - [`reverse_array_two_pointer.py`](problems_solved_in_class/day_04/reverse_array_two_pointer.py) — In-place two-pointer array reversal ($O(N)$ time, $O(1)$ space).
  - [`rotate_array_left.py`](problems_solved_in_class/day_04/rotate_array_left.py) — Left shifting array elements by $k$ positions.
  - [`rotate_array_right_negative_indexing.py`](problems_solved_in_class/day_04/rotate_array_right_negative_indexing.py) — Right cyclic rotation utilizing Python negative slice mechanics.
- **🏠 Homework Problems (8):**
  - [`01_right_rotation_positive_indexing.py`](problems_solved_in_home/day_04/01_right_rotation_positive_indexing.py) — Right rotation using modular indexing arithmetic: `(i + k) % n`.
  - [`02_left_rotation_reverse_algorithm.py`](problems_solved_in_home/day_04/02_left_rotation_reverse_algorithm.py) — Classic 3-step block-reversal rotation algorithm in $O(1)$ space.
  - [`03_rearrange_positive_negative_numbers.py`](problems_solved_in_home/day_04/03_rearrange_positive_negative_numbers.py) — Segregating positive and negative numbers (Dutch National Flag variation).
  - [`04_reorder_array_using_index_array.py`](problems_solved_in_home/day_04/04_reorder_array_using_index_array.py) — Permuting an array according to a given index mapping.
  - [`05_reverse_array_single_pointer.py`](problems_solved_in_home/day_04/05_reverse_array_single_pointer.py) — Reversing an array using a single loop counter and symmetric indices.
  - [`06_rearrange_array_alternately.py`](problems_solved_in_home/day_04/06_rearrange_array_alternately.py) — Rearranging sorted array in alternating max/min order.
  - [`07_rearrange_array_arr_i_equals_i.py`](problems_solved_in_home/day_04/07_rearrange_array_arr_i_equals_i.py) — In-place cyclic placement such that `arr[i] == i`.
  - [`08_rearrange_array_o1_extra_space.py`](problems_solved_in_home/day_04/08_rearrange_array_o1_extra_space.py) — Encoding two values at a single index using quotient and remainder math.

---

### [Day 05] In-Place Modification & Character Encoding
*Focus: In-place shifting, zero partitioning, and ASCII character transformations.*

- **🏫 In-Class Problems (2):**
  - [`ascii_character_value_conversion.py`](problems_solved_in_class/day_05/ascii_character_value_conversion.py) — Character code manipulation and case conversion via ASCII offsets.
  - [`first_occurrence_search_removal_shifting.py`](problems_solved_in_class/day_05/first_occurrence_search_removal_shifting.py) — Search, delete, and left-shift remaining elements in-place.
- **🏠 Homework Problems (2):**
  - [`01_move_zeroes.py`](problems_solved_in_home/day_05/01_move_zeroes.py) — Shifting all zeros to end while maintaining non-zero order (LeetCode 283).
  - [`02_check_if_array_is_sorted.py`](problems_solved_in_home/day_05/02_check_if_array_is_sorted.py) — Validating monotonic non-decreasing order in a single $O(N)$ pass.

---

### [Day 06] Hash Maps, Frequencies & Duplicates
*Focus: Frequency tables, hash map lookups, sliding window duplicates, and LeetCode problems.*

- **🏫 In-Class Problems (3):**
  - [`contains_duplicate.py`](problems_solved_in_class/day_06/contains_duplicate.py) — Determining if any element occurs more than once via hash sets.
  - [`count _freq_of_every_element.py`](problems_solved_in_class/day_06/count%20_freq_of_every_element.py) — Building frequency distribution dictionaries in $O(N)$ time.
  - [`non_repeating_element.py`](problems_solved_in_class/day_06/non_repeating_element.py) — Finding the first and all elements with frequency count of 1.
- **🏠 Homework Problems (5):**
  - [`1207UniqueNumberofOccurrences.py`](problems_solved_in_home/day_06/1207UniqueNumberofOccurrences.py) — Checking if value frequencies are all mutually unique (LeetCode 1207).
  - [`1748SumofUniqueElements.py`](problems_solved_in_home/day_06/1748SumofUniqueElements.py) — Summing elements that appear exactly once (LeetCode 1748).
  - [`219ContainsDuplicateII.py`](problems_solved_in_home/day_06/219ContainsDuplicateII.py) — Duplicate elements within index distance $k$ (LeetCode 219).
  - [`2956FindCommonElementsBetweenTwoArrays.py`](problems_solved_in_home/day_06/2956FindCommonElementsBetweenTwoArrays.py) — Counting bidirectional intersection occurrences (LeetCode 2956).
  - [`442FindAllDuplicatesinanArray.py`](problems_solved_in_home/day_06/442FindAllDuplicatesinanArray.py) — Locating all duplicate numbers in $O(N)$ time (LeetCode 442).

---

### [Day 07] Running State, Prefix Extrema & Strings
*Focus: Continuous tracking of running extrema, single-pass profit calculation, and string hashing.*

- **🏫 In-Class Problems (3):**
  - [`max_value_so_far.py`](problems_solved_in_class/day_07/max_value_so_far.py) — Real-time tracking and emission of running maximums across sequential inputs.
  - [`range_min_max.py`](problems_solved_in_class/day_07/range_min_max.py) — Continuous running range calculation: `max_so_far - min_so_far`.
  - [`weather_station_min.py`](problems_solved_in_class/day_07/weather_station_min.py) — Tracking cumulative minimum sensor reading with constant space.
- **🏠 Homework Problems (3):**
  - [`12Best_Time_to_Buy_and_Sell_Stock.py`](problems_solved_in_home/day_07/12Best_Time_to_Buy_and_Sell_Stock.py) — Single-transaction maximum profit via prefix minimum (LeetCode 121).
  - [`387First_Unique_Character_in_a_String.py`](problems_solved_in_home/day_07/387First_Unique_Character_in_a_String.py) — Finding index of first non-repeating character (LeetCode 387).
  - [`First_Repeated_Character.py`](problems_solved_in_home/day_07/First_Repeated_Character.py) — Identifying the first repeating character using a lookup set.

---

### [Day 08] Two Pointers, 2D Matrices & $k$-Sum Problems
*Focus: Matrix diagonal geometry, sorted array two-pointer converging search, and $k$-Sum algorithms.*

- **🏫 In-Class Problems (3):**
  - [`1572. Matrix Diagonal Sum.py`](problems_solved_in_class/day_08/1572.%20Matrix%20Diagonal%20Sum.py) — Primary and secondary matrix diagonal sum in $O(N)$ time (LeetCode 1572).
  - [`167. Two Sum II - Input Array Is Sorted.py`](problems_solved_in_class/day_08/167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.py) — Target pair search on sorted arrays via two converging pointers (LeetCode 167).
  - [`leetcode_1_Two_sum.py`](problems_solved_in_class/day_08/leetcode_1_Two_sum.py) — Classic Two Sum on unsorted arrays using complement hash map (LeetCode 1).
- **🏠 Homework Problems (3):**
  - [`15__3Sum.py`](problems_solved_in_home/day_08/15__3Sum.py) — Finding all unique triplets summing to zero (LeetCode 15).
  - [`18__4Sum.py`](problems_solved_in_home/day_08/18__4Sum.py) — Finding unique quadruplets summing to target value (LeetCode 18).
  - [`Max Pair Sum Less Than K.py`](problems_solved_in_home/day_08/Max%20Pair%20Sum%20Less%20Than%20K.py) — Finding the maximum pair sum strictly less than threshold $K$ via two pointers.

---

## 🗂️ Directory Tree

```text
DSA_Training/
│
├── README.md
│
├── problems_solved_in_class/
│   ├── day_01/
│   │   ├── array_min_max.py
│   │   ├── average_of_odd_and_even_numbers.py
│   │   └── first_and_second_largest.py
│   ├── day_02/
│   │   └── attendance_marker.py
│   ├── day_03/
│   │   └── fibonacci_time_space_complexity.py
│   ├── day_04/
│   │   ├── first_last_occurrence_two_pointer.py
│   │   ├── reverse_array.py
│   │   ├── reverse_array_two_pointer.py
│   │   ├── rotate_array_left.py
│   │   └── rotate_array_right_negative_indexing.py
│   ├── day_05/
│   │   ├── ascii_character_value_conversion.py
│   │   └── first_occurrence_search_removal_shifting.py
│   ├── day_06/
│   │   ├── contains_duplicate.py
│   │   ├── count _freq_of_every_element.py
│   │   └── non_repeating_element.py
│   ├── day_07/
│   │   ├── max_value_so_far.py
│   │   ├── range_min_max.py
│   │   └── weather_station_min.py
│   └── day_08/
│       ├── 1572. Matrix Diagonal Sum.py
│       ├── 167. Two Sum II - Input Array Is Sorted.py
│       └── leetcode_1_Two_sum.py
│
└── problems_solved_in_home/
    ├── day_01/
    │   └── input_output_format_and_validation.py
    ├── day_02/
    │   └── unique_employee_id.py
    ├── day_03/
    │   ├── 01_exam_score_statistics.py
    │   ├── 02_placement_cutoff_count.py
    │   ├── 03_first_last_occurrence.py
    │   ├── 04_reverse_student_id.py
    │   └── 05_print_all_pairs.py
    ├── day_04/
    │   ├── 01_right_rotation_positive_indexing.py
    │   ├── 02_left_rotation_reverse_algorithm.py
    │   ├── 03_rearrange_positive_negative_numbers.py
    │   ├── 04_reorder_array_using_index_array.py
    │   ├── 05_reverse_array_single_pointer.py
    │   ├── 06_rearrange_array_alternately.py
    │   ├── 07_rearrange_array_arr_i_equals_i.py
    │   └── 08_rearrange_array_o1_extra_space.py
    ├── day_05/
    │   ├── 01_move_zeroes.py
    │   └── 02_check_if_array_is_sorted.py
    ├── day_06/
    │   ├── 1207UniqueNumberofOccurrences.py
    │   ├── 1748SumofUniqueElements.py
    │   ├── 219ContainsDuplicateII.py
    │   ├── 2956FindCommonElementsBetweenTwoArrays.py
    │   └── 442FindAllDuplicatesinanArray.py
    ├── day_07/
    │   ├── 12Best_Time_to_Buy_and_Sell_Stock.py
    │   ├── 387First_Unique_Character_in_a_String.py
    │   └── First_Repeated_Character.py
    └── day_08/
        ├── 15__3Sum.py
        ├── 18__4Sum.py
        └── Max Pair Sum Less Than K.py
```

---

## 🧠 Core Algorithmic Patterns Practiced

1. **Two Pointers (Convergent & Traversal)**
   - Used for in-place array reversal, checking symmetry, searching pairs in sorted arrays, and reducing polynomial time bounds in $k$-Sum problems ($O(N^2)$ for 3Sum, $O(N^3)$ for 4Sum).
2. **Frequency Counting & Hash Maps**
   - Utilizing Python dictionaries and sets to trade $O(N)$ auxiliary space for instantaneous $O(1)$ average-time lookups and duplicate checks.
3. **Running State & Streaming Extrema**
   - Maintaining running maximums, running minimums, and calculating dynamic metrics (e.g., Best Time to Buy and Sell Stock) in a single linear pass with $O(1)$ extra memory.
4. **In-Place Array Rearrangements & Rotations**
   - Three-step array reversal technique (`reverse(0, k-1)`, `reverse(k, n-1)`, `reverse(0, n-1)`), single-pointer symmetric swapping, and mathematical encoding to store multiple values in a single memory slot.
5. **2D Matrix Operations**
   - Diagonal traversals (`primary: arr[i][i]`, `secondary: arr[i][n - 1 - i]`) in a single loop without redundant nested iterations.

---

## 🛠️ How to Run Any Solution

All solutions are written in standalone, clean Python 3. You can execute any script directly from the root of the project using your terminal:

```bash
# Example: Run Day 01 class problem
python problems_solved_in_class/day_01/array_min_max.py

# Example: Run Day 04 rotation homework
python problems_solved_in_home/day_04/02_left_rotation_reverse_algorithm.py

# Example: Run Day 08 3Sum problem
python problems_solved_in_home/day_08/15__3Sum.py
```