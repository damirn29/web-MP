```html
<body>
    <div class="head">
        <div class="head__eyes head__eyes_color_blue"></div>
        <div class="head__hair head__hair_color_brown"></div>
        <div class="head__mouth head__mouth_open"></div>
    </div>
    <div class="leg">
        <div class="leg__left-foot leg__left-foot_fingers_5"></div>
        <div class="leg__right-foot leg__right-foot_size_41"></div>
        <div class="leg__right-foot leg__right-foot_tattoo"></div>
    </div>
    <div class="hand">
        <div class="hand__palm hand__palm_fingers_5"></div>
        <div class="hand__finger hand__finger_ring"></div>
        <div class="hand__wrist hand__wrist_bracelet"></div>
    </div>
</body>
```


![cards](/img/1.png)
![form](/img/2.png)
![BEM](/img/3.png)
![header](/img/4.png)

1. .box>h2+.box__card*3>h3+p+a
2. form>(label+input)*5+input[type="button"]
3. .container>h2+p+.container__box>(img+p)*4
4. .header>header__logo+nav>ul>li*6