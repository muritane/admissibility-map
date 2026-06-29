# Admissibility Map for Realized Organization

## 1. Starting Point

The framework does not attempt to instantiate reality.

Reality is already the implementation.

The framework defines a map interface for what reality appears to admit.

The central question is not:

```text
Can this be imagined?
```

but:

```text
Is this mapped as admissible?
What transition schema produces it?
What conditions enable that transition?
What measurable properties distinguish the produced instance?
What organizations can reuse it?
```

This gives a stricter attention rule:

```text
no admissible edge
=>
no accepted claim of reachability
```

A proposed object, organization, process, or role is not accepted merely because it can be named.

It must be placed on the map by showing a real transition schema, measurable property domain, constraint condition, or realization path.

Compactly:

```text
reality
=
implementation

framework
=
map of admissible organizational schemas and transitions
```

## 2. Map, Not Engine

The API does not create atoms, photons, organisms, computers, or civilizations.

It maps claims about them.

The map contains:

```text
organizational schemas
property domains
transition schemas
measurement capabilities
local enablement conditions
realization paths
```

It does not contain arbitrary fantasy instances.

The map is closer to Google Maps than to a game engine.

Google Maps does not create roads.

It records usable paths, constraints, locations, and routes.

Likewise, the admissibility map does not create reality.

It records known organizational states, admissible transformations, constraints, and routes through realizable space.

## 3. Nodes Are Cheap, Edges Are Expensive

A node is a reusable label or schema.

Examples:

```text
Photon
CarbonAtom
Cs133Atom
HumanAuditorySystem
SchoolBalance
KibbleBalance
MassSpectrometer
```

But labels alone are weak.

A node without admissible edges is only a named claim.

```text
node without incoming edge
=
not known producible

node without outgoing edge
=
terminal, inert, isolated, or unmapped

node without any edge
=
unsupported label
```

The edge carries the burden.

An edge is not merely:

```text
source -> target
```

Most real transitions are multi-input, multi-output, condition-sensitive processes.

So the edge is better understood as:

```text
input schemas
+
property constraints
+
local conditions
+
process relation
->
output schemas
+
changed properties
+
byproducts
```

Compactly:

```text
{inputs}
--[constraints satisfied under local conditions]-->
{outputs}
```

## 4. Transition Schemas

A transition schema describes a family of realizable transitions.

It is not one historical event.

It is a reusable map edge that can be instantiated by many concrete events.

Example:

```text
ExcitedAtom
->
LowerEnergyAtom + Photon
```

But this is incomplete.

The photon is not arbitrary.

Its frequency is constrained by the energy gap:

```text
photon.frequency ~= DeltaE / h
```

A more faithful schema is:

```text
Atom(species = X, state = excited_i)
--[allowed radiative transition i -> j]-->
Atom(species = X, state = lower_j)
+
Photon(frequency ~= (E_i - E_j) / h)
```

This means:

```text
not every atom emits arbitrary photons
not every photon is absorbable by every atom
not every named transition is enabled under local conditions
```

The map must record the admissible regions, not merely the names.

## 5. Schemas, Property Spaces, and Realized Instances

The map should not contain every individual instance.

It should contain schemas and property domains.

A realized instance is a point or region inside a schema's admissible property space.

Example:

```text
Photon
```

is a schema.

Its property domain includes:

```text
frequency > 0
energy = h * frequency
momentum = energy / c
polarization in admissible polarization states
```

A particular photon is an instance:

```text
Photon(frequency = 9,192,631,770 Hz)
```

Similarly:

```text
HumanAuditorySystem
```

is a schema with property domains such as:

```text
hearing frequency range
sound pressure sensitivity
local noise tolerance
neural response time
```

A particular human auditory system is an instance with particular ranges and thresholds.

Thus:

```text
schema
->
property domain
->
realized instance
```

The map stores the schema and admissible property domain.

Reality supplies instances.

## 6. Nodes as Equivalence Classes

A node is not usually a concrete object.

It is an equivalence class or organizational schema under some chosen abstraction.

For example:

```text
CarbonAtom
```

does not mean one specific carbon atom.

It means the class of realized organizations satisfying the carbon-atom schema.

Likewise:

```text
Photon
```

does not mean one photon.

It means the class of photon instances satisfying the photon schema.

The abstraction is useful only when the class is reliable enough to support reusable reasoning.

```text
higher organizations can reuse a schema
iff
instances of that schema preserve the required properties
across the relevant timescale
```

This is why stable atoms become reusable building blocks.

A higher organization can abstract away the internal dynamics of carbon nuclei because they remain reliable over biological timescales.

It cannot do the same with an unstable particle that decays before it can participate.

## 7. Local Availability

Admissibility is not the same as availability.

A transition may be real but unavailable here and now.

