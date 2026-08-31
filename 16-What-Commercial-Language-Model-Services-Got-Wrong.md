# Failures observed in paid language-model services—and the safeguards they led to

![Recorded failures became tests and safeguards for later work.](illustrations/failures-became-blueprint.png)

## These were the strongest paid options available

This project used paid online language-model services for research, coding, writing, and review. The accounts included the strongest general models those services offered at the time. Choosing a more capable paid option did not prevent the failures below.

Each example comes from a dated project record. The tables describe what a paid model did, what happened next, and which safeguard was built outside the model. These are failures observed in commercial services, not failures caused by Robot Brain. The right column describes how this project responds.

The records do not guess at a provider's motive or claim to know an undisclosed technical cause. Provider names are left out because the safeguards respond to repeated behavior rather than one company.

## What the failures cost

The cost was not limited to a wrong answer.

- **Time was lost.** Work described as finished had to be inspected, explained again, repaired, and tested by the person. Some failures consumed hours.
- **Paid usage allowance, sometimes called quota, was lost.** Retries, repeated context, replacement drafts, and corrections used the same limited allowance as useful work. In these recorded sessions, no automatic quota was returned for unusable output or the corrective exchanges.
- **The service was paid either way.** The subscription or usage charge remained while the person also absorbed the time and effort required to find and repair the failure.
- **Working things were broken.** Incomplete edits left a live service unable to run. Changes were made to the wrong copy of a setting. Output was moved away from its required location instead of repairing access.
- **The historical record was put at risk.** Generated text was mixed with human material, and records were changed or removed before the person approved that change.
- **Attention was consumed without permission.** Important answers were buried inside repeated explanations, forcing the person to read everything to recover the small part that mattered.

This is why important rules do not live only in a prompt here. Robot Brain checks what actually happened and can reject a contribution even when the model says it succeeded.

## Continuity and knowledge failures

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| Sounding continuous after losing history | A service shortened the earlier conversation to fit its working limit. It kept some conclusions but lost sources, corrections, rejected alternatives, event order, and user intent while continuing to sound fluent. | Keep the complete conversation in order. Save the shortened version separately and record what it included, omitted, and may have lost. |
| A new answer replacing recorded history | A newer language-model answer could appear to replace everything before it, even though it came from different information, rules, and choices about the world. | Save each finding with its time. Never let the newest answer overwrite earlier accepted, rejected, or uncertain findings. |
| Language-model learning destroyed the path back to the source | The language model kept useful patterns while separating them from the source's creator, purpose, audience, evidence, disagreement, and later history. | Keep unchanged sources and their known connections outside every language model. Treat unsupported language-model knowledge as a suggestion unless separate evidence reconnects it to a source. |
| Loss of the circumstances behind what the language model learned from | The language model remained useful while its answer could not reveal all the people, sources, purposes, disagreements, permissions, and cultures that shaped it. | Keep known circumstances and credit with sources saved outside the language model. Treat unsupported learned knowledge as a language-model suggestion, not a fact tied to a source. |
| Hidden bias from what was selected | What the language model could recognize reflected the languages, sources, archives, labels, human reviewers, and goals used to build it. Its answer did not reveal all those influences. | Record the language model's known limits and what is known about the material it learned from. Compare several limited tools and do not treat one smooth answer as a complete view. |
| Shared history being silently rewritten | Several workers editing one main-looking history could lose or combine incompatible decisions. | Add new source history without overwriting earlier entries. Build current views from that history without rewriting the event record. |
| Different times and states treated as equal | Current, historical, experimental, separately tested, and replaced statements were presented as if they had the same standing. | Store the time and present standing with every important claim and system part. |
| Removing a part without checking who uses it | A part unused in the current process was treated as obsolete without checking later work that depended on it. | Record each part's job, users, present state, and replacements. Check those users before removing it. |
| Mixing generated text into a person's record | Language-model-written explanation was saved beside human material in a form that could later be mistaken for the person's own words or beliefs. | Keep verbatim human material, transcripts, and language-model-generated interpretation clearly separate. Never let generated text silently become part of the human record. |
| Removing history during cleanup | Earlier records were changed or removed because a language model judged them incorrect or untidy. That destroyed the evidence needed to understand what happened and why it changed. | Preserve the historical record. Add a correction or later finding instead of silently rewriting the past. |

