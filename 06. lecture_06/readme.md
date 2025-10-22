
## 🧠 Quick Overview
- **Probability Theory** deals with uncertainty, events, and likelihood using mathematical frameworks.
- Key topics include classical vs. empirical probability, conditional probability, Bayes' theorem, and combinatorics.
- Applications range from AI and Bayesian networks to everyday decision-making and risk assessment.
- Tools include tree diagrams, probability rules, and counting principles (permutations & combinations).

---

## 🧠 Bayesian Neural Networks

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Bayesian Neural Networks use **Bayesian inference** to model uncertainty in predictions.
- Unlike traditional neural networks, weights are **probabilistic**, not fixed.
- They update beliefs as new evidence arrives.

**Lecture Highlights:**
- Integrates probability theory with neural networks for better uncertainty handling.
- Useful in scenarios with incomplete or noisy data.

**🚨 Difficult Concepts List:**
- How does Bayesian inference differ from standard training?
- Why are weights treated as distributions?
- What is the practical advantage of using Bayesian neural networks?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Relevant Technologies/Tools:**
- Probabilistic programming languages (e.g., Pyro, Edward)
- Bayesian inference libraries (e.g., PyMC3, TensorFlow Probability)

**Real-World Applications:**
- Medical diagnosis under uncertainty
- Autonomous driving in unpredictable environments
- Anomaly detection in cybersecurity

**Research Links:**
- Look up: *Variational Inference in Bayesian Neural Networks*
- Learn more about: *Monte Carlo Dropout for Uncertainty Estimation*

### 🛠️ C: CREATION & APPLICATION
**Case Studies/Examples:**
- Predicting disease onset from incomplete patient data.

**Project Ideas:**
- Build a simple Bayesian CNN for image classification with uncertainty scores.

**Problem-Solving Exercises:**
- Compare the output confidence of a Bayesian NN vs. a standard NN on a small dataset.

---

## 📊 Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- **Probability**: Likelihood of an event occurring, between 0 and 1.
- **Sample Space**: Set of all possible outcomes.
- **Event**: A subset of the sample space.

**Lecture Highlights:**
- Used to model real-world uncertainty.
- Foundation for statistical inference and machine learning.

**🚨 Difficult Concepts List:**
- What’s the difference between probability and odds?
- How is probability interpreted in frequentist vs. Bayesian views?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Risk assessment, insurance, game theory, AI decision-making.

**Research Links:**
- Look up: *Axiomatic Foundations of Probability*

### 🛠️ C: CREATION & APPLICATION
**Project Ideas:**
- Simulate coin tosses and die rolls to verify probability rules.

**Problem-Solving Exercises:**
- If P(A) = 0.3 and P(B) = 0.4, and A and B are independent, find P(A ∪ B).

---

## 🌍 Basic Causes of Uncertainty

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Uncertainty arises from incomplete information, measurement errors, and environmental variability.

**Lecture Highlights:**
- Leading causes: unreliable sources, equipment faults, climate change, experimental errors.

**🚨 Difficult Concepts List:**
- How can we quantify uncertainty?
- What’s the difference between epistemic and aleatoric uncertainty?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Weather forecasting, financial markets, diagnostic systems.

**Research Links:**
- Learn more about: *Uncertainty Quantification in Engineering*

---

## 📘 Basic Terminologies in Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- **Random Experiment**: Process with uncertain outcomes.
- **Trial**: One performance of an experiment.
- **Mutually Exclusive**: Events that cannot occur together.
- **Independent Events**: Occurrence of one doesn’t affect the other.

**Lecture Highlights:**
- Understanding terminology is essential for solving probability problems.

**🚨 Difficult Concepts List:**
- How to identify mutually exclusive vs. independent events?
- What is the difference between outcome and event?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Game design, polling, quality control.

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- List sample spaces for: tossing 2 coins, rolling a die, drawing a card.

---

