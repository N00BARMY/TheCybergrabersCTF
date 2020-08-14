# Solution of Zero-width

Hey , everyone. I am **Hack2Death** , I created the challege Zero-Width ,here is solution of it from my side.

The question says we have to find **Tabby Clark aka (Th3Frozen)'s** key from the internet.Let's run  username: `Th3Frozen` with tool sherlock.py.

**Note**: sherlock.py is used to hunt accounts of particular username from the internet.For more info you can check out the tool link is provided here.

**Link**:https://github.com/sherlock-project/sherlock

![image](https://i.imgur.com/Lvx7Gjl.png)
![image](https://i.imgur.com/ZjPQB1D.png)

Thus we get three geniune links,Lets check one by one.

**Link 1**: https://www.reddit.com/user/Th3Frozen


![image](https://i.imgur.com/iUAYgot.png)

Lets try to  decrypt Yby!!!Abg_Ntnva_,vg_abg_gurxrl .

![image](https://i.imgur.com/IV6hscR.png)

Looks like it is rabbit hole.

![image](https://i.imgur.com/U7SV4v9.png)

Lets try   `cZcNI9V5OJ2z5iqhQC9x`  to  give as a passpharse to code.jpg 

![image](https://i.imgur.com/tZBdUqy.png)

No luck ,it also a rabbit hole.

**Link 2**:https://www.instagram.com/Th3Frozen


![image](https://i.imgur.com/IwbCLkL.png)

It also a rabbit hole.

**Link 3**:https://www.github.com/Th3Frozen

Let's apply the search filter `user:Th3Frozen key` in searchbar .

![image](https://i.imgur.com/2p5gyju.png)

key=dc74e8eab42084cf19b02000edad4604

Let's use key to extract file from code.jpg.
**command**: steghide extract -sf code.jpg

![image](https://i.imgur.com/kWWjYZU.png)

Let's open uni.txt.

`You don’t climb mountains without a team, you don’t climb mountains without being fit, you don’t climb mountains without being prepared and you don’t climb mountains without balancing the risks and rewards. And you never climb a mountain on accident-it has to be intentional.” — Mark Udall`

Here file name is uni.txt and image name is code.So it might be unicode or zero-width space charcter.

![image](https://i.imgur.com/rK1dva5.png)

Link to decode it: https://offdev.net/demos/zwsp-steg-js

![image](https://i.imgur.com/93snGBG.png)

Flag is: cyb3rg4abs{He_wA5_Li3r_n0_Am0uNT}



