# Hi there, I'm [Alireza Rezaei](https://github.com/rezaeiar) <img alt="hi" width="50px" src="https://camo.githubusercontent.com/e8e7b06ecf583bc040eb60e44eb5b8e0ecc5421320a92929ce21522dbc34c891/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6876524a434c467a6361737252346961377a2f67697068792e676966" />

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
