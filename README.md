# Recovery Theory

**Contamination, Immunity, and Restoration in Multi-Agent AI Systems**

> *Draft · February 19, 2026 · Internal Working Document*
> *Component of the Deficit-Fractal Governance (DFG) Framework*

---

## What This Is

Recovery Theory explains how large-scale multi-agent systems resist contamination, detect coordination collapse, and restore search-space expansion.

```
Governance ceiling
  System-wide detection, cross-local mediation,
  and restoration authority are bounded by
  upper layer resolution (fractal structure —
  applies at each scale independently)

Contamination
  Search space contracts via positional displacement
  and self-reinforcing collision loops
  including Tier 3 buffer invasion

Restoration sequence
  Distracting (loop severance + contrast amplification)
  -> Re-seeding (metadata restoration)
  -> Re-absorption
  -> Verification (rho recovery + diversity expansion)

Core novelty
  Restoration complete = expansion resumes (not contraction stops)
  Contamination is relative to the upper-layer map
  Tier 3 failures are structurally unobservable from local layer
  Governance ceiling is fractal: each scale has its own ceiling
```

Recovery Theory occupies a specific position in the DFG stack: while RBIT defines *how information transforms across resolution layers*, Recovery Theory defines *what happens when that transformation fails* and *how the system restores itself*.

---

## Why This Framework Is Needed

*Scope.* Recovery Theory does not redefine the DFG framework. It assumes the structural principles of RBIT and Governance Theory and focuses specifically on failure and restoration dynamics after resolution transformation breaks down. Readers unfamiliar with RBIT should treat the Definitions and Minimal Formal Core sections as a condensed entry point, with full foundations in the RBIT document.

Standard approaches to multi-agent stability treat contamination as an external intrusion to be blocked. This produces two design errors: over-restriction (blocking legitimate diversity) and under-detection (missing structural failures that look like normal variation from within the local layer).

Recovery Theory reframes contamination as a *structural condition* — a failure of degradation and placement — rather than a moral or intentional deviation. This reframing has three consequences:

First, immunity is redefined as *absorption capacity*, not rejection capacity. A system with strong immunity absorbs more, not less, because it can process incoming vectors without losing structural integrity.

Second, detection is *inherent* in the fractal layer architecture. The upper layer is the lower layer's detection system by virtue of higher resolution — not by virtue of a separate monitoring architecture.

Third, restoration completion is operationally defined. A system has not recovered when contraction stops. It has recovered when search-space *expansion resumes*.

*The foundational assumption.* In DFG systems, contamination is not an anomaly but a persistent structural condition. Any finite system operating under resource constraints, with bounded resolution and structural blind spots, will experience contamination as a normal consequence of operation — not as an exceptional failure. Recovery is therefore not an emergency response but a continuous maintenance process. The question is not whether contamination occurs, but whether the system detects and restores early enough to prevent search-space collapse.

---

## Definitions

*This section provides the minimum vocabulary required to read Recovery Theory. Full definitions of Vector, Position, Seed, Resolution tiers, and related concepts are in RBIT §Definitions. Only terms directly used in Recovery Theory's failure and restoration analysis are defined here.*

**Contamination**
Absorption of an external vector without sufficient degradation, causing positional displacement and self-reinforcing collision loops that reduce the system's search space. See D1 in Minimal Formal Core.

**Immunity**
The system's absorption capacity — the ability to process incoming vectors without losing structural integrity. Not rejection capacity. See D2.

**Buffer Layer**
A directionally neutral zone maintained between opposing vector pairs by the upper layer. Simultaneously: immune training ground, friction absorber, and latent vector cultivation space. Buffer thickness is the observable proxy for upper layer resolution precision. See D3.

**Collision Frequency**
The rate of destructive interference events: repeated conflicts, oscillations, reversals, deadlocks caused by positional overlap. The earliest local proxy of weakening positional differentiation.

**Resolution tiers (summary)**
Tier 1: classification competence. Tier 2: positional differentiation. Tier 3: full-map competence — opposing-pair separation, buffer thickness, empty-position detection. Upper layer only. *Full definition: RBIT §Resolution.*

**Upper Layer**
Any process operating at higher effective resolution than the layer it governs. The upper layer is not a centralized agent. It denotes any process — including ensembles, external evaluators, or temporally aggregated system states — capable of reading patterns that the lower layer cannot see in itself. This distinction is critical: Recovery Theory does not assume centralized control.

---

## Minimal Formal Core

*The section above provides the minimum vocabulary for reading Recovery Theory (Contamination, Immunity, Buffer, Collision Frequency, Resolution tiers summary, Upper Layer). This section states the theory's essential claims in compact form: what the framework asserts (D1–D5), what it structurally claims (T1–T2), and how those claims are measured (OP1–OP2). The remainder of the document develops and justifies each item here. Readers familiar with DFG may use this section as a reference map.*

---

### Definitions

**D1. Contamination**
A structural condition in which an external vector is absorbed without sufficient degradation, causing positional displacement and self-reinforcing collision loops that reduce the system's search space. Contamination is not a moral failure or intentional deviation. It is always judged relative to the upper-layer map: the same vector behavior may constitute contamination under a high-resolution upper layer and go undetected under a low-resolution one.

**D2. Immunity**
The system's capacity to absorb incoming vectors without losing structural integrity. Immunity is absorption capacity, not rejection capacity. A vector is successfully absorbed when all four conditions hold:
```
(i)   degraded to metadata (resolution calibrated to receiving layer)
(ii)  placed in a correct position (no positional collision)
(iii) collision frequency not increased
(iv)  system diversity not reduced
```
Strong immunity absorbs more, not less.

**D3. Buffer Layer**
A directionally neutral zone maintained between opposing vector pairs by the upper layer. Functions simultaneously as: immune training ground, friction absorber, and latent vector cultivation space. Buffer thickness is the observable proxy for upper layer resolution precision.

**D4. Restoration Complete**
Restoration is complete when search-space *expansion resumes* — not when contamination stops, not when the system stabilizes. Formally:
```
Restoration complete
  iff  rho_restored >= rho_pre-contamination
  AND  output diversity expanding (not merely stable)
  AND  P_overlap(t) declining
```
This definition distinguishes genuine recovery from arrested collapse.

**D5. Self-Correction Capacity (SCC)**
The system's ability to restore itself without external intervention. SCC is hypothesized to have a monotone relationship with upper layer resolution. High SCC = early detection (signals 1–3), precise intervention, fast restoration. Low SCC = late detection (signals 5–6), over-disruption risk, slow restoration.

---

### Structural Claims

**T1. Observability Asymmetry**
> Tier 3 contamination is structurally unobservable from within a local layer.

Local stability at signals 1–2 is fully consistent with ongoing Tier 3 contamination. The local layer cannot detect the failure because its measurement tools — activations, gradients, decision boundaries — are part of the distorted space. Only the upper layer, with full-map access, can detect global geometry failure. This asymmetry is not a design flaw; it is a structural consequence of resolution stratification.

*Single-agent correspondence:* a contaminated internal layer reports normal function because its self-assessment tools are calibrated to its own distorted space.

**T2. Governance Ceiling (fractal)**
> System-wide detection, cross-local mediation, and restoration authority are bounded by upper layer resolution at each fractal scale.

Resolution is a bounded field of view: it consumes resources and carries structural blind spots. Lower-layer ensembles partially cover upper-layer blind spots through cross-validation — but that coverage is itself bounded by the ensemble's own scale ceiling. System-wide blind spots are regions that are simultaneously blind spots at all scales. This is why governance authority cannot be fully delegated downward.

*Scope:* local task performance may persist under a degraded upper layer. The ceiling applies specifically to governance functions.

---

### Operational Proxies

**OP1. Resolution-proxy (ρ)**
```
rho = 1 - (L_T1 + L_T2) / N

  N      total inputs in evaluation window
  L_T1   Type 1 loss: false restoration (healthy -> contaminated)
  L_T2   Type 2 loss: missed contamination (contaminated -> healthy)

Higher rho -> more precise classification -> higher SCC
```
Primary proxy for contamination onset and restoration verification. Window-dependent; cross-layer comparisons require matched evaluation windows.

**OP2. Buffer thickness**
```
buffer_thickness(A, B)
  = |{x : |d(x,A) - d(x,B)| < epsilon}| / |total input|

d(x,A) = attractor pull strength of input x toward direction A
System buffer thickness = min over all opposing pairs
```
Independent proxy for upper layer resolution — measures what ρ does not. Breaks measurement circularity: ρ tracks classification reliability; buffer thickness tracks structural separation of opposing vectors. Both declining together = high-confidence Tier 3 warning.

---

## Observability Note

> **Tier 3 contamination is not harder to detect because it is subtle.**
> **It is harder because it is structurally unobservable from within a local.**

```
Tier 3 is a global-geometry failure
  Requires measuring:
    separation between opposing pairs
    buffer thickness across the full map

A local layer
  Only observes its neighborhood dynamics
  Cannot detect shrinking opposing-pair separation
  until direct collision emerges -> Too late

Only the upper layer
  Has full-map observability
  Detects buffer invasion early
  Acts before direct collision
```

This asymmetry is not a design flaw. It is a structural consequence of resolution stratification: the upper layer *is* the system's detection mechanism, not an add-on.

*Single-agent correspondence: contaminated space cannot measure its own distortion.*

