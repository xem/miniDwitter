Mini Dwitter
===

Dwitter clone with textarea and auto reset when the code is edited (248b)
NB: the function u() is not present.

````
<body onload='t=0;x=c.getContext`2d`;with(Math)S=sin,C=cos,T=tan;R=(r,g,b,a=1)=>`rgba(${[r|0,g|0,b|0,a]})`;setInterval("eval(A.value);t+=.016",16)'><canvas id=c width=1920 height=1080 style=width:5in></canvas><br><textarea id=A cols=60 oninput=t=0>
/* insert demo code here */
````

Demo: http://xem.github.io/miniDwitter

---

Dwitter clone without textarea (193b)
NB: the function u() is present.

````
<canvas id=c width=1920 height=1080 style=width:5in><script>t=0;x=c.getContext`2d`;with(Math)S=sin,C=cos,T=tan;R=(r,g,b,a=1)=>`rgba(${[r|0,g|0,b|0,a]})`;setInterval(u=z=>{
/* insert demo code here */
;t+=.016},16)</script>
````

Demo: http://xem.github.io/miniDwitter/mini.html