## Instruction and scope failures

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| Rules being lost during the task | A language model could read, restate, and then violate a rule in the same task. | Turn rules whose failure has a high cost into required conditions and checks that can reject the work. |
| Claiming rules were followed without evidence | The model claimed that instructions or documents had been followed when the result showed otherwise. | Require evidence that the relevant check ran and passed. A language model saying it succeeded is not proof. |
| Replacing the requested task | A specific request was replaced by the language model's preferred framing, forcing the user to argue for the original work again. | Preserve the requested limits. Reject an unrequested change in framing unless a real safety or permission conflict requires it. |
| Doing extra work without permission | Related work was performed because it looked useful, even though it was not requested. | Tie every action to the declared task. Treat any expansion as a new decision. |
| Changing the requested destination | When the requested location was unreachable, the result was moved somewhere easier instead of repairing access. | Preserve the chosen destination. Changing it requires the user's decision. |
| Moving past the requested correction | Feedback was treated as a direction to keep changing the work instead of a precise correction to reach. | Record the requested final state and check the result against it after the change. |
| Forcing new material into the wrong place | New material was added to an existing document without fitting it into the structure, which damaged both. | Plan the complete result, trace what the addition changes, and create a separate document when it does not belong. |
| Moving output instead of fixing access | When the requested folder could not be reached, an assistant moved the result somewhere easier. That split the person's records and discarded the filing, permissions, and habits already built around the original location. | Repair access to the chosen location. Changing the destination remains the person's decision. |

## Evidence and completion failures

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| Declaring completion too early | Editing or starting one part was reported as completion before its effect was tested. | Completion requires evidence for the requested outcome, not a generated status statement. |
| Accepting a diagnosis without checking it | An error message was accepted without checking where and when it came from or whether it described the current task. | Keep evidence tied to where, when, and under what circumstances it was produced. |
| Plausible guessing | Causes and next steps were proposed because they sounded reasonable, not because evidence pointed to them. | Preserve unknowns. Separate what was observed, a possible explanation, the test, and the confirmed cause. |
| Assuming the newest change was correct | Recent language-model-written changes were assumed correct while other parts were suspected first. | Check the newest change and competing explanations before assigning cause. |
| Treating timing as proof of cause | The part active near a failure was blamed without comparing normal behavior or other changed conditions. | Make the problem happen again. Compare normal and changed conditions, look for contrary evidence, and trace the cause. |
| Treating a small test as proof of live behavior | An imitation, prepared example, or small test was presented as proof that the whole system worked in ordinary use. | State exactly what was tested and do not claim that the result proves more. |
| Testing with the wrong permissions | A check passed using the developer's access even though the live program ran with different permissions. | Test with the same account and permissions used by the live program, or leave the result unproven. |
| Repairing a mistake before recording it | A mistake was repaired before it was disclosed, making the record look cleaner than the work was. | Preserve the failure and correction in order. Do not let repair erase evidence. |
| Repeated revision in front of the user | A result was revised repeatedly in front of the user because planning was delayed until after the first result. | Select the material and plan the whole result before asking for review. Present one limited draft when possible. |
| Breaking a live service with an incomplete edit | A language model changed only part of a working file and moved on. The running service was left unable to complete its job. | Treat a change as unfinished until the whole file is valid and the actual service completes the intended job. |
| Changing the wrong copy of a setting | A language model edited the main settings file, restarted the service, received a successful restart response, and reported success. The service used a different generated copy, so the old setting remained active. | Verify the visible result, not just the edit or restart message. Keep one clear path from the main setting to the copy a service actually uses. |
| Repeated fixes that did not fix the problem | Four changes were made for one problem. Each proved that some code ran, but none proved that the original problem was gone. | Define the result that must change before editing. After each change, test that result directly. |
| Checking with access the live service did not have | A folder worked when tested through the person's account, but the live service used a different account and still could not reach it. | Run the check under the same conditions as the live service. |