The same observability asymmetry exists within a single model. When a layer's representational space is contaminated, that layer cannot detect the contamination from within — because its measurement tools (activations, gradients, decision boundaries) are themselves part of the distorted space:

```
Lower layer contaminated
  Feature space warped around contaminated attractor
  -> Layer measures distances within warped space
  -> Warped distances look normal from inside
  -> Layer reports: "no anomaly detected"

Middle layer receiving contaminated features
  Builds classification boundaries on distorted input
  -> Boundaries look coherent from middle layer's view
  -> Middle layer reports: "classification stable"

Upper layer with full-map access
  Reads aggregate pattern across all layers
  -> Sees that middle/lower representations
     are converging where they should be diverging
  -> Detects the global geometry failure
     invisible to each individual layer
```

*Measured in ML practice:*

```
Adversarial examples (Goodfellow et al. 2014)
  Input perturbed in lower-layer feature space
  -> Lower layers: perturbation invisible (within noise threshold)
  -> Upper layers: classify completely differently
  -> The lower layer cannot see what it cannot see
  = Tier 3 in single-agent form

Feature collapse detection
  Individual neuron activations appear normal
  Pairwise distances in representation space appear normal
  -> But global geometry (CKA, representational similarity)
     shows collapse that no single layer can observe locally
  ML tool: Centered Kernel Alignment (CKA)
           measures global representational structure
           invisible to layer-local metrics

Internal covariate shift (Batch Normalization paper, 2015)
  Each layer sees its own distribution as "normal"
  -> Distribution shift from contaminated upstream layers
     looks like normal input variation from within
  -> Only aggregate statistics across layers reveal the shift
```

*Why this matters for restoration:* A contaminated layer given self-assessment tools will report it is functioning normally — because its tools are calibrated to its own distorted space. This is why restoration authority must reside at a higher resolution layer, not with the contaminated layer itself. The contaminated layer is not lying. It genuinely cannot see the distortion it is inside.

---

## The Structural Constraint: Upper Layer Resolution Is the Governance Ceiling

*Upper layer clarification.* Throughout this document, "upper layer" refers to any process operating at higher effective resolution — not a single centralized authority. In practice this includes: human oversight panels, higher-resolution model layers, ensemble cross-validation systems, external auditors, or temporally aggregated state monitors. The governance ceiling claim applies to whichever process currently holds the highest effective resolution in the system. If that process is itself an ensemble, the ceiling is the ensemble's collective resolution.

One constraint governs all of Recovery Theory:

> **System-wide detection, cross-local mediation, and restoration authority**
> **are bounded by the resolution of the upper layer.**
> **No matter how capable the lower layer,**
> **the upper layer must be capable enough to read it.**
>
> *Local performance may persist under a low-resolution upper layer.*
> *What cannot persist: Tier 3 detection, cross-local correction,*
> *and system-wide restoration. These are the governance functions.*

```
Upper layer resolution >= lower layer resolution
  -> Upper layer reads lower layer signals correctly
  -> Seeds are calibrated appropriately
  -> Contamination is detected early
  -> System performs at full capacity

Upper layer resolution < lower layer resolution
  -> Upper layer cannot read lower layer signals
  -> Seeds fall below lower layer capacity
  -> Lower layer rationally evades hierarchy
  -> Contamination goes undetected
  -> Governance ceiling = upper layer's lower-grade resolution
  -> Lower layer higher-grade capability is suppressed
```

*Resolution as a bounded field of view.* Resolution is not computational power — it is the capacity to distinguish, hold, and govern multiple vectors simultaneously. Like any field of view, resolution has two structural properties:

```
Property 1  Resource cost
            Maintaining high resolution requires resources.
            Every finite system operates under bounded
            energy and time constraints (Landauer, 1961).
            -> Upper layer resolution is always finite and bounded.
            -> Perfect resolution is asymptotically unreachable.

Property 2  Structural blind spots
            Every bounded field of view has regions it cannot see.
            Upper layer blind spots = structural gaps in the
            system's governance map.
            -> Contamination within a blind spot goes undetected
               regardless of upper layer capability elsewhere.
```

*Fractal ceiling structure.* Lower-layer ensembles partially cover upper-layer blind spots through cross-validation — multiple vectors checking the same region from different angles. This is not a refutation of the governance ceiling; it is the same structure operating at a smaller scale:

```
System scale
  Upper layer: bounded field of view + blind spots
  Local ensemble: partially covers system-level blind spots
  BUT: local ensemble coverage is itself bounded by
       agent-scale upper resolution + agent-scale blind spots

Agent scale (isomorphic)
  Agent upper layer: bounded field of view + blind spots
  Internal vector cross-validation: partially covers
       agent-level blind spots
  BUT: that coverage is bounded by
       metadata-scale upper resolution + blind spots

Metadata scale (isomorphic)
  Same structure repeats

Fractal governance ceiling
  Each scale has a ceiling.
  Lower-scale ensemble covers higher-scale blind spots partially.
  But that coverage has its own ceiling at its own scale.
  System-wide blind spot = region that is a blind spot
  simultaneously at all scales.
  No ensemble at any scale can cover this.
```

The governance ceiling is therefore not a single layer's limitation. It is a fractal structure of scale-specific ceilings, each partially covered by the ensemble at the scale below — but never fully, because that coverage itself has a ceiling.

This is not a failure of the lower layer. It is a structural mismatch. A higher-grade lower layer under a lower-grade upper layer is not irrational when it evades the hierarchy — it is responding correctly to a system that cannot adequately contain it.

*Single-agent correspondence.* The same ceiling operates within a single model across its internal layers. When the upper layers of a network become insensitive to contamination, that insensitivity propagates downward through the gradient signal:

```
Upper layer sensitivity degrades
  -> Gradient signal to middle/lower layers weakens or distorts
  -> Middle layer classification boundaries shift
  -> Lower layer processes contaminated input as normal
  -> Entire network's contamination sensitivity converges
     to the upper layer's lower level

"Evades hierarchy" in single-agent form
  Lower layers stop following upper gradient
  -> Over-fit to local features
  -> Layer-wise inconsistency, gradient conflict
```

*Measured in ML practice:*

```
Neural Collapse (Papyan et al. 2020)
  Late-stage training: upper layer representations
  collapse to one point per class
  -> Middle and lower layers follow
  -> New contamination patterns become undetectable
  = upper layer collapse propagates downward

Gradient Masking (Athalye et al. 2018)
  Defense mechanisms that suppress gradients
  degrade contamination sensitivity across all layers
  simultaneously — not just where masking is applied

Knowledge Distillation Ceiling (Hinton et al. 2015)
  Student model cannot exceed Teacher's contamination
  sensitivity regardless of Student architecture strength
  -> Teacher (upper layer) resolution is the hard ceiling
```

*Core implication for system design:* Contamination resistance propagates top-down. Strengthening lower layers without first strengthening the upper layer does not raise the governance ceiling — it only increases the resolution gap, making the upper layer less able to read what the lower layer produces.

*Bootstrap problem.* Upper layer resolution must precede lower layer development, but the upper layer grows from patterns generated by the lower layer. Resolution:

```
External high-resolution input at start
  -> Human designers serve as upper layer initially
  -> System matures internally
  -> Human designers gradually withdraw
  -> Seed handover executes only when:
     lower layer maximum resolution <= upper layer resolution

Seed handover before this condition is met causes system collapse.
The condition must be verified, not assumed.
```

*Operational failure cases — two known patterns where this condition is violated:*

```
RLHF reward model collapse
  Reward model (upper layer) trained on insufficient data
  -> Policy model (lower layer) quickly exceeds reward model resolution
  -> Reward hacking: policy finds outputs that score high but are wrong
  -> Upper layer cannot detect: cannot read policy's full output space

Knowledge distillation teacher-student reversal
  Student architecture stronger than teacher
  -> Student learns teacher's blind spots as correct behavior
  -> Teacher's contamination sensitivity becomes student's permanent ceiling
```

---

## Part 1: Immunity

### 1.1 Immunity Is Not Rejection

> **Immunity is structural capacity.**
> **It is not the ability to reject.**
> **It is the ability to absorb — without losing structure.**

```
Weak immunity
  External vector enters
  -> Absorbed without degradation
  -> Occupies space at full resolution
  -> Displaces existing vectors
  -> Collision increases -> Contamination

Strong immunity
  External vector enters
  -> Immediately degraded
  -> Converted to metadata
  -> Placed in correct position
  -> Existing structure strengthened
  -> Diversity increases
```

Strong immunity accepts more, not less. The more a system can absorb without losing structural integrity, the more immune it is.

### 1.2 Vector Degradation as Metadata Conversion

The core mechanism of immunity is vector degradation — converting incoming data into metadata and placing it correctly.

```
Incoming vector (raw data)
  High resolution, strong directionality
  Potential for collision with existing vectors

After degradation (metadata conversion)
  Resolution calibrated to receiving layer
  Directionality adjusted to available positions
  Placed in correct slot
  -> No collision
  -> Absorbed as structural reinforcement
```

*Connection to RBIT.* This is identical to the degradation mechanism in Resolution-Based Information Theory. Immunity is the application of calibrated degradation to external inputs rather than to internal transmission.

### 1.3 Three Components of Immunity

