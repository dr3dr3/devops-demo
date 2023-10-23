---
title: Testing Links with ID
---

<!-- .slide: id="title-slide" -->

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="400" height="220" stroke="var(--r-main-color)" stroke-linecap="round" stroke-linejoin="round" fill="#fff" fill-rule="evenodd" font-family="Roboto" font-size="14" text-anchor="middle">
    <defs>
        <style>@font-face{font-family:"Open Sans";src:url(data:application/font-woff;charset=utf-8;base64,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) format("woff"); font-weight:bold;font-style:normal;}</style>
        <path d="M0 0l4 5h-8z" id="A" class="D" stroke="none"/>
        <path d="M0 0l3 10h-6z" id="B" class="D" stroke="none"/>
        <path id="C" d="M28.2631.3597Q0 3.548 0 35"/>
    </defs>
    <g transform="matrix(0 1 -1 0 194.5 24.5)">
        <path d="M35 0Q3.548 0 .3597 28.2631" class="B E" stroke-width="3" fill="none"/>
        <use y="23.3333" transform="matrix(-1.49730277 -.08991343 .08991343 -1.49730277 -2.09797699 69.93696465)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="translate(24.5 24.5)">
        <path d="M35 0Q7.9455 0 1.8037 20.913" class="B E" stroke-width="3" fill="none"/>
        <use y="23.3333" transform="matrix(-1.48619592 -.20303125 .20303125 -1.48619592 -4.73738899 69.67780526)" xlink:href="#B" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(0 -1 1 0 24.5 194.5)">
        <path d="M35 0Q3.548 0 .3597 28.2631" class="B E" stroke-width="3" fill="none"/>
        <use y="23.3333" transform="matrix(-1.49730277 -.08991343 .08991343 -1.49730277 -2.09797699 69.93696465)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(-1 0 0 -1 189.5 194.5)">
        <path d="M30 0Q3.0433 0 .3087 28.2597" class="B E" stroke-width="3" fill="none"/>
        <use y="23.3333" transform="matrix(-1.49801399 -.07716271 .07716271 -1.49801399 -1.80046073 69.95355984)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(0 1 -1 0 374.5 24.5)">
        <use xlink:href="#C" class="B E" stroke-width="3" fill="none"/>
        <use x="23.3333" transform="matrix(.08991343 1.49730277 -1.49730277 .08991343 32.90197301 -34.93701465)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(-1 0 0 -1 374.5 194.5)">
        <use xlink:href="#C" class="B E" stroke-width="3" fill="none"/>
        <use x="23.3333" transform="matrix(.08991343 1.49730277 -1.49730277 .08991343 32.90197301 -34.93701465)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(0 -1 1 0 209.5 194.5)">
        <path d="M28.2597.3087Q0 3.0433 0 30" class="B E" stroke-width="3" fill="none"/>
        <use x="23.3333" transform="matrix(.07716271 1.49801399 -1.49801399 .07716271 33.19948927 -34.95360984)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="translate(109.5 49.5)">
        <path d="M0 30V6.75" class="B E" stroke-width="3" fill="none"/>
        <use transform="matrix(1.5 0 0 1.5 0 0)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="translate(204.5 24.5)">
        <use xlink:href="#C" class="B E" stroke-width="3" fill="none"/>
        <use x="23.3333" transform="matrix(.08991343 1.49730277 -1.49730277 .08991343 32.90197301 -34.93701465)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="translate(219.5 109.5)">
        <path d="M0 0h23.25" class="B E" stroke-width="3" fill="none"/>
        <use x="20" transform="matrix(0 1.5 -1.5 0 30 -30)" xlink:href="#A" class="C" fill="var(--r-main-color)"/>
    </g>
    <g transform="matrix(0 -1 1 0 9.5 159.5)">
        <rect width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
        <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
            <tspan x="50" y="25.94">COMMIT</tspan>
        </text>
    </g>
    <a xlink:href="#/code" target="_parent">
        <title>Code</title>
        <rect x="59.5" y="9.5" width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
        <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
            <tspan x="109.5" y="35.44">CODE</tspan>
        </text>
        <rect x="59.5" y="9.5" width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-selection-color)" fill-opacity="0.0" onmouseover="evt.target.setAttribute('stroke-width', '6');" onmouseout="evt.target.setAttribute('stroke-width','3');"/>
    </a>
    <rect x="59.5" y="169.5" width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
    <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
        <tspan x="109.5" y="195.44">BUILD</tspan>
    </text>
    <g transform="matrix(0 -1 1 0 349.5 159.5)">
        <rect width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
        <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
            <tspan x="50" y="25.94">RELEASE</tspan>
        </text>
    </g>
    <rect x="239.5" y="169.5" width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
    <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
        <tspan x="289.5" y="195.44">OBSERVE</tspan>
    </text>
    <g transform="matrix(0 -1 1 0 179.5 159.5)">
        <rect width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
        <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
            <tspan x="50" y="25.94">TEST</tspan>
        </text>
    </g>
    <rect x="69.5" y="79.5" width="80" height="60" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
    <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
        <tspan x="109.5" y="115.44">PLAN</tspan>
    </text>
    <rect x="239.5" y="9.5" width="100" height="40" rx="10" class="B" stroke-width="3" fill="var(--r-background-color)"/>
    <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
        <tspan x="289.5" y="35.44">DEPLOY</tspan>
    </text>
    <rect x="249.5" y="79.5" rx="10" width="80" height="60" class="B" stroke-width="3" fill="var(--r-background-color)"/>
    <text class="C D F G H" white-space="pre" fill="var(--r-main-color)" stroke="none" font-family="Open Sans" font-size="18px" font-weight="bold">
        <tspan x="289.5" y="115.44">PLAN</tspan>
    </text>
</svg>

---

In between...

---

<!-- .slide: id="code" -->

Placeholder slide

<a href="#/title-slide">Back to Title</a>