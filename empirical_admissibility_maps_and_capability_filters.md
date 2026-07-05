# Empirical Admissibility Maps and Capability Filters

## 1. Starting Point

An admissibility map should not begin by inventing categories and forcing reality into them.

It should begin from realized organizations and observed interactions.

The intended analogy is again close to a navigation system:

```text
realized territory
->
observed paths, blocks, surfaces, constraints
->
map representation
->
navigation queries
```

A map does not create the territory.

It also does not need to enumerate every microscopic detail of the territory.

It records enough stable structure for bounded agents to ask useful questions:

```text
What is represented?
What is reachable?
What is locally enabled?
What is blocked?
Which distinctions change admissibility?
Which capabilities expose new paths?
Which interactions transform the map?
```

Thus the framework should be read as an empirical abstraction method.

It is not:

```text
name everything
->
declare everything connected
```

It is closer to:

```text
observe realizations
->
observe interactions
->
identify distinctions that matter
->
form equivalence classes
->
map admissible transitions
->
query reachability
```

## 2. Empty Map State

There can be a map schema before any territory has been loaded into it.

```text
map structure exists

nodes = {}
edges = {}
attributes = {}
constraints = {}
observations = {}
```

This is not an empty reality.

It is an empty representation.

```text
empty map
!=
empty world
```

A road, cafe, bridge, molecule, instrument, compiler, or organism may already be realized even if the map has no representation of it.

Before ingestion:

```text
territory exists
representation does not yet contain it
```

After ingestion:

```text
observation
->
representation update
->
new queryable structure
```

This state zero can reappear locally at any time.

A new city may be unmapped.

A private industrial site may be absent.

A newly installed dependency may not yet be recorded.

A biological interaction may exist before it has been experimentally characterized.

The map begins empty relative to that region of realization.

## 3. Realization, Representation, And Verification

The framework should keep three things separate:

```text
realized
represented
verified
```

A realized organization may not yet be represented.

A represented organization may not yet be verified.

A verified organization may later change, decay, move, fail, or become unavailable.

Thus:

```text
realized
!=
represented
```

and:

```text
represented
!=
verified
```

For example:

```text
map says road exists
->
agent arrives
->
road is blocked
->
map corrected
```

or:

```text
documentation says program compiles
->
local environment lacks dependency
->
transition not locally enabled
->
map refined
```

The representation remains answerable to the realized world.

```text
realization constrains
->
observation populates
->
queries expose gaps
->
interaction tests
->
map corrected
```

## 4. Organizations And Interactions

The basic grammar can still be written:

```text
organization
->
interaction
->
organization
```

But this should not be read as a claim that arbitrary labels are valid organizations or arbitrary arrows are valid interactions.

An organization is admitted into the map only where there is enough realized structure to support relevant interaction claims.

An interaction is admitted only where a realized transition class can be observed, measured, inferred, or operationally tested.

More generally:

```text
organizations
+
admitted interaction
->
organizations
```

Many interactions involve several participants.

For example:

```text
person
+
closed door
->
opening interaction
->
person
+
open door
```

or:

```text
source code
+
compiler
+
dependencies
+
target configuration
->
compilation
->
compiled artifact
+
compiler
```

The interaction transforms the relevant organization of the situation.

It does not require every participant to disappear and be replaced.

## 5. Transition Classes

The map should not enumerate every concrete event.

It should construct transition classes.

Google Maps does not store:

```text
Alice drives her blue car through segment R at 14:32
Bob drives his red car through segment R at 14:35
Carla drives her white van through segment R at 14:37
```

as unrelated primitives.

It records a reusable transition class such as:

```text
vehicle-like organization
+
road segment R
+
required local conditions
->
traversal admitted
```

Likewise, a compiler does not enumerate every possible program as a separate metaphysical case.

It represents something closer to:

```text
well-formed source program
+
language rules
+
compiler version
+
dependency set
+
target platform
->
compiled artifact
```

The transition class compresses many concrete cases while preserving the distinctions needed to accept or reject the transformation.

## 6. Equivalence Classes

The map also should not preserve every difference between organizations.

It should preserve differences that change admissibility, capability, measurement, or reachability.

Everything else can be quotiented away relative to the map's purpose.

```text
A ~ B

when replacing A with B
does not change the relevant
admissibility, measurement, or reachability queries
```

This equivalence is not absolute.

It is map-relative and query-relative.

