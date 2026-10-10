# leetcode top interview 150: What's Actually in the List, How to Sequence It, and How to Stop Forgetting Problems a Week After You Solve Them

The Top Interview 150 is 150 problems. That number sounds survivable, and it is — right up until you scroll the plan and notice that it opens with Merge Sorted Array and closes somewhere around Edit Distance and Maximal Square. Between those two points there's a topic label and a checkbox. No explanation of why a problem is in that section, no note about which pattern to reach for, no hint about what to do when you've solved 40 problems and still freeze on something new.

That gap is where most people lose the plot with this list. Not the problems themselves.

## What's in the Top Interview 150 study plan

It's a free study plan on LeetCode, separate from the numbers-based problem archive. The 150 problems are grouped by topic rather than by difficulty or ID, which is the useful part: you can see the shape of the interview before you start cramming.

The topic blocks:

- Array / String — the biggest block in the plan; 22 problems by the count in the official PDF, from Merge Sorted Array through Text Justification, and it includes three hards (Candy, Trapping Rain Water, and Text Justification) sitting inside what looks like an easy section
- Two Pointers — Valid Palindrome, Two Sum II, Container With Most Water, 3Sum and friends
- Sliding Window — including Minimum Window Substring and Substring with Concatenation of All Words, two of the harder problems in the plan
- Matrix — Valid Sudoku, Spiral Matrix, Rotate Image, Set Matrix Zeroes, Game of Life
- Hashmap — Ransom Note, Isomorphic Strings, Word Pattern, Valid Anagram, Group Anagrams, Happy Number
- Intervals, Stack, Linked List — including LRU Cache and Remove Nth Node From End of List
- Binary Tree General, Binary Tree BFS, Binary Search Tree — the largest single concentration of tree questions, plus Populating Next Right Pointers, Flatten Binary Tree to Linked List and Binary Tree Maximum Path Sum
- Graph General and Graph BFS — Snakes and Ladders, Minimum Genetic Mutation, Word Ladder
- Trie, Backtracking, Divide & Conquer
- Kadane's Algorithm, Binary Search, Heap
- Bit Manipulation, Math
- 1D DP and Multidimensional DP — Climbing Stairs, House Robber, Word Break, Longest Increasing Subsequence, Minimum Path Sum, Unique Paths II, Longest Palindromic Substring, Interleaving String, Edit Distance, Best Time to Buy and Sell Stock III and IV, Maximal Square

Two things jump out of that structure. First, the difficulty mix is uneven: some topic blocks are almost all easy problems, and the DP section is basically a wall of mediums with a couple of hards attached. Second, the list assumes you already know what a sliding window is. It tells you a problem belongs to a category; it doesn't teach you the category.

## A sequencing plan that doesn't collapse in week three

The list's ordering is decent, but "decent" isn't the same as "comfortable." A workable pace looks like this:

| Weeks | Focus | Rough daily load |
| --- | --- | --- |
| 1 | Array/String easy problems + Hashmap | 2–3 easy problems |
| 2 | Two Pointers, finish Array/String mediums | 2 easy + 1 medium |
| 3 | Sliding Window, Matrix, Intervals | 1 easy + 2 medium |
| 4 | Stack, Linked List, Binary Search | 2–3 medium |
| 5 | Trees (general, BFS, BST) | 2 medium |
| 6 | Graphs, Trie, Backtracking, Divide & Conquer | 2 medium |
| 7–8 | DP (1D, then multidimensional), Heap, Bit Manipulation, Math | 1 medium + 1 hard, or 2 medium |
| ongoing | Re-solve everything you failed | 3–5 problems, mixed topics |

That's eight weeks of doing the 150 plus review, at roughly 1.5–2 hours a day. If you have an interview in four weeks, cut the DP block down to Climbing Stairs, House Robber, Word Break and Longest Increasing Subsequence and accept that you're gambling on the rest. If you have three months, the pace above is almost leisurely.