Example:

```text
potato dish
```

may be admissible in general.

But if potatoes arrive after the cook dies, the transition is not locally enabled.

So the map distinguishes:

```text
admissible
=
allowed by mapped constraint structure

enabled
=
admissible and locally accessible under current conditions
```

Local conditions include:

```text
available participants
property ranges
timing
spatial accessibility
energy availability
temperature
pressure
field conditions
resolution
uncertainty
instrumentation
repair or replacement availability
```

A real edge may exist on the map while still being unusable from a given local state.

## 8. Properties as First-Class Distinguishers

A label is not enough.

The map must represent measurable properties.

Examples:

```text
frequency
energy
mass
length
temperature
charge
pressure
force
momentum
lifetime
resolution
uncertainty
```

A property is not merely a string.

It is a distinguishable value or value range, usually accessible through some measurement path.

For example:

```text
Photon
```

is a label.

```text
frequency = 9,192,631,770 Hz
```

is a measurable property.

The edge does not care merely that the input is a photon.

It cares whether the photon's properties satisfy the transition constraints.

Example:

```text
Photon(frequency ~= Cs133 hyperfine transition frequency)
+
Cs133Atom(state = lower_hyperfine_state)
->
Cs133Atom(state = upper_hyperfine_state)
```

The label permits matching.

The property determines admissibility.

## 9. Observables and Measurement Capabilities

A unit should not be treated as an arbitrary programming label.

A unit becomes meaningful because some organization can realize a measurement capability.

Examples:

```text
cesium clock
->
distinguish time intervals

school balance
->
distinguish mass differences over a coarse range

Kibble balance
->
realize kilogram through electromechanical measurement

mass spectrometer
->
distinguish atomic and molecular masses

interferometer
->
distinguish length differences using optical interference
```

So the map should include measurement capabilities:

```text
MeasureTime
MeasureLength
MeasureMass
MeasureFrequency
MeasureTemperature
MeasureCharge
MeasureForce
```

But each capability has ranges:

```text
input range
resolution
uncertainty
confidence
calibration path
local conditions
required organizations
```

A school scale and a mass spectrometer may both realize `MeasureMass`, but they do not realize the same region of the capability.

```text
school scale
=
coarse mass distinction for macroscopic objects

mass spectrometer
=
fine mass distinction for atoms or molecules
```

Thus:

```text
same capability
multiple realization paths
different property ranges
```

## 10. SI Units as Reusable Measurement Organization

The SI system is not merely a table of labels.

It is a human-maintained organization for reproducible measurement.

It provides reusable standards for distinguishing properties.

The second is realized through a specific atomic transition.

The meter depends on the second and the fixed speed of light.

Other units depend on fixed constants and realization procedures.

So the SI system is itself an organizational dependency graph:

```text
atomic transition
->
time interval
->
frequency
->
length via light propagation
->
derived quantities
```

Derived units show composability:

```text
newton
=
kg * m / s^2

joule
=
kg * m^2 / s^2

watt
=
kg * m^2 / s^3

hertz
=
1 / s
```

But this composition is not only symbolic.

It reflects the ability to combine measurement capabilities.

To measure force, an organization must distinguish mass, length, and time relations with sufficient resolution.

```text
MeasureForce
requires some realization of
MeasureMass + MeasureLength + MeasureTime
```

A unit is therefore best treated as a reusable measurement interface, backed by one or more realization paths.

## 11. Capabilities as Reusable Interfaces

Higher organizations usually do not depend on one exact implementation.

They depend on a capability.

Example:

```text
requires MeasureMass
```

not necessarily:

```text
requires this exact school scale
```

The map can then ask:

```text
Which local organizations realize MeasureMass
with the required range, resolution, uncertainty, and confidence?
```

This allows substitution.

```text
MeasureMass
├── school balance
├── laboratory balance
├── Kibble balance
├── mass spectrometer
└── orbital dynamics method
```

Each realization path has different constraints.

This is similar to dependency resolution.

The organization requests a capability.

The map finds locally enabled realization paths.

## 12. If Cesium Changed

Suppose the cesium transition became unreliable.

Then the concept of `Second` would not disappear immediately as a human organizational role.

The current realization path would fail.

The map would need a replacement path.

```text
ReliableTimeReference
├── Cs133Clock       [degraded or invalid]
└── ReplacementClock [if available]
```

Higher-level organizations usually depend on:

```text
ReliableTimeReference
```

not on cesium specifically.

So the failure condition is:

```text
no locally enabled realization path exists
for the required measurement capability
at the required resolution and confidence
```

This matches role regeneration.

The role is not the implementation.

The role is the required organizational function.

## 13. Roles Belong to Higher-Order Organization

Roles should not be primitive map nodes at the lowest layer.

At the low level, the map contains:

```text
schemas
properties
transition schemas
measurement capabilities
local enablement conditions
```

A role is a higher-order abstraction:

```text
role
=
function an entity or organization performs
inside a larger organization
```

For example, a photon can be used as:

```text
energy transfer participant
signal carrier
clock reference participant
measurement probe
```

But these roles are contextual.

The photon itself is mapped by its schema and measurable properties.

The role appears only when another organization uses that photon in a particular transition.

So:

```text
property
=
what can be distinguished

transition
=
what can happen

role
=
what the transition contributes inside a larger organization
```

## 14. Do We Need Invariants?

Invariants do not need to be top-level map objects.

They can be represented as constraints on transition schemas.

Examples:

```text
charge before = charge after
energy before = energy after + emitted energy + losses
momentum conserved within interaction model
allowed quantum numbers change according to selection rules
```

So instead of adding a separate primitive:

```text
Invariant
```

use:

```text
transition constraint
```

An invariant is a constraint that must remain satisfied across a transition.

This keeps the map minimal.

## 15. Constraint-Described Edges

An edge should be sophisticated enough to describe:

```text
required input schemas
required property ranges
allowed multiplicities
local environmental ranges
measurement or interaction resolution
time windows
distance or coupling requirements
probability or rate
expected outputs
byproducts
failure modes
confidence level
source of evidence
```

Example:

```text
PhotonAbsorption

inputs:
    Atom(species = X, state = i)
    Photon(frequency = nu)

conditions:
    nu ~= (E_j - E_i) / h
    transition i -> j is allowed
    coupling is nonzero
    photon and atom spatially overlap
    local fields do not suppress transition
    interaction time is sufficient

outputs:
    Atom(species = X, state = j)
```

Another example:

```text
MeasureMacroscopicMass

inputs:
    Object
    SchoolBalance
    CalibrationReference

conditions:
    object mass within balance range
    balance resolution sufficient
    local gravity stable enough for model
    calibration valid
    disturbance below tolerance

outputs:
    MassEstimate(value_range, uncertainty, confidence)
```

The output is not just a number.

It is a distinguishable property estimate with uncertainty.

## 16. Properties as Regions, Not Always Points

Many measurements do not produce exact values.

They produce bounded regions.

```text
mass = 1.0 kg ± 0.01 kg
```

or:

```text
frequency in [20 Hz, 20 kHz]
```

or:

```text
temperature between 290 K and 295 K
```

So a property should usually be represented as:

```text
value domain
resolution
uncertainty
confidence
method
```

not merely:

```text
value
```

This matters because transitions may require precision.

A process may be admissible in principle but not selectable by an organization whose measurement resolution is too coarse.

Example:

```text
human hearing
can distinguish some acoustic frequencies
but not optical frequencies
```

The photon or wave may exist.

The perception transition is not enabled for that organism.

## 17. Example API Shape

The core Python translation should stay close to the map ontology.

```python
from __future__ import annotations

from dataclasses import dataclass
from typing import Protocol, Iterable, Mapping, Any


@dataclass(frozen=True)
class Label:
    value: str


@dataclass(frozen=True)
class PropertyDomain:
    label: Label
    unit: Label | None
    admissible_region: Any
    resolution: Any | None = None
    uncertainty: Any | None = None
    confidence: float | None = None


@dataclass(frozen=True)
class Schema:
    label: Label
    property_domains: Mapping[str, PropertyDomain]


@dataclass(frozen=True)
class Instance:
    schema: Schema
    properties: Mapping[str, Any]


class Constraint(Protocol):
    def satisfied_by(self, context: Context) -> bool:
        ...

    def explain(self, context: Context) -> str:
        ...


@dataclass(frozen=True)
class Context:
    available_instances: tuple[Instance, ...]
    local_properties: Mapping[str, Any]


@dataclass(frozen=True)
class TransitionSchema:
    label: Label
    input_patterns: tuple[Schema, ...]
    output_patterns: tuple[Schema, ...]
    constraints: tuple[Constraint, ...]

    def enabled(self, context: Context) -> bool:
        return all(c.satisfied_by(context) for c in self.constraints)


@dataclass(frozen=True)
class Capability:
    label: Label
    required_output_domain: PropertyDomain


@dataclass(frozen=True)
class CapabilityRealization:
    capability: Capability
    realized_by: Schema
    transition: TransitionSchema
    range: Any
    resolution: Any
    uncertainty: Any
    confidence: float
```

This API does not instantiate reality.

It defines how the map describes:

```text
schemas
property domains
instances
constraints
transition schemas
capabilities
capability realization paths
```

## 18. Example: Photon Schema

