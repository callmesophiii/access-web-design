# access-web-design

This is my final submission for the Scrimba accessibility challenge. 

🧠 Reflection Questions

1. The hardest part was making sure the form gave feedback that screen readers could catch. I had to use `aria-live` so that the success message would be read out loud. Also, setting up labels and required fields correctly took some testing to make sure everything worked well for keyboard and screen reader users.
 
2. ARIA attributes give extra info to screen readers. For example, `aria-labelledby` tells the screen reader what the form is about, and `aria-live` helps it announce messages automatically. Without ARIA, screen reader users might miss important stuff like form feedback.

3. I used the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) and the axe DevTools browser extension. They helped me make sure the text and background colors had enough contrast so everyone, including people with vision problems, could read the content clearly.
