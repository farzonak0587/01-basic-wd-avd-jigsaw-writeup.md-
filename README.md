# Process Writeup

## Name: Farzona K
## Course: SEP10 Web Design
## Period: 8
## Concept: Applied Visual Design Jigsaw

### Section: Context 
We were still in Web Design, Unit 1, but this time the theme was Applied Visual Design. Although this covered the fundamentals of CSS, some of the subjects were far more complex. For instance, there were the basics, typography, geometry, colors, animation, and positioning. You could use a lot more of the new elements for decorating your webpage.

#### Basics of Applied Visual Design: 
* Basics ( bold `strong`, underline `u`, /italicized `em`, strikethrough `s`,horizontal line `hr`,`opacity`, `box-shadow` and other CSS basics)
* Typography ( `text-transform:`, Font Size, `font-weight:#px`, `line-heigt:#px` and Hover) 
* Colors ( Hex Codes, Dominant and Complementary colors, `linear-gradient`,`repeating-linear-gradient`, HSL and Subtle Pattern for Background)
* Positioning ( `position: relative`, `position: absolute`, `position: fixed`, `float: direction`, `z-index` and `margin:auto`)
* Geometry (`transform: scale(#)`,`transform: skewY (#deg)`, `skewX`, `:before`, and `:after` )
* Animation ( `animation:name;`, `animation-duration: #ms;`,`Content:hover`,`Animation-Iteration-Count: #;`,Keyframes, Opactiy,and Movement)
 

#### Process: 
Due to the large number of Free Code Camp Lessons on Applied Visual Design, our class was forced to divide up and focus on a single topic in groups. Our partner and those behind us had to work together. There were only five topics available for us to select from because my teacher had previously covered one. My group and I decided on colors as our second option and positioning as our first. After receiving our first choice, we had to complete the Positioning Lessons on Free Code Camp first. 

There was onyl 7 [Free Code Camp Lessons](https://freecodecamp.org/](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/change-an-elements-relative-position)) on Positioning: 
1. Change an Element's Relative Position
2.  Move a Relatively Positioned Element with CSS Offsets
3. Lock an Element to its Parent with Absolute Positioning
4. Lock an Element to the Browser Window with Fixed Positioning
5. Push Elements Left or Right with the float Property
6. Change the Position of Overlapping Elements with the z-index Property
7. Center an Element Horizontally Using the margin Property

We had to begin creating our [webpage](https://app.pickcode.io/share/cm3ndop7x9svk9fpuzivm2qnp) after we had completed the lessons and taken notes on each one. The purpose of the webpage was to explain the teachings to the other students in my class. During class, we worked on our portions of the webpage after first laying it out. We went with the flow because we didn't really have a clear plan. Following the completion of our webpage, we got to work on our presentation. During the presentation, we had to be aware of what to say and do. After outlining the main concepts of our presentation in writing, we presented. Presentations followed the order of the classes; for instance, those who had the basics presented first, followed by colors, positioning, geometry, and animation. 

### Challenge 1
I didn't really struggle with the Free Code Camp lessons because they were rather simple, but I struggled to understand relative and absolute positioning when I was creating the webpage. Since they both changed an element's position, I assumed they were the same thing in the Free Code Camp lessons. The only distinction I could think of was that you had to use the opposite direction from which you were attempting to move it when using `position: relative`. For example: 
```CSS
position:relative;
top:15px;
```
would move it 15px **AWAY** from the top. It would move it towards the bottom.However, the opposite directions were not used by `position: absolute`. For instance: 
```CSS
position:absoulte;
left:15px;
```
would just move it 15 pixels to the left. 

My group and I didn't give it much thought and simply presented it as though that was the difference. However, the other group, which also had positioning as a topic, was having trouble with `position: relative` and `position: absolute`. My teacher showed us the distinction, which was different from what we had assumed, after observing that both groups were having difficulty and that students were not truly understanding it. What he showed us was 

giving the H2 `position: relative`: ![image](https://github.com/user-attachments/assets/248bd806-6bdc-46a2-a4dd-71ae4022fe85)
giving the H2 `position: absolute`:![image](https://github.com/user-attachments/assets/8a9eca6e-c35a-438d-b8a4-a95aeca3bd83)

I now understood what `position: absolute` meant after seeing what he showed us. By using `position: absolute`, the elements surrounding a particular element simply forget it exists and carry with their necessary tasks. similar to how `position: absolute` caused the h3 to move up over the h2. **THE ELEMENTS AROUND A ELEMENT WITH `POSITION: ABSOLUTE` IGNORE THAT THE ELEMENT IS EVEN THERE. WHILE WITH  `POSITION: RELATIVE` IT DOESNT IGNORE IT.**
### Challenge 2
Anotherthing my group made a mistake on was that we didn't really practice/rehearse for our presentation because everyone knew what to say. For the presentation.md, we all had to put what we were going to say during the ppresentation,and we ddid,but one of my group mates didn't write it down and didn't tell us what he was going to say. Then the presentation came,and my group mates were just confused because we couldn't hear him,and we had no clue what he was trying to say, so then we just went on with the presentation by explaining the lessons. 

We realized that we definitely need to practice our presentation skills after making a mistake that cost us some points during the presentation. 

### Challenge 3
I first got lost by `@keyframes` since I was unable to understand the topic being discussed by the group presenting about animation. It was confusing because they didn't really focus on the subject. 
Here is what the group put for their presentations: 

1. ![image](https://github.com/user-attachments/assets/35a2da10-731e-409d-8f39-252991660084)

As far as I was aware, it was used to create animations, and you could change their styles using `@keyframes`. But what was the difference between using  `@keyframes` and just putting it in the {} selector brackets for that specific element/animation?

When I was trying to understand what `@keyframes` were in the other presentations, I discovered that they were actually checkpoints in the animation timeline. By changing these checkpoints, we can make changes. Additionally, they have control over the animation's events.

EXAMPLE: ![images](https://github.com/user-attachments/assets/b7a3e06a-d964-4308-bc5a-9ad9c6af4a01)

You could change what occurs in each section of the animation by using `@keyframes`. Because the element is altered using keyframes, what it does throughout the entire animation would not be the same.

### Takeaways
The things I really need to remember are:
* **PRACTICE** before presenting, so the presentation goes smoothly
* In contrast to `position: absolute`, which lets it go with the flow and forgets that an element was ever there if you move it, meaning that there is no space where there would be with `position: relative`.
* Keyframes provide you more artistic control over your animation by allowing you to change what occurs at a particular point of your animation. 
