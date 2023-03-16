# **Nikita Yabbarov**
## Junior Frontend Developer
### Contacts:
#### _**Phone:** +7 964 621 84 96_
#### _**E-mail:** marvint@inbox.ru_
#### _**Discord:** @Nikitka709_

***

### About Me:
_I am passionate about IT technologies. I like how our enviroment changes fastly especially in digital world and I would like to be a part of it and maybe apply new information not only as a hobby or side hustle. Also I am very lasy person, but I try to finish RSSchool course at last._

***

### Skills:
* _HTML_
* _CSS_
* _JavaScrips_
* _Git/GitHub_

***

### Сode example:
###### Human readable duration format:
```
function formatDuration (seconds) {
  var time = { year: 31536000, day: 86400, hour: 3600, minute: 60, second: 1 },
      res = [];

  if (seconds === 0) return 'now';
  
  for (var key in time) {
    if (seconds >= time[key]) {
      var val = Math.floor(seconds/time[key]);
      res.push(val += val > 1 ? ' ' + key + 's' : ' ' + key);
      seconds = seconds % time[key];
    }
  }
 
  return res.length > 1 ? res.join(', ').replace(/,([^,]*)$/,' and'+'$1') : res[0]
}
```
***

### Work Experice:
* _Not yet_
* _[My CV Markdown](https://Nikitka709.github.io/rsschool-cv/cv)_

***

### Education:

* _Kazn Federal University: biochemistry **2007-2013**_

***

### English: B2-C1
### German: B1
