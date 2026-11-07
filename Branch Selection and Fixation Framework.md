## From Branch Switching of Polynomial Roots to Quantum Measurement: A Conceptual Proposal



## A Loose Association:

What first brought wavefunction collapse to mind was the intuitive impression that, in root finding or root extraction, "one particular root is found or made definite": among multiple possible outcomes, some operation makes one outcome definite. This led to a question: could this "act of making an outcome definite," reminiscent of wavefunction collapse, itself be defined as a basic mathematical operation, with axiomatic rules specifying its behavior? Like root finding and root extraction, it could then become a tool for further composition, deduction, and calculation.

I provisionally call this line of inquiry "branch selection and fixation." It does not yet have a complete definition or axiomatic system, and I do not want to commit prematurely to any particular interpretation. What these branches represent and how the other possibilities change once one is fixed can remain open for now. At this stage, I am only outlining the idea.

The phenomenon intended here is probably not ordinary "root extraction"; it may be closer to "branch switching in multivalued functions" and "root permutation in the process of making a function single-valued."

There are two parts to this:
- Root exchange and uncertainty: Under certain mathematical conditions, the roots of an equation exchange identities as its parameters change, so we cannot consistently assign them fixed labels throughout the parameter space.

- Fixing one outcome through an operation: Can we define a new mathematical operation that describes selecting one of several possible branches, and incorporate the selection process itself into mathematical calculation?



## A Mathematical Phenomenon: Root Exchange (Monodromy)

A typical example is 

$$
 z^2=w 
$$



It has two roots: 

$$
 z_1=\sqrt{w},\qquad z_2=-\sqrt{w} 
$$



Suppose we let $w$ make one circuit around the origin in the complex plane: 

$$
 w=e^{i\theta},\quad 0\leq\theta\leq 2\pi 
$$



The two roots can then be written as 

$$
 z_1=e^{i\theta/2} 
$$

, 

$$
 z_2=-e^{i\theta/2} 
$$



When $w$ makes one circuit around the origin and returns to its starting point: 

$$
 z_1\longrightarrow z_2 
$$

, 

$$
 z_2\longrightarrow z_1 
$$



In other words, the input parameter has returned to its starting point, but the two roots have exchanged identities.



For a cubic equation, the situation can be more complex: the three roots may undergo a cyclic exchange.

For example: 

$$
 z^3=w 
$$



The three roots are: 

$$
 z_k=e^{i(\theta+2k\pi)/3} 
$$



When $w$ makes one circuit around the origin, the three roots exchange positions in sequence, forming a three-cycle.



Let the parameter w make one circuit along the unit circle in the complex plane while we continuously track one root:

$z^2 = w$, $w = \exp(i\theta)$, $z_+(\theta) = \exp(i\theta/2)$
$\theta$: $0 \to 2\pi$; $w$: $1 \to 1$; $z_+$: $1 \to -1$

The parameter returns to its starting point, but the tracked branch reaches the other root; it returns to its initial value only after a second circuit.

This mathematical effect depends on the path taken. It closely resembles the description "the roots keep exchanging positions, and it is initially impossible to tell which is which."



## Connections to Physical Phenomena

This phenomenon seems related to exceptional points in quantum mechanics and to topological exchanges of quantum states.

In certain non-Hermitian quantum systems, the eigenvalues and eigenstates of the Hamiltonian coalesce at particular points in parameter space.



Suppose: 

$$
 H(\lambda)|\psi\rangle=E(\lambda)|\psi\rangle 
$$



Near an exceptional point, the eigenvalues may exhibit square-root branching: 

$$
 E_\pm(\lambda)=E_0\pm\sqrt{\lambda} 
$$



When the parameter makes one circuit around the exceptional point: 

$$
 E_+\longrightarrow E_- 
$$

, 

$$
 E_-\longrightarrow E_+ 
$$





This has almost the same mathematical structure as the square-root exchange described above.

In 2001, Dembowski and colleagues observed the topological structure of an exceptional point in microwave-cavity experiments, finding that one circuit around the exceptional point led to an exchange of the eigenvalues and eigenstates.

A study published in PRX Quantum in 2025 used superconducting circuits to investigate eigenvalue braiding near a third-order exceptional point.

The study observed topological exchanges among three eigenstates and used a key mathematical tool: 

$$
 B_3 
$$

, the three-strand braid group.



What is particularly interesting is this:

The initial picture was of three roots continually exchanging places, with no fixed identities; modern quantum physics does indeed have theories that describe exchanges among multiple eigenstates in terms of "braiding."

However, the exchange of eigenstates at exceptional points is not the same as wavefunction collapse in ordinary quantum measurement.

Their mathematical structures are similar, but their physical mechanisms differ.



## Can We Define a New Mathematical Symbol Specifically for "Root Extraction, Turning Over a Card, and Fixing a Solution"?

My idea is not actually to reinvent the square root, but to define a new mathematical operation:

**A system has several possible branches, which can exchange identities as its parameters change;**

**When a particular operation occurs, one branch is selected and becomes the system's current definite state.**



To express this abstractly, suppose a system has three possible states: 

$$
 \mathcal{S}=\{s_1,s_2,s_3\} 
$$



Let us define a new operation, provisionally denoted by 

