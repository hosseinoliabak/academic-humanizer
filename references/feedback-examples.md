# Worked author-feedback examples

These nine cases extend the initial feedback in [the audit guide](academic-audit.md). Impact levels
and category names are user-supplied detector feedback, not verified measures of authorship. Each
revision is a candidate for author review. Evaluate it in its paragraph before adopting it; do not
apply the candidates as repeated sentence templates. The supplied thesis statements remain manuscript
input to preserve, except where an evidence note below identifies a separate source check.

## 1. Service-provider problem framing

**Original, supplied medium impact**

> Detecting attacks in a familiar dataset addresses only part of the problem faced by a service
> provider protecting several customer networks.

**Feedback:** Predictable Syntax; Overly Formal; Sophisticated Clarity; Mechanical Precision.

**Candidate**

> For a service provider protecting several customer networks, the problem extends beyond detecting
> attacks in a familiar dataset.

**Audit and preservation:** Recast the sentence around the provider's setting. Retain dataset,
service provider, several customer networks, and the limit of the familiar-dataset setting. Their
precision is useful; a more casual synonym would not resolve repetitive framing. The surrounding
paragraph must still explain what additional problem the provider faces.

## 2. Motivation and investigation

**Original, supplied medium impact**

> The thesis turns this motivation into a controlled technical investigation.

**Feedback:** Lacks Creative Grammar; Robotic Formality; Overly Formal.

**Candidate**

> Motivated by this experience, the researcher develops a controlled technical investigation in the
> thesis.

**Audit and preservation:** This candidate uses the researcher and experience identified in the
supplied surrounding paragraph. It connects motivation to action without claiming that the investigation
is complete or successful. If the experience and researcher are not established in another passage,
retain "this motivation" and avoid introducing those referents. Do not vary grammar just to make a
simple statement less regular.

## 3. Participant differences and evaluation

**Original, supplied medium impact**

> Differences between participants are therefore part of the evaluation problem, not merely an
> implementation detail.

**Feedback:** Technical Jargon; Sophisticated Clarity; Overly Formal; Mechanical Transitions;
Mechanical Precision.

**Candidate, dependent on the preceding argument**

> The evaluation problem therefore includes differences between participants; their significance
> extends beyond implementation.

**Audit and preservation:** Retain the evaluation role and the claim that implementation alone does
not capture these differences. "Therefore" remains provisional until the preceding text supports the
inference. The isolated sentence cannot establish that link. Do not invent an effect size, statistical
test, or operational consequence. The negative contrast is part of the supplied claim, not disposable
padding; describe its grammar accurately rather than assuming it is a subordinate clause.

## 4. Thesis purpose and local false alarms

**Original, supplied medium impact**

> The present thesis examines the resulting balance between collaborative detection and local false
> alarms.

**Feedback:** Lacks Creative Grammar; Robotic Formality; Impersonal Tone.

**Candidate, when the preceding argument has established the resulting balance**

> The resulting balance between collaborative detection and local false alarms is the focus of
> this thesis.

**Audit and preservation:** Remove ceremonial "present" and bring the balance into the topic position.
Keep "resulting" unless the preceding argument supports an equally precise explanation of the result
relationship. Retain the balance as an object of investigation, not an achieved improvement.
Do not assert that collaboration reduces false alarms or improves detection. Avoid adding first-person
language merely to counter an impersonality label. If the surrounding paragraph repeats "the thesis
examines," revise the group of sentences rather than substituting another abstract reporting verb.

## 5. Federated learning and local records

**Original, supplied medium impact**

> Federated learning is relevant when participants can contribute to model training while retaining
> the underlying records locally.

**Feedback:** Robotic Formality; Impersonal Tone; Technical Jargon; Sophisticated Clarity;
Mechanical Transitions; Mechanical Precision.

**Candidate**

> For participants who can contribute to model training while retaining the underlying records
> locally, federated learning is relevant.

**Audit and preservation:** Bring the participant conditions forward while retaining the claim about
relevance. Do not replace it with a general capability statement, even when that statement is also
supported by a source. Retain federated learning, model training, the participants' ability to
contribute, and local retention of the records. "While" carries a real
relationship here and need not be removed. Do not turn local record retention into a guarantee of
privacy or security. The source check below supports the local-training description, not the suitability
of a particular deployment or the availability of labels at its participants.

