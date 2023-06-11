## Cookie
Browser's Console code to Grab Cookie from File Sharer Site GDTOT


## How to get Cookies from gdtot , appdrive , hubdrive , etc for downloading cookies from  APPDRIVE , GDFLIX , DRIVEAPP , DRIVEBIT , DRIVELINKS , DRIVESHARER , DRIVEACE , GDTOT , HUBDRIVE , KATDRIVE , DRIVEFIRE , KOLOP , etc   Login to specific Website & than paste the below script in place of URL address. Note - Make sure your script includs javascript: before running. Run this script in URL bar


## Script 👇
```
javascript:(function () {
  const input = document.createElement('input');
  input.value = JSON.stringify({url : window.location.href, cookie : document.cookie});
  document.body.appendChild(input);
  input.focus();
  input.select();
  var result = document.execCommand('copy');
  document.body.removeChild(input);
  if(result)
    alert('Cookie copied to clipboard');
  else
    prompt('Failed to copy cookie. Manually copy below cookie\n\n', input.value);
})();
```


## Gdtot Crypt 👇
To Clone or Leech gdtot link follow these steps:
1. Login/Register to [gdtot](https://new1.gdtot.sbs).
2. Copy this script and paste it in browser address bar.
   - After pressing enter your browser will prompt a alert.

3. Now you'll get Crypt value in your clipboard
   
   NGxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxWdSVT0%3D
   
4. From this you have to paste value for CRYPT in config.env file.


## 😃 Contact me
[🧑‍💻 Owner](https://telegram.me/JayArmo)

[📢 Update Channel](https://telegram.me/Jay_Bots)

[💬 Support Group](https://telegram.me/Jay_Bots_Support)

[buy me a ☕ coffee](https://www.buymeacoffee.com/jayarmo)


## Enjoy And don't forget to star this repo 🙂


## Credits...
[`JayArmo`](https://github.com/JayArmo)
-----
