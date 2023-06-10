# Daily-Check-In-Genshin-Impact
This script will automatically check in every day in HoYoLab, and works with Genshin Impact and Honkai Impact 3rd too
```js
function getCookie(name) {
const value = `; ${document.cookie}`;
const parts = value.split(`; ${name}=`);
if (parts.length === 2) return parts.pop().split(';').shift();
}
console.log('ltoken='+getCookie('ltoken')+'; ltuid='+getCookie('ltuid')+';');
```