The review block at the end isn't optional. Solving a problem once and moving on is how you end up at problem 143 with no memory of how the two-pointer trick from problem 11 worked.

## The three places this list actually breaks

**Pattern selection.** The most common way a prepared candidate fails a coding screen isn't bad code. It's spending 15 minutes of a 45-minute interview trying approaches that don't fit the problem. The list tells you a problem is a "Sliding Window" problem after you've already clicked into the topic — in the interview, nobody hands you the heading.

**Retention.** LeetCode shows you accepted, wrong answer, time limit exceeded. It doesn't show you that your last four failures were all variations of the same mistake. Without that signal, "review" becomes "redo random problems and hope."

**DP and graphs, specifically.** These two blocks are where the list stops feeling like practice and starts feeling like guesswork. A problem like Edit Distance or Word Ladder has a solution that comes from recognizing a structure, not from remembering a formula. The editorials help, but reading 40 editorials is a slow way to build the underlying model.

If you've been circling these three problems, you're not doing anything wrong with the list. You're missing the layer underneath it.

## Where AlgoMonster fits into the Top Interview 150

AlgoMonster is built by a group of ex-Google engineers and competitive programmers, and it approaches interview prep from the opposite direction: instead of a problem list, it's a pattern curriculum. Around 48 coding patterns, roughly 231 lessons and problems, and about 670–700 diagrams and illustrations, all text-based rather than video. The official site also describes 500+ lessons across six courses, 1,000+ illustrations and 3,000+ editorials, with bonus courses for CS foundations and building an LLM from scratch.

The mapping to the Top Interview 150 is mostly indirect, and that's the point. You take the pattern chapter on sliding window, two pointers or multidimensional DP, learn the template and the decision logic, then go back to the list and grind the corresponding block as reps. The list gives you volume and topic distribution; AlgoMonster gives you the "why does this approach work here and not there" layer.

The parts that matter most for this specific list:

- Decision flowcharts for problem categorisation — the "is the input sorted? am I looking for a contiguous subarray? is this a tree or a graph?" chain that you're supposed to be running in your head during the interview
- Pattern templates in several languages, so the implementation is the easy part and the selection is the thing you practice
- An in-browser code editor with an AI assistant that explains concepts, gives hints and points at the specific line where your solution breaks instead of just marking it wrong
- Speedrun mode for timed review, which is the closest thing here to interview pressure
- Company-specific question sets for Google, Meta and Amazon, updated monthly
- Progress tracking that surfaces weak areas rather than just counting accepted submissions