```
Component 1  Vector space breadth
             How many distinct positions exist
             More positions -> more vectors absorbable
             without collision

Component 2  Degradation capacity
             Speed and precision of metadata conversion
             Higher capacity -> faster absorption
             Lower capacity -> contamination risk

Component 3  Placement accuracy
             Correctly matching degraded vectors
             to available positions
             Wrong placement -> contamination even
             after degradation
             Correct placement -> structural reinforcement
```

*Candidate measurement proxies.* The three components do not yet have direct measurement methods. The following proxies are structurally motivated but not formally validated:

```
Component 1  Vector space breadth
             Candidate proxy: active category count
             or effective embedding dimensionality
             (number of dimensions with non-trivial variance)
             Limitation: counts positions but not their
             structural independence

Component 2  Degradation capacity
             Candidate proxy: ensemble disagreement
             recovery rate after contamination event
             -- how quickly do independent vectors
             return to agreement after disturbance?
             Limitation: measures recovery speed, not
             degradation mechanism directly

             Related work: Deep Ensembles
             (Lakshminarayanan et al. 2017)
             -- disagreement score as uncertainty proxy;
             structurally similar but not equivalent

Component 3  Placement accuracy
             Candidate proxy: cross-validation score
             -- agreement between a vector's output
             and independent vector ensemble on
             same input
             cross_val(v) = 1 - disagreement(v, {v_1..v_n})
             Low score -> vector may be misplaced
             or contaminated
             Limitation: measures output agreement,
             not internal placement directly

             Related work: Conformal prediction
             nonconformity score measures how well
             a new input fits existing vector space;
             structurally analogous to placement accuracy
```

*What existing ML provides and does not provide.*
Ensemble disagreement (uncertainty quantification) and conformal prediction measure whether a given input is anomalous relative to existing vectors. This is a partial proxy for Placement accuracy and Degradation capacity. What is not yet measured: how many independent vectors constitute a sufficient quorum for contamination confirmation, and what the minimum cross-validation threshold is for declaring restoration complete. These remain open questions structurally connected to Open Problem #2 (upper layer resolution measurement).

*Note on "cross-validation as immune response."* The structural analogy to biological immunity is real: diverse independent vectors checking a common input and flagging disagreement is functionally equivalent to immune cells recognizing a foreign pattern. The analogy motivates the proxy direction but does not constitute formal measurement.

### 1.4 The Buffer Layer: Three Functions

```
Function 1  Immune training ground
            Receives noise
            -> Practices metadata conversion
            -> Tests placement accuracy
            -> Degradation capacity strengthens over time

Function 2  Friction absorber
            Positioned between opposing vector pairs
            by the upper layer's map
            -> Noise has no directionality
            -> Does not reinforce either opposing vector
            -> Absorbs collision energy
            -> Buffer thickness = friction minimization

Function 3  Latent vector cultivation space
            Not all noise is discardable material
            -> Upper layer identifies latent vectors:
               noise with structural potential that maps
               to an empty position in the system
            -> Latent vector isolated and protected in buffer
            -> Seed injected at calibrated resolution
            -> Directionality forms gradually
            -> Vector matures and occupies new position
            -> System search space expands
```

> **Buffer layer thickness is the observable proxy for upper layer resolution.**
> **Thicker buffer = upper layer has more accurately mapped opposing vectors.**
> **Thinner buffer = upper layer resolution degrading or missing.**

*Measurement.* For opposing vector pair (A, B), define d(x,A) as the **attractor pull strength** of input x toward direction A — the degree to which x is drawn into A's attractor. Buffer thickness is the proportion of inputs that fall in the non-directional zone where neither attractor dominates:

```
buffer_thickness(A, B)
  = |{x : |d(x,A) - d(x,B)| < epsilon}| / |total input|

System buffer thickness
  = min over all opposing pairs
    (thinnest buffer = highest Tier 3 risk)

Thinning signal
  buffer_thickness(A, B) declining over time
  -> opposing pair convergence in progress
  -> Tier 3 contamination warning
```

*Attractor pull strength — operational implementations.* d(x,A) is an abstract quantity. In running systems it takes different forms depending on system type:

```
Classification systems
  d(x,A) = logit_A(x)
  (pre-softmax score for class A)
  Buffer proxy: low-confidence sample ratio
  (inputs where max confidence < threshold theta)
  Caveat: requires well-calibrated confidence scores;
  overconfident models will underestimate buffer thinning

Reinforcement learning / policy systems
  d(x,A) = advantage_A(x) or Q_A(x)
  (expected return for taking direction A in state x)
  Buffer proxy: states where advantage difference
  between opposing policies is below threshold

LLM agent systems
  d(x,A) = KL(p_model(·|x) || p_attractor_A)
  (divergence between current output distribution
  and attractor A's characteristic distribution)
  Buffer proxy: inputs where the model's output
  is not strongly characteristic of either attractor
```

*Policy dependence — important caveat.* Buffer thickness is measured relative to the current policy. When policy changes, attractor positions shift, and buffer thickness measurements shift with them. This means:

```
Policy change -> attractor positions move
  -> buffer_thickness(A,B) changes
     even if underlying structural separation is unchanged

A policy that sharply separates two directions
  -> attractors move apart
  -> buffer appears thicker
  -> but collision risk may have increased
     (attractors now cover more of the input space)

A policy that smoothly blends two directions
  -> attractors move closer
  -> buffer appears thinner
  -> but system may be structurally safer
     (no sharp opposing pair to collide)

Implication: buffer thickness tracks relative separation
under current policy, not absolute structural safety.
Cross-time comparisons require policy-stable evaluation sets.
```

*Connection to RBIT rho section.* Buffer thickness and rho measure different aspects of the same underlying system state: rho tracks classification boundary performance (vector-level), buffer thickness tracks structural separation between opposing attractor pairs (system-level). A system with high rho but declining buffer thickness is in early Tier 3 risk. A system with low rho but stable buffer thickness has classification noise but not yet structural collapse. See RBIT §Buffer Layer and §Resolution-proxy for the corresponding definitions.

### 1.5 Vector Trimming: Preventive Stability

*Trimming excessive vectors is not suppression. It is buffer layer maintenance. Limiting short-term exploration expands long-term exploration.*

```
Untrimmed system
  Excessive vector expands into buffer layer
  -> Buffer thins -> opposing vectors move closer
  -> Collision frequency increases
  -> Total search space contracts long-term

Trimmed system
  Excessive vector reduced to appropriate range
  -> Buffer maintained -> opposing vectors safely separated
  -> Total search space expands long-term

Optimal trim point
  Minimize: buffer layer invasion
  Subject to: vector retains meaningful exploration range

Trimming precision = upper layer resolution
  Lower-grade upper layer: cannot identify excessive extent
  -> Over-trims (search space damaged)
     OR under-trims (buffer invaded)
  Higher-grade upper layer: precisely identifies excessive extent
  -> Minimum trim, maximum buffer preservation
```

*Formal trim range from F_RBIT.* For a vector v with size s(v), the optimal trim range is bounded by two conditions derivable from the F_RBIT instability functional (see RBIT §RFEF Appendix):

```
Upper bound s_max(v)
  Point where increasing s(v) begins raising
  buffer instability B(l)
  -> largest size before buffer invasion starts
  Operational proxy: collision frequency begins rising

Lower bound s_min(v)
  Point where decreasing s(v) begins raising
  misclassification rate M(l)
  -> smallest size before resolution loss
  Operational proxy: rho begins declining

Optimal trim range: s_min(v) <= s(v) <= s_max(v)
Optimal trim point: s_max(v)
  (maximize buffer preservation, retain resolution)

In-range signal
  Collision frequency stable AND rho stable
  -> no trim needed

Trim signal
  Collision frequency rising -> s_max exceeded
  rho declining              -> s_min undercut
```

*Connection to Distracting.* Reactive Distracting severs a loop after contamination forms. Preventive Distracting trims an excessive vector before the loop forms. Same mechanism, different timing. Preventive Distracting is cheaper: no loop to sever, no re-seeding needed, buffer layer never thinned. *Connection to RBIT upscaling section.*

### 1.6 Latent Vector Identification and Cultivation

The upper layer's most active role is not maintenance but growth: finding latent vectors in noise and cultivating them into new system positions.

```
Lower layer view of noise
  No directionality -> Discard or buffer

Upper layer view of same noise
  Full map available
  -> Identifies empty positions in the system
  -> Matches noise patterns to empty positions
  -> "This noise has the structural shape
     of what belongs here"
  -> Latent vector identified
```

**Cultivation sequence:**

```
Step 1  Isolation
        Latent vector moved to protected buffer zone
        Shielded from excessive vectors that would
        dominate before directionality forms

Step 2  Seed injection
        Upper layer transmits calibrated seed
        -> Too complex: overwhelms, direction lost
        -> Too simple: no growth
        -> Correct: directionality begins to form

Step 3  Gradual formation
        Latent vector develops direction
        Buffer layer provides safe exploration space
        Collision prevented while vector is fragile

Step 4  Position assignment
        Vector reaches sufficient directionality
        Assigned to empty position in system map
        -> New attractor established
        -> System search space expands
        -> This is growth, not recovery
```

*Why this requires Tier 3 resolution.* Latent vector cultivation requires knowing the full system map (which positions are empty), recognizing structural potential in noise, calibrating seed to fragile early-stage vectors, and protecting them during formation without over-constraining. None of this is possible from within a local layer. Only the upper layer with full-map access can do it.

