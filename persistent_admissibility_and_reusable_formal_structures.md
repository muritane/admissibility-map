# Persistent Admissibility and Reusable Formal Structures

## 1. Starting Point

A bounded agent does not begin with a complete representation of reality.

It begins with limited access:

```text
observations
+
actions
+
finite memory
+
finite computation
```

The surrounding realization is larger, more detailed, and more dynamic than the agent can explicitly store.

If the agent seeks successful interaction, it must therefore construct representations that are smaller than the realized world while still preserving the distinctions required for action.

The basic problem is not:

```text
How can the agent represent everything exactly?
```

It is:

```text
Which distinctions must be preserved
so that interaction remains successful?
```

This creates a general pressure toward abstraction, compression, and formal structure.

The pressure does not come from a preference for elegance.

It comes from boundedness.

---

## 2. Minimal Operational Assumptions

A minimal starting point may require only the following:

```text
1. Something can affect the agent.
2. The agent can distinguish at least some observations.
3. The agent can perform at least some actions.
4. Different actions can lead to different later observations.
5. The agent cannot explicitly represent every relevant detail.
6. Some interactions count as more successful than others.
```

From these assumptions, further needs follow.

If actions can have different consequences, the agent benefits from prediction.

If prediction is useful, the agent benefits from a representation of regularities.

If the world is too large to represent exhaustively, the representation must compress.

If compression removes distinctions that change outcomes, interaction fails.

Thus:

```text
boundedness
+
interaction
+
differential consequences
+
success criterion
->
representation pressure
```

The target is not a complete mirror of reality.

The target is a representation that supports successful navigation through reality.

---

## 3. Observation, Action, and the Empirical Loop

An empirical model is not an isolated formal object.

It participates in a loop:

```text
realized world
->
observation
->
representation
->
query or prediction
->
action
->
new observation
->
correction
```

Without observations, there is nothing empirical to compress.

A formal system may still be invented, but it has not yet become a model of a realized domain.

Without queries, actions, or consequences, there is no operational criterion for deciding which compression is useful.

Many descriptions may be possible, but nothing selects among them.

The success of interaction supplies the selection pressure.

A model remains answerable to the realized world because failed predictions and failed actions expose missing distinctions, false transitions, or invalid equivalence classes.

---

## 4. Representation Pressure

Representation pressure arises whenever an agent cannot preserve every detail but must still distinguish among consequential possibilities.

The pressure is not simply to record change.

It is to record differences that predict different continuations.

```text
difference
+
different admissibility or consequence
->
pressure to represent the difference
```

Conversely:

```text
difference
+
no change in supported queries or outcomes
->
pressure to quotient the difference away
```

For example, two cars may differ in color but remain equivalent for a bridge-crossing query.

The same two cars may cease to be equivalent for a paint-repair query.

Two terrain regions may look visually similar but differ in whether a truck can traverse them.

The distinction becomes relevant when it changes admissibility.

This suggests a general criterion:

> Preserve distinctions whose omission changes the answers to supported observation, action, measurement, recovery, or reachability queries.

Everything else may be compressed relative to those queries.

---

## 5. Why Formal Structures Arise

When observations repeat or exhibit stable relations, the agent can replace many instances with one reusable structure.

Instead of storing:

```text
object falls
object falls
object falls
```

it may represent:

```text
under admissible conditions,
objects follow a recurring downward-motion pattern
```

The important step is not merely reducing three entries to one.

It is constructing a finite structure that can apply to additional instances not yet observed.

```text
finite description
->
open-ended applicability
```

This is the transition from an archive to a model.

Many familiar formal objects can be understood as responses to recurring representation pressures:

```text
functions
->
stable dependence across varying inputs

graphs
->
possible and impossible transitions

equivalence classes
->
differences that do not affect supported queries

geometry
->
shape, position, continuity, and reachability

probability
->
unresolved distinctions with stable consequence patterns

constraints
->
compact descriptions of admissible regions

recurrences
->
finite rules for indefinitely extendable sequences
```

This does not imply that every bounded agent must reproduce human mathematics.

It suggests that sufficiently capable bounded agents interacting successfully with structured environments are under pressure to develop math-like formalisms: variables, relations, transformations, equivalence, composition, order, geometry, uncertainty, and constraint.

---

## 6. Extensional and Intensional Representation

A representation can list instances explicitly:

```text
point 1
point 2
point 3
...
```

This is extensional representation.

