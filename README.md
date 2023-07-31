# Daily-Check-In-Genshin-Impact
This script will automatically check in every day in HoYoLab, and works with Genshin Impact and Honkai Impact 3rd too

Step 1: Open Google Script and paste the Code.

Step 2: Open the [link](https://act.hoyolab.com/bbs/event/signin/hkrpg/index.html?act_id=e202303301540311&hyl_auth_required=true&hyl_presentation_style=fullscreen&utm_source=hoyolab&utm_medium=tools&utm_campaign=checkin&utm_id=6&lang=en-us&bbs_theme=dark&bbs_theme_device=1), then log in first.

Step 3: Right-click on the Hoyolab page and select "Inspect" instead of "Console". Then paste the code below.
```js
function getCookie(name) {
const value = `; ${document.cookie}`;
const parts = value.split(`; ${name}=`);
if (parts.length === 2) return parts.pop().split(';').shift();
}
console.log('ltoken='+getCookie('ltoken')+'; ltuid='+getCookie('ltuid')+';');
```
Step 4: Copy the ltoken and Ituid, then paste them into column 1 of the code.

Step 5: Open the trigger and press the trigger button.
![image](https://github.com/Julius-Ulee/Daily-Check-In-Genshin-Impact/assets/61336116/567cc2c7-4b50-4de4-a05d-e84d463b5447)

Step 6: Run the code.

## Support me as a programmer 
<table>
    <tr>
      <th>Rp. 5k Minimum</th>
      <th>Bitcoin</th>
    <tr>
      <td>
        <a href="https://saweria.co/AmeliaBotDiscord"><img title="💵 Saweria" src="https://user-images.githubusercontent.com/26188697/180601310-e82c63e4-412b-4c36-b7b5-7ba713c80380.png" alt="Donate For Amelia" height="41" width="174" /></a>
      </td>
      <td>
        <a href="https://julius-ulee.github.io/Donate/"><img title="🪙 Bitcoin" src="https://img.shields.io/badge/Bitcoin-EAB300?style=for-the-badge&logo=Bitcoin%20SV&logoColor=white" alt="Donate Via Bitcoin" height="41" width="174" /></a>
      </td>
    </tr>
  </table>

  ## Credits
  > Make sure to credit me!
