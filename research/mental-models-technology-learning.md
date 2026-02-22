# Mental Models in Technology Learning: An Academic Research Synthesis

## Purpose

This document synthesizes academic and practitioner research on mental models as they relate to training people on new and emerging technology. It draws on foundational cognitive science, educational psychology, human-computer interaction (HCI), and recent AI/ML-specific research. Marketing copy and thought leadership have been excluded; sources are peer-reviewed or from established academic institutions.

---

## 1. Foundational Theory: What Are Mental Models?

### 1.1 Kenneth Craik — The Origin (1943)

The concept of mental models originates with Scottish psychologist **Kenneth Craik** (1914–1945). In his 1943 book *The Nature of Explanation*, Craik proposed that the mind constructs "small-scale models" of reality to anticipate events and reason about the world. He argued that our brains create internal representations that mirror external processes, allowing us to mentally simulate scenarios and predict outcomes without physically interacting with them.

Craik viewed the brain as "a calculating machine which can model or parallel external events." His work was written before the impact of digital computers, so he based his ideas on analog devices. Einstein reportedly considered *The Nature of Explanation* a great book (as recounted by Warren McCulloch).

> **Key citation:** Craik, K. J. W. (1943). *The Nature of Explanation*. Cambridge University Press.
>
> **Retrospective analysis:** Wilkes, K. V. (1983). Forty years on: Kenneth Craik's *The Nature of Explanation* (1943). *Perception*, 12(3), 233–236. [PubMed](https://pubmed.ncbi.nlm.nih.gov/6366731/)

### 1.2 Philip Johnson-Laird — Formalizing the Theory (1983)

Johnson-Laird acknowledged that "the first modern formulation of this thesis is to be found in Kenneth Craik's remarkably prescient book." His 1983 book *Mental Models: Towards a Cognitive Science of Language, Inference, and Consciousness* provided a comprehensive framework: people reason by constructing mental models of situations rather than relying solely on formal rules of logic.

**Key principles:**
- Human beings construct mental models of the world using tacit mental processes
- Models can be constructed from perception, imagination, or the comprehension of discourse
- Their structure is *analogous* to the structure of the situation they represent (unlike formal logical representations)
- People reason by manipulating these models, not by applying logical rules

Johnson-Laird and Ruth M. J. Byrne later developed a full theory of reasoning based on mental model construction and manipulation.

> **Key citation:** Johnson-Laird, P. N. (1983). *Mental Models: Towards a Cognitive Science of Language, Inference, and Consciousness*. Harvard University Press.

### 1.3 Gentner & Stevens — The Landmark Edited Volume (1983)

Published the same year as Johnson-Laird's book (and developed independently), this edited volume brought together researchers from cognitive science, AI, physics education, and HCI to explore how people construct internal representations of the systems they interact with.

The first chapter, written by **Donald Norman**, explains that mental models provide both predictive and explanatory power for understanding our interaction with our environment, with other people, and with technological artifacts. Norman emphasized that mental models are:
- Always evolving
- Not necessarily accurate
- But *must be functional* — they need to be useful enough to guide action

**Notable chapters and contributors:**

| Author(s) | Chapter | Domain |
|---|---|---|
| Norman, D. A. | "Some observations on mental models" | General theory |
| Gentner, D. & Gentner, D. R. | "Flowing waters or teeming crowds: Mental models of electricity" | Analogical reasoning |
| McCloskey, M. | "Naive theories of motion" | Physics misconceptions |
| de Kleer, J. & Brown, J. S. | "Assumptions and ambiguities in mechanistic mental models" | AI/mechanistic reasoning |
| Larkin, J. H. | "The role of problem representation in physics" | Expert problem-solving |
| Young, R. M. | "Surrogates and mappings: Two kinds of conceptual models for interactive devices" | HCI |

> **Key citation:** Gentner, D., & Stevens, A. L. (Eds.). (1983). *Mental Models*. Lawrence Erlbaum Associates.

### 1.4 Donald Norman — Mental Models in Design (1988/2013)

Norman's *The Design of Everyday Things* (originally published as *The Psychology of Everyday Things*, 1988; revised 2013) operationalized mental model theory for technology design. He identified three distinct aspects:

1. **The Design Model** — the conceptualization the designer has in mind
2. **The User's Model** — what the user develops to explain the operation of the system
3. **The System Image** — the collective set of instructions, appearances, behaviors, and feedback the product presents

**The critical insight:** The designer and user communicate *only through the system image*. Ideally, the user's model and the design model are equivalent. But when the system image fails to convey the designer's conceptual model, the user constructs an incorrect mental model — leading to confusion, errors, and frustration.

Norman drew a sharp distinction between conceptual models and mental models: "Conceptual models are devised as tools for the understanding or teaching of physical systems. Mental models are what people really have in their heads and what guides their use of things."

**The danger of misaligned models:** Designers are likely to be experts in how the system works, whereas users may have a limited or incorrect understanding. This creates a situation where designers build systems that reflect their expert understanding, not the novice mental model of the user.

> **Key citations:**
> - Norman, D. A. (1983). Some observations on mental models. In D. Gentner & A. L. Stevens (Eds.), *Mental Models* (pp. 7–14). Lawrence Erlbaum Associates.
> - Norman, D. A. (1988). *The Design of Everyday Things*. Basic Books. (Revised edition 2013.)

---

## 2. How Mental Models Form for Fundamentally New Technology

### 2.1 Analogical Reasoning — Gentner's Structure-Mapping Theory

When people encounter fundamentally new technology, the primary cognitive mechanism for building initial understanding is **analogy**. Dedre Gentner's **Structure-Mapping Theory** (1983) provides the foundational account:

**Core mechanism:** An analogy is a mapping of knowledge from one domain (the *base*) to another (the *target*) which conveys that a system of relations holding among base objects also holds among target objects. An analogy maps relational structure while disregarding surface-level object descriptions.

**The Systematicity Principle:** People prefer to map systems of predicates that contain higher-order relations, rather than isolated predicates. This reflects a tacit preference for coherence and deductive power.

**Implications for technology learning:**
- People often understand a new situation by drawing an analogy to a familiar situation
- Analogies can serve as mental models — e.g., people reason about electric current using a mental model based on water flow (Gentner & Gentner, 1983)
- When analogical transfer occurs, it can be *extremely effective* — importing a large connected system can lead to rapid insight compared to incremental learning
- **However,** analogical retrieval is unreliable: people mostly fail to retrieve relationally similar cases and instead retrieve surface-similar cases (which may be misleading)