Or it can specify a rule that admits or generates instances:

```text
x belongs to an admissible region
```

```text
F(n) = F(n-1) + F(n-2)
```

```text
x^2 + y^2 = r^2
```

This is intensional representation.

The second form can compress indefinitely many admissible instances into a finite description.

A circle can be approximated by a polyline, but a center-and-radius description preserves its regularity more compactly.

A sequence can be enumerated, but a recurrence preserves the rule that generates further elements.

A neural network can accept indefinitely many inputs from a represented domain without storing one separate entry for each input.

The structure is finite.

Its admissible input class may be open-ended or mathematically infinite.

This is not the explicit representation of infinitely many events.

It is a finite organization whose rule applies across an indefinitely large class of cases.

---

## 7. Direct Edges, Paths, and Derived Edges

Human language frequently compresses paths into apparent edges.

```text
Berlin
->
Munich
```

This usually does not identify a primitive realized transition.

It abbreviates a path whose exact form depends on starting point, destination point, capability, infrastructure, legal conditions, timing, and local state.

```text
position in Berlin region
->
local traversal
->
network entry
->
sequence of admissible segments
->
network exit
->
position in Munich region
```

The abstract edge is justified only if at least one admissible lower-resolution path exists.

This suggests two edge types:

```text
direct edge
=
transition admitted at the current resolution
```

```text
derived edge
=
summary of an admissible path at a finer resolution
```

The distinction matters because human reasoning often treats reachability as adjacency.

A long, fragile, expensive, or condition-dependent path is mentally replaced by an easy edge.

That abstraction can backfire when the hidden path contains blocked transitions.

A disciplined map should therefore permit expansion:

```text
abstract edge
->
path witness
->
local conditions
->
measurable transitions
```

An abstract edge without any admissible path witness is not compression.

It is an unsupported claim.

---

## 8. Roads, Rivers, and Interaction Conditions

A road admits ordinary car traversal not because the label `road` has causal power.

It does so because the realized organization usually satisfies a collection of interaction conditions:

```text
support reaction
+
sufficient traction
+
limited deformation
+
acceptable slope
+
continuous traversable surface
+
adequate clearance
+
stability
+
legal and operational permission
```

A river often fails one or more of these conditions.

A shallow river may still admit a truck crossing if the riverbed provides enough support, traction, and continuity, while water depth, flow, drag, intake height, electrical protection, and vehicle geometry remain within admissible ranges.

Thus `shallow` is not an absolute property.

It is shorthand for a relation among:

```text
water depth
riverbed properties
vehicle geometry
vehicle mass
flow velocity
traction
clearance
intake height
operator capability
```

The relevant question is not:

```text
Is this a road or a river?
```

It is:

```text
Does this realized organization
support the required interaction chain
for this acting organization
under the current conditions?
```

Labels summarize recurring interaction profiles.

They do not replace the underlying admissibility conditions.

---

## 9. Abstract Functions and Physical Realization

A mathematical function is a stable mapping defined over an admissible domain.

For example:

```text
y = NAND(x1, x2)
```

The abstract relation does not by itself create a reusable physical NAND gate.

A physical gate must be organized so that, for admissible voltage ranges, timing conditions, temperature ranges, and noise levels, it repeatedly realizes approximately the same input-output relation.

The abstract function is invariant across varying inputs.

The physical realization is not invariant in the strict microscopic sense.

It changes during every operation.

A CPU does not appear automatically because a truth table is mathematically definable.

It must be designed and maintained as a physical organization whose transitions are sufficiently predictable and whose post-interaction states remain usable.

```text
physical organization
+
admissible input
->
controlled transition
->
expected output
+
post-interaction organization still capable of further operation
```

This is a stronger requirement than merely instantiating a mapping once.

It requires repeated realizability.

---

## 10. Reuse as Persistent Admissibility

A reusable organization does not return to the exact same physical state after each interaction.

Instead, it remains within an equivalence class that continues to admit the required future interactions.

```text
organization_t
+
interaction
->
organization_(t+1)
```

with:

```text
organization_(t+1)
!=
organization_t
```

but:

```text
organization_(t+1)
~
organization_t
```

relative to the supported interaction queries.

This relation is operational, not absolute.

A road after one vehicle passes is not physically identical to the road before the traversal.

A transistor after switching has undergone heat exchange and microscopic change.

A heart after one beat is chemically and mechanically different.

A receptor after binding and release is not in the exact same microstate.

