# Embedded Problem Solving, Virtual Infrastructure, and Sufficient Paths

## 1. Starting Point

Reality evolves continuously.

An embedded organization does not stand outside that evolution.

It participates in it, senses only part of it, acts through physically realized mechanisms, and must continue updating while the conditions of action change.

This yields a basic structure:

```text
evolving world
+
partial observation
+
bounded organization
+
goal or query
->
problem of finding a realizable path
```

The central question is not:

```text
What is the complete state of reality?
```

Nor is it:

```text
What is the globally optimal plan?
```

It is:

```text
Given the current observations,
the available organization,
the relevant constraints,
the acceptable costs,
and the time available,
what path is sufficiently realizable?
```

This is the problem of embedded problem solving.

---

## 2. Reality Changes Without Waiting for the Model

No physical organization interacts with a static world.

While a plan is being constructed:

```text
materials age
traffic moves
weather changes
agents act
signals propagate
resources are consumed
measurements become outdated
goals are revised
```

Therefore:

```text
model at time t
does not equal
world at time t + Δt
```

A model may still remain useful if the distinctions it preserves change slowly enough relative to the supported task.

The problem is not that reality changes.

The problem is whether reality changes faster than the model can remain sufficient.

---

## 3. Progress Is Not a Conserved Quantity

Physical theories contain conserved quantities under appropriate symmetries:

```text
energy
momentum
angular momentum
charge
```

Progress is different.

Progress depends on a selected objective.

Let:

\[
g
\]

denote a goal and:

\[
P_g(x)
\]

a measure of progress toward that goal from state \(x\).

Then:

\[
P_g
\]

is not a universal property of the world.

It is a goal-relative projection.

A transition may count as:

```text
progress toward one goal
regress toward another
irrelevant to a third
```

There is no universal conservation law of progress.

Progress may increase, decrease, oscillate, disappear when the goal changes, or become undefined when the relevant organization fails.

---

## 4. Partial Observability Is Structural

An embedded organization does not receive reality directly.

It receives physically mediated signals:

```text
photons
pressure
electrical measurements
chemical gradients
database entries
sensor readings
messages
memory traces
```

Observation is itself an interaction.

Therefore:

```text
world
->
measurement process
->
signal
->
internal state
```

The internal state is not the world.

It is a physically realized response to selected interactions with the world.

Partial observability is not merely a temporary lack of information.

It follows from physical embedding, finite interfaces, limited sensing, delayed signals, noise, and changing conditions.

---

## 5. Finite Awareness of an Evolving World

The combination is fundamental:

```text
the world changes continuously
+
the organization observes only finitely
```

This means that every internal model is both:

```text
incomplete
and
aging
```

A perfectly detailed observation of a small region does not provide the complete state of the world.

A complete model at one instant would still begin to age as soon as the world evolves.

Thus:

> Embedded problem solving is performed with incomplete descriptions of states that continue changing during observation, planning, and execution.

---

## 6. Why a Witness Is Needed

A description may specify:

```text
a goal
a task
a path
a capability
a prediction
a plan
```

But a description does not create the transition it describes.

A witness is a physically realizable chain showing how the selected claim can be satisfied.

For a task \(d\), a witness may be:

```text
initial state
->
control sequence
->
intermediate states
->
target region
```

The witness is not an ultimate source.

It is not a metaphysical origin.

It is a realizable path sufficient to ground the claim.

---

## 7. There Is No Mystical Source

What is called a source is often only an earlier organized stage in a longer chain.

For software:

```text
source text
->
parser
->
syntax tree
->
compiler
->
machine representation
->
processor transitions
```

The source code is not the source of execution in an absolute sense.

It is a selected input representation that participates in a transformation chain.

Likewise:

```text
blueprint
is not
building
```

```text
DNA
is not
organism
```

```text
plan
is not
trip
```

```text
map
is not
terrain
```

The useful question is not:

```text
Where is the ultimate source?
```

It is:

```text
Which physically realized transformation chain
connects this representation to the claimed outcome?
```

---

## 8. Inverse Problems and Boundedness Are Distinct

A target is usually specified at a level different from its physical realization.

For example:

```text
reach the destination
```

must become:

```text
select route
->
control vehicle
->
respond to traffic
->
follow traversable segments
->
arrive
```

This is an inverse problem.

The desired outcome is given.

The realizable mechanism must be found.

Even an unbounded reasoner cannot bypass the need for a physically realizable path.