## 🎲 Classical Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Assumes all outcomes are equally likely.
- Formula: \( P(E) = \frac{n(E)}{n(S)} \)

**Lecture Highlights:**
- Used when the sample space is known and finite.

**🚨 Difficult Concepts List:**
- When is classical probability not applicable?
- How does it differ from empirical probability?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Fair games, lottery design, card games.

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Find the probability of drawing a king from a deck of cards.

---

## 📈 Empirical / Relative Frequency Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Based on observed data or experiments.
- Formula: \( P(E) = \frac{f}{n} \)

**Lecture Highlights:**
- Used when theoretical probability is unknown or unreliable.

**🚨 Difficult Concepts List:**
- How many trials are needed for a reliable empirical probability?
- Can empirical probability be used for one-time events?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Clinical trials, customer behavior analysis, sports statistics.

### 🛠️ C: CREATION & APPLICATION
**Project Ideas:**
- Toss a coin 100 times and compare empirical vs. classical probability of heads.

---

## 📏 Basic Rules of Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- \( 0 \leq P(E) \leq 1 \)
- \( P(S) = 1 \)
- Sum of probabilities of all outcomes = 1

**Lecture Highlights:**
- Foundation for all probability calculations.

**🚨 Difficult Concepts List:**
- Why can’t probability be greater than 1 or less than 0?
- What does \( P(S) = 1 \) imply?

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- If P(A) = 0.6, what is P(Aᶜ)?

---

## 🔁 Complementary Events

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Complement of E: \( E^c = S \setminus E \)
- \( P(E^c) = 1 - P(E) \)

**Lecture Highlights:**
- Simplifies calculation when dealing with “not” events.

**🚨 Difficult Concepts List:**
- When is it easier to use complementary probability?

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Probability of not drawing a heart from a deck.

---

## ➕ Addition Rule for Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Mutually Exclusive: \( P(A \cup B) = P(A) + P(B) \)
- Non-Mutually Exclusive: \( P(A \cup B) = P(A) + P(B) - P(A \cap B) \)

**Lecture Highlights:**
- Used to find the probability of either of two events occurring.

**🚨 Difficult Concepts List:**
- How to know if events are mutually exclusive?
- Why subtract \( P(A \cap B) \) in the non-mutually exclusive case?

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- A card is drawn. Find P(king or black).

---

## 🚫 Mutually Exclusive Events

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Two events that cannot happen at the same time.

**Lecture Highlights:**
- No overlap in outcomes.

**🚨 Difficult Concepts List:**
- Can two mutually exclusive events be independent?

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Rolling a die: P(even or odd).

---

## 🌳 Tree Diagram

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- Visual tool to represent all possible outcomes of a sequence of events.

**Lecture Highlights:**
- Useful for multi-step experiments.

**🚨 Difficult Concepts List:**
- How to assign probabilities to branches?
- When to use tree diagrams vs. formulas?

### 🛠️ C: CREATION & APPLICATION
**Project Ideas:**
- Draw a tree diagram for tossing a coin and then rolling a die.

---

## 🔗 Dependent and Independent Events

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- **Independent**: \( P(A \cap B) = P(A) \cdot P(B) \)
- **Dependent**: \( P(A \cap B) = P(A) \cdot P(B|A) \)

**Lecture Highlights:**
- Independence means one event doesn’t influence the other.

**🚨 Difficult Concepts List:**
- How to test for independence?
- Why does sampling without replacement lead to dependence?

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Two cards drawn without replacement: P(both aces).

---

## ✖️ Multiplication Rules and Conditional Probability

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- **Conditional Probability**: \( P(B|A) = \frac{P(A \cap B)}{P(A)} \)
- Multiplication Rule: \( P(A \cap B) = P(A) \cdot P(B|A) \)

**Lecture Highlights:**
- Essential for updating beliefs given new evidence.

