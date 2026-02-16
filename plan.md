# Reasoning precisely about imprecisions (metric program equivalence)

Modern programs increasingly interact with continuous data, randomness,
quantum, and physical processes. In this setting, the typical *binary* notions
of program equivalence become too coarse, and more flexible, quantitative ones
are called for. In autonomous driving, for example, one does not expect two
programs to match the same speeds *exactly*; instead the idea is to determine
*how close* their behaviours are, typically measured in terms of a suitable
metric.

The course highlights how metric reasoning can be used in practice, with
illustrations from probabilistic programming and other computational models.
Our focus will be rather on fundamental principles -- involving a core
`programming language' (lambda-calculus), corresponding laws of metric
equational systems, and their *categorical* semantics.

The emphasis throughout is on intuition, the essence of things, and main ideas,
rather than full technical detail. Thus no prior knowledge of lambda-calculus
or category theory is assumed.

## Lecture 1: Linear lambda-calculus and its equational system

+ brief course overview (motivations, programme and its rationale)
+ introduction to linear lambda-calculus
    + types and term formation rules
    + substitution
    + the equational system
    + extensions (only some brief comments)

## Lecture 2: Categorical semantics of linear lambda-calculus

+ the essence of category theory
+ necessary definitions
    + category
    + symmetric monoidal category
    + SMC category
+ the semantics of linear lambda-calculus

## Lecture 3: Metric lambda-calculus

+ the metric equational system
+ examples of 'metric reasoning'
+ remarks on linearity / needing to track 'resource usage'
+ the challenge of giving a categorical semantics

## Lecture 4: Categorical semantics of metric equations + applications

+ the categorical semantics of metric lambda-calculus
+ soundness and (approximate) completeness (only some brief comments)
+ applications
+ concluding remarks