Boundedness creates a second problem:

```text
the set of possible paths
cannot be searched exhaustively
```

Therefore:

```text
physical mediation
->
inverse problem
```

```text
bounded computation, sensing, memory, and time
->
need for selective search
```

---

## 9. A Third Source of Difficulty: Open Execution

Planning is not performed once in a closed world.

Execution exposes the organization to new information and new disturbances.

Therefore:

```text
plan
->
act
->
observe
->
update
->
act again
```

is more general than:

```text
plan once
->
execute
->
done
```

The need for revision is not caused only by poor planning.

It follows from:

```text
partial observability
world evolution
other agents
noise
model error
resource variation
implementation drift
```

A plan is therefore better understood as a revisable policy than as a complete script.

---

## 10. Waterfall and Agile as Special Cases

The contrast between waterfall and agile development reflects a general distinction.

Waterfall approximates:

```text
specify
->
plan
->
construct
->
deliver
```

This works best when:

```text
requirements are stable
dependencies are understood
feedback is slow or expensive
variation is limited
```

Agile approximates:

```text
observe
->
construct a small increment
->
test
->
receive feedback
->
revise
```

This works better when:

```text
requirements evolve
models are incomplete
feedback is available
uncertainty is high
```

Neither is universally correct.

Each assumes a different rate of environmental change, observation quality, and revision cost.

---

## 11. Plans as Policies

A fixed plan is a sequence:

\[
a_0,a_1,\dots,a_T
\]

A policy is a mapping:

\[
\pi(o_t,m_t)\rightarrow a_t
\]

where:

\[
o_t
\]

is the current observation and:

\[
m_t
\]

is the current maintained model or memory state.

The policy can adapt actions to new observations.

Thus:

```text
plan
=
preselected action sequence
```

```text
policy
=
implemented rule for choosing actions during execution
```

In evolving and partially observed environments, policies are usually more robust than fixed plans.

---

## 12. Virtual Forces

Some planning methods construct virtual structures that guide motion.

Artificial potential fields define:

```text
goal attraction
+
obstacle repulsion
->
virtual force
```

A robot then follows the resulting direction.

The force is not physically present in the environment.

It is a computational organization used to generate a realizable control path.

This can simplify planning, but it can also fail.

For example:

```text
competing virtual forces
->
local minimum
->
no path to goal
```

Virtual forces are therefore useful intermediate structures, not guarantees of global success.

---

## 13. Virtual Roads

A more explicit strategy is to construct a graph through a continuous space.

The graph contains:

```text
nodes
=
sampled admissible states
```

```text
edges
=
locally realizable transitions
```

This produces a virtual road network.

The planner then solves:

```text
continuous inverse problem
->
graph construction
->
graph search
->
realizable path
```

The graph is not the world.

It is an intermediate organization preserving enough connectivity to support the query.

---

## 14. Probabilistic Roadmaps

A probabilistic roadmap samples valid configurations before a specific path is requested.

The general procedure is:

```text
sample admissible configurations
->
connect nearby configurations
when local motion is realizable
->
store graph
```

Later:

```text
new start and goal
->
connect them to the graph
->
search graph
->
recover continuous path
```

The expensive construction can be reused across many queries.

Thus a probabilistic roadmap is not merely a representation.

It is reusable virtual infrastructure.

---

## 15. Rapidly Exploring Random Trees

A rapidly exploring random tree grows during the search.

It begins at a start state.

Then:

```text
sample a state
->
find nearest existing node
->
extend toward sample
->
add new node and edge
```

Repeated extension causes the tree to spread through reachable free space.

When the tree approaches the target, a path can be extracted.

Unlike a precomputed roadmap:

```text
RRT
constructs virtual roads on demand
```

The resulting tree is usually temporary and query-specific.

---

## 16. Constructing Roads on Demand

The literal pattern is:

```text
problem appears
->
construct an intermediate network
->
search that network
->
extract a sufficient path
```

The virtual roads do not need to include every physically possible transition.

They need only preserve enough reachability to support the current task.

This suggests:

> A solver may first construct the space in which the problem becomes easy, then solve the transformed problem inside that space.

---

## 17. Sufficient Paths

An embedded organization rarely needs the globally optimal path.

It needs a path that satisfies constraints within acceptable cost.

Let:

\[
\gamma
\]

be a candidate trajectory.

A sufficient path may satisfy:

\[
\operatorname{Success}(\gamma)\geq \alpha
\]

\[
\operatorname{Cost}(\gamma)\leq B
\]

\[
\operatorname{Risk}(\gamma)\leq \rho
\]

\[
\operatorname{Time}(\gamma)\leq \tau
\]

The exact optimum may be unavailable, unknowable, or too expensive to compute.

A minimally sufficient path is therefore not necessarily the shortest path.

It is a path inside an acceptable region of success, cost, risk, and time.

---

## 18. Optimality Is Also Query-Relative

A route may be optimal for:

```text
shortest distance
```

but not for:

```text
lowest travel time
lowest fuel consumption
lowest risk
fewest transfers
highest accessibility
lowest uncertainty
```

Thus:

\[
\gamma^\ast
=
\arg\min_{\gamma} J(\gamma)
\]

depends on the objective \(J\).

When several objectives matter:

\[
J(\gamma)
=
w_1T(\gamma)
+
w_2C(\gamma)
+
w_3R(\gamma)
+
w_4U(\gamma)
\]

where:

```text
T = time
C = cost
R = risk
U = uncertainty
```

There is no unique optimal path without a selected objective and weighting.

---

## 19. Google Maps as Reusable Inverse-Problem Infrastructure

The travel problem is:

```text
current location
+
destination
->
physically realizable trip
```

The full physical transition space includes many possibilities:

```text
walking
driving
cycling
rail
bus
boat
aircraft
private aircraft
helicopter
off-road movement
construction of new infrastructure
```

A navigation service restricts the space.

It constructs a graph over common and supported methods.

This deliberate omission makes the problem tractable and reusable.

The system solves not:

```text
all physically possible travel
```

but:

```text
supported travel under selected transport modes,
legal constraints,
known infrastructure,
and available data
```

Its usefulness comes from narrowing the inverse problem enough to solve it repeatedly for millions of users.

---

## 20. Search Engines as Virtual Roads Through Documents

A search engine faces:

```text
information need
->
relevant documents
```

Searching all documents from scratch for every query would be too expensive.

Instead it constructs:

```text
indexes
embeddings
link graphs
term statistics
cached summaries
ranking models
```

These are virtual roads through document space.

Then:

```text
query
->
small candidate region
->
ranking
->
results
```

The index does not preserve every property of every document.

It preserves enough structure to support common retrieval queries.

---

## 21. Libraries as Virtual Roads Through Implementation Space

A programming library compresses many implementation paths into reusable interfaces.

Without a library:

```text
goal
->
design low-level mechanism
->
implement
->
test
```

With a library:

```text
goal
->
select known interface
->
compose
->
adapt
```

The library is virtual infrastructure through implementation space.

It does not solve every possible problem.

It makes a supported family of problems cheaper.

---

## 22. Scientific Theories as Virtual Roads Through Explanation Space

A theory provides reusable transformations:

```text
observations
->
state variables
->
equations
->
predictions
```

It does not enumerate every possible explanation.

It organizes recurring regularities into a path through reasoning space.

A useful theory reduces the cost of moving from:

```text
question
```

to:

```text
prediction, explanation, or intervention
```

Its equations are often short because they reuse previously constructed mathematical infrastructure.

---

## 23. Short Equations Hide Large Organizations

An equation may be compact because it composes many reusable building blocks.

For example:

\[
i\hbar\frac{\partial\psi}{\partial t}
=
\hat H\psi
\]

is short, but:

```text
ψ
contains a state over a selected space
```

```text
H
contains the implemented dynamics
```

```text
the notation assumes
complex numbers, operators, derivatives, boundary conditions,
measurement rules, and physical constants
```

Compactness is often achieved by packaging repeated structure into named objects.

The equation is short because the surrounding conceptual infrastructure is large.

---

## 24. Edge Cases and Simplified Regimes

A general problem may become simple when some variables enter limiting regimes.

Examples include:

```text
small perturbation
->
linear approximation
```

```text
low velocity relative to c
->
Newtonian approximation
```

```text
negligible interaction
->
independent-component approximation
```

```text
large data limit
->
asymptotic behavior
```

```text
short horizon
->
local planning
```

A framework should therefore distinguish:

```text
general construction
```

from:

```text
special regimes where many variables can be ignored,
combined, or approximated
```

The existence of many variables does not imply every problem requires all of them explicitly.

---

## 25. Search as Selective Road Construction

Search is not always traversal through a preexisting map.

