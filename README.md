# Practice 4 · Receipt printer

**Week 04 · Operators + console I/O**  
**Theme:** Talk to the machine


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** _add your link here_


## What to build
A tiny receipt: price, quantity, tip percent in. Subtotal, tip, and total out. Double math for money.

## Requirements
- Read `price`, `qty`, and `tip_pct` with clear prompts
- `subtotal`, `tip`, and `total` are named doubles
- Print those three results with labels
- Use `100.0` (or another double) so the tip is not always zero

## Sample session
```
Price? 20
Qty? 2
Tip percent (e.g. 15)? 15
Subtotal: 40
Tip: 6
Total: 46
```

## Starter
`main.cpp` — boxes are declared. You write the conversation and the math.

## Deliverables
1. Course-visible GitHub repo (link opens)
2. README with a sample run
3. Short demo video (tool + code + run)
4. Canvas links

## Scope fence
No loops, functions, or arrays required. Keep `main` readable.

## Integrity
- AI = tutor, not ghostwriter
- Fake ownership → zero
- Due: Monday night (not Sunday)
- Discussions (every week): first post Friday, replies Sunday
- Late: course policy (−10%/day unless stated otherwise)

## Rubric
Graded on: it runs, it meets the prompt, output is labeled, and the GitHub repo plus demo video are there.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
