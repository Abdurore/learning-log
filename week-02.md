# Week 2 (9 to 15 Nov)

## Mon 9 Nov
- Top K Frequent Elements (#347): solved with bucket sort.
  Count each number in a dictionary, then put numbers in an array indexed by frequency,
  and read from the highest index down until k numbers are collected.
  Time O(n), space O(n). Started Sun 8 Nov, power cut stopped me, finished Mon.
- CS50P Problem Set 1: finished Math Interpreter and Meal Time. Chapter 1 complete.
- Hours today: ~2
- Blocker: power cut in the afternoon, finished at night.
- Lesson: bucket sort by frequency is the no-heap way to do "top k".

## Tue 10 Nov
- Valid Parentheses (#20): Hint (found the "most recent unmatched opener" idea myself, needed help with the dictionary and loop structure).
  Stack (array with push/pop) plus a dictionary of opener to closer.
  Time O(n), space O(n).
- Lesson: when order matters ("most recent first"), reach for a stack.
- Blocker: school paperwork all day, started at 11 pm.

- ## Wed 11 Nov
- Cold re-solves of Top K Frequent Elements and Valid Parentheses.
  Valid Parentheses: got about halfway from memory. Top K: needed many hints, so it isn't learned yet.
- CS50P Lecture 2 (Loops): whole lecture watched on my phone.
- Hours today: ~2
- Blocker: school paperwork all day, laptop battery low tonight.
- Lesson: re-reading a solution isn't the same as knowing it. Retry from memory first thing tomorrow.

## Thu 12 Nov
- Valid Parentheses: re-solved twice from memory, also written by hand in my jotter. Top K: still working on it, will break it into small steps tomorrow.
- No power again, so no CS50P Problem Set 2. Used my phone for videos and a paper jotter of all 6 problems, tracing the steps by hand.
- Hours today: ~2. Lesson: hand-tracing works when there's no power.

## Fri 13 Nov
- Top K Frequent Elements: worked it on paper with a tiny example ([1,1,1,2,2,3], k=2).
  Count each number, then pick the top k by count. The sort version makes sense now.
  The bucket version still feels memorised, so I'll test myself and redo it cold on Mon 16 Nov.
  Label: Solution (not solved alone yet).
- CS50P Problem Set 2: first two problems solved. Skipped the optional shorts on purpose.
- Hours today: ~1.5
- Lesson: shrinking a problem to a tiny example beats watching another tutorial.

## Sat 14 Nov
- Valid Parentheses: solved cold from memory, third time now.
  Stack (array push/pop) + dictionary of opener to closer. Time O(n), space O(n).
  Label: Hint (found the key idea myself on 10 Nov).
- CS50P Problem Set 2: last 3 problems done, all 5 complete.
- Hours today: ~2
- Lesson: re-solving after a gap made it stick.

- ## Week 2 summary
- DSA: 2 problems this week (Top K, Valid Parentheses). 7 seen in total, 0 solved Alone.
  Valid Parentheses is solid on recall. Top K still in progress.
- CS50P: Lecture 2 and Problem Set 2 done. Chapter 1 and 2 complete.
- Hours: ~[X] of 12. Missed days: none. Blockers: power cuts, school paperwork.
- Next week: Top K cold, first Python re-solves, CS50P Lecture 3.
