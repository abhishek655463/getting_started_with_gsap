# getting_started_with_gsap
---
## what is Gsap 

GSAP is **(Green Sock Animation Platfom)** it is java script library for animation, it is wide library we can animate anything with this library(it is a pre written code that can use to perform commom task).

* gsap use for movement animation moving or transaction.

---

## some commands

x and y :- these are position of element or text.

1) stagger :- it handle to work things in sequence for and apply over group if we have h1 3 times and they have stagger then all will execute in a line one by one.here is a example of code with staggger 

```
gsap.from("h1",{
    x:600,
    opacity:0,
    duration:2,
delay:1,
stagger:1
})

```

stagger accept value -1 to 1 

1--> execute code up to down. 
-1 --> revese down to up.

---

2) repeate :- to repeat the animation (it take number how may times it have to play it work n+1)

* -1 --> this value make effect infinite.

---

3) yoyo :- this make repeate in same sequence if a box move from left to right, yoyo will make it follow the same path and move the box at it's inital position.
---
---
## Timeline is gsap.
explaintation:- the time line is use to sequence and controlled animation, it helps to **start**, **end** and **synchronization** of different animaiton.

```
# to use time line we create a variable of timeline and then use them in aniamtion.

let tl=gsap.timeline();

tl.to("box",
{
    x:200,
    duration:1
})

tl.to("box2",{
    y:300,
    duration:2
})
```

* anything in timeline with manage by gsap and work accordingly.
