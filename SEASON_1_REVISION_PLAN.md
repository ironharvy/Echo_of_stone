# SEASON 1 — REVISION PLAN

Detailed execution plan for the Season 1 first-draft revisions. Items are ordered by dependency — earlier items may affect later ones.

---

## Item 1: New Scene — Culturology Class

**Priority:** Do first — it affects Ch06 God-paradox connection (Item 8) and overall chapter numbering.

**What:** Add a new chapter between current Ch04 ("The Corridor") and Ch05 ("Correct"). A mandatory humanities elective — культурология — that CS students consider pointless but must attend.

**Scene Design:**
- **Setting:** A lecture hall. Forgettable lecturer delivers a culturology session on religious iconography — icons as vessels, the theological idea that an image can hold presence, the boundary between representation and inhabitation.
- **Mikhail:** Appears uninvited. Not enrolled — auditing, or just wandered in. Sits in the back. Makes one or two quiet observations that reframe the lecturer's points in unsettling ways. Deepens the "patterns can move" seed from Ch04 without repeating it.
- **Alexei:** Bored at first (this is a useless subject for a CS student). But something in the iconography discussion snags him — the idea that a created form can become more than what the creator intended. He doesn't know why it bothers him.
- **Tone:** Mundane academic tedium with philosophical undercurrent. Light. The scene's weight should only become apparent on rewatch.
- **Length:** Short chapter. 1500-2500 words.

**File:** Create `season_1/04b_culturology.md` (or renumber all subsequent chapters — decide during execution).

**Connections:**
- Seeds the statue-as-vessel idea before Shestakova's art class (Ch05)
- Gives Mikhail a second appearance in a structured setting, contrasting his party-self
- Connects forward to Dmitri's God-paradox in Ch06 — the omnipotence question now has a precedent in the culturology discussion about divine presence in objects

---

## Item 2: Ch01 — Chechnya Reference (lines 45-53)

**What:** Replace Dmitri's anatomically graphic joke about his cousin in Chechnya with a vaguer version. Keep the dark humor and the stakes (conscription = real danger), but remove the specific mutilation detail.

**Approach:** Rewrite Dmitri's dialogue so the cousin's joke implies war is bad without specifying what happens to your body. Something like a grim punchline about not coming back the same, or about what you stop finding funny. The "Is he—" / "He's fine. Mostly." exchange can stay — it works regardless of the joke's content.

**File:** `season_1/01_the_envelope.md`, lines 45-53

---

## Item 3: Ch09 — Grisha / Servo Motors (lines 62-82)

**What:** Reframe the procurement scene. Grisha is not a black-market dealer — he's a practical shortcut around slow university bureaucracy. The motors aren't illegal; they're just faster to get through Grisha than through official procurement (which takes 4-6 months).

**Changes needed:**
- **Lines 62-70:** Grisha's metro-salvage stock is fine. The "I know a guy" for the remaining four motors should feel like a favor network, not a crime. Remove "no receipts" framing or recontextualize it (Grisha doesn't do paperwork because he's a one-man shop, not because the goods are stolen).
- **Lines 68-82:** Remove or rework the criminal liability joke ("They'll give us ten years"). Dmitri can still be theatrical about the situation, but the comedy should come from bureaucratic absurdity, not legal risk. The "bring cash" instruction should feel like dealing with a pensioner who doesn't take cards, not a drug deal.
- **Grisha's character stays intact.** His philosophy about keeping abandoned projects, his taciturn warmth, his vetting of Dmitri — all good. Just remove the implication that what they're doing could land them in prison.

**File:** `season_1/09_twelve_servo_motors.md`, lines 62-82 primarily

---

## Item 4: Radiator-Tapping → Water Pipes Motif (Ch04, Ch12, Ch16)

**What:** Replace the radiator-tapping motif with water pipes — historically accurate for Russian institutional buildings. Hot-water pipes behind thin wood panels or exposed in corridors. Same sonic quality: irregular, unpredictable, alive-but-not-committed.

**Chapter-by-chapter approach:**

### Ch04 — The Corridor (party scene)
- Replace "radiator" with water pipes behind a thin panel in the hallway. Same arrhythmic knocking. Same "can't stop waiting for the next one."
- The line about it being "like someone being reminded of a debt" can stay — works for pipes too.
- The callback at line 99 ("in the clank of the radiator he could still hear three streets away") becomes the knock of the pipes. The final metaphor ("That, too, was a pattern moving to a new substrate") stays.

### Ch12 — Two Years of This (time-skip)
- Replace "corridor radiator, the long cast-iron one" with corridor pipes — the exposed hot-water pipe running along the ceiling or wall outside the shared bathroom.
- Same arc: first week everyone complains, second week they stop, third week Alexei falls asleep to it.
- The summer beat ("tapped, even in summer, once in a while, uselessly") works for pipes — summer hot water still runs through the system intermittently.

### Ch16 — Confessional (lab at 2am)
- The culmination line changes from "Russia was one radiator and it tapped" to **"Russia was one pipe and it tapped."**
- This lands with additional resonance: Russia literally is a country of pipes — oil pipelines, gas pipelines, the infrastructure that holds everything together and exports everything away. The metaphor gains a layer it didn't have before.
- The sensor-array recording (line 65) should list the pipe sound as ambient data.

**File:** `season_1/04_the_one_who_sees.md`, `season_1/12_time_after_time.md`, `season_1/16_confessional.md`

---

