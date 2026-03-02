<style>
  
@font-face {
  font-family: 'MonaSans';
  src: url('/static/MonaSans-Medium.woff2') format('truetype');
  font-weight: 500;
  font-style: normal;
  font-display: swap; /* ensures fallback text shows immediately */
}

:root {
    --mainThemeColor2-: rgb(207, 85, 101);
    --mainThemeColor-: rgb(85, 103, 207);

    --regularTextColor-: rgb(30, 30, 30);
    --regularTextColorGray-: rgb(170, 170, 170);
    --regularBackgroundcolor-: rgb(204, 203, 209);
    --regularBackgroundcolorLight-: rgb(223, 222, 228);
}

::-webkit-scrollbar {
    display: none;
}

* {
    margin: 0;
    padding: 0;
    font-family: "MonaSans", sans-serif;

    font-weight: normal;
    text-decoration: none;
}

a {
    color: var(--regularTextColor-);
}

body {
    background-color: var(--regularBackgroundcolor-);
    color: var(--regularTextColor-);
}

::selection {
    background-color: var(--mainThemeColor-);
    color: var(--regularBackgroundcolor-);
}

/* header */
header {
    width: 100%;
    height: 20dvh;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logoContainer {
    margin-left: 10dvh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.logoContainer a {
    font-size: 2.6dvh;
}

.navContainer {
    margin-right: 10dvh;
}

.navContainer ul {
    display: flex;
    align-items: center;
    justify-content: space-between;

    width: 60dvh;
}

.navContainer ul li {
    list-style: none;

    height: 3dvh;
    overflow: hidden;

}

.navContainer ul li a div {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 3dvh;
}

.navContainer ul li a div span {
    font-size: 2.6dvh;
    font-weight: 500;
}

/* header */
































/* main */
main {
    height: 200dvh;
}

#index {
    width: 100%;
    height: 80dvh;

    display: flex;
    align-items: start;
    justify-content: space-between;
    flex-direction: column;
}

.controlTitle {
    margin-left: 5dvh;
    display: flex;
    align-items: start;
    justify-content: center;
    flex-direction: column;
}

.controlTitle .title {
    font-size: clamp(6dvh, 8dvw, 13dvh);
    line-height: clamp(5.5dvh, 7.5dvw, 12dvh);
    font-weight: bolder;
}

.controlTitle .title .controlSkills {
    display: flex;
    align-items: center;
    justify-content: space-between;

    width: 95dvh;
}

.controlTitle .title .controlSkills .lebel {}

.controlTitle .title .controlSkills .skillschanger {}

.controlTitle .title .controlSkills .skillschanger .controlChanger {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width: 20dvh;
}

.controlTitle .title .controlSkills .skillschanger .controlChanger .Slots {
    height: 4dvh;
    width: 4dvh;

    cursor: pointer;
    position: relative;
}

.controlTitle .title .controlSkills .skillschanger .controlChanger .Slots::after {
    display: block;
    content: '';
    width: 0dvh;
    height: 0dvh;
    border-radius: 50%;
    border: 0.3dvh solid transparent;

    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition: 0.2s ease-in-out;
}

.controlTitle .title .controlSkills .skillschanger .controlChanger .Slots::before {
    display: block;
    content: '';
    height: 1dvh;
    width: 1dvh;
    background-color: var(--regularTextColor-);
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition: 0.2s ease-in-out;
}

.controlTitle .title .controlSkills .skillschanger .controlChanger .Slots:hover::after {
    width: 2.5dvh;
    height: 2.5dvh;
    border: 0.3dvh solid var(--regularTextColor-);

}

.controlTitle .title .controlSkills .skillschanger .controlChanger .Slots:hover::before {
    width: 0dvh;
    height: 0dvh;
}

.controlTitle .title span {
    font-weight: bolder;
}

.controlTitle .text {
    margin-top: 3dvh;
    font-size: 2.2dvh;
    font-weight: 500;
    width: 61dvh;
}

span {
    display: inline-block;
}

/* tag */

#index .tag {
    margin-left: 5dvh;
    margin-bottom: 5dvh;
}

