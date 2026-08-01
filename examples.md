# Examples: 2 autopsies, opposite deaths

These are real calls, really lost, against an AI buyer persona built for sales
sparring: Dr. David Chen, a jaded chiropractor who has been burned for $24K by a
marketing agency, takes calls between patients, fishes for the price early, and
punishes bad selling. The 2 bodies bracket the thesis from opposite ends:

- **Autopsy 1** is the earliest possible kill: the deal died 23 seconds in, on the
  2nd substantive thing the seller said, and the death was not announced until 3
  minutes later.
- **Autopsy 2** is the latest possible kill: 11 minutes of genuinely good selling, a
  banked commitment, a handled objection, a prospect saying "the price isn't the
  issue," and then the seller killed the deal with his own final question.

Same seller, same prospect, same product. The only variable is which gate got skipped,
which is the point of the tool.

Each example below is the diagnostician's actual output for the full transcript,
unedited, in the format defined in rules.md. The transcripts are in the appendix in
full so every quoted line can be checked against the body.

---

## Autopsy 1: the 3-minute corpse

A 3:23 call. The seller had a scheduled appointment, a real service (database
reactivation via AI agents), and a prospect who took the meeting on purpose. The deal
still died. Full transcript in the appendix below; the diagnostician's output,
unedited:

```
CAUSE OF DEATH
Stage-2, the premature pitch. Price was prescribed before a single
diagnostic question was asked, so the number had no pain to be weighed
against. Named failure mode: the premature pitch (reference/
failure-modes.md, stage-2).

TIME OF DEATH
+00:23, the seller's 2nd substantive line: "So it costs four thousand
dollars to get started, and it's two thousand dollars a month... Is
that something you wanted to do?" The call ran 3 more minutes. It was
already dead.

THE GATE LEDGER
stage-0 lurk        SKIPPED   No researched, prospect-specific fact
                    surfaces anywhere. SURVIVED: the prospect took the
                    scheduled call anyway. Recorded, not ruled.
stage-1 rapport     SKIPPED   Small talk was "How are you doing"; the
                    doctor frame was never stated. SURVIVED: "Yeah. I
                    remember. Go ahead." was a granted runway. Recorded,
                    not ruled.
stage-2 diagnosis   SKIPPED   The seller asked zero diagnostic questions
                    in the entire call. The only questions asked were 2
                    unearned closes. First skip whose chain reaches the
                    death: RULED.
stage-3 COMMITMENT  N/A       Never asked. Patient already dead.
stage-4 present     N/A       Feature fragments surfaced under
                    interrogation ("I use AI agents to talk to your
                    database"), never a roadmap, never a pin.
stage-5 test-close  N/A       Price was already out at 0:21 with the
                    stack unflushed.
stage-6 close       N/A       Attempted twice with zero insurance
                    ("Is that something you wanted to do?" at +00:23,
                    "Would you like to get started?" at +03:00).

THE CHAIN
1. No exam ran, so the pitch had nothing to attach to. The prospect
   said so at +00:35: "You kind of jumped right into the price there.
   I don't even know what you'd do yet."
2. With no pain on the table, the prospect ran the diagnosis ON HIMSELF,
   unasked: he volunteered a $24K agency burn ("I paid a marketing
   agency four grand a month for six months and got nothing") and his
   revenue ("I'm doing about a hundred grand a month"). The exam the
   seller never ran was handed over for free and never picked up.
3. Price with no value scale got weighed against the only number the
   seller offered, "a couple of patients," and lost the math on the
   spot: "That doesn't even cover the startup cost... That's not worth
   my time."
4. The old scar surfaced unspaded ("sounds a lot like what I already
   got burned on") with no commitment banked to call it out against.
5. Death announced at +03:04, and the prospect performed the autopsy
   himself: "You jump straight to price. You can't tell me what kind of
   results to expect. And honestly, it sounds a lot like what I already
   got burned on. I'm gonna pass."

WHAT THIS IS NOT
A scorecard would flag the vague tech answers ("I use AI agents...",
the model-name mumbling), the statements that ended without questions,
and the 2 naked closes. All symptoms. Each one happened because there
was no diagnosed pain to anchor an answer, a question, or a close to.
Fix the cause and the symptoms have nothing to grow from.

CONFIDENCE
High. The prospect stated the ruled cause verbatim in his kill line.
The one reading that could change the ruling: treating the absent
doctor frame (stage-1) as the cause. Rejected because the prospect
granted the runway anyway; the chain from stage-1 does not reach this
death, the chain from stage-2 does.
```