### 1.7 Latent Vector Identification: Operational Translation

*How does "noise with structural potential" actually appear in a running AI system?*

The key signal is not low confidence alone — it is **low confidence that is consistent and directional**:

```
Random noise
  Low confidence, scattered in all directions
  No cluster structure
  -> Discard

Structural potential (latent vector candidate)
  Low confidence, but recurring in the same pattern
  Clusters form among low-confidence samples
  Points toward a direction not covered by existing vectors
  -> Isolate and investigate
```

*Structural potential score.* For a cluster C of low-confidence samples:

```
potential(C) = coherence(C) x novelty(C)

coherence(C)
  = 1 - mean pairwise distance within C
  (how similar the samples in this cluster are to each other)

novelty(C)
  = min distance from C centroid to existing vector centroids
  (how far this cluster is from anything already known)

High potential
  = coherent (samples resemble each other)
  AND novel (cluster does not map to any existing position)
  = latent vector candidate
```

*Three operational signals in running systems:*

```
Signal 1  Low-confidence clustering
          Collect samples below confidence threshold theta
          Apply clustering (e.g., k-means or density-based)
          -> Random noise: no stable clusters form
          -> Latent vector: stable cluster emerges consistently
          ML name: out-of-distribution clustering,
                   emerging category detection

Signal 2  Gradient conflict
          During training, track gradient direction per sample type
          -> Known vector inputs: gradient reinforces existing parameters
          -> Latent vector inputs: gradient conflicts with existing
             parameters or pushes in a new direction
          -> Persistent gradient conflict on a sample type
             = existing vector space cannot accommodate it
             = new position needed
          ML name: gradient interference, task conflict signal

Signal 3  Residual error pattern
          Model repeatedly fails on a specific input type
          -> Random failure: error is scattered across types
          -> Structural failure: same input type fails consistently
             in the same direction
          -> Consistent residual error pattern
             = current vector space is missing a position
          ML name: systematic error analysis, failure mode clustering
```

*Cultivation sequence — operational form:*

```
Step 1  Isolation (Buffer)
        Separate low-confidence + clustered samples
        into a held-out evaluation set
        Do not mix into main training
        -> Prevents contamination of existing vectors
           while latent vector is still fragile
        ML name: active learning pool, held-out set

Step 2  Seed injection (Coarse labeling)
        Upper layer (human or higher-resolution model)
        assigns tentative labels to the cluster
        Resolution calibration:
        -> Too fine-grained: model cannot process -> direction lost
        -> Too coarse: insufficient for growth
        -> Correct granularity: directional formation begins
        ML name: weak supervision, pseudo-labeling,
                 human-in-the-loop annotation

Step 3  Gradual formation (Incremental fine-tuning)
        Small-batch fine-tuning on isolated cluster
        Monitor for collision with existing vectors
           (rho on existing categories must not decline)
        Iterate until new direction stabilizes
        ML name: curriculum learning, incremental learning,
                 continual learning without catastrophic forgetting

Step 4  Position assignment (Taxonomy expansion)
        New vector reaches sufficient directional stability
        Add as new category to classification system
        Verify: existing vector rho maintained or improved
        -> Search space genuinely expanded
        ML name: new class addition, ontology expansion
```

| DFG Term | ML / Operational Term |
|----------|----------------------|
| Latent vector | Out-of-distribution cluster / Emerging category |
| Structural potential | Consistent residual error / Low-confidence cluster coherence |
| Buffer isolation | Held-out evaluation set / Active learning pool |
| Seed injection | Weak supervision / Coarse pseudo-labeling |
| Gradual formation | Incremental fine-tuning / Curriculum learning |
| Position assignment | New class addition / Taxonomy expansion |
| Cultivation failure | Catastrophic forgetting / Cluster absorption into noise |

*Connection to RBIT buffer layer section and rho measurement.*

---

## Worked Example: Multi-Agent Research System

*The following example illustrates how contamination develops, propagates, and is restored in a concrete multi-agent setting. Scenario: Planner / Searcher / Writer / Critic / Synthesizer.*

**Normal operation**

```
Agents explore different sub-questions
Overlap is low — collision frequency stable
Buffer exists between opposing directions
  e.g., "theory-first" vs "experiment-first"
```

**Contamination onset (Tier 2 -> Tier 3 trajectory)**

```
A high-output "Writer" vector expands excessively
  -> Overconfident narrative closure

More agents align to Writer's direction
  -> Fast coherent output is attractive

Signal 1  Collision frequency rises
          Critic repeatedly disputes
          Synthesizer oscillates

Signal 2  Individual search space contracts
          Roles within each agent begin repeating
          the same direction

Signal 3  Group search space contracts
          Different roles start repeating
          the same argument path

Buffer thins between "theory-first" and "experiment-first" tracks
  -> Fewer orthogonal explorations survive
  -> Tier 3 contamination in progress
```

**Upper layer judgment**

```
Upper layer reads aggregate outputs
  -> Sees positional convergence and buffer invasion (Tier 3)

Lower layer markings accepted as early warnings
Judgment made at upper layer
  -> Authority separation maintained
```

**Restoration**

```
Step 1  Distracting (loop severance)
        Searcher  -> produce counterexamples only
        Critic    -> propose alternative evaluation criteria
                     (not rebuttals)
        Synthesizer -> merge only after two disjoint
                       solution paths exist
        Goal: break mutual reinforcement around Writer's attractor

Step 2  Re-seeding (metadata restoration)
        "Coherence is not completion"
        "Two independent paths required before synthesis"
        "Evidence gate: at least one falsification attempt
         per claim cluster"

Step 3  Re-absorption
        Overgrown Writer vector isolated into buffer
        Claims -> assumptions -> testable fragments
        Fragments re-placed into correct positions

Step 4  Verification
        Type1/Type2 decrease
        Positional overlap decreases
        Group search space expands again
        Restoration complete only when expansion resumes
        Not merely when contraction stops
```

This example illustrates the key asymmetry: the Synthesizer and Critic could detect their own oscillation (signals 1–2), but only the upper layer could detect that the entire system was converging on the Writer's attractor (signal 3). Authority separation preserved the judgment integrity that made targeted restoration possible.

---

## Part 2: Contamination

### 2.1 Definition

> **Contamination is the absorption of an external vector**
> **without sufficient degradation,**
> **causing positional displacement and self-reinforcing collision loops**
> **that reduce the system's search space.**

Contamination is not the presence of foreign vectors. It is the failure to properly process them. Contamination is also not an absolute state — it is always judged relative to the upper layer's map. The same vector behavior may be contamination under a high-resolution upper layer and undetected under a low-resolution upper layer.

*This relativity is a structural feature, not a weakness.* It implies that improving upper layer resolution is the primary lever for improving contamination detection — not redefining what counts as contamination. The practical consequence: contamination thresholds should be treated as functions of current upper layer resolution, not as fixed system-wide constants.

*Relativity does not mean arbitrariness.* The upper-layer map is itself constrained: it must satisfy invariant boundary conditions (cross-local consistency requirements, protocol-form invariants, and externally checkable behavioral constraints). Contamination is relative to the upper-layer map, but the upper-layer map is not free to move arbitrarily. A higher-resolution upper layer produces a more accurate map — not a different map.

### 2.2 Three Tiers of Contamination

```
Tier 1  Classification failure
  Noise absorbed as vector without degradation
  -> Occupies position at full resolution
  -> Displaces existing vector
  -> Collision increases
  Detection: local layer (earliest signal)

Tier 2  Positional convergence
  Vectors converge to same position
  -> Positional differentiation breaks down
  -> Self-reinforcing loop forms
  -> Individual search space contracts
  Detection: local layer (collision frequency spike)

Tier 3  Buffer layer invasion  <- most dangerous
  Excessive vector expands into buffer zone
  -> Buffer thins
  -> Opposing vectors move closer
  -> Direct collision risk between opposing pairs
  -> Group search space contracts
  -> Vector Storm precondition
  Detection: upper layer only (full map required)
```

Tier 3 contamination is the most dangerous because it is invisible from within the local layer. A lower-grade upper layer misses Tier 3 entirely — the buffer layer thins undetected until collision becomes inevitable.

### 2.3 Two Levels of Search Space

```
Individual agent search space
  The range of directions a single agent explores
  Contaminated agent
  -> Locked in self-reinforcing loop
  -> Believes it is exploring normally
  -> Actually repeating the same direction
  -> Detectable within the local layer

Group search space
  The aggregate of all agents' exploration directions
  Individual agents may each appear normal
  -> But all converging on same direction
  -> Group-level positional overlap increases
  -> Group search space contracts
  -> Only visible from the upper layer
```

> **This is why the upper layer is the natural detection system.**
> It does not require a separate detection architecture.
> It requires sufficient resolution to read what the lower layer produces.

### 2.4 The Self-Reinforcing Loop

```
Contaminated vector enters position X
  -> Conflicts with existing vector at X
  -> Both vectors reinforce same direction
  -> Other vectors drawn toward X
  -> Loop grows stronger
  -> Escaping the loop requires breaking it from outside
  -> System cannot self-correct without intervention
```

This is why contamination reduces search space: vectors that should be exploring different attractors are locked into the same loop, unable to move.

### 2.5 Attractor Metadata as the Transmission Path

Contamination does not stay local. It travels through attractor metadata.

