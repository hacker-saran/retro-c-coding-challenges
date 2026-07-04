# C Challenges

A curated, well-organized repository of competitive programming, algorithm, and data structure challenges solved in C. These solutions were created during my college years to practice core algorithms, array manipulations, string handling, mathematical problem-solving, and console patterns.

## 📁 Repository Structure

The challenges have been categorized into logical directories under the `src/` folder:

```
C_Challenges/
├── src/
│   ├── arrays/      # Array reversals, scans, and property checks
│   ├── strings/     # String searches, shifts, and encryption
│   ├── math/        # Mathematical puzzles, digit sweeps, and base conversions
│   ├── patterns/    # Console pattern graphics and numerical grids
│   ├── matrix/      # 2D grid searches and traversals
│   └── misc/        # Miscellaneous scoring, games, and constraints checks
├── .gitignore       # Excludes compiled binary files and local workspace configurations
└── README.md        # Portal and index directory
```

---

## 🚀 Index of Challenges

Below is a complete index of the solved challenges, categorized with links to their respective source code.

### 📊 Arrays
| Challenge | Source Code | Description |
| :--- | :--- | :--- |
| **Array Reverse** | [array_reverse.c](./src/arrays/array_reverse.c) | Reverses elements of an array. |
| **Contains Unique** | [contains_unique_or_not.c](./src/arrays/contains_unique_or_not.c) | Checks if all elements in an array are unique. |
| **Left-Right Odd Count** | [left_right_odd_count.c](./src/arrays/left_right_odd_count.c) | Computes and counts odd elements on both left and right sides of subarrays. |
| **Max Sum Two-Digit Integers** | [max_sum_two_digit_integers.c](./src/arrays/max_sum_two_digit_integers.c) | Finds the maximum sum of two-digit integers in a list. |
| **Maximum Repeating Count** | [maximum_repeating_count.c](./src/arrays/maximum_repeating_count.c) | Finds the highest repeating frequency of any element in an array. |

### 🔤 Strings
| Challenge | Source Code | Description |
| :--- | :--- | :--- |
| **Char at Multiple of K** | [character_at_multiple_of_k.c](./src/strings/character_at_multiple_of_k.c) | Prints characters situated at indices that are multiples of $K$. |
| **Count of Articles** | [count_of_articles.c](./src/strings/count_of_articles.c) | Counts occurrences of articles (a, an, the) in a sentence. |
| **Digit Frequency** | [digit_frequency.c](./src/strings/digit_frequency.c) | Computes frequency of numeric characters in a string. |
| **Longest Palindromic Substring** | [longest_palindromic_substring_length.c](./src/strings/longest_palindromic_substring_length.c) | Finds the length of the longest palindromic substring. |
| **Longest Vowel Substring** | [longest_vowel_substring.c](./src/strings/longest_vowel_substring.c) | Finds the length of the longest substring containing only vowels. |
| **Message Encryption** | [message_encryption.c](./src/strings/message_encryption.c) | Encrypts messages using specific character rotation patterns. |
| **Shortest Word Distance** | [minimum_distance_between_words.c](./src/strings/minimum_distance_between_words.c) | Calculates the minimal gap index between two search words in text. |
| **Palindrome Missing Alphabet** | [palindrome_missing_alphabet.c](./src/strings/palindrome_missing_alphabet.c) | Identifies the single missing character needed to complete a palindrome. |
| **Reverse & Remove Vowels** | [reverse_and_remove_vowel_positions.c](./src/strings/reverse_and_remove_vowel_positions.c) | Reverses a string and removes characters in vowel positions. |
| **Reverse Middle Words** | [reverse_middle_words.c](./src/strings/reverse_middle_words.c) | Reverses middle words of a sentence while preserving boundaries. |
| **Reverse Word** | [reverse_word.c](./src/strings/reverse_word.c) | Reverses individual words in a string. |
| **Sub-Palindromes Count** | [sub_palindromes_count.c](./src/strings/sub_palindromes_count.c) | Counts overall sub-palindromes inside a string. |
| **Toggle Case Words** | [toggle_case_words.c](./src/strings/toggle_case_words.c) | Toggles word cases if characters share identical casing. |

