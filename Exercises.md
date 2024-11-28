
## Exercise 1

Given a list of strings representing commands: 'append X' and 'backspace', implement a text editor.
For each 'append X' command, add X to your text.
For 'backspace', remove the last character if any exists.
Return all intermediate states after each command.

**Example:**
Input: ["append abc", "append def", "backspace", "append xy"]
Output: ["abc", "abcdef", "abcde", "abcdexy"]


## Exercise 2

Design and implement an algorithm that can efficiently find the k most frequently occurring words in a text.

**Requirements:**

Words should be case-insensitive (e.g., "Hello" and "hello" count as the same word)
Punctuation and special characters should be ignored (e.g., "word." and "word," count as "word")
The output should include both the words and their frequencies

**Example:**

Input file contains: "The quick brown fox jumps over the lazy dog. The dog sleeps."
If k = 3, output should be:

"the" (3 occurrences)
"dog" (2 occurrences)
Any of "quick"/"brown"/"fox"/"jumps"/"over"/"lazy"/"sleeps" (1 occurrence each)

**Follow-up Questions:**

- How would you modify your solution to exclude common words (stop words) like "the", "a", "an"?
- How would you modify your solutuin to handle large text files that could
  be several gigabytes in size, containing millions of words.
- How would you adapt the algorithm to handle streaming data in real-time?
- What if you needed to track word frequencies over different time periods?