It can also create the map while proceeding.

Examples include:

```text
tree search
beam search
Monte Carlo tree search
RRT
hypothesis generation
iterative theorem proving
```

The common structure is:

```text
expand a small region
->
evaluate
->
retain promising structure
->
expand again
```

Search builds virtual roads selectively.

It spends resources only where future paths appear useful.

---

## 26. AI Chatbots as Reusable Intermediate Organizations

A language model does not search all text at inference time.

Training constructs a reusable parameter organization.

This organization preserves many statistical and structural regularities.

Then:

```text
prompt
->
internal state transitions
->
candidate continuation
```

The model is not omniscient.

It does not contain explicit optimal paths for all queries.

It provides low-cost access to many sufficiently useful paths through language and concept space.

Its outputs remain conditioned by:

```text
training distribution
context
available tools
sampling
model capacity
current prompt
```

---

## 27. AI Systems as Road Builders and Road Users

An AI system may use both:

```text
preconstructed virtual infrastructure
```

and:

```text
roads built on demand
```

Preconstructed infrastructure includes:

```text
model weights
indexes
retrieval databases
tools
code libraries
ontologies
```

On-demand infrastructure includes:

```text
temporary plans
search trees
scratch representations
generated code
subgoals
tool-call sequences
```

Thus an AI system can be understood as both:

```text
a user of existing virtual roads
and
a builder of temporary roads for the current query
```

---

## 28. Minimal Sufficiency Under Cost

A solver does not need omniscient intermediate steps.

It needs intermediate states that preserve enough information to continue successfully.

Let:

\[
z_t
\]

be an intermediate representation.

It is sufficient for a task family \(Q\) when:

```text
the distinctions retained in z_t
are enough to select acceptable next actions
for supported queries
```

The representation may omit enormous amounts of information.

Its value depends on:

\[
\text{task performance}
-
\text{construction cost}
-
\text{maintenance cost}
-
\text{query cost}
\]

This yields a general objective:

\[
V(R)
=
\mathbb E[\text{utility from supported queries}]
-
\lambda_1\operatorname{BuildCost}(R)
-
\lambda_2\operatorname{MaintainCost}(R)
-
\lambda_3\operatorname{UseCost}(R)
\]

A representation is useful when the saved future effort exceeds its construction and maintenance cost.

---

## 29. Representations as Virtual Infrastructure

A representation can be viewed in two complementary ways.

### Quotient view

It groups physically distinct states when their differences do not matter for supported queries.

```text
many states
->
one task-relevant class
```

### Infrastructure view

It creates reusable routes through a difficult search space.

```text
many possible transitions
->
selected reusable pathways
```

The quotient view emphasizes omission.

The infrastructure view emphasizes traversal.

Together:

> A representation suppresses irrelevant distinctions while constructing reusable paths among the distinctions that remain.

---

## 30. Maps Need Not Be Passive

A map can do more than describe.

It can shape future action.

Examples:

```text
road graph
->
route selection
```

```text
index
->
document retrieval
```

```text
library API
->
implementation composition
```

```text
scientific model
->
experimental design
```

```text
social norm
->
coordination
```

A maintained representation becomes part of the causal organization that generates future transitions.

It is not only a picture of the world.

It is infrastructure inside the world.

---

## 31. Reuse Changes the Economics of Problem Solving

Suppose a single inverse problem costs:

\[
C_{\text{raw}}
\]

to solve from first principles.

A reusable representation costs:

\[
C_{\text{build}}
\]

to construct and:

\[
C_{\text{query}}
\]

per later use.

After \(N\) uses, reuse is beneficial when:

\[
C_{\text{build}} + NC_{\text{query}}
<
NC_{\text{raw}}
\]

Therefore repeated inverse problems create pressure for reusable structure.

The more often the query family recurs, the more valuable infrastructure becomes.

---

## 32. Virtual Roads Can Become Physical Roads

Virtual infrastructure may later guide physical construction.

For example:

```text
predicted traffic pattern
->
road design
->
physical road
```

```text
simulated circuit
->
fabricated processor
```

```text
architectural model
->
building
```

```text
planned workflow
->
institutional process
```

The virtual road begins as a representation.

It may later reorganize physical transition space itself.

Thus representations do not merely navigate existing possibilities.

They can help construct new possibilities.

---

## 33. Physical Roads Are Also Representations

A physical road is not only a material path.

It is also a persistent organization that compresses future motion planning.

