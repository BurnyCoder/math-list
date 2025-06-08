# Mathematical Logic

[Back to Foundations](./index.md)

Mathematical logic is a subfield of mathematics exploring the applications of formal logic to mathematics. It has close connections to metamathematics, the foundations of mathematics, and theoretical computer science.

## Propositional Logic

Propositional logic is the branch of logic that studies ways of joining and/or modifying entire propositions, statements or sentences to form more complicated propositions, statements or sentences, as well as the logical relationships and properties that are derived from these methods of combining or altering statements.

### Propositions
A **proposition** is a declarative statement that is either true or false.

**Examples:**
*   "The sky is blue." (Proposition, which is true)
*   "2 + 2 = 5" (Proposition, which is false)
*   "What time is it?" (Not a proposition)

### Logical Connectives

*   **Negation (\(\neg\))**: "not"
    *   \(\neg P\) is true if \(P\) is false.
*   **Conjunction (\(\land\))**: "and"
    *   \(P \land Q\) is true if both \(P\) and \(Q\) are true.
*   **Disjunction (\(\lor\))**: "or"
    *   \(P \lor Q\) is true if at least one of \(P\) or \(Q\) is true.
*   **Implication (\(\rightarrow\))**: "implies" or "if...then..."
    *   \(P \rightarrow Q\) is false only when \(P\) is true and \(Q\) is false.
*   **Biconditional (\(\leftrightarrow\))**: "if and only if"
    *   \(P \leftrightarrow Q\) is true when \(P\) and \(Q\) have the same truth value.

### Truth Tables

A truth table is a mathematical table used in logic to compute the functional values of logical expressions on each of their functional arguments, that is, for each combination of values taken by their logical variables.

**Example: Truth table for \(P \rightarrow Q\)**

| \(P\) | \(Q\) | \(P \rightarrow Q\) |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |

## Predicate Logic

Predicate logic is an extension of propositional logic that allows for more complex statements involving variables and quantifiers.

### Predicates
A **predicate** is a statement that contains variables and may be true or false depending on the values of these variables.

**Example:**
Let \(P(x)\) be the statement "x > 3". \(P(4)\) is true, while \(P(2)\) is false.

### Quantifiers

*   **Universal Quantifier (\(\forall\))**: "for all"
    *   \(\forall x, P(x)\) means that \(P(x)\) is true for every value of \(x\).
    **Example:** \(\forall x \in \mathbb{R}, x^2 \ge 0\). (For all real numbers x, x squared is greater than or equal to 0).

*   **Existential Quantifier (\(\exists\))**: "there exists"
    *   \(\exists x, P(x)\) means that there is at least one value of \(x\) for which \(P(x)\) is true.
    **Example:** \(\exists x \in \mathbb{Z}, x^2 = 4\). (There exists an integer x such that x squared is 4. Here x could be 2 or -2). 