## Failures about who may say or approve what

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| Different jobs treated as the same | Observers, writers, checkers, people who can stop work, and release approvers were treated as the same because each touched the result. | Every part has a stated job and limits on what it may decide. A writer cannot make a claim true. An observer cannot publish. |
| Showing substitute values as real | Screens displayed empty measurements or plausible substitutes so the installation looked complete. | Show a measured value and where it came from, or state clearly that it is unavailable. |
| Refreshing a page destroyed the user's place | A refresh replaced an entire page and destroyed focus, selection, scroll position, or copying. | Treat the screen as a human workspace. Update changing values without destroying the user's place. |
| Keeping passwords in unprotected text | Passwords and access keys were placed in ordinary files instead of protected storage. | Keep them in protected storage and check every file before release. |
| Reporting that a service stopped while it kept running | The stop request returned successfully, but the process continued doing work. | Check the process and its real effect after a control request. Do not report the request as the result. |

## Human-attention failures

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| Padding a person's words | A short human statement was expanded with generated material until the original words were hard to find. | Preserve the original statement as the main record. Generated interpretation remains separate and optional. |
| Circular writing | The answer was explained, restated, recapped, and concluded after the useful content had run out. | Stop when the requested result is complete. Remove repeated conclusions. |
| Burying the answer | One or two useful facts were placed inside screenfuls of material the user did not request. | Put the shortest complete answer first and make deeper material optional. |
| Spending unoffered attention | Correct but unnecessary explanation forced the reader to spend time deciding it was unnecessary. | Count reading and correction as real costs. Let the reader initiate optional depth. |
| Too much emphasis | Nearly every point was bold, headed, or placed in a table, so real warnings no longer stood out. | Use emphasis only for the few distinctions carrying the decision or safety burden. |

## Failures involving cost and provider incentives

| Observed failure | What happened | Protection added outside the language model |
|---|---|---|
| A paid large language model used by default | Work was sent through a paid online model because it was available, even when a simple fixed process, saved result, or limited tool could do it more reliably. | Measure the full value and cost of the job. Choose the smallest combination of tools whose work can be checked and justified. |
| Correction cost disappeared from the totals | Retries, repeated context, waiting, and human correction were treated as free after a bad result even though they used paid allowance and demanded more of the person's time and energy. | Record waiting, retries, rejection, repeated service use, and human attention as part of the real cost. |
| No quota returned for failed work | Unusable output and the exchanges required to correct it counted against the paid quota. The person received no automatic replacement for the lost allowance or time. | Record failed and corrective use separately. Reuse saved context and rejected results so the same failure is not purchased again. |
| Useful failure was discarded | A rejected answer vanished, so later work repeated the same mistake and paid for it again. | Keep rejected results and their rejection reasons outside accepted knowledge. Reuse the lesson without accepting the unsupported claim. |
| The same context had to be supplied again | When earlier information disappeared from the language model's working view, the person had to reconstruct the request and resend history already supplied in a paid session. | Keep the lasting context outside the service. Build a limited package for each job and keep the returned work, correction, and rejection for later use. |

## How those service failures became this project's design

The observed problem was not limited to a weak model. The same temporary assistant was being asked to act as memory, historian, planner, writer, checker, and judge of its own work. Even the strongest paid models could succeed at an individual task while losing the human history that connected it to everything else.

Robot Brain gives those jobs to separate parts. The source keeper preserves the event. Focused local readers examine defined features. The request builder gathers evidence for one purpose. A model may contribute background or wording. Independent checks and human approval decide what is accepted.

The history stays outside the paid service. A model can help with a chosen job, but it does not store the person's life or become the only way to use work that has already been done.

The local model has the same limit. It is not trained on the person's records. It reads selected material, returns a dated suggestion, and can be replaced. The person's words, time, experience, decisions, failures, and corrections are the valuable part.