$$
 \boxed{\mathfrak{F}} 
$$



We call it the "branch fixation operator" (this is a provisional symbol I have introduced for discussion, not an established mathematical symbol).

It has two parts.



Part One: Branch Exchange.

Define an exchange operation: 

$$
 \mathfrak{P}: (s_1,s_2,s_3) \longrightarrow (s_2,s_3,s_1) 
$$



This represents a cyclic permutation of the three possible states.



Part Two: Branch Fixation.

Define: 

$$
 \mathfrak{F}_k(\mathcal{S})=s_k 
$$



This represents selecting one of several possible branches.

We can therefore express your idea as 

$$
 \boxed{ \mathcal{S} \xrightarrow{\mathfrak{P}} \mathcal{S}' \xrightarrow{\mathfrak{F}_k} s_k } 
$$





This process can be understood as follows:

1. The system has multiple distinguishable possible branches.
2. The branches exchange identities as the system evolves.
3. An operation triggers branch selection.
4. The system enters a definite branch.



But this raises a question about 

$$
 \mathfrak{F}_k 
$$

:

How is $k$ determined?

If we specify $k$ directly, this is simply a choice we make.

If we let it select randomly, we must define the probability: 

$$
 P(s_k) 
$$





## Conceptual Framework

Let us try to develop an independent conceptual framework, provisionally called:

Branch Selection and Fixation Theory (Branch Selection and Fixation Framework)

It could have three basic axioms.

### Axiom 1: Multiple Branches Exist

For a given parameter setting, a system has multiple possible states: 

$$
 \Psi=\sum_{i=1}^{n}c_i|s_i\rangle 
$$



### Axiom 2: Branches Can Be Permuted

As the system's parameters change, the branches may be permuted: 

$$
 \mathfrak{P}(\Psi) = \sum_{i=1}^{n}c_i|s_{\sigma(i)}\rangle 
$$



where $\sigma$ is a permutation.

### Axiom 3: Branch Fixation

When a particular selection event occurs: 

$$
 \mathfrak{F}(\Psi)=|s_k\rangle 
$$



where $k$ identifies the branch ultimately selected.



## Questions

This is only a conceptual framework. The following questions may arise:

1. What conditions trigger fixation?
2. Why is this branch selected rather than another?
3. Is there a temporal relationship between permutation and fixation?
4. After fixation, do the other branches disappear, become unobservable, or continue to exist?
5. Do the roots themselves keep exchanging identities until an operation fixes one of them? For example, could three roots repeatedly exchange identities in a cycle until a selection at some point fixes one root?
6. Do the roots in fact exist throughout, while we are unable to determine which root currently corresponds to which state? Could what we call collapse simply be an operation that identifies a previously unidentifiable branch?
7. Could root exchange and fixation themselves constitute a new physical process? Could selection arise from an intrinsic mechanism in the system, analogous to turning over a card, extracting a root, or locking in an outcome, rather than from human observation?



I cannot answer these questions here, because I do not know the answers myself.



## An Interpretation in Terms of Possibilities

Let us keep all possibilities open simultaneously for now.

Suppose there is a system: 

$$
 \Omega=\{\omega_1,\omega_2,\ldots,\omega_n\} 
$$



Here, $\Omega$ is a set of possibilities, not an already determined physical state.

For now, we leave unspecified:

- Whether these possibilities actually exist.
- Whether they can exchange identities.
- Whether they are merely states that an observer cannot distinguish.
- Whether the other states disappear once one is made definite.
- Whether the process of making one definite is random or follows some intrinsic rule.

For now, we acknowledge only one fact: a system's description contains multiple possibilities, and certain operations alter our degree of certainty about those possibilities.



## Mathematical Object

What is described here seems to be an object with the following properties:

- It contains multiple possible solutions.
- These solutions may exchange identities.
- The exchange process may not be fully describable using a single label.
- An operation can make one solution definite, temporarily or permanently.
- The act of making a solution definite may itself change the entire system.

We may provisionally call this a dynamic branch object.

Note that this is only a mathematical concept to be investigated, not an established mathematical theory.

The aim is to study not only what the multiple solutions are, but also "how they change" and "what effects arise from the act of making one solution definite."



## Mathematical Structure

The initial description of this idea was:

"Extract the roots, then fix one of them."



Ordinary root extraction: 

$$
 x=\sqrt{a} 
$$



This already specifies what result we seek.

But what if we approached this the other way around?

Suppose an operation on a mathematical object yields multiple solutions whose identities are not permanently fixed.

Could we then define a new operation 

$$
 \mathfrak{R}(X) 
$$



that returns a single object encompassing branch relationships, exchange rules, and potential fixed states, rather than a numerical value directly?

Then define another operation: 

$$
 \mathfrak{L}(\mathfrak{R}(X)) 
$$



where $\mathfrak{L}$ does not necessarily eliminate the other branches, but instead brings the system into some definite state.



For now, these two symbols are only part of a preliminary research sketch.

They suggest a direction: treat the generation of multiple possibilities and the fixation of one possibility as two independent basic mathematical operations.

Could this allow us to study the mathematical structure first, without yet knowing exactly what collapse is?

First construct the mathematical object and examine whether it is internally consistent; then ask whether it can describe quantum measurement.