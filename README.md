head
head__eyes head__eyes_color_blue
head__hair head__hair_color_brown
head__mouth head__mouth_open

leg
leg__left-foot leg__left-foot_fingers_5
leg__right-foot leg__right-foot_size_41
leg__right-foot leg__right-foot_tattoo

hand
hand__palm hand__palm_fingers_5
hand__finger hand__finger_ring
hand__wrist hand__wrist_bracelet

`
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
`

![cards](/img/1.png)
![form](/img/2.png)
![BEM](/img/3.png)
![header](/img/4.png)

.box>h2+.box__card*3>h3+p+a
form>(label+input)*5+input[type="button"]
.container>h2+p+.container__box>(img+p)*4
.header>header__logo+nav>ul>li*6