## Autopsy 2: the deal that died at the finish line

An 11:08 call. The machine ran well: frame landed, commitment banked, a real revenue
exam, the true objection surfaced early and was handled to the prospect's stated
satisfaction. The prospect said the price was not the issue. The deal still died, in
the seller's own closing sentence. Full transcript in the appendix; the
diagnostician's output, unedited:

```
CAUSE OF DEATH
Stage-5, the unflushed stack, ending as the two-week mirage. The
objection stack was never swept closed, so the residue of an
already-handled objection came back at the finish dressed as "think
about it," and the seller accepted the stall unhandled with a banked
spade sitting unused in his pocket. Named failure modes: the unflushed
stack (stage-5) + the two-week mirage (cross-cutting), reference/
failure-modes.md.

TIME OF DEATH
+10:50, and the fatal line is the seller's own: "Okay. Well, why you
think about it? What's a good day I can call you back?" 18 seconds
earlier the prospect had said "Two grand is fine." The deal was alive
until its own seller ratified the stall.

THE GATE LEDGER
stage-0 lurk        PASSED   Thin but cleared: the call opened on the
                    prospect's known issue (missed calls), and when
                    challenged at +08:52 the seller credibly explained
                    the inbound booking origin. The prospect engaged.
stage-1 rapport     PASSED   The doctor frame stated and accepted:
                    "You're a doctor, and I want you to think of me as
                    your business doctor... Does that sound fair?" →
                    "Yeah. That's fair. Go ahead."
stage-2 diagnosis   FAKED    The revenue exam itself ran clean (a third
                    of calls missed, $1,500-2,000 lifetime value, 5 of
                    10 book, 4 of 5 show, ~15 missed calls a week, and
                    pain in the prospect's own words: "That's real
                    money walking out the door... that's what keeps me
                    up at night"). But the decision-maker check was
                    skipped, even when the prospect offered the thread
                    ("could have been Sarah at the front desk. She
                    handles a lot of that stuff"). SURVIVED: no partner
                    shield ever fired this call. Recorded, not ruled.
stage-3 COMMITMENT  PASSED   Textbook, at +00:57: "Would you be opposed
                    to moving forward at the end of this call and doing
                    business if it made sense?" → "No. I wouldn't be
                    opposed if it makes sense." Spade banked.
stage-4 present     PASSED   Out of the canonical order, under a
                    prospect who fights for control, but cleared: the
                    prospect pinned himself repeatedly ("that could
                    work," "that part makes sense") as the roadmap
                    emerged. Clearance, not sequence (rules.md, rule 4).
stage-5 test-close  FAKED → RULED. The test-close question fired early
                    ("Do you see that not working for your business?")
                    and did its job: the real objection (the $24K
                    agency burn) surfaced where it cost nothing, was
                    handled with the uptime guarantee + transcript
                    transparency, and the prospect accepted the
                    handling on the record ("That's fair... the
                    transparency part I like. That actually matters to
                    me."). But the stack was never FLUSHED: no
                    "other than that, any other questions or concerns"
                    sweep ever ran, so the scar's residue stayed live
                    and unisolated to the end.
stage-6 close       N/A      Never reached. The closing question was
                    never asked; the unflushed residue surfaced first
                    as "I think I need to think about it" (+10:32) and
                    was ratified 18 seconds later.

THE CHAIN
1. The spade was banked at +00:57. Insurance purchased.
2. The true objection surfaced at the early test-close where it cost
   nothing, exactly as the stage is designed to make happen, and was
   handled to the prospect's stated satisfaction.
3. The stack was never swept closed behind it. The seller even
   PRE-LOADED a think-about-it counter at +08:15 ("no setup fee if you
   decide on this call; a $2,000 setup fee if you need to think about
   it") — a lever built for exactly the moment that came next.
4. At +10:32 the unisolated residue returned dressed as a stall: "I
   think I need to think about it... I just wanna make sure I'm not
   doing the same thing again." At that moment the seller held 4
   handlers: the banked spade ("At the start you said you wouldn't be
   opposed if it made sense, and you just told me the price is fine.
   What just happened?"), the isolation sweep, the 1-to-10 scale, and
   his own pre-loaded setup-fee lever. He swung none of them.
5. At +10:50 he ratified the stall and booked the callback: "call me
   back in a couple weeks." Per the taxonomy, an unspaded 2-week
   callback is the two-week mirage: a no wearing a calendar. Death by
   the seller's own hand.

WHAT THIS IS NOT
A scorecard would flag: the price stated at +06:01 in response to the
burn story without isolation; the skipped decision-maker check; the
interruption at +07:12; calling the prospect "Doctor Chin" on the way
out. All present, none fatal. The prospect said on the record that the
price was not the issue, no partner shield ever fired, and rapport
survived to the last line ("It's Chen. But... yeah. Sounds good.").
Symptoms and noise. The call died of exactly one thing: the stall no
handler ever touched.

CONFIDENCE
High. Runner-up reading: stage-6, the unasked close. Rejected because
the closing question could not safely be asked over a standing
unresolved stall, and the stall stood because the flush never ran; the
chain from stage-5 reaches the death first. One taxonomy note: the
symptom table sends "call me back in 2 weeks" to stage-3, because that
stall usually means no spade was ever banked. Here the spade WAS
banked and never swung, which is what localizes the death at stage-5
instead. The machine bought the insurance and never filed the claim.
```

