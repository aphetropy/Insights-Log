# • Contrapositive

> **Key Takeaway:** The conditional statement "If $P$, then $Q$" ($P \implies Q$) is logically equivalent to its contrapositive "If NOT $Q$, then NOT $P$" ($\neg Q \implies \neg P$). If your original conditional is true, you can deduce that its contrapositive is also an absolute truth.

---

## • What is Logical Equivalence?

Remember that **logical equivalence** is not achieved simply by the presence of true values in a truth table. It means that the truth tables of two propositions display the **exact same truth values for each row in their specific order**.

---

## • Practical Examples

* **Original Condition ($P \implies Q$):** 
  *"If I study, then I will pass."*
* **Contrapositive ($\neg Q \implies \neg P$):** 
  *"If I did not pass, then I did not study."*

---

## • Common Pitfalls (Logical Fallacies)

### 1. Converse ($Q \implies P$)
* **Example:** *"If I passed, then I studied."*
* **Why it fails:** If your original conditional is true, the converse is **not necessarily true**, as there is the hypothesis of passing for other reasons (e.g., luck, guessing, prior experience).

### 2. Inverse ($\neg P \implies \neg Q$)
* **Example:** *"If I do not study, then I will not pass."*
* **Why it fails:** The same applies to the inverse.

> • **Bonus Fact:** The inverse is actually the **contrapositive of the converse**! 
> 
> Notice that the converse is $Q \implies P$. Therefore, the inverse of our original conditional ($\neg P \implies \neg Q$) is the contrapositive of its converse (reversing the propositions and negating both). Thus, the inverse is **logically equivalent to the converse**, not to the original condition!

---

## • Why This Insight Matters in CS

Proving something through its contrapositive can be an easier path / shortcut in mathematical proofs and algorithms, and it can also be used for code simplification techniques.


♥ *Translated and formatted with assistance from ChatGPT (OpenAI).*