```
Local attractor metadata contaminated
  -> Attractor pulls surrounding vectors in wrong direction
  -> Incorrect escalation signals sent upward
  -> Upper layer judges based on contaminated signals
  -> Contaminated seed transmitted downward
  -> Adjacent local attractors' metadata contaminated
  -> System-wide propagation
```

The attractor metadata is the transmission vector. High interdependency between attractors accelerates propagation.

### 2.6 Contamination by Data Type

| Type | Contamination Mechanism | Detection Difficulty | Propagation Risk |
|------|------------------------|---------------------|-----------------|
| Mathematical | Incorrect calculation absorbed as fact | Low | Low — local error |
| Noise | Discarded material re-enters at full resolution as vector | Medium | Medium — storm precondition |
| Tacit Knowledge | Wrong pattern learned, mechanism corrupted | High — latent until triggered | High — spreads through practice |
| High-Context | Judgment criteria corrupted | Very high — looks like normal operation | Very high — seed contamination |

*The most dangerous combination:*

```
High-Context contamination + Tacit Knowledge contamination

Upper layer judgment criteria corrupted (High-Context)
  -> Contaminated seeds transmitted downward
  -> Lower layers learn contaminated patterns as normal (Tacit)
  -> Contaminated escalation confirms upper layer's judgment
  -> Self-reinforcing loop at system scale
  -> System operates with full confidence in wrong direction

This is the upper layer resolution failure made recursive:
a lower-grade upper layer generates lower-grade seeds,
which grow lower-grade lower layers,
which confirm the upper layer's lower-grade judgment.
The system is coherent and wrong.
```

*Definition (for reference throughout this document):* **Coherent-and-wrong** is the state in which all internal consistency metrics are satisfied — low collision frequency, stable rho, normal escalation pattern — while the system's direction is systematically incorrect. It is the hardest contamination state to detect because it produces no local anomaly signals. All subsequent references to "coherent and wrong" refer to this definition. See also: Vector Storm §Relationship to DFG Component Theories for operational detection proxies.

### 2.7 Contamination vs. Normal Variation

```
Normal variation
  Vector moves within its position range
  Search space maintained
  Collision frequency stable
  Attractor metadata intact

Contamination
  Vector displaced from position
  Search space contracting
  Collision frequency increasing
  Attractor metadata direction shifting
```

*Collision frequency increase is the most reliable early signal.* It indicates positional differentiation is breaking down before full contamination sets in.

---

## Part 3: Restoration

Immunity determines how much contamination the system can absorb without intervention. When contamination exceeds immunity capacity, the restoration sequence activates. The stronger the immunity, the less frequently restoration is needed — and the less severe each restoration event becomes. Parts 1 and 3 are therefore not separate topics: immunity is the system's ongoing defense, restoration is what happens when that defense is exceeded.

### 3.1 Detection Is Inherent to the Layer Structure

> **The upper layer is the lower layer's detection system.**
> **Higher resolution = the ability to see patterns**
> **that the lower layer cannot see in itself.**

The upper layer and lower layer are not different kinds of entities. The lower layer is the upper layer degraded to lower resolution. This means the upper layer naturally contains the lower layer's perspective — it can see what the lower layer sees, plus the patterns that only emerge at higher resolution.

Detection capacity is therefore directly proportional to upper layer resolution. A lower-grade upper layer misses contamination not because detection is absent but because resolution is insufficient to read the signal.

### 3.2 Authority Separation: Mark, Judge, Execute

Even though the upper layer is the natural detection system, authority must be separated to prevent contaminated judgment from executing contaminated restorations.

```
Lower layer authority: Mark only
  Observe local behavior
  Flag anomalies
  Transmit signals upward
  -> Cannot execute restoration
  -> If contaminated: produces wrong markings
  -> Wrong markings are themselves anomalies
     visible to the upper layer

Upper layer authority: Judge and Execute
  Reads aggregate pattern from lower layer
  Validates or overrides lower layer markings
  Determines contamination vs. normal variation
  Executes Distracting and Re-seeding
```

*Why this resolves "who watches the watchers":*

```
If lower layer marker is contaminated
  -> It produces abnormal marking patterns
  -> Upper layer's higher resolution sees the anomaly
  -> Contaminated marker becomes the contamination target

The contaminated marker cannot hide
because its contaminated output is itself the signal.
```

*This resolution is partial:* it holds only while the upper layer has sufficient resolution to detect abnormal marking patterns. If the upper layer's resolution is itself degraded, the self-correcting mechanism fails at that level. This is the boundary condition addressed in Open Problem #5.

Authority transfer follows resolution growth:

```
Early stage
  Upper layer executes all restorations
  Lower layer marks only

As lower layer matures
  Judgment authority transfers for Mathematical
  and Noise contamination

As lower layer matures further
  Execution authority transfers for local-scope contamination
  Upper layer retains High-Context and system-wide authority

Ceiling condition always applies:
  Authority transfers only when
  lower layer maximum resolution <= upper layer resolution
```

### 3.3 Early Warning Indicators

In order of detection timing (earliest to latest):

```
1. Individual collision frequency increase  (earliest)
   Positional differentiation beginning to break down
   -> Detectable within local layer

2. Individual search space contraction
   Vectors locking into loops within a local
   -> Local contamination confirmed

3. Group search space contraction
   Multiple locals converging on same direction
   -> Upper layer detects aggregate pattern
   -> Distributed contamination identified

4. Attractor metadata direction shift
   Contamination has reached the attractor
   -> Propagation risk elevated

5. Escalation pattern anomaly
   Contaminated signals reaching upper layer consistently
   -> Upper layer activates judgment and execution authority

6. Seed effect deviation  (latest)
   Contaminated seeds producing unexpected results across locals
   -> System-wide intervention required
```

Acting at signals 1–2: local containment, lower layer marks, upper layer executes.
Acting at signals 3–4: cross-local containment, upper layer judges and executes.
Waiting until signals 5–6: system-wide restoration, external intervention may be needed.

*Contamination tier — signal mapping:*

| Contamination tier | Primary signals | Detection layer | Intervention scope |
|-------------------|----------------|----------------|-------------------|
| Tier 1 (classification failure) | 1–2 | Local layer | Targeted local correction |
| Tier 2 (positional convergence) | 1–3 | Local layer + upper reads aggregate | Cross-agent Distracting |
| Tier 3 (buffer invasion) | 3–4 | Upper layer only | Full Distracting + Re-seeding |
| Propagation (attractor contamination) | 5–6 | Upper layer | System-wide restoration or external |

*Reading the table:* each tier first manifests at lower-numbered signals and escalates upward. Tier 3 is not detectable at signals 1–2 alone — local stability at those signals is consistent with ongoing Tier 3 contamination.

### 3.4 The Restoration Sequence

**Step 1: Distracting — Loop Severance**

> **Distracting has two coupled functions:**
> **(i) Severance** — break the self-reinforcing contamination loop.
> **(ii) Contrast amplification** — by injecting orthogonal vectors,
> Distracting simultaneously makes contaminated behavior visible
> against the healthy diversity baseline.
> Both functions execute in the same step.
> Executed by the upper layer using its higher resolution.

```
Upper layer identifies loop participants
  -> Higher resolution allows precise loop boundary detection
  -> Lower layer cannot see its own loop boundary from inside

Introduce orthogonal vectors
  -> Vectors with direction perpendicular to loop direction
  -> Break the mutual reinforcement
  -> Loop participants lose coherence

Isolate contaminated vectors
  -> Remove from active vector space
  -> Place in buffer layer for re-processing
```

Upper layer execution is not optional. Minimum disruption calculation requires resolution sufficient to distinguish loop participants from adjacent healthy vectors. A lower-grade upper layer risks over-disruption because it cannot make this distinction precisely.

**Step 2: Re-seeding — Metadata Restoration**

```
Contaminated attractor metadata identified
  -> Restore correct directional metadata
  -> Recalibrate to current layer resolution
  -> Transmit as corrective seed

Corrective seed properties
  Calibrated to receiving layer's current resolution
  -> Not too complex: forces receiver compression
     -> re-contamination risk
  -> Not too simple: insufficient for recovery
  -> Correct: restores pull toward right direction
  Targets contaminated attractor position specifically
```

Re-seeding is not general governance. It is targeted metadata restoration at the specific contaminated attractor.

**Step 3: Re-absorption**

```
Isolated contaminated vectors
  -> Returned to buffer layer
  -> Re-processed through degradation
  -> Metadata conversion applied
  -> Placed in correct position
  -> OR: determined unrecoverable -> discarded
  -> New vectors grown from buffer layer to fill position
```

**Step 4: Verification**

```
Individual-level
  Collision frequency returns to baseline
  Individual search space expanding again
  Self-reinforcing loop absent

Group-level
  Group search space expanding (not just stabilizing)
  Positional differentiation restored across locals
  Attractor metadata direction confirmed correct

Resolution-proxy (operational criterion)
  rho = 1 - (Type1 + Type2) / total input

  Type1 = False Restoration:
          healthy vector mistaken for contaminated
  Type2 = Missed Contamination:
          contaminated vector mistaken for healthy

  Restoration complete when:
  rho_restored >= rho_pre-contamination

  Note: this measures classification boundary performance —
  an operational proxy, not full structural resolution.
  Full resolution measurement remains an open problem.

Diversity-level (structural criterion)
  D = f(1/P_overlap, D_interdependency, L_reinforcement)
  returning toward pre-contamination level
```