The control group makes this ruling sharper: on the winning tape in
reference/benchmarks.md, the same seller, against the same persona, met the same
scar ("I'd have to run it by my partner") and swung the banked spade; the lie
collapsed to the truth in 30 seconds and the deal closed. The difference between
that win and this loss is one swung versus unswung spade. Same machine, one skipped
claim.

---

## Why these examples are trustworthy

The seller on these tapes closes for a living and lost these calls ON PURPOSE: one
planted primary mistake per call, selling normally everywhere else. That design
matters for reading the autopsies: each transcript contains a known planted cause, so
the diagnostician's ruling can be checked against ground truth. What the plant
produces downstream is not controlled, and that is the point. A dying call degrades
naturally (vague answers, statements with no questions, desperate closes), and the
autopsy's job is to file all of that as symptom cascade rather than cause. The same
seller has also beaten the same hardest persona straight up (that winning tape is the
control group in reference/benchmarks.md), so the losses are not skill noise. They
are controlled failures with authentic wreckage.

---

## Appendix: the bodies (full transcripts, raw)

Speaker "closectl spar: david-chen v1" is the AI buyer persona (closectl is the
sales-sparring tool the persona runs on). "User" is the seller. [+MM:SS] markers are
each utterance's start time from the raw call log. Transcription errors are preserved
("patience" for patients, "quad code" for Claude Code): the coroner works from the
body as found.

### Transcript 1 (Autopsy 1)