Yet each may remain in the same admissibility class:

```text
still drivable
still computable
still able to beat
still able to bind
```

The deeper invariant is therefore not exact state identity.

It is continued capability.

> Persistent admissibility is the continued membership of a changing organization in an equivalence class that supports the relevant future interactions.

---

## 11. Strict Identity, Similarity, and Time

Under ordinary physical evolution, exact repetition of a complete reality state is not what occurs in reusable systems.

Time advances.

Energy is exchanged.

Heat dissipates.

Components age.

Signals propagate.

The wider environment changes.

Even replaying the same video on the same screen is a new interaction:

```text
new electrical transitions
new photons
new thermal state
new environmental context
new observer state
```

The replay may be equivalent for the query:

```text
Did the viewer receive the same represented audiovisual sequence?
```

It is not identical at the complete physical-state level.

Thus empirical sameness should usually be interpreted as equivalence under a selected resolution and query set.

```text
same for this task
!=
identical in every physical respect
```

A requirement for exact total-state repetition would make ordinary reuse impossible.

The practical requirement is stricter than vague similarity but weaker than identity:

```text
sufficiently similar
with respect to specified admissibility conditions,
measurements,
and future interactions
```

---

## 12. Recovery and Maintenance

Recovery should not be defined as return to an identical state.

It should be defined as return to an admissible region.

```text
interaction
->
deviation
->
relaxation, repair, control, or replenishment
->
state re-enters supported admissibility class
```

This pattern appears across domains.

### Digital circuits

Electrical states relax into voltage ranges interpreted as stable logical values.

### Roads

Maintenance restores surface continuity, traction, drainage, and structural capacity.

### Hearts

Metabolism, circulation, cellular repair, and regulation maintain the capacity for further beats.

### Cells

Transport, synthesis, degradation, membrane regulation, and energy conversion preserve future interaction capability.

### Software systems

Error handling, process restart, state validation, and dependency repair restore executable conditions.

Recovery is therefore part of what makes a reusable function physically realizable.

Without recovery or maintenance, repeated use eventually moves the organization outside its admissible class.

```text
usable
->
degradation
->
borderline
->
failure
```

Reuse is always conditional, approximate, and bounded.

---

## 13. One-Time Events and Reusable Organizations

A one-time event can still matter.

But it provides little leverage if no stable relation can be reused.

If a person could drive only once, learning a reusable driving policy would have far less value.

If a heart could beat only once, there would be no persistent pumping organization in the ordinary sense.

If a cell could admit only one molecule in its lifetime, receptors and transport machinery would have radically different design pressures.

The existence of reusable organization is favored when:

```text
one structural investment
supports many future interactions
```

This is sometimes described economically as amortization, but the more fundamental property is repeated admissibility.

The organization persists because each interaction usually leaves it capable of further interactions, often with maintenance and energy input.

The reusable structure is not valuable merely because it compresses past events.

It is valuable because it organizes future possibilities.

---

## 14. Neural Networks and Open-Ended Inputs

A neuron-like unit may be represented as:

```text
y = sigma(w . x + b)
```

The parameters do not store a separate response for every possible input.

They define a transformation over an admissible input region.

Many distinct inputs may receive the same or similar output.

Relative to the task, the structure induces equivalence classes over inputs.

```text
x1 ~ x2
when replacing x1 with x2
does not change the task-relevant output
```

A single linear threshold unit cannot realize XOR over the usual binary representation because the required classes are not linearly separable.

A larger network can create intermediate distinctions and thereby represent the required partition.

This illustrates a general point:

```text
representation capacity
=
which distinctions the structure can preserve
and which admissible transformations it can realize
```

The trained weights may converge without an explicit human-readable rule.

Even so, the resulting organization remains a finite parameterization of behavior across a large or mathematically infinite input domain.

The important property is not infinite storage.

It is finite structure with open-ended applicability.

---

## 15. Concepts as Reusable Interaction Summaries

Human concepts may be understood as reusable summaries of interaction-relevant regularities.

A concept such as `road` compresses a recurring pattern involving:

```text
spatial continuity
surface support
traversal
legal conventions
signage
connection to other segments
maintenance expectations
```

A concept such as `face` preserves distinctions useful for identification, social prediction, communication, and recognition.

If every face were physically identical and remained identical under all relevant conditions, there would be little pressure to represent fine facial variation for individual identification.

The existence of variation alone is not enough.