Two vehicles may be equivalent for one road because both fit the lane, satisfy the weight limit, and can follow the turn geometry.

The same two vehicles may stop being equivalent at a low bridge, narrow gate, ferry ramp, charging station, legal boundary, or weight-restricted bridge.

```text
equivalent here
!=
equivalent everywhere
```

The map therefore preserves distinctions only when those distinctions force different continuations.

## 7. Distinctions Are Forced By Admissibility

Categories should not be treated as fixed starting points.

The useful categories emerge from the constraints and interaction surfaces that matter.

Instead of:

```text
road admits cars
road rejects pedestrians
```

the map should ask:

```text
which organizations can participate
in the relevant traversal interaction
under the local constraints?
```

The answer may depend on:

```text
maximum axle load
maximum gross weight
height
width
length
turning radius
turning swept path
surface compatibility
friction
ground clearance
energy source
legal authorization
directionality
time window
weather
visibility
operator capability
```

If only gross weight matters, many different vehicles may be equivalent.

If height matters, the class splits.

If turning geometry matters, the class splits again.

If legal authorization matters, two physically identical organizations may receive different admissibility marks.

Thus:

```text
constraint appears
->
distinction becomes relevant
->
equivalence class splits
```

The map is not taxonomy-driven.

It is admissibility-driven.

## 8. Open Classes

An admissible class need not be closed by enumeration.

A bicycle lane is not best understood as:

```text
admits exactly:
  bicycle model A
  bicycle model B
  bicycle model C
```

It is closer to:

```text
admits organizations
whose traversal interaction
satisfies the relevant local constraints
```

Those organizations may include:

```text
bicycles
e-bikes
cargo bikes
adaptive cycles
some scooters
future vehicle forms
```

depending on the local physical, legal, and operational constraints.

A new organization does not need a new category if it behaves equivalently with respect to all relevant queries.

It does need a new distinction if it changes admissibility.

```text
new realization
->
same admissibility behavior
->
absorbed into existing class
```

or:

```text
new realization
->
different admissibility behavior
->
class split or new class introduced
```

This keeps the map extensible without making it arbitrary.

## 9. Interaction Surfaces And Conditions

An organization does not interact with everything in every way.

It interacts through realized surfaces.

```text
organization
->
interaction surface
->
admissibility conditions
->
interaction
->
changed organization or changed reachability
```

For a road, relevant surfaces and conditions may include pavement, lane width, bridge structure, signs, signals, grade, intersections, and legal rules.

For a cell, relevant surfaces and conditions may include membranes, receptors, transport proteins, gradients, available energy, molecular shape, charge, and binding affinity.

For an atom, relevant conditions may include energy levels, angular momentum, charge, spin, field configuration, and selection rules.

The map should not say:

```text
cell admits molecule because the label says so
```

It should say:

```text
molecule
+
cellular interaction surface
+
local biochemical conditions
->
transport, binding, reaction, rejection, or no interaction
```

The same organization can expose different surfaces for different interaction classes.

For a human:

```text
eye
->
optical interaction

ear
->
acoustic interaction

skin
->
mechanical and thermal interaction

lungs
->
gas exchange

digestive tract
->
chemical processing

hand
->
grasping and manipulation
```

Each surface has its own admissible ranges.

## 10. Capability Filters

An admissibility map can be filtered by the capabilities of the observing or acting organization.

This is analogous to a map layer, but more general.

For example:

```text
visible with unaided human eye
```

is a capability filter.

Under that filter, some represented organizations remain directly available:

```text
building
road sign
printed text at readable distance
traffic signal
chair
door
```

Others may be present in the map but unavailable to that capability:

```text
infrared signal
ultraviolet marking
Wi-Fi field
magnetic field
airborne chemical trace
microscopic organism
subsurface cable
```

The map should therefore distinguish:

```text
represented but inaccessible through this capability
```

from:

```text
not represented in the map
```

These are different failures.

In the first case, the organization is in the map, but the current capability filter hides or disables direct interaction.

In the second case, the map has no loaded representation to query.

## 11. Grayed Out Does Not Mean Nonexistent

When a capability filter is applied, parts of the map may be grayed out.

This should not mean:

```text
does not exist
```

It should mean:

```text
not directly observable, reachable, measurable, or manipulable
through the selected capability set
```

For example:

```text
infrared emitter

human unaided vision:
  unavailable

infrared camera:
  available

infrared camera + display:
  available to human visual system
```

Nothing about the emitter changed.

