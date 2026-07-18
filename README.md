# Hi there, I'm [Alireza Rezaei](https://github.com/rezaeiar)

```js
const aboutMe = () => {
  const myLife = {
    innerName: "Alireza Rezaei",
    innerBirthday: "June 15",
    quote: "With effort, everything will happen in its time",
    hobbies: ["coding", "algorithm", "travel"],
    getHobbiesCount: function() {
      return this.hobbies.length;
    },
    introduce: function() {
      return `Hi, I'm ${this.innerName}. My birthday is on ${this.innerBirthday}.
              One of my favorite quotes is "${this.quote}".
              I enjoy ${this.getHobbiesCount()} hobbies: ${this.hobbies.join(", ")}.`;
    }
  };
  return myLife;
};
const myInfo = aboutMe();
console.log(myInfo.introduce());
```
<br/><br/>

### My Skills
[![My Skills](https://skillicons.dev/icons?i=html,css,js,tailwind,bootstrap,figma,firebase,git,github,materialui,postman,react,redux,sass,ts,vercel,vite)](https://github.com/rezaeiar)