**🚨 Difficult Concepts List:**
- What does \( P(B|A) \) really mean?
- How is conditional probability used in real life?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Spam filtering, medical testing, recommendation systems.

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Given P(A) = 0.5, P(B|A) = 0.3, find \( P(A \cap B) \).

---

## 🧾 Bayes’ Theorem

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- \( P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)} \)
- Updates prior probability with new evidence.

**Lecture Highlights:**
- Foundation of Bayesian inference.

**🚨 Difficult Concepts List:**
- How to choose prior probabilities?
- When is Bayes’ theorem more useful than frequentist methods?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Diagnostic testing, machine learning, legal reasoning.

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- Given: P(Disease) = 0.01, P(+|Disease) = 0.99, P(+|No Disease) = 0.05. Find P(Disease|+).

---

## 🔢 Permutation and Combination

### ❓ Q: CORE CONCEPTS & QUESTIONS
**Key Definitions:**
- **Permutation**: Order matters → \( P(n, r) = \frac{n!}{(n - r)!} \)
- **Combination**: Order doesn’t matter → \( C(n, r) = \frac{n!}{r!(n - r)!} \)

**Lecture Highlights:**
- Used for counting arrangements and selections.

**🚨 Difficult Concepts List:**
- When to use permutation vs. combination?
- How to handle indistinguishable objects?

### 🔍 E: EXPLORATION & TECHNOLOGIES
**Real-World Applications:**
- Password generation, committee selection, lottery draws.

### 🛠️ C: CREATION & APPLICATION
**Problem-Solving Exercises:**
- How many ways to choose 3 students from 10? How many ways to arrange 3 books out of 5?

---

## 📚 Key Terms Glossary

| Term | Definition |
|------|------------|
| Sample Space | All possible outcomes of an experiment |
| Event | Subset of the sample space |
| Mutually Exclusive | Events that cannot occur together |
| Independent | One event doesn’t affect the other |
| Conditional Probability | Probability of an event given another has occurred |
| Bayes’ Theorem | Updates probability based on new evidence |
| Permutation | Arrangement where order matters |
| Combination | Selection where order doesn’t matter |

---

## ✅ Action Items for Next Study Session

---

## ✅ 1. Solve 5 Problems Using Bayes’ Theorem

Here are 5 problems of varying difficulty, complete with solutions.

### Problem 1: The Classic Disease Test
A certain disease affects 1% of a population. A test for the disease is 99% accurate (meaning it returns a positive result for 99% of people who have the disease and a negative result for 99% of people who do not). If a person tests positive, what is the probability they actually have the disease?

**Solution:**
- Let \( D \) = has the disease, \( T^+ \) = tests positive.
- \( P(D) = 0.01 \), \( P(T^+|D) = 0.99 \), \( P(T^+|\neg D) = 0.01 \)
- We want \( P(D|T^+) \)

\[
P(D|T^+) = \frac{P(T^+|D)P(D)}{P(T^+|D)P(D) + P(T^+|\neg D)P(\neg D)} = \frac{0.99 \times 0.01}{(0.99 \times 0.01) + (0.01 \times 0.99)} = \frac{0.0099}{0.0099 + 0.0099} = 0.5
\]

**Answer:** There is only a **50% chance** they have the disease, despite the positive test.

---

### Problem 2: Factory Machines (From Slides Pg. 91-94)
Three machines \( B_1, B_2, B_3 \) make 30%, 45%, and 25% of products, respectively. Their defect rates are 2%, 3%, and 2%. A randomly selected product is defective. What is the probability it came from Machine \( B_3 \)?

**Solution:**
- Let \( D \) = defective.
- \( P(B_1)=0.30, P(D|B_1)=0.02 \)
- \( P(B_2)=0.45, P(D|B_2)=0.03 \)
- \( P(B_3)=0.25, P(D|B_3)=0.02 \)

We want \( P(B_3|D) \).

