### <samp>&gt; Hi there 

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
```
Feel free to connect with me on [Telegram](https://t.me/makewasocket)!
