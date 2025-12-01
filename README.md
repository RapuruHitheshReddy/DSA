## Most Challenging Problem Solved Recently

### Problem: Longest Substring Without Repeating Characters  
**LeetCode:** https://leetcode.com/problems/longest-substring-without-repeating-characters/


This problem required a deep understanding of window-based optimization, making it one of the most challenging I solved recently. My initial brute-force approach checked all substrings, resulting in O(n²) time complexity and timing out on larger test cases.
To optimize, I designed a Sliding Window solution backed by a character index map that tracks the last occurrence of each character. Whenever a repeating character appeared inside the active window, I efficiently shifted the left boundary to skip over previously seen characters without reprocessing elements.

This allowed each character to be visited at most twice, achieving an optimal O(n) runtime. Additionally, I accounted for edge cases such as long repeated sequences, mixed ASCII character sets, and empty strings. Solving this enhanced my skills in pointer manipulation, window management, and writing high-performance string-processing algorithms.

### My Submission:
https://leetcode.com/submissions/detail/1831668049/