Without a road:

```text
each traveler
must solve terrain traversal locally
```

With a road:

```text
many travelers
reuse a stabilized path
```

The road embodies prior search, engineering, labor, legal coordination, and maintenance.

It is physical infrastructure and externalized memory.

---

## 34. Institutions as Shared Roadmaps

Institutions construct repeatable pathways through social and organizational space.

Examples include:

```text
legal procedures
educational curricula
supply chains
scientific peer review
financial settlement
medical protocols
```

They reduce repeated inverse problems by specifying:

```text
roles
interfaces
allowed transitions
verification steps
recovery procedures
```

Institutions are therefore socially distributed virtual and physical road systems.

They make coordinated action cheaper, but may also exclude paths they were not built to support.

---

## 35. Failure Modes of Virtual Infrastructure

Virtual roads can fail when:

```text
the world changes
the model is incomplete
the query changes
the cost function changes
the environment leaves the sampled region
the graph disconnects
the representation suppresses a now-relevant distinction
```

Examples include:

```text
road closure
->
route graph stale
```

```text
new terminology
->
search index weak
```

```text
novel prompt
->
model distribution shift
```

```text
unexpected obstacle
->
planned trajectory invalid
```

Maintenance is therefore not optional.

Virtual infrastructure must be revised when its preserved distinctions no longer support successful traversal.

---

## 36. Recovery as Road Reconstruction

When a path fails, the organization may:

```text
repair the existing path
construct a detour
switch maps
change transport mode
relax the goal
acquire new resources
```

Recovery is therefore another inverse problem.

A recovery witness is:

```text
failure detection
->
state re-estimation
->
new road construction or selection
->
return to an acceptable region
```

Robust systems do not merely have one path.

They have ways to construct alternatives when the current path becomes unusable.

---

## 37. A Minimal Formalization

Let:

\[
X
\]

be a physical state space,

\[
F
\]

a transition relation or dynamics,

\[
O_t
\]

the current organization,

\[
y_t
\]

the current observation,

\[
m_t
\]

the maintained internal model,

\[
g
\]

a goal or query,

and:

\[
\pi
\]

a policy.

The organization evolves through:

\[
x_{t+1}\sim F(x_t,a_t,e_t)
\]

with:

\[
y_t\sim H(x_t)
\]

and:

\[
a_t=\pi(y_t,m_t,g)
\]

while the maintained model updates through:

\[
m_{t+1}=U(m_t,y_t,a_t)
\]

A witness trajectory for goal \(g\) is:

\[
\gamma
=
(x_0,a_0,x_1,a_1,\dots,x_T)
\]

such that:

\[
x_T\in G_g
\]

within specified cost, risk, and time constraints.

---

## 38. Virtual Infrastructure as a Graph

A virtual infrastructure can be represented as:

\[
R=(V,E)
\]

where:

```text
V
=
selected states, abstractions, concepts, or configurations
```

```text
E
=
admissible or useful transitions among them
```

A query adds:

\[
s,g\in V
\]

or connects a new start and goal to the graph.

The solver then searches for:

\[
\gamma_R:s\rightsquigarrow g
\]

The graph is sufficient when a path in \(R\) can be transformed into a physically realizable witness with acceptable cost.

---

## 39. Sufficient Rather Than Complete Representations

A representation \(R\) need not preserve the entire state space.

It needs to preserve the distinctions required by the supported query family \(Q\).

Let:

\[
\Phi_R:X\rightarrow Z
\]

map physical states to represented states.

Then \(R\) is sufficient for \(Q\) when:

\[
\operatorname{Loss}_Q(\Phi_R)\leq\varepsilon
\]

for the supported interactions.

This allows:

```text
many physical differences
to be ignored
```

provided they do not destroy acceptable path construction for \(Q\).

---

## 40. The Core Construction

The framework can be summarized as:

```text
reality evolves
->
models age
```

```text
organizations are embedded
->
observation is partial and mediated
```

```text
goals specify outcomes
->
inverse problems arise
```

```text
bounded resources
->
exhaustive search is unavailable
```

```text
open execution
->
plans must remain revisable
```

```text
repeated inverse problems
->
pressure for reusable intermediate structure
```

```text
reusable intermediate structure
->
virtual roads
```

```text
virtual roads
+
search
->
sufficient paths
```

```text
sufficient paths
+
physical execution
->
witness trajectories
```