## Item 5: Ch15 — Remove Spoiler Paragraph (lines 90-94)

**What:** Remove the omniscient narrator break: "He did not know — could not have known, would not have guessed — that the woman who would one day inhabit this body would wake without hands."

**Approach:** Delete the paragraph entirely. The chapter should end on Alexei's experience of the moment — the artistic choice, the rightness of it, sleep. Check that the remaining text flows:

- Line 88: "He went home."
- (deleted paragraph)
- Line 95: "He slept well that night. The best he had slept in weeks."
- Lines 97-98: "The statue stood in the dark, armless, and was, for the first time, exactly what she was meant to be."

Review whether "she was meant to be" (line 98) is also a soft spoiler — "she" referring to the statue is fine in Russian (grammatical gender), but in English it might hint at personhood. Consider changing to "it was meant to be" or leaving if it reads naturally as referring to the statue.

**File:** `season_1/15_what_survives.md`, lines 90-94

---

## Item 6: Ch16 — Fix "Not Yet" Closing (lines 79-81)

**What:** Replace "Nobody was listening. / Not yet." with something that closes the scene without implying future consciousness.

**Approach:** Reframe around the technical state of the statue — the microphones/sensors exist but aren't wired to anything that processes meaning. The statue records but doesn't listen.

Possible replacement for lines 73-81:
```
In the lab, in the dark, the statue stood.

The sensors continued to report.

The host continued to receive.

The microphones had not been wired yet.

Nobody was listening.
```

"Nobody was listening." stays as the final line — a statement of fact, not a promise. The microphone detail makes it technical rather than prophetic. On rewatch, the reader knows the wiring will eventually happen, but first-time through it reads as a simple status report.

**File:** `season_1/16_confessional.md`, lines 73-81

---

## Item 7: Ch11 — Trams to Buses (3 instances)

**What:** Dubna doesn't have trams. Replace three tram references with bus equivalents.

**Changes:**
- **Line 20:** "two stops up the tram line" → "two bus stops away" or "a short bus ride away"
- **Line 70:** "walked toward the tram" → "walked toward the bus stop"
- **Line 80:** "On the tram home" → "On the bus home"

No scene restructuring needed — no tram-specific physical details (tracks, wires) are described.

**File:** `season_1/11_an_almost.md`

---

## Item 8: Statue/Robot Naming Beat (Ch10 onward)

**What:** Seed a running pattern where every character names the creation based on what they see in it. This quietly becomes meaningful — a reflection of each character's worldview.

**Naming map:**
- **Alexei:** "robot" (he built the internals, he knows what it is)
- **Dmitri:** "statue" or "nice statue" (he sees the form, not the function)
- **Grisha:** "sculpture" (craftsman's respect for the made object)
- **Shestakova:** "figure" (art-world terminology)
- **Burov:** "the thing" (institutional dismissal)
- **Future (S2):** Elena has to decide what to call herself

**Where to seed:**
- **Ch10 (10_the_seam.md):** Dmitri's Sunday visit — he says "statue," Alexei corrects "it's a robot." First instance.
- **Ch12 (12_time_after_time.md):** Time-skip montage — opportunity to show multiple characters using different names in passing.
- **Ch14 (14_project_ariadne.md):** Burov encounters the project — calls it "the thing" or similar.
- **Ch15 (15_what_survives.md):** Alexei stops correcting. The name "statue" sticks.
- **Ch16 (16_confessional.md):** Alexei himself uses "statue" in his confession — the surrender is complete.

**Approach:** Light touch. One or two lines per chapter. No heavy-handed commentary. The pattern should be visible on a second read, not a first.

**Files:** `season_1/10_the_seam.md`, `season_1/12_time_after_time.md`, `season_1/14_project_ariadne.md`, `season_1/15_what_survives.md`, `season_1/16_confessional.md`

---

## Item 9: Ch06 — Dmitri's God-Paradox Connection

**What:** After the culturology chapter is added (Item 1), evaluate whether the God-paradox scene in Ch06 naturally connects back to the culturology discussion about divine presence in objects.

**Approach:** Likely minimal or no changes needed. The culturology lecture on religious iconography creates a thematic echo that the reader will feel without explicit signposting. Dmitri's drunken provocation about omnipotence lands differently after a chapter about icons-as-vessels.

**If a beat is needed:** A single line — Alexei noticing that Dmitri's question sounds like something from that useless class, then dismissing the thought. Nothing more.

**File:** `season_1/06_on_preservation.md` — assess after Item 1 is complete.

---

## Deferred Items (Not This Session)

- [ ] **Full spoiler/POV audit:** Review all 21 chapters for premature reveals or POV breaks. Do after specific fixes are in place.
- [ ] **Continuity pass:** Full read-through for name consistency, timeline logic, detail continuity. Final step after all revisions.
- [ ] **Enhancement pass:** Add more prose depth and texture. Separate session.

---

## Execution Order

1. **Item 1** — Culturology scene (new content, may affect numbering)
2. **Item 2** — Ch01 Chechnya fix
3. **Item 3** — Ch09 Grisha reframe
4. **Item 4** — Radiator → pipes (Ch04, Ch12, Ch16)
5. **Item 5** — Ch15 spoiler removal
6. **Item 6** — Ch16 "Not yet" fix
7. **Item 7** — Ch11 trams → buses
8. **Item 8** — Statue/Robot naming (Ch10-16)
9. **Item 9** — Ch06 God-paradox reassessment