The variation must change some supported observation, action, or prediction.

Thus concepts need not be treated as arbitrary names attached to reality.

They can be treated as maintained equivalence classes induced by recurring differences in admissibility, prediction, measurement, and consequence.

---

## 16. Implications for AI

A system trained only to reproduce labels may inherit human categories without learning the interaction structures that justify them.

A more grounded system would connect concepts to:

```text
observations
capabilities
actions
constraints
path witnesses
measurements
failure modes
recovery conditions
```

Instead of learning only:

```text
this is a road
```

it would also learn:

```text
this region supports wheeled traversal
under these load, traction, geometry, weather,
and legal conditions
```

Instead of assuming:

```text
A -> B
```

it would distinguish:

```text
directly admitted transition
```

from:

```text
derived reachability supported by an explicit path
```

Instead of treating repeated execution as exact reset, it would model:

```text
state drift
recovery
maintenance
degradation
continued admissibility
```

Such a system could expose when an apparently simple concept or action hides a long, uncertain, or impossible path.

---

## 17. A Compact Construction

The framework can be summarized as the following progression:

```text
bounded agent
+
structured realization
+
observation and action
+
success criterion
->
representation pressure
```

```text
representation pressure
->
compression
+
preservation of consequential distinctions
```

```text
recurring regularities
->
finite reusable structures
with open-ended applicability
```

```text
abstract transformations
+
physically maintained organizations
->
repeated realizability
```

```text
physical change after every interaction
+
continued membership in a task-relative equivalence class
->
persistent admissibility
```

```text
persistent admissibility
+
path-grounded abstract edges
+
capability-relative queries
->
navigation through a world larger than the representation
```

---

## 18. Core Principles

### Principle 1: Boundedness creates representation pressure

An agent that cannot explicitly represent every relevant detail must compress.

### Principle 2: Successful interaction constrains compression

A compression is useful only if it preserves distinctions required for supported tasks.

### Principle 3: Formal structures are reusable regularity encodings

Functions, graphs, equations, constraints, and equivalence classes finitely represent behavior over open-ended classes of instances.

### Principle 4: Abstract reachability must be path-grounded

An abstract edge is admissible only when a lower-resolution path can witness it under stated conditions.

### Principle 5: Mathematical definition does not guarantee physical realization

A reusable function requires a physical organization engineered or evolved to realize the mapping predictably over admissible inputs.

### Principle 6: Physical reuse is not exact repetition

Every interaction changes the organization and its environment.

### Principle 7: Recovery means return to an admissible class

The post-interaction organization need not be identical; it must remain capable of the required future interactions.

### Principle 8: Persistence is continued capability

What persists operationally is not a complete state but a trajectory that remains within a task-relative equivalence class.

---

## 19. Open Questions

Several questions remain before this becomes a formal theory.

```text
How should organizations be individuated?
```

```text
How are direct edges selected at a chosen resolution?
```

```text
What constitutes an adequate path witness?
```

```text
How are equivalence classes induced from supported queries?
```

```text
How should approximation error and uncertainty be represented?
```

```text
How are degradation, maintenance, and recovery costs integrated?
```

```text
When does a recurring interaction justify introducing a reusable formal object?
```

```text
Can one derive families of mathematical structures from distinct representation pressures?
```

```text
Which aspects of math-like formalism are likely to converge across independently developed bounded agents?
```

```text
How can an AI expose the concrete paths hidden behind human conceptual shortcuts?
```

These are not objections to the framework.

They define a research program.

---

## 20. Design Target

The design target is a representation system in which:

```text
observations constrain models
```

```text
actions test models
```

```text
successful interaction selects useful distinctions
```

```text
formal structures compress recurring regularities
```

```text
abstract edges remain grounded in admissible paths
```

```text
physical functions are represented through reusable organizations
```

```text
reuse means persistent admissibility rather than exact reset
```

```text
identity is replaced by task-relative equivalence
```

```text
maintenance and recovery preserve future capability
```

The central claim is:

> A bounded agent navigating a world more detailed than it can explicitly represent is pressured to construct finite, reusable, math-like structures that preserve the distinctions required for successful interaction. These structures become physically useful only when realized by organizations that remain within the relevant admissibility classes across changing states and repeated interactions.

The world is not compressed because its details are unreal.

It is compressed because the agent is bounded.

The abstraction is not justified because it is convenient.

It is justified when it continues to support successful observation, prediction, action, recovery, and navigation.
