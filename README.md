# get-chicken-JS-DOM-Project
Simple Project to practice JS DOM manipulation

**DEMO:**

| Before Styling | After Styling |
| --- | ---|
| ![before_styling](https://github.com/jessumguy/get-chicken-JS-DOM-Project/assets/43509228/e5515201-5b76-40ab-83ef-3fe8838eb0fd)|  ![completed](https://github.com/jessumguy/get-chicken-JS-DOM-Project/assets/43509228/caea9475-b38e-46c6-8141-ebd61f9d7068)|

**Reflection 15/07/2023** 

Upon starting the Library App on the OOP chapter in The Odin Project, I realised the gaps in my knowledge on DOM Manipulation, and so I decided to take a step back to revisit this topic with a simple project so as to better grasp its basics.

This main highlight of this project is clicking the respective add/remove buttons to create and remove article parent elements, each containing an h3, remove button, image and paragraph child element.

The notable challenge was implementing the child remove button whereby when clicked, the specified article container parent element should be removed from the DOM. Spent quite a bit of time googling and trial and error until I eventually found the solution in the answer to this stackoverflow question https://stackoverflow.com/questions/23504528/dynamically-remove-items-from-list-javascript

The simple solution is to assign a unquie `id` to every new article element created, and then to link the child remove button to said `id`. The answer also provides another approach to achieving involving the use of arrays to store the created article elements which I intend to check out in a future project.

In conclusion, I feel that I have achieve what I set out to learn in DOM manipulation through this project.