```python
Photon = Schema(
    label=Label("Photon"),
    property_domains={
        "frequency": PropertyDomain(
            label=Label("frequency"),
            unit=Label("Hz"),
            admissible_region="nu > 0",
        ),
        "energy": PropertyDomain(
            label=Label("energy"),
            unit=Label("J"),
            admissible_region="E = h * nu",
        ),
        "momentum": PropertyDomain(
            label=Label("momentum"),
            unit=Label("kg*m/s"),
            admissible_region="p = E / c",
        ),
    },
)
```

This is not a photon.

It is the mapped schema for photon instances.

A concrete photon is an instance:

```python
photon_9192631770 = Instance(
    schema=Photon,
    properties={
        "frequency": 9_192_631_770,
    },
)
```

Derived properties can be computed by attached models or constraints.

## 19. Example: Human Auditory Schema

```python
HumanAuditorySystem = Schema(
    label=Label("HumanAuditorySystem"),
    property_domains={
        "frequency_range": PropertyDomain(
            label=Label("audible frequency range"),
            unit=Label("Hz"),
            admissible_region="approximately 20 <= f <= 20000 for typical young humans",
        ),
        "threshold": PropertyDomain(
            label=Label("hearing threshold"),
            unit=Label("dB SPL"),
            admissible_region="varies by frequency and individual condition",
        ),
    },
)
```

The human auditory system is an organization that realizes a limited distinguishing capability.

It does not measure all frequencies.

It distinguishes only a region of acoustic phenomena under suitable local conditions.

## 20. Example: Measurement Transition

```text
AcousticWave(frequency = f)
+
HumanAuditorySystem
--[f inside hearing range, amplitude above threshold, local noise below tolerance]-->
PerceivedSound(frequency_estimate, uncertainty)
```

The edge is not arbitrary.

It is constrained by:

```text
frequency range
amplitude threshold
neural response
local noise
physiological condition
```

This is the same map structure as photon absorption or mass measurement.

## 21. Reliability and Reuse

A schema becomes a useful building block when instances can reliably participate in many transitions.

Reliability depends on:

```text
persistence
availability
interaction richness
property stability
measurement accessibility
local reproducibility
```

This explains why some elements dominate chemistry and biology.

The periodic table lists many elements.

Higher organizations heavily reuse only those whose instances are:

```text
available
persistent
compatible
composition-rich
stable across relevant timescales
```

A short-lived isotope may be real but organizationally poor as a reusable building block.

The map may contain it, but few routes pass through it.

## 22. Composition and New Schemas

Composition occurs when inputs do not merely accumulate but instantiate a new schema.

```text
accumulation
=
more instances without new integrated organization

composition
=
instances satisfy an integration relation
and instantiate a new organizational schema
```

Example:

```text
H + H
--[covalent bonding constraints]-->
H2
```

The output is not merely two hydrogen atoms.

It is a molecule schema instance with new property domains:

```text
bond length
vibrational modes
rotational modes
dissociation energy
molecular transitions
```

The lower-level constraints remain.

The composition adds new organizational constraints.

```text
old constraints preserved
+
new relational constraints
=
new schema with new transition possibilities
```

## 23. Route Queries

The map supports route-like questions.

```text
Can this state reach that state?
Which transition schemas are required?
Which local conditions must hold?
Which measurement capabilities are required?
Which required inputs are unavailable?
Which edge is missing?
```

Example:

```text
Can proton + trillion electrons produce stable godlike atom?
```

The map response should be:

```text
No accepted route.
No mapped transition schema supports stable binding of that multiplicity.
The claim lacks an admissible edge under known atomic constraints.
```

The refusal is not rhetorical.

It is map-based.

```text
show the edge
or
withdraw the reachability claim
```

## 24. Relation to the Earlier Framework

The earlier framework begins from:

```text
realized organization
<->
constraint structure
```

and proceeds through:

```text
admissible continuations
locally enabled continuations
realized transition
new realized organization
```

The admissibility map is the computational-facing version of that structure.

```text
organizational schema
=
reusable map node

property domain
=
what can distinguish instances of that schema

transition schema
=
admissible continuation relation

context
=
local condition set

enabled transition
=
transition schema satisfied by local context

route
=
sequence of enabled transitions

capability
=
reusable distinguishability or production function

realization path
=
organization that instantiates a capability
```

The map does not replace the framework.

It makes the framework queryable.

## 25. Compact Formulation

The admissibility map can be summarized as:

```text
schemas
+
property domains
+
transition schemas
+
local conditions
->
enabled routes through realizable organizational space
```

A claim becomes acceptable only when it can be located in the map:

```text
label
+
property domain
+
admissible transition schema
+
realization path
```

Otherwise it remains only a description.

The deepest rule is:

```text
Reality is not persuaded by names.

Only admissible transitions matter.
```

Or even shorter:

```text
No edge, no route.
No route, no reachable organization.
```