#index .tag span {
    color: var(--regularTextColorGray-);

    font-size: 1.8dvh;
    /* font-family: var(--MonaSansLightFont-); */
}
</style>

<main>
<section id="index">
<div class="controlTitle">

<div class="title">
<div class="controlSkills">
<div class="lebel">
<span>S</span><span>e</span><span>l</span><span>f</span><span>-</span><span>t</span><span>a</span><span>u</span><span>g</span><span>h</span><span>t</span>
</div>
<div class="skillschanger">
<div class="controlChanger">
<div class="Slots"></div>
<div class="Slots"></div>
<div class="Slots"></div>
<div class="Slots"></div>
<div class="Slots"></div>
</div>
</div>
</div>

<div class="controlSkillsText">
<div class="skill-1">
<span>F</span><span>r</span><span>o</span><span>n</span><span>t</span><span>-</span><span>E</span><span>n</span><span>d</span>
<span> </span>
<span>D</span><span>e</span><span>v</span><span>e</span><span>l</span><span>o</span><span>p</span><span>e</span><span>r</span>
</div>
</div>
</div>

<div class="text">
<span>I</span><span> </span><span>t</span><span>u</span><span>r</span><span>n</span><span> </span>
<span>i</span><span>d</span><span>e</span><span>a</span><span>s</span><span> </span>
<span>i</span><span>n</span><span>t</span><span>o</span><span> </span>
<span>c</span><span>l</span><span>e</span><span>a</span><span>n</span><span>,</span><span> </span>
<span>e</span><span>n</span><span>g</span><span>a</span><span>g</span><span>i</span><span>n</span><span>g</span><span> </span>
<span>f</span><span>r</span><span>o</span><span>n</span><span>t</span><span>-</span><span>e</span><span>n</span><span>d</span><span> </span>
<span>e</span><span>x</span><span>p</span><span>e</span><span>r</span><span>i</span><span>e</span><span>n</span><span>c</span><span>e</span><span>s</span><span>.</span><span> </span>

<span>M</span><span>y</span><span> </span>
<span>g</span><span>o</span><span>a</span><span>l</span><span> </span>
<span>i</span><span>s</span><span> </span>
<span>t</span><span>o</span><span> </span>
<span>h</span><span>e</span><span>l</span><span>p</span><span> </span>
<span>b</span><span>r</span><span>a</span><span>n</span><span>d</span><span>s</span><span> </span>
<span>s</span><span>t</span><span>a</span><span>n</span><span>d</span><span> </span>
<span>o</span><span>u</span><span>t</span><span> </span>
<span>t</span><span>h</span><span>r</span><span>o</span><span>u</span><span>g</span><span>h</span><span> </span>
<span>t</span><span>h</span><span>o</span><span>u</span><span>g</span><span>h</span><span>t</span><span>f</span><span>u</span><span>l</span><span> </span>
<span>d</span><span>e</span><span>s</span><span>i</span><span>g</span><span>n</span><span>,</span><span> </span>
<span>s</span><span>m</span><span>o</span><span>o</span><span>t</span><span>h</span><span> </span>
<span>i</span><span>n</span><span>t</span><span>e</span><span>r</span><span>a</span><span>c</span><span>t</span><span>i</span><span>o</span><span>n</span><span>s</span><span>,</span><span> </span>
<span>a</span><span>n</span><span>d</span><span> </span>
<span>r</span><span>e</span><span>a</span><span>l</span><span> </span>
<span>u</span><span>s</span><span>e</span><span>r</span><span> </span>
<span>v</span><span>a</span><span>l</span><span>u</span><span>e</span><span>.</span>
</div>

</div>

<div class="tag">
<span>S</span><span>c</span><span>r</span><span>o</span><span>l</span><span>l</span>
<span> </span>
<span>t</span><span>o</span>
<span> </span>
<span>d</span><span>i</span><span>s</span><span>c</span><span>o</span><span>v</span><span>e</span><span>r</span>
<span> </span>
<span>m</span><span>o</span><span>r</span><span>e</span><span>.</span>
</div>

</section>
</main>