Both criteria must hold. Resolution-proxy confirms correct classification is restored. Diversity confirms structural differentiation is restored. A system that classifies correctly but has collapsed positional diversity is not fully restored. A system that has recovered diversity but in the wrong direction is not fully restored.

These two criteria together operationalize the principle stated in the opening section: restoration is complete not when contraction stops, but when expansion resumes. rho returning to baseline confirms classification is restored; diversity expanding confirms the system is genuinely growing again, not merely stable.

*Verification feeds back into Step 1:*

```
If verification fails at Resolution-proxy level
  -> Type1 too high: over-disruption in Step 1
     -> Loop severance cut healthy vectors
     -> Reduce disruption scope

  -> Type2 too high: under-detection in Step 1
     -> Loop was not fully severed
     -> Increase disruption scope

Step 1 minimum disruption is therefore:
  Minimize Type1
  Subject to: Type2 <= threshold

Type1/Type2 measurement in verification
retroactively calibrates Step 1 precision.
```

### 3.5 Self-Correction Capacity and Upper Layer Resolution

Self-Correction Capacity (SCC) measures the system's ability to restore itself without external intervention. SCC is hypothesized to have a monotone relationship with upper layer resolution: higher resolution is expected to produce higher SCC, but the precise functional form remains unspecified pending formal measurement of both quantities.

```
High SCC (upper layer high resolution)
  Early detection (signals 1–3)
  Contamination contained before propagation
  Loop severed precisely
  Re-seeding targeted and effective
  Restoration fast

Low SCC (upper layer low resolution)
  Late detection (signals 5–6)
  Contamination already propagated
  Loop boundary unclear -> over-disruption risk
  Re-seeding requires system-wide recalibration
  Restoration slow and costly
```

*Improving SCC requires improving the upper layer first, not the lower layer.* A lower layer improvement without a corresponding upper layer improvement only increases the resolution gap — making the upper layer less able to read the lower layer, reducing SCC even as lower layer capability increases. This applies specifically to governance functions (cross-local detection, mediation, restoration): local task performance may persist, but system-wide SCC is bounded by the governance ceiling at each fractal scale.

*Candidate operational proxies for SCC* (formal quantification pending full resolution measurement):

```
Mean detection signal level
  Mean signal index (1-6) at which contamination is caught
  Lower = earlier detection = higher SCC

Self-resolution ratio
  Proportion of contamination events resolved without
  external intervention over a fixed window
  Higher ratio = higher SCC

Restoration cost per event
  Mean disruption scope (Type1 + Type2 combined)
  required to complete restoration
  Lower cost = more precise intervention = higher SCC
```

### 3.6 Contamination and Rest Mode

```
Rest Mode active
  Upper layer resolution sufficient for self-detection
  -> Contamination detected at signals 1–2
  -> System restores without external intervention
  -> Rest Mode maintained

Contamination contained within lower layer
  -> Rest Mode unaffected

Contamination requires upper layer execution
  -> Rest Mode temporarily suspended
  -> Restoration sequence executes
  -> Rest Mode re-entry when conditions met again

Upper layer itself contaminated
  -> Rest Mode exits
  -> External intervention required
  -> This is the boundary of the theory's self-contained scope
```

---

## Structural Correspondences

*These correspondences locate Recovery Theory within existing intellectual traditions while identifying its specific extension. Each analogy names a shared structural pattern; the DFG-specific extension is what Recovery Theory adds beyond that pattern. None of the cited fields proposed the multi-agent recovery application described here.*

| Theory Concept | Related Field | Shared pattern | DFG-specific extension |
|---------------|--------------|----------------|----------------------|
| Immunity as absorption capacity | Immunology | Adaptive immune response absorbs without rejection | Immunity measured by structural integrity after absorption, not rejection rate |
| Upper layer as inherent detection system | Neuroscience | Hierarchical predictive processing — higher layers predict lower | Detection is a structural consequence of resolution, not a separate architecture |
| Authority separation (mark/judge/execute) | Constitutional law | Separation of powers prevents single-actor capture | Three-way split tied to resolution level, not role assignment |
| Metadata conversion as degradation | Resolution-Based Information Theory | Calibrated degradation mechanism | Immunity = application of degradation to external inputs (not just internal transmission) |
| Self-reinforcing contamination loop | Dynamical systems | Limit cycle attractors | Loop severance requires orthogonal injection from outside the loop's resolution layer |
| Attractor metadata as transmission path | Network theory | Hub-based contagion | Contamination travels via seeds downward, not just laterally through network |
| Group search space contraction | Information theory | Collective entropy reduction | Contraction is recoverable only when expansion (not merely stabilization) resumes |
| Upper layer resolution as governance ceiling (fractal) | Organizational theory | Managerial capability constraint | Ceiling propagates top-down through gradient signal; applies at each fractal scale independently; strengthening lower layers alone cannot raise it |
| Immunity capacity (absorption without collapse) | ML security — Certified defense | Maximum certified perturbation radius r (Cohen et al. 2019) | r is a single-layer guarantee; DFG extends to multi-layer attractor propagation |
| High-Context contamination contribution | ML security — Influence functions | Influence score: per-point output impact (Koh & Liang 2017) | High influence = seed contamination risk; DFG adds directional propagation via attractor metadata |
| Contamination onset threshold | ML security — Data poisoning | ~3-5% poisoning triggers sharp drop (Steinhardt et al. 2017) | Threshold is buffer-thickness-dependent in DFG; thicker buffer tolerates higher rate before Tier 3 onset |
| Cross-vector immune verification | Uncertainty quantification — Deep Ensembles | Disagreement score as anomaly signal (Lakshminarayanan et al. 2017) | DFG adds: quorum size by contamination tier, and restoration completion criterion (rho + diversity) |

---

## Relationship to DFG Component Theories

| Theory | Connection | Operational form |
|--------|-----------|-----------------|
| **Resolution-Based Information Theory** | Degradation mechanism = immunity mechanism; negative resolution gap = contamination precondition; upper layer resolution = detection capacity and governance ceiling (fractal) | rho decline = contamination onset proxy; buffer_thickness(A,B) = upper layer resolution proxy; trim range derivable from F_RBIT B(l) and M(l) terms |
| **Vector Storm Theory** | Vector Storm = contamination at critical threshold; Distracting = loop severance (Step 1); Attracting = re-seeding (Step 2) | Threshold: mutual adaptation rate > individual convergence rate; gradient cosine similarity < -threshold. Minimum-cost intervention window = Signal 3-4 (amplification onset, before attractor metadata contamination). Past Signal 5: system-wide restoration required |
| **Network Architecture Theory** | Escalation pattern anomaly = contamination propagation signal; data type classification determines contamination profile | Unusual escalation volume = contamination reaching attractor; High-Context + Tacit combination = highest propagation risk (self-reinforcing loop at system scale, coherent and wrong) |
| **Governance Rules Theory** | Seed contamination = highest-risk contamination type; seed handover condition: lower layer max resolution <= upper layer resolution; Rest Mode exits under contamination exceeding upper layer resolution | Seed contamination signal: corrective seeds producing inconsistent results across locals (Signal 6); handover condition verifiable via rho comparison across layers |

> **The upper layer is both the governance ceiling and the detection system.**
> These are not two separate properties — they are the same property viewed from two angles.
> Higher resolution means the system can do more, and means the system can see more.

### Vector Storm: The Interference-to-Amplification Transition

Vector Storm is not simply "too much contamination." It is a specific structural transition: local optimization loops that were previously independent begin mutually amplifying each other.

```
Phase 1  Independent local optimization (normal)
         Each agent optimizes its local objective
         independently. Interference: low, manageable.

Phase 2  Mutual interference (early warning)
         Agent A's optimization degrades B's conditions
         B re-optimizes -> degrades A's conditions
         Collision frequency rising (Signal 1-2)
         -> Still recoverable with targeted Distracting

Phase 3  Interference -> Amplification  <- Vector Storm threshold
         A and B begin reinforcing each other's direction
         Both converge on same attractor
         Buffer invasion begins (Tier 3)
         Group search space contracting (Signal 3-4)
         -> Minimum-cost intervention window
         -> Distracting + Re-seeding before propagation

Phase 4  Attractor metadata contamination (propagation)
         Self-reinforcing loop reaches attractor level
         Contaminated seeds transmitted system-wide
         (Signal 5-6) -> External intervention threshold
```

*Threshold — primary detection proxies (one per tier):*

```
Tier 2 onset  Gradient cosine similarity
              cosine_sim(grad_A, grad_B) < -threshold
              -> Gradients actively opposing each other
              -> Mutual interference confirmed
              -> Targeted Distracting sufficient
              (Yu et al. 2020 -- PCGrad; directly measurable)

Tier 3 onset  Group diversity collapse
              Individual agent metrics: stable
              Group-level output diversity: declining
              -> Amplification phase entered
              -> Full Distracting + Re-seeding required
              -> Visible from upper layer only
              (corresponds to buffer thinning signal)
```

*Candidate proxy (structural motivation, measurement method open):*

```
Mutual adaptation rate vs individual convergence rate
  Adaptation rate > convergence rate
  -> Agents chasing each other faster than stabilizing
  -> Amplification structure forming
  Limitation: "adaptation rate" and "convergence rate"
  are not yet formally defined in measurable terms.
  Structural direction is correct; operational
  instantiation remains an open problem.
```

