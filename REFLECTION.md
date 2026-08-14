# REFLECTION QUESTIONS AND ANSWERS FOR LAB 2

**Tamanda Kamoto**
**BECE/21/SS/008**

---

### QUESTION 1
If you have a CSS rule for p { color: red } and another for .intro { color: blue }, and an HTML element <p class='intro'>, what colour will the text be? Why?

**ANSWER**
The text will be blue. CSS specifity states that the rule with the highest score overrides the other. When we compare the scores for p which is 0,0,1 and .intro which is 0,1,0; .intro has the highest score making the text colour blue.

---

### QUESTION 2
What does rem stand for, and what is its advantage over px for accessibility? What happens to text sized in rem if a user changes their browser's default font size to 20px?

**ANSWER**
rem stands for root element. rem scales up when a user increases font size thereby ensuring visually impaired users view the page properly whereas px maintains a fixed font size making text unreadable. 1 rem is usually equivalent to 16px therefore changing a browser's default font size to 20px then 1 rem will be equivalent to 20px.

---
