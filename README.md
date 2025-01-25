# getting_started_with_gsap 🧮
---
## what is Gsap 

GSAP is **(Green Sock Animation Platfom)** it is java script library for animation, it is wide library we can animate anything with this library(it is a pre written code that can use to perform commom task).

* gsap use for movement animation moving or transaction.
---
## Adding gsap animation 👼
to add gsap animation we use *gsap CDN* --> cdnjs website --> copy "gsap.min.js" copy and paste in your code.

```
# to work with animation we use following piece of code.

gsap.to
{
x:568,
duration:5,
delay:2
}
```

gsap.to --> it is use to define final position of element from initial position. here initial position is fixed and final is define by developer


(fixed)(initial position)⬛   ----------------------------->🟦(final position)(by dev)

gsap.from() --> it is reverse of *gsap.to()* and it is little different to use for example the developer decide the inital position and final position is fixed.

(by dev)(initial position)🟦  ----------------------------->⬛(final position)(fixed)


                  