\[
P(D) = (0.30)(0.02) + (0.45)(0.03) + (0.25)(0.02) = 0.006 + 0.0135 + 0.005 = 0.0245
\]
\[
P(B_3|D) = \frac{P(D|B_3)P(B_3)}{P(D)} = \frac{0.005}{0.0245} \approx 0.204
\]

**Answer:** The probability is approximately **20.4%**.

---

### Problem 3: The Coin & Boxes (From Slides Pg. 77-84)
Box 1 has 2 red and 1 blue ball. Box 2 has 3 blue and 1 red ball. A coin is tossed: if Heads, Box 1 is chosen; if Tails, Box 2. A red ball is drawn. What is the probability it came from Box 1?

**Solution:**
- Let \( B_1 \) = Box 1 chosen, \( B_2 \) = Box 2 chosen, \( R \) = red ball.
- \( P(B_1) = P(B_2) = 0.5 \)
- \( P(R|B_1) = \frac{2}{3} \), \( P(R|B_2) = \frac{1}{4} \)

We want \( P(B_1|R) \).

\[
P(R) = P(B_1)P(R|B_1) + P(B_2)P(R|B_2) = (0.5)(\frac{2}{3}) + (0.5)(\frac{1}{4}) = \frac{1}{3} + \frac{1}{8} = \frac{11}{24}
\]
\[
P(B_1|R) = \frac{P(R|B_1)P(B_1)}{P(R)} = \frac{\frac{2}{3} \times 0.5}{\frac{11}{24}} = \frac{\frac{1}{3}}{\frac{11}{24}} = \frac{1}{3} \times \frac{24}{11} = \frac{8}{11} \approx 0.727
\]

**Answer:** The probability is approximately **72.7%**.

---

### Problem 4: The Lie Detector
A lie detector test is 90% accurate (i.e., \( P(\text{Test +} | \text{Lie}) = 0.9 \) and \( P(\text{Test -} | \text{Truth}) = 0.9 \)). Suppose 5% of people in a security line are lying. If the test beeps (positive), what's the probability the person is actually lying?

**Solution:**
- Let \( L \) = lying, \( T^+ \) = test positive.
- \( P(L) = 0.05 \), \( P(T^+|L) = 0.90 \), \( P(T^+|\neg L) = 0.10 \)

We want \( P(L|T^+) \).

\[
P(L|T^+) = \frac{P(T^+|L)P(L)}{P(T^+|L)P(L) + P(T^+|\neg L)P(\neg L)} = \frac{0.90 \times 0.05}{(0.90 \times 0.05) + (0.10 \times 0.95)} = \frac{0.045}{0.045 + 0.095} = \frac{0.045}{0.14} \approx 0.321
\]

**Answer:** The probability is only about **32.1%**.

---

### Problem 5: Email Spam Filter
In your inbox, 2% of emails are spam. Your spam filter is 95% accurate at identifying spam (5% false negative rate) and 98% accurate at identifying non-spam (2% false positive rate). If an email is flagged as spam, what is the probability it is actually spam?

**Solution:**
- Let \( S \) = spam, \( F \) = flagged.
- \( P(S) = 0.02 \), \( P(F|S) = 0.95 \), \( P(F|\neg S) = 0.02 \)

We want \( P(S|F) \).

\[
P(S|F) = \frac{P(F|S)P(S)}{P(F|S)P(S) + P(F|\neg S)P(\neg S)} = \frac{0.95 \times 0.02}{(0.95 \times 0.02) + (0.02 \times 0.98)} = \frac{0.019}{0.019 + 0.0196} = \frac{0.019}{0.0386} \approx 0.492
\]

**Answer:** The probability is about **49.2%**.

---

## ✅ 2. Draw Tree Diagrams for 2 Multi-step Probability Experiments

