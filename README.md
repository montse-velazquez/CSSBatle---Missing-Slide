# CSSBatle---Missing-Slide
**Objective:**
Practice the use of the __position property__ by trying to remake the same image that is presentade but in hour VS Code Studio, and try to do the less charts possible. 

![Image that needs to be replicated](https://cssbattle.dev/targets/6@2x.png)

> The smallest chars done so far has been __105 chars__.

**Observations:**
One the challenege we spend less than 5 minutes using ```position: absolute;``` property, and in our first try we made __589 chars__. 

I use the next code, however i believe that with __flexbox__ or even __grid__ properties we can be able to represent the same figure and with a chance that it could coded with less chars. 

```html
 <style>
      body {
        background-color: #E3516E;
      }
      
      .box1 {
        background-color: #51B5A9;
        position: absolute;
        top: 50px;
        left: 100px;
        border-radius: 100px 0 0 0;
      }
      .box2 {
        background-color: #FADE8B;
        position: absolute;
        top: 50px;
        left: 200px;
        border-radius: 0 100px 0 0;
      }
      .box3 {
        background-color: #F7F3D7;
        position: absolute;
        top: 150px;
        left: 100px;
        border-radius: 0 0 0 100px;
      }
      div {
        width: 100px;
        height: 100px;
      }
    </style>
    </body>
</head>
<body>
  <div class="box1"></div>
  <div class="box2"></div>
  <div class="box3"></div>
</body>
```
**Conclusion:** 
By this code we were able to duplicate the same figure as it showed above. 

**References:**

>Challenge taken from --> [CSSBattle](https://cssbattle.dev/play/6).
