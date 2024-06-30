# [rssschool-cv](https://tsubasakatakiri.github.io/rsschool-cv/cv)

# __Aliaksei Reut__

## __My contacts__

* __Phone:__ +375 (29) 272-68-49
* __Email:__
    + __Business:__ aliakseireut93@gmail.com
    + __Personal:__ katakiritsubasa@gmail.com
* __Github:__ [Tsubasa Katakiri](https://github.com/TsubasaKatakiri)
* __LinkedIn:__ [Aliaksei Reut](https://www.linkedin.com/in/aleksei-reut-bbb89824a/)
* __Telegram:__ [@aliakseireut](https://t.me/Aliaksei_Reut)
* __Discord:__ [Tsubasa Katakiri](discordapp.com/users/844284828114354186)



## __Code example__

__[String incrementer kata from CODEWARS](https://www.codewars.com/kata/54a91a4883a7de5d7800009c/javascript)__

```
function incrementString (strng) {
  if(strng.match('[0-9]$')){
        let numPart = strng.split("").filter(e => e.match('[0-9]')).join("");
        let textPart = strng.split("").filter(e => !e.match('[0-9]')).join("");
        let numLength = numPart.length;
        numPart = `${((parseInt(numPart)) + 1)}`;
        numPart = numPart.length<numLength ? numPart.padStart(numLength, '0') : numPart;
        return `${textPart}${numPart}`;
    }
    else{
        return `${strng}1`;
    }
}
```

