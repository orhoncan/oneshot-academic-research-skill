# Mermaid Diagram Patterns for Academic Research

Common diagram patterns for visualizing research concepts, processes, and relationships.

## Concept Hierarchies

### Theory Structure
```mermaid
graph TD
    A[Main Theory] --> B[Sub-theory 1]
    A --> C[Sub-theory 2]
    A --> D[Sub-theory 3]
    B --> B1[Component 1.1]
    B --> B2[Component 1.2]
    C --> C1[Component 2.1]
    C --> C2[Component 2.2]
```

### Taxonomy
```mermaid
graph TD
    Root[Research Domain] --> Cat1[Category A]
    Root --> Cat2[Category B]
    Root --> Cat3[Category C]
    Cat1 --> Sub1[Subcategory A1]
    Cat1 --> Sub2[Subcategory A2]
    Cat2 --> Sub3[Subcategory B1]
    Cat2 --> Sub4[Subcategory B2]
```

## Process Flows

### Research Methodology
```mermaid
flowchart LR
    A[Research Question] --> B[Literature Review]
    B --> C[Hypothesis Formation]
    C --> D[Study Design]
    D --> E[Data Collection]
    E --> F[Analysis]
    F --> G{Results Significant?}
    G -->|Yes| H[Report Findings]
    G -->|No| I[Refine & Retest]
    I --> D
```

### Experimental Procedure
```mermaid
flowchart TD
    Start[Recruitment] --> Screen[Screening]
    Screen --> Consent[Informed Consent]
    Consent --> Baseline[Baseline Measures]
    Baseline --> Random{Randomization}
    Random -->|Group A| Int1[Intervention A]
    Random -->|Group B| Int2[Intervention B]
    Random -->|Control| Ctrl[Control Condition]
    Int1 --> Post[Post-test]
    Int2 --> Post
    Ctrl --> Post
    Post --> Follow[Follow-up]
    Follow --> Analysis[Data Analysis]
```

### Information Processing Model
```mermaid
flowchart LR
    Input[Sensory Input] --> Attention[Attention]
    Attention --> STM[Short-term Memory]
    STM --> Process[Processing]
    Process --> LTM[Long-term Memory]
    LTM --> Retrieval[Retrieval]
    Retrieval --> Output[Response/Output]
    LTM -.->|Feedback| Process
```

## Theoretical Relationships

### Causal Model
```mermaid
graph LR
    IV1[Independent Variable 1] --> DV[Dependent Variable]
    IV2[Independent Variable 2] --> DV
    Med[Mediator] --> DV
    IV1 --> Med
    Mod[Moderator] -.->|Moderates| IV1
```

### Bidirectional Relationships
```mermaid
graph LR
    A[Factor A] <--> B[Factor B]
    B <--> C[Factor C]
    C <--> A
    D[External Factor] --> A
    D --> B
    D --> C
```

### Feedback Loop
```mermaid
graph TD
    A[Behavior] --> B[Outcome]
    B --> C[Evaluation]
    C --> D[Adjustment]
    D --> A
    C -.->|Positive| E[Reinforcement]
    C -.->|Negative| F[Extinction]
```

## Comparison Matrices

### Theory Comparison (as diagram)
```mermaid
graph TD
    Comp[Comparison Dimension]
    T1[Theory 1] --> Comp
    T2[Theory 2] --> Comp
    T3[Theory 3] --> Comp
    Comp --> Dim1[Dimension A]
    Comp --> Dim2[Dimension B]
    Comp --> Dim3[Dimension C]
```

Note: For detailed comparisons, use tables instead of diagrams.

## Timelines

### Research History
```mermaid
timeline
    title Development of Theory X
    1960s : Early work by Smith
         : Foundation studies
    1970s : Refinement by Jones
         : First applications
    1980s : Critical reviews
         : Paradigm shift
    1990s : Modern interpretation
         : Integration with Theory Y
    2000s : Meta-analyses published
         : Current consensus
    2010s : Recent extensions
         : Neurological basis found
    2020s : Contemporary applications
         : AI integration
```

### Study Timeline
```mermaid
gantt
    title Study Schedule
    dateFormat YYYY-MM-DD
    section Phase 1
    Literature Review    :2024-01-01, 30d
    Protocol Development :2024-01-15, 20d
    section Phase 2
    Recruitment         :2024-02-01, 45d
    Data Collection     :2024-02-15, 60d
    section Phase 3
    Analysis            :2024-04-15, 30d
    Write-up            :2024-05-01, 45d
```

## State Diagrams

### Psychological States
```mermaid
stateDiagram-v2
    [*] --> Resting
    Resting --> Aroused: Stimulus
    Aroused --> Processing: Attention
    Processing --> Response: Decision
    Response --> Resting: Completion
    Processing --> Aroused: Interruption
    Aroused --> Resting: Habituation
```

### Learning Stages
```mermaid
stateDiagram-v2
    [*] --> Novice
    Novice --> Intermediate: Practice
    Intermediate --> Advanced: Mastery
    Advanced --> Expert: Experience
    Intermediate --> Novice: Regression
    Expert --> [*]
```