The represented accessibility changed because the acting organization changed.

```text
human
+
infrared camera
+
display
->
new mediated observation surface
->
infrared signal becomes visually queryable
```

The map therefore tracks not only what is realized, but what is available to whom, through which mediating organization, under which conditions.

## 12. Capability Changes As Map Transformations

Adding a tool can change reachable continuations without changing the underlying territory.

```text
human
+
microscope
->
new observation capability
```

```text
human
+
vehicle
->
new traversal capability
```

```text
programmer
+
installed compiler
->
new build capability
```

```text
cell
+
expressed receptor
->
new binding or signaling capability
```

In each case:

```text
same surrounding realization
+
changed capability set
->
changed admissibility map for that organization
```

The world need not be remade for the map to change.

It is enough that the acting organization gains or loses an interaction surface.

## 13. Domain Examples

A road segment admits traversal only for organizations whose relevant properties satisfy the local traversal constraints.

```text
vehicle-like organization
+
road segment
+
height, width, load, turn, law, time, weather
->
traversal admitted or rejected
```

A cafe admits service only under certain organizational conditions.

```text
visitor
+
cafe
+
opening hours
+
staff availability
+
payment method
+
legal and practical constraints
->
service interaction
```

A cell admits some molecular interactions and rejects others.

```text
molecule
+
cell surface
+
receptor state
+
gradient
+
energy availability
->
transport, binding, signaling, metabolism, or rejection
```

An atom admits only constrained transitions.

```text
atom
+
incoming photon or field
+
energy and selection conditions
->
absorption, emission, scattering, or no transition
```

A software project admits a build only under specified local conditions.

```text
source tree
+
compiler
+
dependencies
+
environment
+
target
->
build artifact or rejection
```

These are different domains.

They share a navigation grammar.

They do not share the same physical constraints.

```text
shared query form
!=
erased domain structure
```

## 14. Map Construction Loop

An empirical admissibility map is built and maintained through a loop.

```text
realized world
->
observation
->
representation
->
equivalence classes
->
transition classes
->
capability filters
->
navigation queries
->
interaction tests
->
correction
->
updated representation
```

The loop matters because the map is never complete.

It is always bounded.

It can still be useful if it preserves the distinctions needed for action, repair, recovery, and reuse.

The map fails locally when:

```text
required organization is missing
required condition is absent
relevant distinction was quotiented away
represented edge is false
capability filter is wrong
local environment differs
measurement cannot distinguish success
claimed transition has no realized path
```

Those failures are not merely philosophical objections.

They are maintenance signals.

## 15. Query Pattern

A practical map should support questions such as:

```text
1. What realized organization is being represented?
2. Which observation or evidence populated this part of the map?
3. Which interaction surface is involved?
4. Which capability set is being used?
5. Which admissibility conditions bind the interaction?
6. Which distinctions are preserved by the map?
7. Which distinctions have been quotiented away?
8. Which equivalence class is being used?
9. Which transition class is being claimed?
10. What local conditions must hold now?
11. What result should be measurable?
12. What changes in future reachability?
13. What is represented but inaccessible under this filter?
14. What is absent from the map entirely?
15. What correction follows if the transition fails?
```

This makes categories secondary.

The primary question is not:

```text
What is this called?
```

but:

```text
What interactions does it admit?
Under which conditions?
For which organizations?
Through which capabilities?
With which measurable consequences?
```

## 16. Design Target

The design target can be summarized as:

```text
empirical admissibility map
with capability-filtered views
```

Such a map should be:

```text
empirical enough to be corrected
abstract enough to compress
specific enough to reject invalid paths
open enough to absorb new realizations
bounded enough to navigate
capability-aware enough to explain inaccessible regions
```

Its categories are not arbitrary labels.

They are maintained equivalence classes induced by observed admissibility, interaction surfaces, local constraints, measurements, and reachability.

The core principle is:

```text
preserve distinctions that change admissibility,
capability, measurement, recovery, or reachability

quotient away distinctions that do not
matter for the supported navigation queries
```

This is why the map can be general without becoming empty.

It does not claim that everything is directly connected to everything else.

It asks which realized interactions connect which organizations through which admissible paths.

```text
organization
->
admitted interaction
->
organization
->
changed reachability
```

The map is useful when it helps a bounded organization see which parts of the realized world are available, which are inaccessible under current capabilities, which are absent from the representation, and which paths can be built, repaired, or reused.