## 6. Public captures as conditional proxies

**Original, supplied medium impact**

> Public capture sources will stand in for customer workloads only where their provenance supports
> that interpretation; they will remain explicitly labeled proxies.

**Feedback:** Technical Jargon; Sophisticated Clarity; Lacks Creativity; Impersonal Tone.

**Candidate**

> Public capture sources will be used as proxies for customer workloads only where their provenance
> supports that interpretation. They will remain explicitly labeled as proxies.

**Audit and preservation:** Separate the permitted use from the labeling requirement. Keep both the
provenance condition and the explicit proxy designation. This is a planned, conditional use, not a
claim that any public capture has been validated as representative of a customer workload. Retain
provenance unless its intended scope is established well enough to explain it without narrowing it.

## 7. Logical roles and physical placement

**Original, supplied high impact**

> These roles need not occupy separate physical machines.

**Feedback:** Robotic Formality; Lacks Creative Grammar.

**Candidate**

> A physical machine may host more than one of these roles.

**Audit and preservation:** Express possible co-location directly without naming roles that the
supplied sentence does not identify. Do not assert that the roles actually share a machine, that all
roles must or can share one machine, or that a specific host has sufficient capacity. The revision
preserves freedom of placement, not functional readiness or a tested deployment.

## 8. Literature-review tasks

**Original, supplied high impact**

> The literature review instead examines the specific information available to a new target, how its
> decision threshold is selected, and how the resulting detector is compared with a fitted local
> alternative.

**Feedback:** Lacks Creativity; Impersonal Tone; Technical Jargon.

**Candidate, dependent on the preceding contrast**

> The literature review instead considers what information is available to a new target and how its
> decision threshold is selected. It also examines how the resulting detector is compared with a
> fitted local alternative.

**Audit and preservation:** Distribute the parallel clauses without losing any review task. Preserve
the new target's information, threshold selection, and comparison with a fitted local alternative.
Do not change "fitted" to "untrained," choose a threshold criterion, or specify who selects it without
evidence. Retain "instead" only when its contrast is established in the preceding text; otherwise ask
for that context before finalizing the connection. Three substantive tasks are not padding.

## 9. FedOE and labeled outlier exposure

**Original, supplied high impact**

> FedOE studies cross-silo DDoS detection at distributed edge servers and uses limited labeled
> outlier exposure (Pourahmadi, Alameddine, Salahuddin, & Boutaba, 2023).

**Feedback:** Overly Formal; Sophisticated Clarity; Mechanical Precision.

**Candidate**

> For cross-silo DDoS detection at distributed edge servers, FedOE uses a limited set of labeled
> attack flows for outlier exposure (Pourahmadi, Alameddine, Salahuddin, & Boutaba, 2023).

**Audit and preservation:** Retain the named framework, setting, limited labeled exposure, and exact
supplied citation. The paper supports describing the outliers as attack flows. Do not change this into
label-free learning or require every edge server to possess attack labels. A precision label is not
a reason to remove cross-silo, DDoS, edge-server roles, or outlier exposure.

## Source checks for the technical candidates

- **Federated learning:** RAG retrieved ETSI GR SAI 002 V1.1.1, section 6.4.2, printed pages 19–20.
  The [official report](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/002/01.01.01_60/gr_SAI002v010101p.pdf)
  was also checked. It describes local training and parameter updates while datasets remain local;
  it also describes security threats. The candidate makes no privacy guarantee.
- **FedOE:** RAG searches returned no relevant FedOE passage. Verification instead used the
  [author-hosted paper](https://rboutaba.cs.uwaterloo.ca/Papers/Journals/2023/PourhamadiTDSC2022.pdf),
  abstract on internal page 1 and sections 4.1–4.2 on pages 5–6. These support cross-silo learning at
  edge servers and limited labeled attack flows. Section 4.1 does not require attack flows at every
  edge server. The supplied 2023 citation is retained; the linked author manuscript carries 2022
  acceptance metadata. These checks do not verify the thesis's design, motivation, or data provenance.
