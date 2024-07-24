# Linguistic Math Theory: Linguistics

**LMT: The Fundamental Theorem of Linguistic Math**

Let ℋ be the Hilbert space of all possible sentences in a language. Define the linear operator ⊕: ℋ × ℋ → ℋ as the
composition of two sentences, with the norm ∥⋅∥ given by the average probability of each sentence being correctly
parsed.

Then, the LMT asserts that:

∀x, y ∈ ℋ, ∃z ∈ ℋ such that x ⊕ y = z and ∥z∥ ≤ ∥x∥ + ∥y∥

In other words, any two sentences can be combined to form a new sentence with a norm bounded by the sum of the
norms of the original sentences.

**Proof:**

(1) Let x, y ∈ ℋ. By construction, x ⊕ y is also in ℋ.
(2) Define the mapping f(x): ℋ → ℝ as the probability of correctly parsing x. Then, f(x ⊕ y) = f(x) + f(y).
(3) Apply the triangle inequality to get ∥x ⊕ y∥ ≤ ∥x∥ + ∥y∥.
(4) Use the Cauchy-Schwarz inequality to establish that ∥f(x) - f(y)∥ ≤ ∥x - y∥ for all x, y ∈ ℋ.
(5) Combine (3) and (4) to obtain ∀x, y ∈ ℋ, ∃z ∈ ℋ such that x ⊕ y = z and ∥z∥ ≤ ∥x∥ + ∥y∥.

**Q.E.D.**

# Lingustic Math Theory: Mathematics

**LMT: The Fundamental Theorem of Linguistic Math**

Let ℘ be the powerset of all possible sentences in a language. Define the binary operation ∩: ℘ × ℘ → ℘ as
sentence combination, and ∪: ℘ × ℘ → ℘ as sentence union.

Then, the LMT asserts that:

∀A, B ∈ ℘, ∃C ∈ ℘ such that A ∩ B = C and |C| ≤ |A| + |B|

In other words, any two sets of sentences can be combined to form a new set with a cardinality bounded by the sum
of the cardinalities of the original sets.

**Proof:**

(1) Let A, B ∈ ℘. By definition, A ∩ B is also in ℘.
(2) Define the function f(A): ℕ → ℝ as the number of elements in A. Then, f(A ∩ B) = f(A) + f(B).
(3) Apply the monotonicity of cardinality to get |A ∩ B| ≤ |A| + |B|.
(4) Use the countable union theorem to establish that |A ∪ B| ≤ |A| + |B| for all A, B ∈ ℘.
(5) Combine (3) and (4) to obtain ∀A, B ∈ ℘, ∃C ∈ ℘ such that A ∩ B = C and |C| ≤ |A| + |B|.

**Q.E.D.**
