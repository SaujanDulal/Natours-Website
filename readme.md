### Reference
  - [JonasSchemtmann](https://codingheroes.io/)

### Takeaways
- Inheritance of properties declared iside the body
- It is always good to have image inside the div container as img is inline element. By wrapping it inside the div, we can adjust the width and position of image
- Google search engine works on h1 element. Here we use span to include all the outdoor content. Cool idea.
- centering element:
  position: absolute;
	top: 40%;
	left: 50%;
	transform: translate(-50%, -50%)

- For broswer performance is the best to only ever animate two different properties. One is opacity and another is transform. That's what browser are optimized for. But with transform we can do a whole lot, everything we need to do for cool animation.

- backface-visibilty : fix the shaking of element while animation. This is bug fix hack.

-  since this is inline element, this would be treated as text. So if you want to center the inline-block. text-align : center is the way to go.
 
- border-radius : 100px was cool

- transition property goes in initial state

- For some reason, i wasn't able to push my repo to github : here i used this solution found on stackoverflow (https://stackoverflow.com/questions/5509543/how-do-i-properly-force-a-git-push)