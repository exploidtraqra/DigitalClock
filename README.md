# DigitalClock
_script css_ :<br>
<img width="150px" height="250px" src="https://github.com/exploidtraqra/DigitalClock/raw/main/screenshot/Screenshot_2022-07-06-17-01-54-249_com.rhmsoft.edit.pro.jpg"/>

_Digital Clock Javascript Vanilla_

# Source
```
(()=>{
setInterval(()=>{
  const d = new Date();
  document.querySelector(".clock").innerHTML=`
    ${d.getHours()}:${d.getMinutes()}:${d.getSeconds()}
    `;
  },30);
})();
```


# PREVIEW

<img width="200px" height="400px" src="https://github.com/exploidtraqra/DigitalClock/raw/main/screenshot/Screenshot_2022-07-06-17-01-51-080_com.rhmsoft.edit.pro.jpg"/>