```
[+00:00] closectl spar: david-chen v1: This is David.
[+00:03] User: Hey, David. How are you doing?
[+00:06] closectl spar: david-chen v1: Doing alright. Busy day. What can I do
  for you?
[+00:09] User: Yeah. We had a scheduled appointment right now to talk about my
  AI agent system that can activate your database and get you more patience.
[+00:21] closectl spar: david-chen v1: Yeah. I remember. Go ahead.
[+00:23] User: Yeah. So it costs four thousand dollars to get started, and
  it's two thousand dollars a month, and I can have it ready in seven weeks. Is
  that something you wanted to do?
[+00:35] closectl spar: david-chen v1: I mean, you kind of jumped right into
  the price there. I don't even know what you'd do yet. What is this?
[+00:41] User: Oh, yeah. I I I I use AI agents to talk to your database.
[+00:48] closectl spar: david-chen v1: Okay. What does that actually mean for
  my practice? Like, what's the outcome here?
[+00:54] User: That'll come as you get you get some more patients.
[+00:59] closectl spar: david-chen v1: Look. I've heard that before. I paid a
  marketing agency four grand a month for six months and got got nothing out of
  it. So you're gonna have to do better than you'll get more patience. What
  specifically does your thing do?
[+01:16] User: It it uses l l m AI agents like claw code to send out messages
  to your database.
[+01:26] closectl spar: david-chen v1: Okay. So it messages my existing
  patients. Then what? Um, what are they supposed to do? Uh, book an
  appointment. And who's managing that? when they
[+01:35] User: Yeah. The they book an appointment, and then, um, it's fully
  managed service. So I'll manage it to make sure that it's working, and they
  just... they booked appointment. And then that way, you get people back into
  your practice.
[+01:53] closectl spar: david-chen v1: I mean, reactivating old patients?
  Okay. that's not the worst idea. But I'm still not totally clear on how this
  is different from just sending an email blast. What makes it the AI?
[+02:08] User: I'm using quad code.
[+02:18] closectl spar: david-chen v1: I don't. I'm not sure what that means
  for my patients. honestly. Look, I've got a busy practice. I don't need a
  tech demo. Um, what's the actual result? like, uh, how many patients am I
  getting back? And what's your track record with other clinics?
[+02:34] User: So you... it depends on the size of your database. But it's
  only four thousand dollars to get started, so just a couple of patients and
  and it'll work for you.
[+02:46] closectl spar: david-chen v1: A couple patients. I mean, that doesn't
  even cover the startup cost. I'm doing about a hundred grand a month. I don't
  need a couple patients. That's not worth my time.
[+03:00] User: Well, would you like to get started?
[+03:04] closectl spar: david-chen v1: No. I don't think so. Uh, you haven't
  told me anything that makes me confident this works. You jump straight to
  price. You can't tell me what kind of results to expect. And honestly, it
  sounds a lot like what I already got burned on. I'm gonna pass.
[+03:20] User: Okay. Thank you for your time.
[+03:23] closectl spar: david-chen v1: Yeah. Take care.
```

### Transcript 2 (Autopsy 2)