## Mind Maps / Concept Maps

### Research Domain
```mermaid
mindmap
  root((Research Topic))
    Theoretical Framework
      Theory A
      Theory B
      Integration
    Methodology
      Quantitative
      Qualitative
      Mixed Methods
    Key Findings
      Finding 1
      Finding 2
      Finding 3
    Applications
      Clinical
      Educational
      Organizational
    Future Directions
      Gap 1
      Gap 2
      Emerging Areas
```

### Literature Synthesis
```mermaid
mindmap
  root((Central Concept))
    Supporting Evidence
      Study 1
        Sample
        Method
        Result
      Study 2
        Sample
        Method
        Result
    Contradicting Evidence
      Study 3
      Study 4
    Moderating Factors
      Context A
      Context B
    Implications
      Theory
      Practice
```

## Network Diagrams

### Citation Network (simplified)
```mermaid
graph TD
    Seminal[Seminal Work<br/>Author 1990] --> Modern1[Modern Study 1<br/>Author 2015]
    Seminal --> Modern2[Modern Study 2<br/>Author 2018]
    Modern1 --> Recent1[Recent Work<br/>Author 2023]
    Modern2 --> Recent1
    Modern2 --> Recent2[Recent Work<br/>Author 2024]
    Theory2[Alternative Theory<br/>Author 2005] --> Modern2
    Theory2 --> Recent2
```

### Construct Relationships
```mermaid
graph LR
    A[Construct A] --- B[Construct B]
    B --- C[Construct C]
    C --- D[Construct D]
    A --- C
    B --- D
    E[External Factor] --> A
    E --> C
```

## Quadrant Charts

### Research Paradigms
```mermaid
quadrantChart
    title Research Approaches
    x-axis Qualitative --> Quantitative
    y-axis Exploratory --> Confirmatory
    quadrant-1 Quantitative Confirmatory
    quadrant-2 Qualitative Confirmatory
    quadrant-3 Qualitative Exploratory
    quadrant-4 Quantitative Exploratory
    Survey Research: [0.7, 0.7]
    Case Studies: [0.2, 0.3]
    Ethnography: [0.1, 0.5]
    RCT: [0.9, 0.9]
    Grounded Theory: [0.2, 0.2]
```

## Sequence Diagrams

### Cognitive Process
```mermaid
sequenceDiagram
    participant Stimulus
    participant Sensory
    participant Attention
    participant Memory
    participant Response
    
    Stimulus->>Sensory: Input received
    Sensory->>Attention: Signal sent
    Attention->>Memory: Query relevant info
    Memory-->>Attention: Retrieve context
    Attention->>Response: Process & decide
    Response->>Stimulus: Action taken
```

## Usage Guidelines

### When to Use Each Type

**Hierarchies**: Use for taxonomies, theory structures, categorizations
- Best for: Showing levels, containment, classification

**Process Flows**: Use for methodologies, procedures, causal sequences
- Best for: Step-by-step processes, decision trees, workflows

**Timelines**: Use for historical development, study schedules
- Best for: Chronological progression, development over time

**State Diagrams**: Use for stage transitions, psychological states
- Best for: Discrete states with transitions

**Mind Maps**: Use for brainstorming, topic overview, synthesis
- Best for: Radial organization, multiple dimensions

**Network Diagrams**: Use for citations, construct relationships
- Best for: Non-hierarchical connections, complex interactions

### Design Principles

1. **Keep it simple**: Maximum 10-12 nodes per diagram
2. **Clear labels**: Short, descriptive text
3. **Consistent direction**: Top-to-bottom or left-to-right
4. **Group related items**: Use subgraphs when helpful
5. **Use color sparingly**: Only to highlight key elements

### Common Mistakes to Avoid

❌ Too many nodes (>15)
❌ Unclear relationships
❌ Inconsistent terminology
❌ Missing legend when needed
❌ Overly complex connections

✅ Focused, single-purpose diagrams
✅ Clear directional flow
✅ Consistent labeling
✅ Legend for symbols/colors
✅ Hierarchical or sequential clarity

### Advanced Tips

**Subgraphs for grouping:**
```mermaid
graph TD
    subgraph "Theoretical Domain"
        A[Concept A]
        B[Concept B]
    end
    subgraph "Empirical Domain"
        C[Finding C]
        D[Finding D]
    end
    A --> C
    B --> D
```

**Styling nodes:**
```mermaid
graph LR
    A[Normal]
    B[Emphasized]:::highlight
    C[Warning]:::warn
    classDef highlight fill:#e1f5ff,stroke:#0066cc
    classDef warn fill:#fff3cd,stroke:#ffc107
```

## When to Use Tables Instead

Use **tables** (not diagrams) for:
- Detailed comparisons with multiple dimensions
- Numerical data or statistics
- Study characteristics (sample sizes, methods, results)
- Side-by-side theory comparison with quotes

Use **diagrams** (not tables) for:
- Processes and workflows
- Hierarchies and relationships
- Temporal sequences
- Conceptual structures
