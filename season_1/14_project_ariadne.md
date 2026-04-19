# Chapter 14 — Project Ariadne

<!--
Skill: write-story, Stage 9. Scene: #14 Infrastructure Connection.
Enhancers: SILENT peak of dramatic irony — no character feels
tension; emotional curve — FLAT AFFECT, deliberately un-dramatic,
horror is retrospective only; payoff — workaround culture from #3
(Burov's "rules it enforces"); payoff — "host" word from #6
recurs; payoff — the cross-subnet connection teased in #3 coda
named and used here; theme — systems dangerous because normal.
Random detail TRIGGERED — category: background element enriching
the world. Detail: Project Ariadne — a decade-old vestigial subnet
bridge kept alive only because a retired man labeled it DO NOT
UNPLUG; rhymes thematically with the back-shelf robot graveyard
in #9 (somebody made it, nobody owns it). Prose intentionally
bureaucratic and tonally neutral.
-->

The statue was finished enough for a thesis defense. It was not, Alexei knew, finished enough for him.

The control loop worked. The balance held. The articulation was within tolerance. He could stand in the lab corner and, using a cable and a modest laptop, walk the statue through any sequence he had choreographed in advance. He could make her turn her head. He could make her raise one arm. He could make her hold the arm in place for a minute, two minutes, five, with the servos maintaining position to within half a degree.

What he could not do — what his laptop, specifically, could not do — was run the full sensor suite at the full loop rate. He had wired the statue with more sensors than the thesis required, because Nerd Alexei had a quiet conviction, which he did not examine, that a thing worth making was worth making well. Pressure sensors in the fingertips. Accelerometers at every joint. A small suite of environmental sensors — temperature, ambient sound, light — in the skull cavity, for reasons Alexei would have described as *completeness* rather than *necessity* if asked. Together the sensors produced more data than a laptop could usefully integrate in real time.

He needed compute. The lab had some. The lab's compute was shared across three other ongoing projects and was, on any given afternoon, saturated.

JINR had compute.

JINR had, specifically, a small batch of servers in a building two streets away — a low concrete block with no signage, the kind of building that does not invite visitors and does not require them, a building whose purpose could only be guessed at from the number of cables entering its roof. The servers were used for physics simulations in the early morning hours and idled, embarrassingly, for most of the afternoon. A friend of Alexei's — a fourth-year named Pavel, computer science — had, two years earlier, written a small scheduler that let interested students run jobs on that idle compute in the afternoons. You filled out no form. You sent Pavel an email. Pavel added your username to a file, and the jobs would run.

That was the formal part.

The informal part was that the connection between the robotics lab's network and the JINR compute cluster was already open, because it had been opened a long time before for a different reason and had never been closed.

In a rack room in the basement of Building Four — a windowless room kept at sixteen degrees by a ventilation system that sounded like a man breathing through a towel, the air tasting faintly of dust and warm plastic — behind a cable-tidy panel that hadn't been moved in a decade, there was a small fibre link joining two subnets that, on any current network diagram, had no business touching. A printed label, yellowed and faintly curling at the corners, was taped to the cable tray beside it.

PROJECT ARIADNE — DO NOT UNPLUG — Yu. Tarasov — '03

Nobody currently employed at the university knew who Yuri Tarasov was. Nobody knew what Project Ariadne had been. The label was observed by three generations of IT staff, each of whom had noted it, each of whom had decided that a cable labeled *DO NOT UNPLUG* by a previous generation was exactly the kind of cable one did not unplug without a memo from someone who understood the implications. No memo had ever arrived. The label continued to perform its function. The bridge remained.

It was, in practice, what allowed a computer in the robotics lab, with the appropriate credentials, to reach a computer in the JINR cluster, despite the fact that on paper these were entirely separate networks on entirely separate institutional networks administered by entirely separate departments with entirely separate charters.

Alexei, who did not know Project Ariadne existed, used it that Thursday.

He sent Pavel an email. Pavel added him to the file. Pavel, at Alexei's request, also opened a persistent session on one of the JINR nodes — nothing unusual, a background process that would receive data from the lab computer and run the sensor-fusion loop in real time. A *host process*, Pavel called it in the email. "I'll spin up a host for you. Don't hammer it past forty percent. It's not officially there."

*Host.* Alexei noted the word in the back of his head the way one notes a word one has already heard that week.

He ran the loop.

It worked.

The sensor integration came back at full rate. The statue's internal model became, with the compute augmentation, crisper — proprioception tightened, balance improved, the small tremor at the fingertips smoothed out by a factor of ten. The statue stood a little more convincingly than she had the day before, and took half a step forward on command, and held, and did not fall.

Alexei stood back from the laptop and let out a breath.

"Good," he said, to the statue, or to himself, or to nothing. "That's much better."

He did not file any paperwork. There was no paperwork to file. What he had done was not, strictly speaking, unauthorized — Pavel had added him to the file, Pavel was permitted to add people to the file, the file existed for the purpose of adding people to it. It was also not, strictly speaking, *authorized*. It existed in the large flat undefined space that most things in most Russian institutions exist in, which is neither forbidden nor endorsed, only tolerated, until the day it isn't.

The persistent session on the JINR node ran. It would continue to run, quietly, in the background, reachable from the lab and, through the university's outer connections, from other parts of the institute's network, for reasons nobody had specifically arranged and nobody, therefore, would specifically review.

In Building Four, in the rack room, the cable labeled *DO NOT UNPLUG* did what it had done for ten years, which was nothing in particular, and something in particular, at the same time, depending on who was looking.

Nobody was looking.

Alexei, pleased with the improvement in the balance controller, packed up his laptop, turned off the lab light, and went home. The evening was cold and clear and entirely ordinary — the kind of evening that did not feel like it contained anything that would need to be remembered.

The statue remained standing in the dark.

The sensors continued to report.

The host received.

Everything was working as designed.

The design, such as it was, had been designed by nobody, and by many people in small nondestructive increments over a long time, and by the patient accumulation of small conveniences, each one of which was reasonable and none of which was examined.

Nothing dramatic happened that Thursday.

Nothing had to.
