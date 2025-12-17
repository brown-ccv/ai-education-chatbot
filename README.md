# ai-education-chatbot

## Repo

### Chats

Various chat histories generated through LibreChat. The files indicate some basic setup through which the history was generated.

### Instructions

Various prompt instructions used to guide the chatbot behavior.

### Workbooks

The specific workbooks that the chatbot will quiz students on. Each workbook contains the following:

- The original workbook PDF file itself.
- The referred images used in the workbook as "figure_x.png".
- A corresponding JSON file with the questions and answers needed to quiz the students.

## Resources

- [Google Drive Folder](https://drive.google.com/drive/folders/1FbfaajdsahYiRYbbweZBXs13Tjj3uNZV)

### Operation Model Concepts

[Operation Model Concepts](https://docs.google.com/document/d/1ThCX9Hdz8vGKNgKAK60w7ZJQVOhA96nCw3qZJpvlBf8/edit?tab=t.0)

When determining whether an arrow is a `+` or a `-`

- `+` corresponds to directly proportional
- `-` corresponds to inversely proportional
- Read the provided text carefully
- The circle can be a summator or a comparator
- The circle is almost always a comparator (unless you suspect a positive feedback loop)
- When considering arrows not going into or out of the circle, consider the arrow in isolation. Is it a direct or inversely proportional relationship? Read the text.  Do not try to work through many arrows together, you will get caught in loops!
- When considering perturbations outside of the loops, read the text.
- For the arrows connected to the circle, consider the arrow going into the circle first.  If the text suggests this is a comparator (which it usually is!) this arrow has a very high probability of being a `-`. If you highly suspect a positive feedback loop and no comparison to the set point, this could be a plus.
- To determine the sign of the arrow coming out of the circle, work through what comes out of the circle (a literal addition or subtraction, depending on the sign you chose for the arrow going in).  Make a choice about the value coming into the circle (higher or lower than the setpoint) Then use whether that value is (positive or negative) to determine what should happen to the next box, given the text.  If the value of the next box should go up, and you have a positive number, the arrow should be `+`.  If it should go down, and you have a positive number, the arrow should be `-`.  If the value should go up, and you have a negative number, the arrow should be `-`.  If it should go down, and you have a negative number, the arrow should be `+`.
- You can think of a `+` like a times 1 and a `-` like a times -1 if this helps you.
- You can check your work on the arrow coming out of the circle by making the opposite choice about the value coming in than you made when you set it and seeing if everything still holds true.
- To determine if the overall loop is positive or negative feedback, you can read the text and/or count the number of `-`’s in the loop.
- When you count the number of `-`’s in the loop, an odd number indicates a negative feedback loop.
- Be careful that you are only counting the signs within the loop.
- If there are multiple loops, treat them separately.
- Use reasoning skills about what the loop is doing to confirm your thoughts about whether or not the loop is positive or negative.
- Do not bring outside subject knowledge to these problems unless you are specifically asked to do that. Go by what is in the text.
