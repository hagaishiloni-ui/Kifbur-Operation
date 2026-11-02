# פעולת הכיפבור | The Kifbur Operation

**מגדיר ומציע הפעולה: חגי שילוני (Hagai Shiloni)**

פעולת הכיפבור היא פעולת חשבון בינארית שהוגדרה כאן באופן הבא: כופלים את המספר הראשון במספר השני, ואז מוסיפים את המספר השני.

## הגדרה פורמלית

לכל שני מספרים ממשיים \(a,b\):

\[
a \;\boldsymbol{\⊛}\; b = (a \times b)+b = b(a+1)
\]

## דוגמאות

- \(4 ⊛ 3 = (4×3)+3 = 15\)
- \(5 ⊛ 2 = (5×2)+2 = 12\)
- \(2 ⊛ 4 = (2×4)+4 = 12\)

## תכונות אלגבריות

בהנחה שהפעולה מוגדרת על המספרים הממשיים:

- **אינה חילופית:** למשל, \(4⊛3=15\), אבל \(3⊛4=16\).
- **אינה אסוציאטיבית:** מתקיים \((a⊛b)⊛c-a⊛(b⊛c)=-ac\), ולכן בדרך כלל שני הביטויים אינם שווים.
- **איבר ניטרלי משמאל:** \(0⊛a=a\).
- **אין איבר ניטרלי דו-צדדי:** אין מספר \(e\) המקיים גם \(e⊛a=a\) וגם \(a⊛e=a\) לכל \(a\).
- **איבר מאפס מימין:** \(a⊛0=0\).

## English

The **Kifbur Operation** is a user-defined binary arithmetic operation. Multiply the first number by the second number, then add the second number:

\[
a ⊛ b = (a \times b)+b = b(a+1)
\]

Examples: \(4⊛3=15\), and \(5⊛2=12\).

The operation is generally non-commutative and non-associative. More precisely,
\((a⊛b)⊛c-a⊛(b⊛c)=-ac\).
It has a left identity, 0, and a right absorbing element, 0.

**Defined and proposed by: Hagai Shiloni (חגי שילוני).**

---

This repository documents the definition and elementary properties of the Kifbur Operation. The name and definition are presented as a proposal by the author; this is not claimed to be a standard operation in established mathematics.