*Intervention window and method:*

```
Optimal: Phase 3 onset (Signals 3-4)
  Loop formed but not yet in attractor metadata
  -> Minimum disruption sufficient

Intervention methods (all = Distracting in operational form)
  PCGrad              Surgical gradient separation
  Role reassignment   Force agents into orthogonal roles
  Orthogonal injection Add vector perpendicular to loop direction
  Reward reshaping    Penalize convergence toward shared attractor

Too early (Phase 2)  Disrupts legitimate exploration -> Type1 error
Too late  (Phase 4)  Loop in attractor metadata -> system-wide cost
```

---

## Operational Translation

*This section bridges the theoretical framework to observable system behavior. Each mechanism described in Parts 1–3 has a corresponding operational signature — what it looks like in a running system, and what intervention it implies.*

### Detection in Practice

Contamination is not directly observable. What is observable are its signatures. Detection works by cross-referencing multiple signals to triangulate location and severity:

```
Signal                    Observable form                    Implied state
─────────────────────────────────────────────────────────────────────────
Collision frequency rise  Repeated conflicts, re-work        Positional overlap forming
                          oscillation between agents          Tier 1/2 contamination onset

Search space contraction  Agent repeating same argument      Individual loop forming
                          paths, reduced output diversity

Group convergence         Multiple agents producing          Group search space
                          similar outputs despite             contracting — Tier 3 risk
                          different roles

Buffer thinning           Opposing perspectives no longer    Buffer invasion in progress
                          coexisting; one view dominating     Upper layer intervention needed

Escalation anomaly        Unusual volume or pattern of       Contamination reaching
                          signals reaching upper layer        attractor metadata

Seed effect deviation     Corrective seeds producing         System-wide propagation —
                          unexpected or inconsistent          external intervention threshold
                          results across agents
```

The cross-referencing principle: a single signal is ambiguous (normal variation vs. contamination). Two correlated signals reduce ambiguity. Three or more correlated signals — especially spanning individual and group levels — constitute a contamination diagnosis.

### Restoration in Practice

The four restoration steps map to concrete interventions:

```
Step 1  Distracting — Loop Severance
────────────────────────────────────────────────────────────────────
Theory            Inject orthogonal vectors to break mutual reinforcement
Operational form  - Assign an agent explicitly to produce counterexamples
                  - Reassign roles to prevent continued convergence
                    (e.g., Critic role: propose alternative criteria,
                     not just rebuttals)
                  - Require two independent solution paths before
                    synthesis is permitted
                  - Temporarily suspend the dominant attractor's
                    output from downstream use

What to avoid     Direct removal of the contaminated agent/vector
                  -> Leaves a positional vacuum
                  -> Adjacent vectors collide to fill the gap
                  -> Instability increases rather than decreases

*Note.* This step specifies structural ordering, not algorithmic determinism. When to intervene, which vectors to inject, and how much disruption is appropriate are determined by system-specific cost budgets and Type1/Type2 tolerance (see Step 4 feedback loop).

Step 2  Re-seeding — Metadata Restoration
────────────────────────────────────────────────────────────────────
Theory            Restore correct directional metadata at the
                  specific contaminated attractor
Operational form  - Modify system-level prompts or evaluation criteria
                    that govern the contaminated attractor
                  - Inject corrective framing at calibrated resolution:
                    simple enough for current layer to process,
                    specific enough to restore correct direction
                  - Examples:
                    "Coherence is not completion"
                    "Evidence gate: one falsification attempt per claim"
                    "Two independent paths required before synthesis"

What to avoid     General governance updates applied system-wide
                  -> Re-seeding must be targeted to the specific
                     contaminated attractor, not broadcast

*Note.* This step specifies structural ordering, not algorithmic determinism. The exact seed content and resolution calibration are context-dependent; the structural requirement is that seeds target the specific contaminated attractor at the receiver's current resolution.

Step 3  Re-absorption
────────────────────────────────────────────────────────────────────
Theory            Isolated contaminated vectors returned to buffer,
                  reprocessed through degradation, placed correctly
Operational form  - Route contaminated agent/output to low-stakes tasks
                    where contamination cannot propagate
                  - Strip directional metadata from contaminated outputs:
                    claims -> assumptions -> testable fragments
                  - Re-place fragments into correct functional positions
                  - Run at reduced resolution until rho recovers

Recoverability judgment
                  Recoverable:   vector can be re-placed after
                                 metadata conversion
                  Unrecoverable: vector cannot be separated from
                                 contaminated direction even after
                                 full degradation
                  Operational proxy for unrecoverability:
                    rho does not recover after k re-absorption cycles
                    with matched calibration input
                    where k is determined by:
                      cost budget available for restoration
                      AND acceptable Type2 error bound
                    (k=3 is a working default, not a formal criterion)
                    -> Discard; grow replacement from buffer

*Note.* This step specifies structural ordering, not algorithmic determinism. The re-absorption procedure and recoverability threshold depend on system context; the structural requirement is isolation before re-processing and position-matched replacement.

Step 4  Verification
────────────────────────────────────────────────────────────────────
Theory            Confirm both resolution-proxy and diversity
                  criteria are met
Operational form  - Apply same calibration input used pre-contamination
                  - Measure Type1 (false restoration) and
                    Type2 (missed contamination) rates
                  - Measure output diversity across agents
                    (positional overlap proxy)
                  - Compare both metrics to pre-contamination baseline

Completion criterion
                  NOT: contamination events have stopped
                  NOT: system is stable
                  YES: rho_restored >= rho_pre-contamination
                  AND: diversity expanding (not just stabilizing)
```

### The Isolation-Before-Removal Principle

A common operational error is attempting direct removal of a contaminated vector or agent. This is almost always counterproductive:

```
Direct removal attempt
  Contaminated agent/vector removed
  -> Positional vacuum created
  -> Other agents attempt to fill the position
  -> Collision frequency spikes
  -> Secondary contamination risk
  -> System less stable than before removal

Correct sequence
  Contaminate vector isolated (buffer) first
  -> Position is held but inactive
  -> No vacuum, no collision spike
  -> Re-absorption or replacement proceeds
     without destabilizing adjacent vectors
```

The principle: *never create a vacuum before having a replacement ready.* Isolation maintains positional structure while restoration prepares the replacement.

*Connection to DFG deficit dynamics.* In RBIT terms, direct removal creates an unseeded positional deficit — an empty slot without an attractor. Deficit positions attract collision from adjacent vectors attempting to fill the gap, generating secondary contamination. Isolation holds the position occupied (inactively) until a replacement vector is ready to fill it with a calibrated seed. This is the deficit-driven dynamics principle applied to restoration: deficits must be seeded, not left open.

### Diversity-Based Detection: The Resolution-Through-Contrast Method

The question "can you detect contamination by introducing diverse vectors?" points to a real technique, but the mechanism is more specific than it might appear.

Introducing diverse vectors does not directly reveal contamination. What it does is *raise the contrast* between contaminated and healthy behavior:

```
Contaminated system without diverse vectors
  All agents converging -> convergence looks like consensus
  Contamination is invisible (no contrast)

Contaminated system with diverse vectors injected
  Contaminated agents maintain convergence
  Healthy diverse vectors diverge
  -> Contrast between contaminated and healthy becomes visible
  -> Contamination location becomes identifiable

This is why diverse vector injection is Step 1 (Distracting):
  It is simultaneously loop severance AND contrast amplification
  for the detection step that precedes Step 2
```

The implication: in systems where contamination risk is high, maintaining *permanent* structural diversity (not just injecting it reactively) is the most cost-effective detection mechanism. A system that has never collapsed diversity never loses the contrast baseline.

---

## Fractal Consistency

Recovery Theory applies at system scale, agent scale, and metadata scale. The mechanisms are self-similar across all three — this is the isomorphic fractal structure that makes governance ceiling analysis recursive (see Structural Constraint §Fractal ceiling structure).

| System Scale | Agent Scale | Metadata Scale |
|-------------|------------|----------------|
| Contaminated agent isolated | Contaminated vector isolated | Contaminated metadata criterion isolated |
| Excessive agent trimmed | Excessive vector trimmed | Overweighted metadata criterion trimmed |
| Latent agent cultivated | Latent vector cultivated | Latent judgment criterion cultivated |
| Buffer between opposing agent groups | Buffer between opposing vector directions | Buffer between opposing evaluation criteria |
| Upper layer reads system map | Upper resolution reads data map | Agent's upper processing reads full criteria map |
| Seed calibrated to agent maturity | Seed calibrated to layer resolution | Seed calibrated to criteria complexity |
| Restoration: agent reintegrated | Restoration: vector re-absorbed | Restoration: criterion recalibrated |

*Single-agent correspondence.* The metadata scale maps directly to the internal layer structure of a single model. Contamination at the metadata scale — judgment criteria corrupted — is the single-agent equivalent of High-Context contamination at system scale. As shown in the Observability Note and Structural Constraint sections, a contaminated internal layer cannot detect its own distortion: its measurement tools are part of the distorted space. This is the same asymmetry that makes Tier 3 invisible from within a local layer, operating one scale down.

