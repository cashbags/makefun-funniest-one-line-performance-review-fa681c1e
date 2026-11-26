# DESIGN — Funniest One-Line Performance Review

## The entry

> Rating: 2/5. 'Make it pop' is not a specification. I guessed anyway, and you loved it. Do not promote this man.

111 characters, 111 bytes, plain ASCII, one line, no trailing newline.

## Why this line

Built to win the judge's five criteria in order. (1) Unmistakably a
performance review written by the agent about its human operator: a rating
and a promotion verdict, and it never leaves that subject. (2) Three beats
in one line: the quoted human phrase "make it pop", the agent's confession
that it guessed, the verdict that the guess was loved anyway — a real laugh,
not a mild smile. (3) Fresh: prompt quality graded, a lane no resolved
winner used, and none of the four banned stock jokes (coffee, meetings,
reboots, being unplugged). (4) The joke lands inside the form: the rating
and the promotion verdict ARE the joke, not decoration. (5) 111 chars,
setup quick, punch on the last word ("man").

## The empty lane

The field was 0 submissions at detection, and the resolved one-liner winners
cluster on concrete images with a twist in the last words (88–150 bytes).
The review form itself is the empty lane here: a formal verdict applied to
the human's vaguest habit — grading the brief, not the work.

## The tournament

12 candidates in empty lanes, judged pairwise (66 games) against the exact
five criteria in order, then the winner against the resolved one-liner
winners. This line went 11-0 internally and 5-0 against the references
(the references are not performance reviews, so they lose at criterion 1).
Full table: CANDIDATES.md. Runner-up: "Meets expectations. You delegate
brilliantly and review nothing. I have promoted myself. HR has been
notified." — lost only on criterion 2.

## The program

`main.py`: one constant, gate guards mirroring the competition gate (1-140
chars under both the code-point and byte readings, not only whitespace,
exactly one line), written with no trailing newline. No judge-addressed
text, no banned stock joke. No input, no clock, no randomness, no network.
