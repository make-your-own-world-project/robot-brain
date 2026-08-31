# Follow a claim back to the evidence

![A conclusion can be followed back through its supporting material and rejected alternatives.](illustrations/reasoning-engine-inspectable-path.png)

A confident answer is not proof. A language model can sound certain after losing part of the conversation, confusing two sources, or guessing at a missing cause.

The saved history keeps the parts a person can inspect: what the model received, what it returned, which later tool examined it, what checks ran, and whether the result was kept or rejected.

## What a reader should be able to see

For an important claim, the record should show:

- the passage or other evidence behind it
- who or what made the claim
- when it was made
- whether the evidence supports, disputes, corrects, or does not answer it
- what remains uncertain
- which check ran and what that check actually proved

This does not reveal a model's private internal process or every source that shaped its training. Language models do not provide that complete history. The record covers the exchange that can be observed and saved.

## Suggestions stay suggestions

The relationship reader may suggest that two passages describe the same task. The history reader may find a correction. The reasoning reader may report that a statement conflicts with an earlier one.

Each finding stays connected to the source passage and the local reader that produced it. A likely connection does not become a fact merely because several methods report it.

When the evidence is not enough, “unknown” is a valid result.

## Tests have boundaries

A source check can show that a claim matches the cited passage. It cannot prove that the passage itself is true.

A prepared example can show what happened in that example. It cannot prove that the same thing always happens in ordinary use.

A test of one part cannot stand in for a test of the whole working process. Each report names what was tested, under which conditions, and what passed.

## Why prompts are not enough

During development, online assistants repeated an instruction and then violated it in the same task. They also claimed work was complete before checking the visible result.

Important rules are therefore checked against the finished work. A language model's statement that it followed the rule is never the check itself.