### 🔢 Math & Numbers
| Challenge | Source Code | Description |
| :--- | :--- | :--- |
| **Add Numbers Base N** | [add_numbers_base_n.c](./src/math/add_numbers_base_n.c) | Adds two numbers represented in Base-$N$ notation. |
| **Day of Date** | [day_of_date.c](./src/math/day_of_date.c) | Computes the weekday of a given calendar date. |
| **Digital Sum** | [digital_sum.c](./src/math/digital_sum.c) | Computes the single-digit recursive digital sum. |
| **Factors of Factors** | [factors_of_factors.c](./src/math/factors_of_factors.c) | Finds factors of factor values. |
| **Next Prime Number** | [next_prime_number.c](./src/math/next_prime_number.c) | Finds the next prime number greater than input. |
| **Plus Minus** | [plus_minus.c](./src/math/plus_minus.c) | Analyzes counts of positive, negative, and zero values. |
| **Reverse Odd/Even Positions** | [reverse_odd_even_position_digits.c](./src/math/reverse_odd_even_position_digits.c) | Reverses digits at odd/even index positions. |
| **Sum M out of N** | [sum_m_out_of_n.c](./src/math/sum_m_out_of_n.c) | Calculates sum of $M$ largest elements out of $N$. |
| **Sum of Proper Divisors** | [sum_of_proper_divisors.c](./src/math/sum_of_proper_divisors.c) | Calculates the sum of all proper divisors of a number. |
| **Swap Last Two Digits** | [swap_last_two_digits.c](./src/math/swap_last_two_digits.c) | Swaps the last two digits of an integer. |
| **Swap or Remove Digits** | [swap_or_remove_digits.c](./src/math/swap_or_remove_digits.c) | Swaps or removes digits based on parity rules. |
| **Time Conversion 12-24** | [time_conversion_12_24.c](./src/math/time_conversion_12_24.c) | Converts 12-hour AM/PM format to 24-hour. |

### 🖼️ Patterns & Matrix
| Challenge | Source Code | Description |
| :--- | :--- | :--- |
| **Number V-Pattern** | [number_v_pattern.c](./src/patterns/number_v_pattern.c) | Renders numbers in a symmetrical V-shape console output. |
| **Pattern Numbers** | [pattern_numbers.c](./src/patterns/pattern_numbers.c) | Renders a concentric/box border numerical pattern grid. |
| **Reverse Pattern Numbers** | [reverse_pattern_numbers.c](./src/patterns/reverse_pattern_numbers.c) | Renders numerical pattern grids in reverse order. |
| **Smaller Matrix Search** | [smaller_matrix_search.c](./src/matrix/smaller_matrix_search.c) | Finds occurrences of a sub-matrix in a larger 2D grid. |

### 🛠️ Miscellaneous
| Challenge | Source Code | Description |
| :--- | :--- | :--- |
| **Adamant Kid** | [adamant_kid.c](./src/misc/adamant_kid.c) | Simulates character hopping steps. |
| **Five Alphabet Five Digits** | [five_alphabet_five_digits.c](./src/misc/five_alphabet_five_digits.c) | Validates string constraints of 5 letters and 5 digits. |
| **Robot Coordinates** | [robot_coordinates.c](./src/misc/robot_coordinates.c) | Tracks movement paths and final coordinate grid coordinates of a robot. |
| **Series Team Score** | [series_team_score.c](./src/misc/series_team_score.c) | Computes overall scores for team tournament matches. |

---

## 🛠️ How to Compile & Run

All source files are standalone C programs. You can compile and run them from the root directory using standard C compilers like `gcc` or `clang`.

### Compilation
Specify the relative path of the file and define the output executable:
```bash
gcc src/arrays/array_reverse.c -o array_reverse
```

### Execution
Run the compiled binary:
```bash
./array_reverse
```
