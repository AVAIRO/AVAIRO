### <samp>&gt; Hi there, I'm <a href="https://t.me/makewasocket" target="_blank">aswin</a>

<details>
  <summary><strong>Click to expand code</strong></summary>

```javascript
function Character(name, favClub, hobby) {
  this.name = name;
  this.favClub = favClub;
  this.hobby = hobby;
}

Character.prototype.bio = function() {
  return `Hi there, I'm ${this.name}, a fan of ${this.favClub} and I enjoy ${this.hobby}!`;
}

Character.prototype.interests = ['programming', 'watching anime', 'playing football', 'hanging out with friends'];

const aswin = new Character('Aswin', 'BVB Dortmund', 'playing football');

console.log(aswin.bio());
console.log(`My interests include: ${aswin.interests.join(', ')}.`);



Contact me  [`Telegram`](https://t.me/makewasocket) or [`Gmail`](deavairoaswin@gmail.com)

</br>


