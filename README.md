# Homework 4 · The receipt, and the bug

**Week 04 · Operators + console I/O**  
**Theme:** Ask, store, compute, print the name


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

In the video: run the working receipt. Then swap in the commented `int / int` tip line, show the `Tip: 0`, and swap it back.

**Your demo:** _add your link here_


## What to build
The receipt from the demo: price, quantity, and tip percent in; subtotal, tip, and total out. Then prove you can spot integer division. Keep one commented-out line that gives the wrong answer, and say in a comment why the console changed.

The point is not the receipt. It is knowing that a program can compile, run, and still be wrong — and being able to say which line did it.

## Requirements
- Read `price`, `qty`, and `tip_pct` with a clear `cout` prompt before each `cin`
- `subtotal`, `tip`, and `total` are named `double` variables — no formula inside `cout`
- Print the three results with labels
- One commented-out line that computes the tip with `int / int`. Next to it, a comment that says what it printed and why
- Run the program twice with different tip percents. A comment that names which line made the output change
- Two comments that explain a choice — why `qty` is an `int`, why `price` is a `double`, or why the prompt comes before the `cin`. Not `// read price`
- File-top comment with your name and the week
- One `.cpp` that still builds — the wrong line stays commented

## Sample output
```
Price? 20
Qty? 2
Tip percent? 15
Subtotal: 40
Tip: 6
Total: 46
```

```
// int pct = 15;
// double tip = subtotal * (pct / 100);   // printed Tip: 0 — int / int is 0 before the multiply
double tip = subtotal * (tip_pct / 100.0); // 100.0 keeps the division in double

// Ran with 15 then 20. Tip went 6 -> 8 because tip_pct feeds the tip line only.
```

Your values can be different. The rule is the same: the numbers on the screen came from the inputs, and the comments prove you know which line did what.

## Starter
`main.cpp` — boxes are declared. You write the conversation, the math, and the comments.

## Deliverables
1. Course-visible GitHub repo (link opens)
2. README: how to run + a sample run + one sentence on why the wrong line printed 0
3. Short demo video: run it right, swap in the wrong line, show the 0, swap it back
4. Canvas links

## Scope fence
One file. No loops, no `if`, no extra functions. Do not leave the file broken.

## Integrity
- AI = tutor, not ghostwriter
- Fake ownership → zero
- Due: Monday night (not Sunday)
- Discussions (every week): first post Friday, replies Sunday
- Late: course policy (−10%/day unless stated otherwise)

## Rubric
Graded on: it runs, it meets the prompt, the comments explain the wrong line and the input change, and the GitHub repo plus demo video are there.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, a real run, and the `Tip: 0` from the wrong line you then comment back.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