**The problem for paradigm-breaking technology:** When truly new technology has no good base analog (e.g., generative AI doesn't map cleanly to any prior technology), users either:
1. Force-fit an inappropriate analogy (e.g., treating a language model as a search engine or a database)
2. Fail to build a coherent model at all
3. Build a model based on surface features rather than underlying mechanisms

> **Key citations:**
> - Gentner, D. (1983). Structure-mapping: A theoretical framework for analogy. *Cognitive Science*, 7(2), 155–170. [Wiley](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog0702_3)
> - Gentner, D., & Holyoak, K. J. (1997). Reasoning and learning by analogy. *American Psychologist*, 52(1), 32–34. [PDF](https://reasoninglab.psych.ucla.edu/wp-content/uploads/sites/273/2021/04/Gentner-and-Holyoak-1997.pdf)
> - Gentner, D., & Markman, A. B. (1997). Structure mapping in analogy and similarity. *American Psychologist*, 52(1), 45–56. [PDF](https://groups.psych.northwestern.edu/gentner/papers/GentnerMarkman97.pdf)
> - Gentner, D., & Smith, L. (2013). Analogical learning and reasoning. In D. Reisberg (Ed.), *The Oxford Handbook of Cognitive Psychology*. [PDF](https://groups.psych.northwestern.edu/gentner/papers/gentner&Smith_2013.3b.pdf)
> - Gentner, D. (2025). Analogy. *Open Encyclopedia of Cognitive Science*, MIT. [MIT](https://oecs.mit.edu/pub/yjq05b3c)

### 2.2 John Carroll — Minimalist Instruction and Active Exploration

John M. Carroll's research at IBM's Watson Research Center in the early 1980s directly addressed how people learn fundamentally new technology (word processors, the first personal computers). His work led to the **Minimalist Instruction** framework.

**The core problem Carroll identified:** The dawn of the "new user" in the early 1980s created massive challenges for training and instructional design. Standard instructional approaches (e.g., Gagné, Merrill) were too passive and failed to exploit prior knowledge or use errors as learning opportunities.

**Key finding:** Effective learning is often "active," proceeding by self-initiated problem solving. Standard manuals "penalize and impede active learning."

**Minimalist principles:**

1. All learning tasks should be meaningful and self-contained activities
2. Learners should be given realistic projects as quickly as possible
3. Instruction should permit self-directed reasoning and improvising by increasing active learning activities
4. Training materials should provide for error recognition and recovery (errors as learning opportunities, not aberrations)
5. There should be close linkage between training and actual system use

**Practical results:** Carroll's team replaced a 94-page manual with 25 task-oriented cards. Each card was self-contained and included error recognition/recovery information. The information provided was not complete step-by-step specifications but only key ideas or hints. Users learned the task in approximately half the time.

**Critical insight for technology training:** Rather than shortchanging learners, a minimalist approach *streamlines* instruction to enable the learning process. Designers should "prescribe less, and enable users to think and do more with new technologies."

> **Key citations:**
> - Carroll, J. M. (1990). *The Nurnberg Funnel: Designing Minimalist Instruction for Practical Computer Skill*. MIT Press.
> - Carroll, J. M. (1998). Minimalism beyond the Nurnberg Funnel. MIT Press.
> - Carroll, J. M. (2014). Creating minimalist instruction. *International Journal of Designs for Learning*, 5(2). [IU ScholarWorks](https://scholarworks.iu.edu/journals/index.php/ijdl/article/view/12887)
> - Van der Meij, H., & Carroll, J. M. (1995). Principles and heuristics for designing minimalist instruction. *Technical Communication*, 42(2), 243–261.

### 2.3 Vosniadou's Framework Theory — How Prior Knowledge Constrains New Learning

Stella Vosniadou's **framework theory** of conceptual change offers a powerful account of why learning paradigm-breaking technology is so difficult. Although developed in the context of naive physics, the mechanisms apply directly to learning new technology paradigms.

**Core thesis:** Naive understanding is "neither a collection of unstructured knowledge elements nor a collection of stable misconceptions that need to be replaced, but rather a complex conceptual system that organizes perceptual experiences and cultural information into coherent explanatory frameworks."

**Two levels of knowledge:**

1. **Framework theories** — Built early, based on fundamental ontological and epistemological presuppositions that define a domain (e.g., permanence, solidity, continuity for matter). These are deep, tacit, and highly resistant to change.
2. **Specific theories** — Built from everyday experiences to explain a limited range of phenomena. Based on beliefs that give rise to mental models, *under the constraints of the framework theory*.

**The synthetic model problem:** When learners encounter information that contradicts their framework theory, they often construct **synthetic models** — hybrid representations that assimilate new information into existing (incompatible) frameworks without metaconceptual awareness. This leads to persistent misconceptions.

*Classic example:* Children told the Earth is round sometimes construct a model of a hollow sphere with a flat surface inside where people live — reconciling "the Earth is round" with the framework presupposition that "the ground is flat."

**Why this matters for technology training:** When people learn AI/ML, they assimilate new information into existing frameworks (e.g., "computers follow explicit instructions" or "more data = better results"). This produces synthetic models that *seem* coherent to the learner but are fundamentally flawed.

> **Key citations:**
> - Vosniadou, S., & Brewer, W. F. (1992). Mental models of the earth: A study of conceptual change in childhood. *Cognitive Psychology*, 24(4), 535–585.
> - Vosniadou, S. (1994). Capturing and modeling the process of conceptual change. *Learning and Instruction*, 4(1), 45–69. [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/0959475294900183)
> - Vosniadou, S. (2002). On the nature of naïve physics. In M. Limón & L. Mason (Eds.), *Reconsidering Conceptual Change*. Springer. [Springer](https://link.springer.com/chapter/10.1007/0-306-47637-1_3)
> - Vosniadou, S., Vamvakoussi, X., & Skopeliti, I. (2008). The framework theory approach to the problem of conceptual change. In S. Vosniadou (Ed.), *International Handbook of Research on Conceptual Change*. Routledge.

---

## 3. Misconceptions and Incorrect Mental Models in AI/ML Learning

### 3.1 Identified Misconceptions About Machine Learning

A study on secondary school students by Tabel et al. (2024) identified **six key misconceptions** about machine learning:

| Misconception | Description |
|---|---|
| **Programmed Behavior** | Belief that AI follows explicit, step-by-step programmed instructions rather than learning from data |
| **Exactness** | Belief that ML models produce exact, deterministic outputs |
| **Data Storage** | Belief that training data is saved and retrieved during inference |
| **Continuous Learning** | Belief that AI continues learning during deployment/application |
| **User-trained Model** | Belief that individual user interactions train the model in real time |
| **Autonomous Data Acquisition** | Belief that AI systems independently seek out and collect their own training data |

The authors note: "The majority of mental model research in the field of ML is focused on general conceptions of AI, yet resulting misconceptions and their influence on the learning process remain underexplored."

> **Key citation:** Tabel, O., et al. (2024). Identifying secondary school students' misconceptions about machine learning: An interview study. *Proceedings of the ACM Conference on International Computing Education Research (ICER)*. [ACM](https://dl.acm.org/doi/fullHtml/10.1145/3677619.3678114)

### 3.2 Folk Theories of AI

Research on how lay users form informal understandings of AI systems reveals a consistent pattern. **Folk theories** are the informal, intuitive explanations people construct for how technology works in the absence of formal instruction.

**Key findings:**

- Alizadeh et al. (2020) found that laypeople have varied expectations: some associate AI with machine learning, others only associate it with automation. The concept of **"Perceived AI"** — "AI defined from the perspective of its users" — captures this variability.
- Wash (2010) proposed eight **folk models** of home computer security threats, showing how informal theories drive behavior even when they are incorrect.
- In algorithmic recommender systems, research shows that users with high levels of understanding acknowledge the role of companies and developers, while users with low understanding develop folk theories that omit these factors entirely.
- Eslami et al. (2016) documented folk theories about social media algorithms, including the finding that users resist algorithmic changes they cannot explain within their existing folk theories.

**Cognitive biases in AI folk theories:** Researchers have identified that evolved human cognitive tendencies (folk theories about agency, intentionality, and causation) "have not evolved to match the nature of AI, and this causes problems in democratizing AI ethics and politics."

> **Key citations:**
> - Alizadeh, F., et al. (2020). eXplainable AI: Take one step back, move two steps forward — Investigating folk theories and users' perception of artificial intelligence. [ResearchGate](https://www.researchgate.net/publication/344491013)
> - Wash, R. (2010). Folk models of home computer security. *Proceedings of the Sixth Symposium on Usable Privacy and Security (SOUPS)*. ACM.
> - Eslami, M., et al. (2016). "Algorithms ruin everything": #RIPTwitter, folk theories, and resistance to algorithmic change in social media. [ResearchGate](https://www.researchgate.net/publication/312372888)
> - Lutz, C., & Tamó-Larrieux, A. (2021). Socio-cognitive biases in folk AI ethics and risk discourse. *AI and Ethics*, 1, 407–419. [Springer](https://link.springer.com/article/10.1007/s43681-021-00060-5)

### 3.3 Mental Models of Generative AI

Recent research (2024–2025) has begun examining mental models of generative AI specifically:

- **Xie et al. (2025)** studied mental models of generative AI chatbot ecosystems, finding that individuals decompose complex AI systems into subcomponents and form smaller models — an "imperfect representation" that allows for human error. Published at IUI 2025.
- Research on LLM-based programming assistants found that "the varied capabilities of these tools across model versions and the mixed availability of extensions (web search, code execution, RAG) create opportunities for user misconceptions about what systems can and cannot do. Such misconceptions may lead to over-reliance, unproductive practices, or insufficient quality control."
- **Bansal et al. (2020)** studied mental models of AI agents in a cooperative game setting, providing one of the earliest controlled studies of how people form models of AI capabilities. Published at CHI 2020.

> **Key citations:**
> - Xie, Q., et al. (2025). Mental models of generative AI chatbot ecosystems. *Proceedings of the 30th International Conference on Intelligent User Interfaces (IUI)*. [ACM](https://dl.acm.org/doi/10.1145/3708359.3712125)
> - Bansal, G., et al. (2020). Mental models of AI agents in a cooperative game setting. *Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems*. [ResearchGate](https://www.researchgate.net/publication/341694166)

### 3.4 The Role of Explainable AI (XAI) in Shaping Mental Models

A growing body of HCI research examines whether AI explanations actually improve users' mental models:

- **"The Who in XAI"** (CHI 2024): Found that people with and without AI backgrounds perceive explanations differently. Both groups showed "unwarranted faith in numbers" but for different reasons. AI explanations can have negative consequences and lead to "harmful manipulation of trust."
- **Hoffman, Mueller, Klein, & Litman (2023)**: Proposed a measurement framework for XAI covering explanation goodness, user satisfaction, mental models, curiosity, trust, and human-AI performance. Mental model accuracy is now used as a standard measure of XAI effectiveness.
- **Incremental XAI** (CHI 2024): Proposed that user expectations and existing mental models are central to designing effective explanations — and that explanations should be delivered incrementally to build on existing understanding.
- A survey by **Liao & Varshney (2023)** in IEEE TPAMI called for human-centered evaluations of explainable models, noting that "a better understanding of the needs of XAI users" is both a necessity and a challenge.

> **Key citations:**
> - Chromik, M., et al. (2024). The Who in XAI: How AI background shapes perceptions of AI explanations. *Proceedings of CHI 2024*. [ACM](https://dl.acm.org/doi/10.1145/3613904.3642474)
> - Hoffman, R. R., Mueller, S. T., Klein, G., & Litman, J. (2023). Measures for explainable AI: Explanation goodness, user satisfaction, mental models, curiosity, trust, and human-AI performance. *Frontiers in Computer Science*, 5.
> - Kulesza, T., et al. (2024). Incremental XAI: Memorable understanding of AI with incremental explanations. *Proceedings of CHI 2024*. [ACM](https://dl.acm.org/doi/10.1145/3613904.3642689)
> - Liao, Q. V., & Varshney, K. R. (2023). Towards human-centered explainable AI: A survey of user studies for model explanations. *IEEE Transactions on Pattern Analysis and Machine Intelligence*. [IEEE](https://dl.acm.org/doi/10.1109/TPAMI.2023.3331846)

---

## 4. Conceptual Change — How People Update Deeply Held Mental Models

### 4.1 The Classical Model: Posner, Strike, Hewson & Gertzog (1982)

The foundational theory of conceptual change in education identifies **four conditions** that must be met for someone to abandon an existing conception and adopt a new one:

1. **Dissatisfaction** — The learner must become dissatisfied with their existing conception (it fails to explain or predict something important)
2. **Intelligibility** — The new conception must be understandable (non-contradictory, its meaning is clear)
3. **Plausibility** — The new conception must be believable and consistent with other accepted knowledge
4. **Fruitfulness** — The new conception must be demonstrably useful — it helps solve problems or opens new possibilities

**Critical finding for technology training:** Simply presenting correct information is insufficient. The learner must first experience genuine dissatisfaction with their current model. And even then, the old ideas often "stay alive in particular contexts" — students show understanding in formal testing but revert to naive models in real-world application.

> **Key citation:** Posner, G. J., Strike, K. A., Hewson, P. W., & Gertzog, W. A. (1982). Accommodation of a scientific conception: Toward a theory of conceptual change. *Science Education*, 66(2), 211–227. [PDF](https://faculty.weber.edu/eamsel/Classes/Practicum/TA%20Practicum/papers/Posner%20et%20al.%20(1982).PDF)

### 4.2 Michelene Chi — Ontological Category Shifts

Chi's framework offers the most rigorous account of *why* some conceptual changes are profoundly difficult.

**Three levels of misconception** (Chi, 2008), increasing in difficulty of correction:

| Level | Type | Example | Difficulty |
|---|---|---|---|
| 1 | **False beliefs** | "Neural networks have neurons like the brain" | Easy — can be corrected by providing correct information |
| 2 | **Flawed mental models** | Treating ML training as analogous to human studying | Moderate — requires restructuring relationships between concepts |
| 3 | **Incorrect ontological categories** | Categorizing a stochastic process (LLM output) as a deterministic procedure | Very difficult — requires awareness of and shift to a new ontological category |

**The ontological incompatibility hypothesis:** Many scientific concepts belong to the ontological category of "constraint-based interactions" (emergent processes), but students categorize them as "matter" (things/entities). Because the category "emergent processes" is not intuitive, students are often not aware it exists. Instruction must *first* make students aware of the correct ontological category, *then* help them assign the concept to it.

**Relevance to AI/ML:** When people treat a language model as an entity that "knows" things (matter/entity ontology) rather than as a process that generates probabilistic outputs (emergent process ontology), they are making an ontological miscategorization. This cannot be corrected by simply adding information — it requires an ontological category shift.

**Instructional implication — ontology training:** Chi (2005) proposed that conceptual change can be facilitated by training students in the appropriate ontology *prior to* domain instruction. Teaching the category first, then the content.

> **Key citations:**
> - Chi, M. T. H., Slotta, J. D., & de Leeuw, N. (1994). From things to processes: A theory of conceptual change for learning science concepts. *Learning and Instruction*, 4(1), 27–43. [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/0959475494900175)
> - Chi, M. T. H. (2008). Three types of conceptual change: Belief revision, mental model transformation, and categorical shift. In S. Vosniadou (Ed.), *International Handbook of Research on Conceptual Change*. Routledge. [ASU PDF](https://education.asu.edu/sites/g/files/litvpz656/files/lcl/chi_concpetualchangechapter_0.pdf)
> - Chi, M. T. H. (2005). Commonsense conceptions of emergent processes: Why some misconceptions are robust. *Journal of the Learning Sciences*, 14(2), 161–199.
> - Slotta, J. D., & Chi, M. T. H. (2006). Helping students understand challenging topics in science through ontology training. *Cognition and Instruction*, 24(2), 261–289. [ResearchGate](https://www.researchgate.net/publication/252482895)

### 4.3 Meta-Analytic Evidence on Conceptual Change Strategies

A 2024 meta-analysis by Pacaci et al. examined the effectiveness of conceptual change strategies in science education across 218 primary studies (18,051 students):

- **Large overall effect size:** g = 1.10 (adjusted g = 0.93 via robust Bayesian analysis)
- Confirms that deliberate conceptual change instruction is substantially more effective than standard instruction
- But also confirms that the most robust misconceptions (Chi's level 3 — ontological miscategorizations) remain the hardest to address

> **Key citation:** Pacaci, C., et al. (2024). Effectiveness of conceptual change strategies in science education: A meta-analysis. *Journal of Research in Science Teaching*. [Wiley](https://onlinelibrary.wiley.com/doi/full/10.1002/tea.21887)

### 4.4 Holistic Mental Model Confrontation

Gadgil, Nokes-Malach, & Chi (2012) found that having students compare their own flawed mental model with a correct scientific model — a process they call **holistic mental model confrontation** — was effective in driving conceptual change. The key was making the *entire* model visible for comparison, not just correcting individual facts.

> **Key citation:** Gadgil, S., Nokes-Malach, T. J., & Chi, M. T. H. (2012). Effectiveness of holistic mental model confrontation in driving conceptual change. *Learning and Instruction*, 22(1), 47–61. [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0959475211000454)

---

## 5. Expert vs. Novice Mental Models in Technology

### 5.1 Structural Differences

Research consistently finds that expert and novice mental models differ not just in *content* but in *structure*:

| Dimension | Expert Models | Novice Models |
|---|---|---|
| Organization | Hierarchical, coherent, interconnected | Flat, fragmented, loosely connected |
| Basis | Deep structures, underlying principles | Surface features, superficial similarities |
| Abstraction | High — based on semantic/functional characteristics | Low — based on perceptual/surface characteristics |
| Automaticity | High — pattern recognition is automatic | Low — requires deliberate, step-by-step processing |
| Predictive power | Strong — can anticipate system behavior | Weak — reactive rather than predictive |

**Toker & Moseley (2013)** used Pathfinder scaling to compare mental models: 23 experts identified 11 critical concepts from an initial set of 30. 16 experts provided data on concept-pair relatedness. 242 practitioners participated total, with 33 novices selected. Results: "the expert model has a more consistent and hierarchical structure than the novice model."

> **Key citations:**
> - Toker, S., & Moseley, J. L. (2013). The mental model comparison of expert and novice performance improvement practitioners. *Performance Improvement Quarterly*. [ResearchGate](https://www.researchgate.net/publication/254727707)
> - Staggers, N., & Norcio, A. F. (1993). Mental models: Concepts for human-computer interaction research. *International Journal of Man-Machine Studies*, 38(4), 587–605.

### 5.2 Expert vs. Novice Behavior Differences

In cybersecurity contexts, research has confirmed these structural differences translate to behavioral ones:

- **Experts** actively look for vulnerabilities and consider multiple factors when encountering a potentially risky situation. They assess safety *before* taking action.
- **Novices** perform fewer security checks, tend to assess safety *after* performing an action, and are more likely to trust large corporations to protect them.

This pattern applies to technology adoption broadly: the degree to which a technology's operation matches a user's existing mental model — the "perceived match between how the system operates and how a user understands events" — is a key factor in adoption.

### 5.3 The Novice-to-Expert Transition

Despite the benefits of expert techniques, many users do not learn them and continue using novice approaches. Understanding if, when, and how users decide to learn and ultimately adopt expert methods is a complex skill-acquisition and decision-making problem.

**The Transition model** (ACM TOCHI, 2022) proposes five cognitive mechanisms underlying the novice-to-expert transition:
1. Implicit learning
2. Explicit learning
3. Decay
4. Planning
5. Perseveration (habitual continuation of established behavior)

**Design implication:** Different metaphors may be needed to train experts vs. novices, and different interface designs may be appropriate for each.

> **Key citations:**
> - Giannisakis, E., et al. (2022). Computational model of the transition from novice to expert interaction techniques. *ACM Transactions on Computer-Human Interaction*, 29(4). [ACM](https://dl.acm.org/doi/10.1145/3505557)
> - Springer volume: Feltovich, P. J., Ford, K. M., & Hoffman, R. R. (Eds.). (1997). *Expertise in Context: Human and Machine*. MIT Press. (Ch. 4: Mental models and the acquisition of expert knowledge.) [Springer](https://link.springer.com/chapter/10.1007/978-1-4613-9733-5_4)

---

## 6. Synthesis: Implications for AI/ML Technology Training

Drawing across these research streams, several empirically grounded principles emerge for training people on AI and similar paradigm-breaking technologies:

### 6.1 The Analogy Problem

People will inevitably map AI to a familiar base domain. Common (and problematic) analogies include:
- **AI as search engine** (leads to expecting factual retrieval rather than generation)
- **AI as database** (leads to expecting stored, retrievable ground truth)
- **AI as human expert** (leads to anthropomorphization and miscalibrated trust)
- **AI as calculator** (leads to expecting deterministic, verifiable outputs)

Training should **explicitly surface and address** these analogies rather than ignoring them. Per Gentner, analogies are most productive when their structural limitations are made explicit.

### 6.2 The Ontological Shift Required

Per Chi's framework, understanding AI/ML properly likely requires an **ontological category shift** — from thinking of AI as an entity/thing (that "knows" or "understands") to thinking of it as an emergent process (that generates outputs through statistical patterns). This is the hardest kind of conceptual change.

**Instructional strategy:** Teach the ontological category *first* (what kind of thing is this?), then the specific content (how does it work?).

### 6.3 Expect and Design for Synthetic Models

Per Vosniadou, learners will construct synthetic models that blend new information with old frameworks. These will seem internally consistent to the learner. Training must:
- Anticipate common synthetic models
- Create opportunities for learners to discover the inadequacy of their models (Posner et al.'s "dissatisfaction" condition)
- Use holistic model confrontation (Chi/Gadgil) — show the full correct model alongside the learner's model

### 6.4 Active Learning Over Passive Instruction

Per Carroll's minimalist instruction research:
- Get learners into real tasks immediately
- Use errors as learning opportunities rather than preventing them
- Provide guidance through key ideas and hints, not complete step-by-step specifications
- Streamline instruction to enable the learning process — prescribe less, enable more

### 6.5 Design for the System Image Gap

Per Norman, the "system image" of AI tools is often profoundly inadequate. When users cannot observe the internal workings of a system, and the system provides no coherent conceptual model through its interface, users will construct incorrect mental models. Training must serve as a supplement to the system image.

### 6.6 Account for Expertise Differences

Per Staggers & Norcio and Toker & Moseley, expert and novice mental models are structurally different. Training designed for one group will not serve the other. Novices need scaffolded models that build from surface features toward deep structure. Experts need models that connect to existing deep knowledge structures.

---

## 7. Key Researchers and Their Contributions (Reference Summary)

| Researcher | Affiliation | Primary Contribution | Key Work |
|---|---|---|---|
| Kenneth Craik | Cambridge | Originated mental model concept | *The Nature of Explanation* (1943) |
| Philip Johnson-Laird | Princeton | Formalized mental model theory for reasoning | *Mental Models* (1983) |
| Donald Norman | UCSD/Northwestern | Mental models in design; user vs. design models | *Design of Everyday Things* (1988/2013) |
| Dedre Gentner | Northwestern | Structure-mapping theory; analogical reasoning | Gentner (1983); Gentner & Stevens (1983) |
| Albert Stevens | BBN Technologies | Co-edited foundational mental models volume | Gentner & Stevens (1983) |
| John Carroll | IBM/Penn State | Minimalist instruction for technology learning | *The Nurnberg Funnel* (1990) |
| Michelene Chi | ASU | Ontological categories; three types of conceptual change | Chi, Slotta, & de Leeuw (1994); Chi (2008) |
| Stella Vosniadou | Athens/Flinders | Framework theory; synthetic models | Vosniadou & Brewer (1992); Vosniadou (1994) |
| Posner, Strike, Hewson, Gertzog | Cornell/Wisconsin | Classical conceptual change conditions (DIPF) | Posner et al. (1982) |
| Nancy Staggers | Utah | Expert vs. novice mental model differences | Staggers & Norcio (1993) |

---

## 8. Suggested Further Reading

### Foundational Texts
- Craik, K. J. W. (1943). *The Nature of Explanation*. Cambridge University Press.
- Johnson-Laird, P. N. (1983). *Mental Models*. Harvard University Press.
- Gentner, D., & Stevens, A. L. (Eds.). (1983). *Mental Models*. Lawrence Erlbaum Associates.
- Norman, D. A. (2013). *The Design of Everyday Things* (revised edition). Basic Books.

### Conceptual Change
- Vosniadou, S. (Ed.). (2008). *International Handbook of Research on Conceptual Change*. Routledge.
- Chi, M. T. H. (2008). Three types of conceptual change. In Vosniadou (Ed.), *International Handbook of Research on Conceptual Change*.
- Posner, G. J., et al. (1982). Accommodation of a scientific conception. *Science Education*, 66(2), 211–227.

### Technology Learning
- Carroll, J. M. (1990). *The Nurnberg Funnel*. MIT Press.
- Carroll, J. M. (2014). Creating minimalist instruction. *International Journal of Designs for Learning*, 5(2).

### AI/ML Mental Models (Recent)
- Tabel, O., et al. (2024). Identifying secondary school students' misconceptions about machine learning. *ICER 2024*. ACM.
- Chromik, M., et al. (2024). The Who in XAI. *CHI 2024*. ACM.
- Xie, Q., et al. (2025). Mental models of generative AI chatbot ecosystems. *IUI 2025*. ACM.
- Hoffman, R. R., et al. (2023). Measures for explainable AI. *Frontiers in Computer Science*.

---

*Document compiled: 2026-02-22. Sources are peer-reviewed publications, academic press books, and established research institution outputs (.edu, ACM, IEEE, Springer, Wiley, Elsevier).*