```text
world change
->
maintenance, replanning, and road reconstruction
```

---

## 41. Core Principles

### Principle 1: Reality evolves continuously

No model remains current merely by existing.

### Principle 2: Progress is goal-relative

It is not a universal conserved quantity.

### Principle 3: Embedded observation is partial

An organization encounters the world through finite physical interfaces.

### Principle 4: A witness is a realizable path

It grounds a claim without pretending to reveal an ultimate source.

### Principle 5: Inverse problems arise from mediated realization

Desired outcomes do not directly specify physical mechanisms.

### Principle 6: Boundedness prevents exhaustive search

Finite organizations must select, compress, and reuse.

### Principle 7: Open execution requires revision

Plans are exposed to new information and changing conditions.

### Principle 8: Policies are more general than fixed plans

They condition action on ongoing observation.

### Principle 9: Virtual forces and virtual roads are constructed guides

They simplify otherwise difficult transition spaces.

### Principle 10: Roadmaps are reusable infrastructure

They convert continuous planning into graph search.

### Principle 11: Some roads are built on demand

Search may construct the space it later traverses.

### Principle 12: A sufficient path need not be globally optimal

It must satisfy the relevant cost, risk, time, and success constraints.

### Principle 13: Representations are both quotients and infrastructure

They suppress irrelevant differences and create reusable routes.

### Principle 14: Search engines, maps, libraries, and models share a structure

Each builds intermediate organization for repeated inverse problems.

### Principle 15: AI systems use and construct virtual roads

They combine learned structure with temporary query-specific paths.

### Principle 16: Reuse changes problem-solving economics

Infrastructure is valuable when its future savings exceed its construction and maintenance cost.

### Principle 17: Virtual infrastructure can reshape physical possibility

Representations may guide construction of new physical paths and organizations.

### Principle 18: Maintenance preserves traversability

A representation remains useful only while its roads correspond sufficiently to realizable transitions.

---

## 42. Open Questions

```text
How should one measure the value of a virtual road
across a changing distribution of future queries?
```

```text
When should a solver reuse an existing roadmap
and when should it construct a new one?
```

```text
How can a system detect that its representation
has suppressed a distinction that has become important?
```

```text
What is the minimal sufficient model
for a selected family of inverse problems?
```

```text
How should search cost, execution cost,
observation cost, and maintenance cost be balanced?
```

```text
When should a plan remain fixed,
and when should it become a revisable policy?
```

```text
How can virtual roads remain grounded
when the physical environment changes faster than the map?
```

```text
What distinguishes useful infrastructure
from rigid structure that blocks better paths?
```

```text
How do institutions preserve, revise,
or monopolize socially important roads?
```

```text
Can a general theory of intelligence be formulated
as the construction, reuse, and repair
of sufficient virtual infrastructure?
```

---

## 43. Design Target

The design target is a framework in which:

```text
constant world evolution is explicit
```

```text
partial observability is structural
rather than treated as an accident
```

```text
inverse problems are separated from bounded search
```

```text
plans are treated as revisable policies
when execution remains open
```

```text
virtual forces and roadmaps are understood
as intermediate organizations
```

```text
search can construct the space it later traverses
```

```text
representations are evaluated by
future problem-solving value relative to cost
```

```text
sufficient paths replace impossible demands
for omniscient optimality
```

```text
maps, indexes, models, libraries, institutions,
and AI systems are analyzed under a shared structure
```

```text
virtual infrastructure remains grounded
through transformable witness trajectories
```

The central claim is:

> Embedded organizations solve problems inside a world that continues changing while they observe, plan, and act. Because observations are partial, desired outcomes are not primitive physical transitions, and exhaustive search is unavailable, problem solving depends on constructing and reusing intermediate organizations. These organizations act as virtual infrastructure: they suppress irrelevant distinctions, preserve useful connectivity, and create roads through otherwise enormous spaces of possible transitions. Some roads are precomputed, some are built on demand, and none needs to represent every physically possible path. A solution is sufficient when a represented path can be transformed into a realizable witness within acceptable cost, risk, time, and tolerance. Intelligence, planning, search, maps, libraries, institutions, and learned models can all be understood as ways of building, selecting, traversing, maintaining, and repairing such roads.

The world does not pause for the map.

The map does not contain the world.

The plan does not command execution.

The road does not guarantee arrival.

What matters is whether the maintained organization can continue constructing sufficiently grounded paths through an evolving and only partially observed reality.
