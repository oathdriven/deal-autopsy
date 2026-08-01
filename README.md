# Deal Autopsy

**The deal dies at the first skipped gate, not where you noticed it die.**

Deal Autopsy is a folder-based AI diagnostician. Feed it the transcript of a sales
call that ended without the deal, and it names the stage where the deal actually
died, which is almost never where the seller noticed. It walks the call through a
7-stage commitment-gate state machine, finds the first gate that was skipped or
faked, and rules that moment the cause of death. Everything downstream, the stall,
the objection, the "let me think about it", is symptom.

It diagnoses. It does not treat. You get one cause, the quoted evidence, the chain
from cause to every symptom you saw, and then it stops. No rewritten pitch, no tips,
no checklist of 12 things you did wrong.

**Who it is for:** technical founders and builders who sell their own product and
keep losing calls they thought went well. If your demos land, your prospects nod,
and the deal still dies in the follow-up, the death happened earlier than you think,
and this finds where.

## Quickstart

### In a Claude project (claude.ai)

1. Create a new project.
2. Upload every file in this folder (keep the `reference/` files too; they are the
   diagnostic ladder).
3. Paste a transcript and say: `Run the autopsy.`

### In Claude Code

1. Clone or download this folder.
2. Open a session in the folder.
3. Paste the transcript (or drop it in the folder as a text file and name it) and
   say: `Read this folder, become the diagnostician, and run the autopsy.`

## What to feed it

- A raw transcript of one sales call that did not close. Timestamps help but are not
  required. Speaker labels help but are not required.
- Works on discovery calls, demos, and closing calls. One call per autopsy.
- Real transcripts often carry customer names and numbers. Scrub anything you would
  not paste into an AI tool before you paste it into this one.

## What comes back

A ruling in a fixed format: **cause of death** (1 to 3 sentences, exactly 1 stage, a
named failure mode), **time of death** (the line where the gate was skipped, with quotes),
a **gate ledger** (each of the 7 stages marked passed, skipped, or faked, with
evidence), **the chain** (how that one skip produced every symptom you saw), **what
this is not** (the loud symptoms a scorecard would have flagged, named as symptoms),
and a **confidence** note stating the one thing that could change the ruling.

## What it refuses to do

- **Fix anything.** Ask it what to do next time and it will tell you that is
  treatment, and it does autopsies.
- **List everything wrong.** One cause, ranked by causality (earliest broken gate
  wins). A list of 12 issues is a symptom inventory, not a diagnosis.
- **Diagnose a call that closed.** No body, no autopsy.
- **Work from a summary.** It needs the transcript, not the obituary.

## What is in the folder

| File | Job |
|---|---|
| `identity.md` | Who the diagnostician is: the Deal Coroner, 25 years of selling, autopsies only |
| `rules.md` | The procedure: walk the 7 gates in order, rule the first skip or fake, output format, hard stops |
| `examples.md` | 2 real autopsies of real calls, deliberately lost against an AI buyer persona: one killed 23 seconds in, one killed by the seller's own final question after 11 good minutes. Full transcripts included |
| `reference/state-machine.md` | The 7 stages and the observable gate condition for each |
| `reference/failure-modes.md` | The named deaths, stage by stage, plus the symptom-to-cause lookup table |
| `reference/benchmarks.md` | What passed gates sound like on a real winning tape, so faked is distinguishable from passed |

## Receipts: how this was validated

- The 2 example bodies are real calls, really dialed and really lost, by a seller who
  closes for a living, with 1 planted mistake per call. Each ruling was checked
  against the planted ground truth before shipping, and matched (stage-2 and stage-5).
- The first body exposed a flaw in the method: the strict "first skipped gate" rule
  would have ruled a rapport skip that the call visibly survived. The rule was
  corrected (the survived-skip filter in rules.md) before the first ruling shipped.
  Both the flaw and the fix are visible in the commit history.
- The folder was then walk-tested by an AI agent given zero context, which had to
  orient, explain the tool, and predict its refusal behavior from the files alone. It
  passed comprehension and caught a list of real defects (a citation to a
  then-nonexistent failure mode, uncheckable timestamps, output-contract drift), each
  fixed in the history.
- Final gate before submission: the folder was loaded into a fresh Claude project, the
  way a stranger would use it, and fed a transcript it had never seen.

## Where the ladder comes from

The state machine is the CommitToClose framework: sales as a state machine, not a
script, where every stage is insurance for a later stage. Full framework:
[committoclose.com](https://committoclose.com).

---

Built by Ryan "RyMac" McKinney. Marine Veteran. 25 years selling, as seen on Entrepreneur on Fire, and the
tapes to prove the machine works both ways: run clean, it closes; skip a gate, this
folder finds it. The framework: [committoclose.com](https://committoclose.com).
The community, where the sparring calls and the breakdowns live:
[skool.com/commit-to-close](https://skool.com/commit-to-close/about).