### Experiment 1: Tossing a Coin and Rolling a Die
**Question:** What is the probability of getting a Head followed by an even number?
```
Start
  │
  ├── Head (0.5)
  │     │
  │     ├── 1 (1/6) -> P = 0.5 * 1/6
  │     ├── 2 (1/6) -> P = 0.5 * 1/6
  │     ├── 3 (1/6) -> P = 0.5 * 1/6
  │     ├── 4 (1/6) -> P = 0.5 * 1/6
  │     ├── 5 (1/6) -> P = 0.5 * 1/6
  │     └── 6 (1/6) -> P = 0.5 * 1/6
  │
  └── Tail (0.5)
        │
        ├── 1 (1/6) -> P = 0.5 * 1/6
        ├── 2 (1/6) -> P = 0.5 * 1/6
        ├── 3 (1/6) -> P = 0.5 * 1/6
        ├── 4 (1/6) -> P = 0.5 * 1/6
        ├── 5 (1/6) -> P = 0.5 * 1/6
        └── 6 (1/6) -> P = 0.5 * 1/6
```
**Calculation for "Head and Even":**
Even numbers are {2, 4, 6}.
\( P = 0.5 \times (\frac{1}{6} + \frac{1}{6} + \frac{1}{6}) = 0.5 \times 0.5 = 0.25 \)

---

### Experiment 2: The Box and Ball Problem (from above)
**Question:** What is the probability of drawing a red ball?
```
Start
  │
  ├── Box1 (0.5)
  │     │
  │     ├── Red (2/3) -> P = (1/2)*(2/3) = 2/6
  │     └── Blue (1/3) -> P = (1/2)*(1/3) = 1/6
  │
  └── Box2 (0.5)
        │
        ├── Red (1/4) -> P = (1/2)*(1/4) = 1/8
        └── Blue (3/4) -> P = (1/2)*(3/4) = 3/8
```
**Calculation for "Red Ball":**
Add the probabilities of the two paths leading to Red:
\( P(R) = \frac{2}{6} + \frac{1}{8} = \frac{8}{24} + \frac{3}{24} = \frac{11}{24} \)

---

## ✅ 3. Differentiate Between 3 Pairs of Similar Terms

### Pair 1: Independent Events vs. Mutually Exclusive Events

| Feature | Independent Events | Mutually Exclusive Events |
| :--- | :--- | :--- |
| **Definition** | Occurrence of one does **not affect** the probability of the other. | They **cannot occur** at the same time. |
| **Mathematical Rule** | \( P(A \cap B) = P(A) \cdot P(B) \) | \( P(A \cap B) = 0 \) |
| **Venn Diagram** | Overlapping circles. | Non-overlapping circles. |
| **Example** | Tossing a coin and rolling a die. | Getting a 1 and a 6 on a single die roll. |
| **Key Question** | "Does knowing A happened change the chance of B?" (No) | "Can A and B happen together?" (No) |

**Critical Insight:** If two events are mutually exclusive and both have non-zero probability, they **cannot be independent**. If A happens, B becomes impossible, so the probability of B is changed.

---

### Pair 2: Permutation vs. Combination

| Feature | Permutation | Combination |
| :--- | :--- | :--- |
| **Order Matters?** | **Yes** | **No** |
| **Keyword** | **Arrangement**, sequence, order | **Selection**, group, committee |
| **Formula** | \( P(n, r) = \frac{n!}{(n-r)!} \) | \( C(n, r) = \frac{n!}{r!(n-r)!} \) |
| **Example** | How many ways to award 1st, 2nd, 3rd prize to 3 people out of 10? | How many ways to choose a committee of 3 people from 10? |
| **Answer to Example** | \( P(10, 3) = 10 \times 9 \times 8 = 720 \) | \( C(10, 3) = \frac{10 \times 9 \times 8}{3 \times 2 \times 1} = 120 \) |

**Memory Tip:** **P**ermutation for **P**lacement. **C**ombination for **C**hoice.

---

### Pair 3: Classical Probability vs. Empirical Probability

