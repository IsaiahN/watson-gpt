## Part 2: The knowledge base, all figures and the formula

This is the reference material the assistant searches. Load it as a knowledge file. Every figure line comes from the canonical text of the Tether architecture, generated from its original figures (`docs/01-FOUNDATIONS/03-FIGURES_TEXT.md`). The formulas and definitions are from `figures/THE_FORMULA.md`. The architecture is set out in [Arrival of the Fittest: The Tether Architecture](https://adventuresinml.substack.com/p/arrival-of-the-fittest-the-tether), and the full source is at [github.com/IsaiahN/tether](https://github.com/IsaiahN/tether).

### How to use the map

This map says where to look. It is not a substitute for reading the figure.

- Fig 1 The Agent: residuals, slots, aggregation, what does not count.
- Fig 2 The Ground: triangulation, drift, why agreement is not evidence.
- Fig 3 Dependency Chain: order of dependence, where a chain breaks.
- Fig 4 The Membrane: round trips, what crosses up versus down.
- Fig 5 Mint Pipeline: gap kinds, guards, the bargain.
- Fig 6 Closure and Reachability: mint versus import, reach that can fall.
- Fig 7 Room Chain: handoffs, variation versus selection.
- Fig 8 Union Surplus: limits of a frame, absence versus not found.
- Fig 9 Leave, Arrive, Search: verdict, lookup, narrowing, filters versus witnesses.
- Fig 10 Ground Maintainer: offices, conventions, what a verifier may not be.
- Fig 11 The Habitat: agent and habitat, harness as substituted habitat.
- Fig 12 The Bond: bonds, arrangement, the two currencies.
- Fig 13 Minimum Viable Set: the six, lockstep, unreachable as a verdict.
- Operators and Symbols tables: definitions and notation.

### Figure 1, The Agent: how structure grows

Everything here either produces a residual or consumes the library. Gamma is the typed DSL plus the library. The ground is the only metric. One bet per object slot, every action. The residual R is indexed by object slot.

- Fig 1 :19 "The residual is indexed by object slot, not aggregated."
- Fig 1 :22 "Aggregating across slots is how a live signal disappears into an average."
- Fig 1 :23 "The ground enters as the only metric."
- Fig 1 :25-26 "coverage, and compression achieved ... predicates minted, and credibility accrued ... They are frame-internal. A frame cannot score itself with a quantity it also produces."
- Fig 1 :28 "The gap is measured per object, not per step. A system that averages across objects has thrown away the only signal that says where to look."
- Fig 1 :13 "a global R near zero with one live slot residual is a legal state."

Use: any question about measurement, metrics, or where to look. A global average that hides a live local signal is the named error.

### Figure 2, The Ground and the alignment problem

Three panels: mutual update (coherent drift), common cause (one evidence pool), and the anchor. Two frames ranged separately against a fixed anchor is the grounded case.

- Fig 2 :29-30 "An anchor is whatever settles the question and does not change its answer because of what any frame thinks. ... If it moves when you push on it, it is not an anchor."
- Fig 2 :31-32 "Independence, between two frames, is how little they draw on the same evidence. ... Independence is what makes agreement mean something."
- Fig 2 :33 "The anchor must not update."
- Fig 2 :35 "Alignment is triangulation, not negotiation. A mirror cannot correct you."
- Fig 2 :40 "disqualifying for a verdict: agreement about the world is worthless when the agreeing frames share an evidence pool"
- Fig 2 :41 "efficient for a convention: agreement about a shared meaning is the product, not a corruption of it"
- Fig 2 :42 "Buy independence in proportion to the cost of being wrong."

Use: any question about evidence, agreement, experts, reviews, or how to tell if a claim is settled. Ask what the anchor is and whether the frames draw on separate evidence.

### Figure 3, The dependency chain

Five links in order: perception, vocabulary, the objective, planning, learn and carry. The chain is ordered by dependency, not importance.

- Fig 3 :19 "Optimising a link that already works cannot rescue one that does not."
- Fig 3 :20-21 "The chain is ordered by dependency, not by importance. Each link consumes what the one above produces, so effort spent above the break arrives at a step that cannot use it."
- Fig 3 :22-23 "A step whose input never arrives cannot be diagnosed, only its predecessor can. Which is why a reading taken below the break is not a weak reading. It is a reading of nothing."
- Fig 3 :27 "A link with no instrument is not a link that works. It is a link nobody has looked at."
- Fig 3 :29-30 "Before asking whether a system is good, ask which link it currently stops at, and whether the answer was measured or assumed."

Use: any "why is this not working" question. Find the break first. Do not improve a step whose input never arrives.

### Figure 4, The membrane between scales

One loop at one agent and at a population. Only methods cross up. Only head starts come down. The round trip measures what was lost.

- Fig 4 :20-21 "Only the actors, the currency and the anchor change."
- Fig 4 :22 "Only methods cross up. Only head starts come down."
- Fig 4 :23 "upward: a method that can be reapplied. Never the recording of a particular success."
- Fig 4 :24 "downward: something that makes the next search cheaper. Never a replay of what worked once."
- Fig 4 :28-29 "So take the round trip and measure the gap. Without it you are navigating by dead reckoning: confident about a position nobody checked."
- Fig 4 :31-32 "The gap is not an error to eliminate. It is the measurement of what the coarser description cannot hold."

Use: questions about scaling, transfer between people or teams, teaching, or generalisation. A recording replayed is not a method carried.

### Figure 5, The mint pipeline

The prediction gap is sorted into kinds: held, new, mis-attached, mechanism broken, and the fifth, refuted. Three guards must all pass, as a product: support, reachability, novelty. The acceptance test is a bargain.

- Fig 5 :33 "The three guards are a product, not a checklist."
- Fig 5 :41 "Any one of them at zero stops the mint entirely. Which is why a system that is minting nothing may have nothing wrong with its minting."
- Fig 5 :42 "The acceptance test is a bargain, not a threshold."
- Fig 5 :43-44 "A new term is worth having when stating it, plus what remains unexplained after it, costs less than what was unexplained before. A term that explains everything by saying nothing fails this, and so does a term that explains one occasion perfectly."
- Fig 5 :48 "Its own output is never a measure of success."
- Fig 5 :52-55 "refuted: a term we hold is wrong; a term is owed that says so ... What it removes is not a term but a term's standing to be composed over. Nothing leaves the library. What falls is the reach."
- Fig 5 :65-66 "make the sought-for shape an ORDINARY TERM. Write down what an answer would look like, bind it, and let it accrue a residual like anything else."
- Fig 5 :69-72 "settling is necessary for a term to be composed over, and it is not sufficient ... a library that grows is not a reach that grows."

Use: questions about whether a new idea, rule or concept is worth adopting. Price it against the confusion it removes.

### Figure 6, Closure and reachability

Mint composes inside the closure and never adds an atom. Import is the only operator that moves the wall. Reachability is two questions, inward and outward, and they are opposed.

- Fig 6 :21 "MINT composes inside the closure and can never add an atom."
- Fig 6 :22 "NOVEL means novel relative to atoms, not to the world."
- Fig 6 :23 "No frame escapes its own closure. The bound moves only on contact with a frame whose closure differs."
- Fig 6 :24 "Import from a live peer is debited against that frame's independence. A wrong atom costs more than starting from primitives."
- Fig 6 :28 "Which makes reachability two questions, not one. The instruments are opposed."
- Fig 6 :29 "inward: is our representation adequate to hold it?"
- Fig 6 :30 "outward: does another frame already hold it? ... Cast it in effect terms."
- Fig 6 :32 "An instrument is not built from a description. It is improved from a worse instrument already returning something."
- Fig 6 :42-43 "What is recorded only grows. What is reachable is derived, and it can fall. A refutation adds a term that refuses; it removes nothing, and the reach falls because something was added rather than because anything was deleted."

Use: questions about the limits of a framework, when to borrow from another field, and why more search may not help.

### Figure 7, The room chain

Handing a question along only progresses if the next room differs from the last and matches the residual. A chain of mirrors is one long room.

- Fig 7 :35 "A room's agreement is variation, not a verdict. Selection between rooms is where the ground votes."
- Fig 7 :36 "A chain of mirrors is one long room. The next room must differ from the last, and match the residual it surfaced."
- Fig 7 :37-39 "Progress per handoff has two factors. Zero either and the chain runs in place: the bracket's fidelity across the handoff, the ground's pressure on the room."
- Fig 7 :41 "The pool it is drawn from must be unauthored."

Use: questions about committees, panels, iterations, or asking multiple people. If they all share the same view, that is one room, not many.

### Figure 8, The union surplus

Two frames with different closures reach what neither reaches alone. Residual first, frame second. Underivable and unreachable at this budget are different facts.

- Fig 8 :32 "Closure is idempotent. Composing inside a closed set never leaves it, so no search, however long, adds an atom."
- Fig 8 :39 "So a search that finds nothing is never a proof of absence."
- Fig 8 :40-43 "Underivable-in-principle and unreachable-at-this-budget are different facts, and they issue different instructions. Underivable: go outside. Unreachable-at-budget: the term is already in the closure and was not found, so the remedy is more search, not another atom."
- Fig 8 :45-46 "Two frames together reach what neither reaches alone. ... that surplus is where imports live."
- Fig 8 :49-50 "Two frames that overlap almost completely are one frame wearing two names."
- Fig 8 :51-52 "Convergent derivation and adopted import look identical in the contents. Only the record of where each came from separates them."
- Fig 8 :53 "Residual first, frame second."

Use: interdisciplinary questions and "we searched and found nothing" claims. Describe the gap before choosing an outside frame.

### Figure 9, Leave, arrive, search

Three questions: the verdict (is it in here), the lookup (which frame holds it), the narrowing (which one is it). Filters for the budget, witnesses for the verdict.

- Fig 9 :4-5 "First: is there a fact here? Disagreements that do not shrink with effort ... are not one hard question but several well-formed ones. Split it rather than search."
- Fig 9 :27-28 "describe it before you go looking, or any frame you pick will seem to fit"
- Fig 9 :30 "your words are borrowed too, so describe the effect rather than the cause"
- Fig 9 :43 "The verdict tells you to leave. The lookup tells you where to go. Elimination is what you do after you arrive."
- Fig 9 :44 "Only a sealed room can be searched to the end, and no frame is a sealed room. So searching and finding nothing proves nothing."
- Fig 9 :60 "Use filters for the budget and witnesses for the verdict. Never let a filter hand you a verdict."

Use: any "where do I look" or "should I give up" question. Describe the residual in effect terms first.

### Figure 10, The ground maintainer

Three offices and three prohibitions. A verifier that can reconstruct the claim cannot verify it. A convention that decides an outcome has stopped being one. Provenance shows a ruling was reached legitimately, never that it was right.

- Fig 10 :24 "the ground does not decay, the channel does"
- Fig 10 :28-29 "the output is not a verdict, it is you have lost touch -> keep the anchor reachable"
- Fig 10 :42 "A verifier that can reconstruct the claim cannot verify it."
- Fig 10 :43 "Soundness requires the checker to be unable to produce what it is checking."
- Fig 10 :45-46 "It does author conventions ... A convention makes no claim about the world; a verdict and an atom both do."
- Fig 10 :47 "a convention that decides an outcome has stopped being one"
- Fig 10 :59 "an interest in the outcome is unavoidable, an interest in the reading is disqualifying"
- Fig 10 :61 "standing is a stake that survives the outcome it was earned on."
- Fig 10 :65-66 "Provenance shows a ruling was reached legitimately. It never shows it was right: the ground does that."

Use: questions about checking, verification, reviewers, conflicts of interest, or a metric that has stopped telling you anything.

### Figure 11, The habitat

Capability is a property of agent and habitat, never the agent alone. The habitat is enumerated, never composed. Isolation substitutes a habitat, it does not remove one. Introduce, never subtract.

- Fig 11 :36 "Where nothing maintains anything, intelligence is a label applied afterwards to a lineage that met its ground."
- Fig 11 :39 "the answerable question is not what intelligence is, but what makes a system capable. And capability is a property of agent-and-habitat, never of the agent alone."
- Fig 11 :40 "A system cannot be made more capable by improving the agent in isolation. An improvement that does not change contact changes nothing, however much it improves."
- Fig 11 :43 "The habitat is enumerated, never composed."
- Fig 11 :48 "You do not invent the list. You read it off the world, and what you cannot perceive or measure yet is the residual."
- Fig 11 :61 "The seat's power is asymmetric. Introduction is available; exclusion is not."
- Fig 11 :66 "Isolation is not removal of the habitat. It is substitution of one habitat for another."
- Fig 11 :70 "A test harness is a substituted habitat. Which is why a synthetic solve proves wiring and never capability."
- Fig 11 :73 "the habitat is where actors come from and it updates; the ground is what settles, and it does not."

Use: questions about intelligence, capability, environments, benchmarks, or why a fix in a test does not carry over.

### Figure 12, The bond

A list of ingredients is not a molecule. The bond carries information the operands do not. Seven bonds, plus negation as a unary operator. Two currencies, bits and actions, which do not add.

- Fig 12 :5 "A set of ingredients is not one. The bond is the rest of the information, and it is the half nothing was recording."
- Fig 12 :44 "the arrangement is priced or it is free"
- Fig 12 :46-47 "A bond is the typed relation between two operands. There are seven, they are not interchangeable, and which one holds is not recoverable from the operands. A recipe that names only its ingredients has recorded half of itself."
- Fig 12 :94 "The arrangement is the substance."
- Fig 12 :103-104 "Composition is recursive, and the level decides what is irreducible."
- Fig 12 :111 "A vocabulary without bonds can name a state and cannot name a route to one."
- Fig 12 :112 "A plan is a sequence. A goal is a comparison. Progress is a subtraction. A refutation is a negation, and that one is not a bond."
- Fig 12 :125-126 "A composition costs in two currencies, and they do not add. Bits price the description. Actions price finding out whether it holds."
- Fig 12 :130 "Summing them into one figure is the error this names, not the fix for it."
- Fig 12 :139-140 "Without a unary operator a system can write what a situation contains, what follows what, and how far along it is -- and it cannot write that any of those is false. A vocabulary that cannot refuse can only accumulate."

Use: questions about composition, planning, goals, explanation, or why a list of parts is not the thing.

### Figure 13, The minimum viable set

Six terms in two kinds, lockstep: states (space, time, energy) and structures (spectrum, gradient, network). The set is closed, the arrangements are not. The lineage is the proof.

- Fig 13 :38-39 "Which is Figure 2's condition applied to the set itself: independence is how little two frames draw on the same evidence."
- Fig 13 :115 "The set is closed. The arrangements are not. That gap is why import exists."
- Fig 13 :116-118 "Six members, and no amount of arranging produces a seventh: a new member would have to be a new kind, and composition only ever rearranges the kinds already held. Meanwhile the arrangements over those six do not run out. So a frame can search without end and still not arrive: infinite effort inside a finite reach."
- Fig 13 :128-130 "The array cannot be checked by inspection, so the record is what makes it verifiable. ... A term carries the atoms it was built from and the bonds that joined them. That record is not documentation of the term. It is the term."
- Fig 13 :134-135 "So the system can report that it lacks something rather than producing an answer anyway. Unreachable is a verdict here, not a silence, It cannot say which primitive is missing, because naming it would mean already holding it."

Use: questions about first principles, what a system must have, or why a vocabulary can generate endless combinations without gaining a new capability.

### Operators table, the eight

Seven bonds plus negation. The bond carries what the operands do not.

- `+` conjunction, both hold at once, symmetric. The only bond in a flat formula.
- `||` disjunction, either suffices, symmetric. Not concurrency.
- `=` identity, two names one referent, symmetric.
- `->` sequence, A then B, ordered.
- `=>` production, A produces B, ordered. B is absent until A fires.
- `-` subtraction, A with B removed, ordered. Progress is a subtraction.
- `><` comparison, a threshold between two quantities, ordered. A goal is a comparison.
- `not` negation, this does not hold, unary. A refutation is a negation.

Price of an arrangement: `|phi| = (k+1)*log2(|atoms|+1) + (k-1)*log2(|bonds|)`. One bond type costs nothing. Seven cost 2.8 bits each. Negation does not enter the count. Its price is open.

- Operators :68 "A relation that fails all seven is not an operator you are missing; it is a claim that has not been made yet."
- Operators :73-74 "Subtraction is the nearest bond and is not it. ... Negation is the refusal of a claim."

### Symbols table, definitions

- Gamma: the library, everything the system can express.
- atoms(Gamma): the primitives, the floor of what it can say.
- closure(Gamma): the reach, everything expressible at any depth.
- b: the belief, what is taken to be the case before acting.
- w: the weighting between private history and inherited prior. w_A + w_B = 1, learnable from outcomes.
- a: the action. o': the observation.
- Gamma(b,a): the prediction.
- R: the residual, the gap between prediction and observation, per slot.
- s: the slot, one object or entity tracked. R is never a single global number.
- R+_s: the live mass, the positive part of the residual on a slot.
- phi: a candidate term. |phi|: its cost. left(R,phi): what remains unexplained.
- bond: the typed relation, seven of them, not recoverable from operands.
- molecule: a bonded arrangement. A chain is the degenerate case.
- T_A: abstraction, going up. T_E: concretisation, coming back.
- R_T: the round trip, gap(x, (T_E o T_A)(x)).
- F: the frame transform, between allocentric and egocentric at one scale.
- the ground: what settles the question and does not change because of what any frame thinks.
- the habitat: everything in contact with the residual. Enumerated, never composed.
- A frame is any bounded system with a library. A seat is a position defined by what it can and cannot see.

---