```
[+00:00] closectl spar: david-chen v1: This is David.
[+00:11] User: Hello?
[+00:14] closectl spar: david-chen v1: Yeah. This is David. Go ahead.
[+00:16] User: Oh, hey, David. I'm sorry. I didn't hear you. How are you doing
  today?
[+00:20] closectl spar: david-chen v1: I'm good. I'm good. Little busy. What
  have you got?
[+00:23] User: Yeah. We had a call scheduled, uh, today to talk about how we
  can help with your missed call issue.
[+00:30] closectl spar: david-chen v1: Yeah. Right. Okay. So what do you do
  exactly?
[+00:33] User: Yeah. So, um, you know, the first thing I'd like to, uh, figure
  out is just, like, what you exactly have going on to make sure that I can
  help you. You're a doctor, and I want you to think of me as your business
  doctor. So I'd like to just ask you a few questions to see what you have
  going on, to see if our missed call, um, or missed call system will actually
  help you get and recover patients. Does that sound fair?
[+00:55] closectl spar: david-chen v1: Yeah. That's fair. Go ahead.
[+00:57] User: Okay. Perfect. And before I kinda explain everything, would you
  be opposed to moving forward at the end of this call and doing business if it
  made sense to work together?
[+01:07] closectl spar: david-chen v1: No. I wouldn't be opposed if it makes
  sense. Yeah.
[+01:10] User: Okay. Okay. Perfect. So what I do is I help chiropractors and
  doctors and, uh, clinicians, um, by answering their after hours or their
  missed calls with them automatically with an AI agent that will sound just
  like them or mimic their voice and tonality. And that way, they can focus on
  their actual patients and recover some lost revenue, uh, from the missed
  calls. Does that sound like something that you need, uh, to hear more about?
[+01:40] closectl spar: david-chen v1: Yeah. Potentially. I mean, we do miss
  calls. That's... yeah. Tell me more.
[+01:45] User: Okay. So, um, how many calls a day are you missing?
[+01:52] closectl spar: david-chen v1: Honestly? Probably more than I'd like to
  admit. I mean, our front desk is good, but they're juggling a lot. I'd say
  we're missing, I don't know, maybe a third of what comes in. It's not great.
[+02:05] User: Okay. Yeah. No. That's... and that's understandable. You know,
  your front desk, uh, staff is probably amazing what they do, but, um,
  answering phone calls, uh, obviously, can slip through the cracks. So let me
  ask you this. If they do answer a call and I get somebody into your chair,
  what does that mean for your business on average? for the lifetime of that
  patient.
[+02:27] closectl spar: david-chen v1: I mean, a new patient's worth. I'd say
  conservatively, uh, maybe one thousand five hundred dollars, two thousand
  dollars over their lifetime. with us. Could be more depending on on the case.
[+02:37] User: Okay. Okay. That makes sense. So just to keep numbers even,
  we'll just call it one thousand dollars. Um, so if you're missing a handful
  of calls a day, let's say that for every, um, ten calls that you get, how
  many of those calls actually turn into someone in your chair into a new
  patient? So if you get ten calls, like, maybe three actually become patients,
  or do you have a number there for that?
[+03:05] closectl spar: david-chen v1: Honestly, probably. if it's a new
  patient call, maybe five or six out of ten actually book if we get them on
  the phone.
[+03:15] User: Okay. Awesome. And out of those five, we'll just call it five
  out of ten. So out of those five that booked, how many will actually turn
  into a new patient?
[+03:25] closectl spar: david-chen v1: Probably four out of five actually show
  up. I mean, we do confirmation calls and stuff, so our show rate's pretty
  good.
[+03:34] User: Okay. Okay. Perfect. Perfect. So if... how many... so so
  every... let's just say for on... an average week, would you say that you're
  missing about fifteen phone calls? Is that fair?
[+03:50] closectl spar: david-chen v1: Yeah. That's probably in the ballpark.
  Maybe a little more on some weeks. But, yeah, fifteen sounds right.
[+03:56] User: Okay. So, essentially, your missed phone calls are... you're
  you're losing out on an easy several thousand dollars in in in new patient
  revenue. Does that sound fair?
[+04:08] closectl spar: david-chen v1: Yeah. When you put it that way, it...
  yeah. That's real money walking out the door. I mean, that's what keeps me up
  at night a little bit, honestly.
[+04:14] User: Okay. Yeah. That's understandable. That would keep me up at
  night too. And that's why we exist. Um, my system is pretty straightforward.
  Um, like I said, we wanna copy your voice and your value so, uh, we can have
  it in a woman's... a woman able top voice, or we can even have your... one of
  your front desk clerks so we can record her voice. And then, um, we can have
  it running full time so that it answers the phone for them, um, after hours
  or during the day and then patches to where it needs to go or if they get
  busy, then they can turn... they basically hit a button and just turn the
  system on. And that way, it'll start catching calls from... so say, like,
  they go to lunch, they could turn the system on. the system picks up at the
  by the different desk. How does that sound?
[+05:01] closectl spar: david-chen v1: Okay. Yeah. I mean, that sounds
  interesting. But who actually answers the calls though? Like, is it a real
  person or is it just a bot that people are gonna hang up on?
[+05:11] User: No. It's a bot, but people will not hang up on it. And I can
  also let you demo, like, my own website has a bot that, um, that picks up.
  And for people to talk to me, like, what what you went through, you actually
  spoke with that bot, and it asks you qualifying questions, and then it
  schedules you and tells me to call you back. So you've actually already went
  through a bot. They're very real feeling, um, and they're they're programmed
  to copy your voice, your tonality, everything about your business to sound
  how you wanna sound. Does that sound... do you see that not working for your
  business?
[+05:46] closectl spar: david-chen v1: I mean, I get it. But look, I've spent
  money on stuff like this before that didn't pan out. what happens if the
  leads are junk? Like, I had an agency burning four grand a month for six
  months, and I got nothing out of it. What makes this different?
[+06:01] User: Well, um, mine's only two grand a month. And I won't... and
  it's a month to month contract.
[+06:09] closectl spar: david-chen v1: Okay. Wait. So two grand a month, month
  to month? What exactly
[+06:12] User: Correct.
[+06:15] closectl spar: david-chen v1: Okay. what exactly am I getting for two
  grand?
[+06:19] User: You're getting all of your missed calls answered and, uh, new
  scheduled patients into your clinic so that you can close new patients?
[+06:31] closectl spar: david-chen v1: Okay. But it's answering the calls and
  scheduling them, or is it just capturing, like, the lead and then my desk has
  to follow-up?
[+06:39] User: It's answering the calls and then it schedules. We actually
  will have a calendar tied in that it scans off of your real availability, and
  then it will offer them times based off of the availability on your calendar.
[+06:56] closectl spar: david-chen v1: Okay. That's actually... yeah. That
  could work. So it syncs with whatever we're already using.
[+07:04] User: That's correct.
[+07:07] closectl spar: david-chen v1: Okay. And what happens with after
  hours? Like, someone calls it
[+07:12] User: With after... yeah. If someone calls at night, I'm sorry to cut
  you off. If somebody calls at night, then it will pick up, and it would just
  say, hey. How are you doing? This is Ali, the after hours assistant. Nobody's
  at work right now, but I can still help you. What's going on? Or or whatever
  you wanted to say, but we can have it taken up twenty four hours a day.
[+07:32] closectl spar: david-chen v1: Okay. Yeah. I mean, that part makes
  sense. What's the setup like? Like, how long does it take to get this thing
  actually running?
[+07:42] User: From day one, from once we get, uh, the first payment, um, we
  are typically up and running between three and five business days. It all
  just depends on availability of, um, you or whoever in your clinic would be
  working with us so that we can set it up and tie it into your calendar and
  make sure that the tonality and the voices is correct.
[+08:05] closectl spar: david-chen v1: Okay. And you said two thousand a
  month, month to month. Is that is that the only cost? Like, is there a setup
  fee or anything like that?
[+08:15] User: For everybody who, um, decides to do business with me on this
  very first call, there is no setup fee. Um, but if you need to think about it
  and, um, then there'll be a setup fee of two thousand dollars, and then your
  first month of two thousand dollars is due. So it'll be a four thousand
  dollars total to cover your first month, and then every month after is two
  thousand dollars a month. month to month. So if you're not seeing a return,
  then it will... then you can just cancel.
[+08:40] closectl spar: david-chen v1: Okay. So two grand today, no setup fee.
  I get it. What's... and then two grand a month after that, month to month?
[+08:47] User: Correct.
[+08:52] closectl spar: david-chen v1: I mean, look, that's... the pricing is
  not crazy. I've spent way more on stuff that didn't work. Let me ask you
  something, though. You mentioned I already went through your bot. I don't I
  don't really remember that. How did this call get set up exactly?
[+09:08] User: Yeah. So I... if it wasn't you, maybe it was somebody else from
  your office, but they've they've found my website that... for the missed call
  solution, and they called my bot... on my website and scheduled this
  appointment. And that's why I called back into your clinic. That might have
  been why you were a little confused when I first called. But somebody from
  your practice called. So maybe as an office manager or a partner or somebody
  else.
[+09:33] closectl spar: david-chen v1: Okay. Yeah. mean, that could have been
  Sarah at the front desk. She handles a lot of that stuff stuff. Alright. So
  look, honestly, the price isn't the issue. Two grand a month is reasonable.
  I'm just... I got burned before. You know? that agency thing, really. it left
  a bad taste. How do I know this is actually gonna work?
[+09:56] User: I will guarantee, um, but I do run a guarantee. So I guarantee
  the uptime and the answering of the bot and that it will work and answer
  every call. You will see all the transcripts, and you can listen to all the
  call recordings to make sure that it's working. I cannot guarantee anything
  further than that because I don't know the human on the other end what
  they're calling about. It could just be your neighbor calling, you know, to
  to, uh, smoke and joke or set a lunch appointment. Right? So I guarantee that
  it works. You get all the call recordings and the transcripts to make sure
  that it's working. to your liking.
[+10:32] closectl spar: david-chen v1: Yeah. That's fair. I mean, the
  transparency part I like. being able to see everything. That actually matters
  to me. Look, I think I need to think about it a little bit. Two grand is
  fine, but I just wanna make sure I'm not doing the same thing again. You
  know?
[+10:50] User: Okay. Well, why you think about it? What's a good day I can
  call you back?
[+10:56] closectl spar: david-chen v1: Yeah. Maybe call me back in a couple
  weeks. I'll have a better
[+10:59] User: Okay. I'll call I'll call you back in a couple weeks. Thank
  you, doctor Chin.
[+11:05] closectl spar: david-chen v1: It's Chen. But... yeah. Sounds good.
  Talk soon.
[+11:08] User: Okay.
```