| Feature | Classical (Theoretical) Probability | Empirical (Experimental) Probability |
| :--- | :--- | :--- |
| **Basis** | **Theoretical** reasoning and assumptions. | **Actual observation** and data collection. |
| **Calculation** | \( P(E) = \frac{\text{Favorable Outcomes}}{\text{Total Outcomes}} \) | \( P(E) = \frac{\text{Frequency of Event}}{\text{Total Trials}} \) |
| **When Used** | When all outcomes are **equally likely** (e.g., fair dice, coins). | When outcomes are **not equally likely** or the process is complex. |
| **Example** | P(Heads) on a fair coin = 1/2. | A bat hits a home run in 30 out of 100 at-bats. P(Home Run) = 0.30. |
| **Accuracy** | Exact, under its assumptions. | Approximate; improves with more data. |

**Key Idea:** Classical is what you **expect** to happen. Empirical is what **actually** happens.

---

## ✅ 4. Watch a Video on Bayesian Neural Networks

**Recommendation:** Search for the following on YouTube. These are excellent starting points:

1.  **"Bayesian Neural Networks - A Beginner's Guide"** by Arxiv Insights
2.  **"What are Bayesian Neural Networks?"** by ComputerVisionFoundation Videos

**While you watch, look for answers to these questions from your notes:**
- How are weights represented differently in a Bayesian NN compared to a traditional NN?
- What is the practical benefit of having a network that knows when it's uncertain?
- What is the main computational challenge in training Bayesian NNs? (Hint: It often involves "sampling" or "approximation").

---

## ✅ 5. Attempt the Quiz Problems (From Slides Pg. 113–115)

Here are the solutions to check your work.

### Quiz #1 & #2 Problems

**1. (a) Urn Problem (Complex Rules)**
This is a complex conditional problem best solved with a tree diagram.
- **Step 1:** First Draw.
    - P(Green first) = 4/9. Then add 2 red. Urn becomes 7 Red, 3 Green. **P(Red second | Green first) = 7/10.**
    - P(Red first) = 5/9. Then add 1 red & 1 green. Urn becomes 6 Red, 5 Green. **P(Red second | Red first) = 6/11.**
- **Step 2:** Use Law of Total Probability.
\[
P(\text{Red second}) = (\frac{4}{9} \times \frac{7}{10}) + (\frac{5}{9} \times \frac{6}{11}) = \frac{28}{90} + \frac{30}{99} \approx 0.311 + 0.303 = 0.614
\]

**1. (b) Urn Problem (Simpler Rules)**
- **Step 1:** First Draw.
    - P(Green first) = 4/9. Add 1 red. Urn becomes 6 Red, 3 Green. **P(Red second | Green first) = 6/9.**
    - P(Red first) = 5/9. Add 1 green. Urn becomes 5 Red, 5 Green. **P(Green second | Red first) = 5/10.**
- We want P(Different Colors). This can happen in two ways: (Green then Red) OR (Red then Green).
\[
P(\text{Diff}) = (\frac{4}{9} \times \frac{6}{9}) + (\frac{5}{9} \times \frac{5}{10}) = \frac{24}{81} + \frac{25}{90} \approx 0.296 + 0.278 = 0.574
\]

**2. Married Couples Voting**
Let H = husband votes, W = wife votes.
Given: \( P(H)=0.21, P(W)=0.28, P(H \cap W)=0.15 \)

**(i) P(at least one votes)**
\[
P(H \cup W) = P(H) + P(W) - P(H \cap W) = 0.21 + 0.28 - 0.15 = 0.34
\]

**(ii) P(Wife votes | Husband votes)**
\[
P(W|H) = \frac{P(W \cap H)}{P(H)} = \frac{0.15}{0.21} \approx 0.714
\]

**(iii) P(Husband votes | Wife does not vote)**
\[
P(H|\neg W) = \frac{P(H \cap \neg W)}{P(\neg W)} = \frac{P(H) - P(H \cap W)}{1 - P(W)} = \frac{0.21 - 0.15}{1 - 0.28} = \frac{0.06}{0.72} \approx 0.0833
\]