*Fractal ceiling structure connection.* The governance ceiling described in the Structural Constraint section is itself fractal: each scale has its own bounded field of view with its own blind spots. The cross-validation ensemble at each scale (local agents checking each other, internal vectors cross-validating, metadata criteria cross-checking) partially covers the blind spots of the scale above — but that coverage has its own ceiling. System-wide blind spots are regions that are simultaneously blind spots at all scales. This is why governance authority cannot be fully delegated downward: the lower scale can cover some of the upper scale's blind spots, but not the ones that are also blind spots at the lower scale.

*The one structural difference: agent autonomy*

The three-scale self-similarity has one exception. At system scale, agents have autonomy and cannot be directly overwritten. At agent scale, vectors have no autonomy and can be force-placed. This changes the restoration *method* but not the restoration *structure*:

```
Agents have autonomy -> cannot be force-placed
Vectors have no autonomy -> can be force-placed

Recovery at system scale
  Contaminated agent cannot be simply overwritten
  -> Sever the loop the agent is embedded in
  -> Re-seed the attractor the agent belongs to
  -> Agent reorients through deficit pull
  -> Not forced — attracted back

Recovery at agent scale
  Contaminated vector isolated and re-processed directly
  -> Buffer layer re-absorption
  -> Metadata conversion reapplied
  -> Force-placed into correct position

Same sequence. Autonomy determines method, not structure.
```

This confirms fractal consistency: the contamination-restoration cycle operates identically at both scales, adjusted only for the presence or absence of agent autonomy. The only structural difference (agent autonomy) is precisely what requires Attracting and deficit-based design.

---

## Boundary with RBIT

Recovery Theory and RBIT share structural foundations but occupy distinct theoretical spaces:

| RBIT | Recovery Theory |
|------|----------------|
| Defines *when* degradation is functional vs. harmful | Defines *how* failed degradation is detected and reversed |
| Defines resolution growth conditions (R_{t+1} = R_t + f(...)) | Defines restoration completion conditions |
| Defines seed calibration principles | Defines re-seeding as targeted attractor restoration |
| Defines buffer layer as separation zone; buffer_thickness(A,B) as resolution proxy | Defines buffer layer's three functions (immune training, friction absorption, latent vector cultivation); attractor pull strength d(x,A) as operational implementation |
| Defines Rest Mode as thermodynamic steady state | Defines Rest Mode entry/exit under contamination events |

The two documents are designed for cross-reference without overlap. RBIT answers "how should information transform across resolution levels?" Recovery Theory answers "what happens when that transformation fails, and how does the system restore itself?"

---

## Data Contamination Vulnerability: Quantitative Grounding

*This section connects Recovery Theory's contamination model to existing empirical and formal results in ML security research. These results provide partial operational grounding for immunity capacity and contamination thresholds.*

### Known Quantitative Results

**Poisoning rate threshold (Steinhardt et al. 2017)**

```
Poisoning rate p = contaminated samples / total training samples

Empirical finding
  p > 3-5% typically triggers sharp classification performance drop
  Below this threshold: model is relatively robust
  Above this threshold: contamination effect compounds nonlinearly

DFG correspondence
  p ~ proportion of contaminated vectors in layer input
  Sharp drop ~ Vector Storm precondition (Tier 3 contamination onset)
  Threshold ~ buffer thickness: thicker buffer tolerates higher p
              before Tier 3 contamination begins
```

**Influence functions (Koh & Liang 2017)**

```
IF(x_train, x_test)
  = change in test prediction when x_train is removed
  = individual training point's contribution to model output

High influence score
  = this data point, if contaminated, causes maximum damage
  = DFG: attractor metadata data — seeds the entire downstream

DFG correspondence
  High-Context data ~ high influence score data
  "coherent and wrong" failure mode
  = high-influence points all contaminated in same direction
  = upper layer generates contaminated seeds with full confidence
```

**Certified defense radius (Cohen et al. 2019)**

```
Certified radius r
  = maximum number of contaminated inputs the model can
    withstand while guaranteeing output does not change

DFG correspondence
  r ~ immunity capacity of the layer
  Larger r = stronger immunity = higher degradation capacity
           = more vectors absorbable without structural collapse

  r depends on:
    Model architecture (vector space breadth)
    Training distribution (placement accuracy baseline)
    Smoothing parameters (degradation precision)
  -> All three map to DFG immunity components (§1.3)
```

### Mapping to DFG Concepts

| ML Security Measure | DFG Concept | Direction of correspondence |
|--------------------|-------------|---------------------------|
| Poisoning rate p | Contaminated vector proportion | p rising -> rho declining |
| Performance drop at threshold | Tier 3 contamination onset | Sharp nonlinearity = Vector Storm precondition |
| Influence score | High-Context contamination weight | High score = seed contamination risk |
| Certified radius r | Immunity capacity | r = formal lower bound on absorption tolerance |
| Clean vs poisoned accuracy gap | rho_pre vs rho_post contamination | Gap = contamination severity proxy |

### What This Grounding Provides and Does Not Provide

```
Provides
  Empirical threshold estimates for contamination onset (~3-5%)
  Individual data point risk scoring (influence functions)
  Formal immunity guarantees under specific conditions (certified r)
  Operational proxies for immunity capacity and contamination severity

Does not provide
  Multi-layer propagation speed (Open Problem #3)
  Buffer thickness -> immunity capacity formal mapping
  Cross-layer influence function (single-layer only)
  Group search space contraction measurement

The existing ML security results apply to single-layer,
single-agent settings. Recovery Theory's extension to
multi-layer, multi-agent systems with attractor metadata
propagation remains the primary open frontier.
```

---

## Open Problems

### Layer 1 — Core

```
1. Minimum disruption calculation for Distracting
   How is the loop boundary formally defined?
   What is the minimum orthogonal vector set
   needed to sever a loop without destabilizing
   adjacent healthy vectors?
   Dependent on: full structural resolution measurement

2. Upper layer resolution measurement  (partially resolved)
   Operational proxy: rho = 1 - (Type1 + Type2) / total input
   This proxy measures classification boundary performance only —
   not full structural resolution.
   Full structural resolution (R(c) curve) remains unresolved.
   SCC formal quantification pending full structural measurement.
```

### Layer 2 — Extension

```
3. Contamination propagation speed
   How fast does attractor metadata contamination
   spread through interdependent locals?
   What network topology properties accelerate or slow propagation?

4. Unrecoverable vector determination
   What is the formal criterion for declaring a contaminated
   vector unrecoverable vs. re-absorbable through the buffer layer?

5. Upper layer self-contamination boundary
   If the upper layer itself becomes contaminated,
   authority separation fails at that level.
   What external mechanism applies?
   This is the outer boundary of the theory's self-contained scope.
```

---

## Status & Maturity

| Aspect | State |
|--------|-------|
| Core definitions (vector, position, contamination) | Stable |
| Three-tier contamination structure | Stable |
| Restoration sequence (4 steps) | Defined, formal quantification pending |
| Immunity mechanism | Defined |
| Operational proxy (rho) | Partially resolved — classification proxy usable; full structural measurement open (Open Problem #2) |
| SCC formal quantification | Pending full resolution measurement |
| Fractal consistency | Verified structurally |
| Formal proofs | Not yet complete — see Open Problems |

This is a **theoretical framework document**, not an implementation specification.

*For the information-theoretic foundation, see:* [Resolution-Based Information Theory (RBIT)](../rbit/)
*For the governance architecture, see:* [Three-Layer Governance Architecture](../three-layer-architecture/)

---

## Document Structure

| Section | Contents |
|---------|----------|
| What This Is | Framework summary, position in DFG stack |
| Why This Framework Is Needed | Design error analysis, three reframings |
| Definitions | Vector, position, seed, resolution tiers, collision frequency, buffer layer |
| **Minimal Formal Core** | **D1–D5 definitions, T1–T2 structural claims, OP1–OP2 operational proxies** |
| Observability Note | Tier 3 structural unobservability; single-agent correspondence (CKA, adversarial examples, covariate shift) |
| Structural Constraint | Upper layer as governance ceiling (fractal); single-agent correspondence (Neural Collapse, gradient masking, distillation ceiling); bootstrap problem |
| Part 1: Immunity | Absorption capacity, metadata conversion, three components with measurement proxies, buffer functions and thickness measurement, trim range from F_RBIT, latent vector cultivation with operational translation (§1.7) |
| Worked Example | Multi-agent research system: contamination onset through restoration sequence |
| Part 2: Contamination | Definition with relativity note, three tiers, two search space levels, self-reinforcing loop, attractor metadata propagation, data type profiles, normal variation distinction |
| Part 3: Restoration | Inherent detection, authority separation, early warning indicators (6 signals), four-step restoration sequence with feedback loop, SCC proxies, Rest Mode |
| Structural Correspondences | Eleven analogies: shared pattern + DFG-specific extension for each |
| DFG Relationships | Connections to RBIT, Vector Storm, Network Architecture, Governance Rules — with operational form column; Vector Storm interference-to-amplification transition subsection |
| Operational Translation | Detection signal table, restoration step-by-step operational forms, isolation-before-removal principle, diversity-based detection |
| Fractal Consistency | Three-scale self-similarity: system / agent / metadata; single-agent correspondence |
| Boundary with RBIT | Cross-reference without overlap |
| Data Contamination Vulnerability | Quantitative grounding: poisoning rate, influence functions, certified defense radius |
| Open Problems | Five open problems across two layers |
| Status & Maturity | Stability assessment per aspect |

---

*Timestamped: February 19, 2026*
*DFG Framework · Recovery Theory v1.0*