👉 [See what the pattern curriculum covers and try the free tier](https://algo.monster?fpr=li69)

That's the honest framing: AlgoMonster doesn't contain the Top Interview 150. It teaches the patterns that the 150 problems are testing. If you use it as a replacement for working through the list, you'll be under-exercised. If you use it to unblock the blocks that keep stalling you, it does something a problem list structurally cannot.

## Plans and what they cost

AlgoMonster doesn't sell per-problem access. There's a free tier and two paid options, both of which unlock the same content — the only difference is how long you get it.

| Plan | What you get | Price | Billing | Link |
| --- | --- | --- | --- | --- |
| Free | Limited access to a subset of patterns and problems; enough to judge the text-and-diagram format | $0 | — | [Start with the free content](https://algo.monster?fpr=li69) |
| Pro — Yearly | All patterns, lessons and problems; unlimited AI assistant; unlimited Speedrun; company question sets updated monthly; 500+ lessons across 6 courses, 1,000+ illustrations, 3,000+ editorials; bonus Foundation Course and Build-an-LLM Course; member discount on live bootcamps; 12 months of full access | $99/year (listed at $198), around $8.25/month billed annually | Billed annually, cancel or upgrade anytime | [Get the yearly plan](https://algo.monster?fpr=li69) |
| Pro — Lifetime | Everything in the annual plan plus lifetime updates, one-time payment, access to future courses as they're added | $189 (listed at $378) | Billed once | [Get lifetime access](https://algo.monster?fpr=li69) |

A few caveats worth knowing before you click. AlgoMonster runs sales constantly, and the numbers I could verify on its own subscribe page ($99/year and $189 one-time) sit well below what several third-party write-ups quote — depending on when they looked, those posts cite lifetime prices anywhere from $99 to $459. Treat any screenshot of this pricing as perishable and check the live page. Some older subscribe pages also listed a Pro Monthly around $18.99/month, which doesn't appear to be the current offer.

You'll also see promo codes floating around on affiliate blogs claiming extra percentages off. I couldn't verify any of them, so I won't repeat them. The straightforward comparison is this: LeetCode Premium sits around $159/year for company tags and frequency data, AlgoMonster's yearly plan is cheaper than that, and the lifetime plan costs roughly a year plus a bit. If you're doing one job search and then disappearing for three years, yearly is the rational choice. If you interview every couple of years the way a lot of engineers do, lifetime breaks even fast.

One more thing. Multiple third-party reviews repeat a "job offer guarantee" claim for AlgoMonster's curriculum. I couldn't confirm the terms on the official pricing page, so file it under marketing until you've read the fine print yourself.

## Where AlgoMonster won't save you

It has no video content at all. Everything is text and interactive diagrams, which is genuinely faster to skim and reference than a 40-minute walkthrough, and also genuinely wrong for people who learn by watching someone code. If you've built your prep around NeetCode-style videos, this format will feel dry and you'll retain less.

The problem count is around 230, against LeetCode's 3,000+. For Google-loop questions pulled from a huge pool, pattern familiarity isn't enough on its own; you need the repetition that volume gives you. Plan on using both.

System design coverage is introductory. If you're targeting L5 or above where a dedicated design round is guaranteed, that's a separate resource, not something you'll get here. Same for behavioural rounds. And there's no live mocks — no timer, no interviewer asking "what happens to your complexity if I add this constraint?" Pattern recognition gets you to the right approach; it doesn't rehearse the follow-ups.

## How I'd actually split the money and the time

If your goal is finishing the Top Interview 150 and you already recognise the major patterns, you don't need a course. Work the list, use the editorials, keep a failure log, and re-solve everything you got wrong. That's the cheap path and it works.

If you're three weeks into the list and your notes are a graveyard of problems you solved once and can't reproduce, the bottleneck is the pattern layer, not the problem count. That's the case where ~$99 for a year, or $189 once, buys something the list doesn't provide.

If you have an interview in four weeks, skip the DP deep-dive, do the array/string, two pointers, sliding window, hashmap and tree blocks properly, and use Speedrun-style timed review to get used to solving under a clock. Half the list done well beats all 150 done shallowly.

## Questions that come up constantly

**Is the Top Interview 150 free?** The study plan and problem list are free to browse and most problems are solvable without a subscription. LeetCode Premium adds company tags and frequency data, not access to the list itself.

**Is 150 problems enough?** For most mid-level loops, if you can actually solve all 150 without hints under time pressure, yes. The caveat is "under time pressure" — knowing a solution and producing it in 25 minutes are different skills.

**How many problems a day?** Two to three mediums a day for six to eight weeks is a realistic pace for someone working full time. One a day is fine if you're starting from zero, but extend your timeline accordingly.

**Does AlgoMonster include the Top Interview 150 problems?** No. It has its own problem set organised by pattern, with Blind 75 and Monster 50 lists among the practice material. The overlap is in subject matter, not in a one-to-one problem list.

**Which should I buy first?** If you can't yet explain when to use a sliding window versus a two-pointer pass, get the pattern layer first. If you can name the pattern but keep fumbling the implementation, you need reps, and LeetCode alone will do.

The list is a good curriculum. It's a bad teacher. Knowing which of those two things you're missing is most of the decision.
