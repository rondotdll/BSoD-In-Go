## Invoke a BSoD In Go Lang

### Based off of [peewpw](https://github.com/peewpw/Invoke-BSOD)'s C# implementation of Windows' Native API Hard Stop abuse.

> Reference this repo for when you feel like killing a PC (**no admin required!**)
---

There isn't really anything that special going on here, we're adjusting our application's system privelege level (level of importance) and invoking a hard-stop system level exception which tricks Windows into thinking something vital has broken, causing an immediate blue screen (basically we walk into the club pretending to be a celebrity and fake our death for views on YouTube)
  
If you want to change the stop code just edit `0xdeadbeef` on line 17 to whatever [8-digit hexadecimal](https://en.wikipedia.org/wiki/Hexspeak) you want.

---

For Windows Only <sub>(duh)</sub>
