---
title: "My-nfc"
author: "Erox"
description: "Just my nfc card "
created_at: "2026-09-25"
---

# Sept 25 : 

Ok so for my nfc card today i started the work , i chose `NT3H2111` this ic for my work , i think i will use the eeprom for nfc on my card and i2c for rewrittin when needed , ik i can use the nfc for rewrittin but why tht when i can just use i2c .

![Datasheet img](assets/datasheet-1.png)

 2 kb is far more than enough for storing just some links , like my portfolio , my github or even my phone num also i can use it as a card access if i use rfid sensors later but thts upto the later me not now at all so why worry? 

 Oh so its a sot902 qfn not a prob for me i have got hot air hehe .

 ![](assets/specs.png)

 Lol too bad for windows users but i use arch btw with easyeda2kicad from yay i got the footprints and symbols of lcsc , but as i am kind guy , i will tag those in my repo .


Wait i just realized its qfn even with a hot air its hard , oh its hard bring it on i will do it mysef .

![](assets/qfn.png)

          A
          |
This is the pic of the qfn ic

ok so started the schematics , added the symbols , made a extra trace for later i2c use on the nt3 .

ah man i dont wanna go around and find the logic voltage in the datasheet , wait i dont need to actually , i2c operates at 3.3v .

Oh just found gold in the datasheet i can use the vout to power a led when i use the card , amazing right? lets do tht

![](assets/vout.png)
the thing i got frm datasheet .

![](assets/led.png)

ok added a led but but its just a ultra frank design obviously i will add res and cap after measuring current and vol frm the vout .

actually we can control tht but why worry now , thts for later not now at all .

![](assets/test.png) ===> this is the test circuit givn in the datasheet maybe i will use it . 

**Total time spent: 1 hours**