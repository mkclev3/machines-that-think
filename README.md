# Final Project: The Soul of Art
[copy intro here]

****Human-Made Art Inspiration****

**Ectasy**


**The Last Unicorn**
<img src="img/Unicorn OG">
<sub> A Scene from 1982 film "The Last Unicorn" <sub>
	This is a scene from the movie “The Last Unicorn” (1982), one of the animated movies we had on repeat when I was a kid. The movie has plenty of problems, but I’m still a fan of the art. Looking at this scene makes me feel strangely sad. I’m reminded of a feeling of melancholy, peace, and maybe a little bit of despair. In this scene, the unicorn has been wandering alone for a long time and wishes to be reunited with the other unicorns. Even if you haven’t seen the movie, though, you can tell what she’s feeling just by looking at it, even though it's a weird mythical deer-horse unicorn thing. I think its is absolutely gorgeous, especially the lighting. Similar to “ecstasy,” something I really love about this piece is how graceful and ethereal the unicorn seems. I feel like I could stare at this frame for forever, its strangely hypnotizing. I also LOVE the trees and the background. Its got such a 1980s animation feel, I miss when movies were animated that way. It pops! Its just so gorgeous and so sad. And like mysterious 


**Nadeesh Prabou Watercolor**

**Breaking Bones**
<img src="img/Bones OG">

This last painting is a digital piece by an artist I’ve been following for a while, [insert tumblr]. This particular piece is a fanart of a creator I don’t really follow, but I wanted to include at least one piece that’s a digital fanart piece because even if it’s a little silly I’m absolutely obsessed with good fanart. Everyone can connect to them so much more than with most random pieces, even if the radom pieces are better done. I know and love the story, so I feel so much more while looking at the piece. I also just love emotional and dramatic and sometimes slightly fantastical people art. It’s just so cool, they make me so happy. I love the lighting in this one so much, and I think it’s very well done. When I first saw it, I spent 10 minutes just trying to figure out their process and what I liked so much about it. I love the sort of anxiety-inducing?? Quality of this one. Looking at it I’m reminded of the feeling of pent up emotions, or the feeling of almost being this close to losing it. I love the fantastical, swishy?? Vibe of it. 
I also feel like he looks angry but resigned, which is maybe a combination ai won’t be as accustomed to. He looks very cold, and it feels powerful? In a way. Like that feeling when u absolutely obliterate someone and are like yea, im unstoppable, its no biggie. I’m interested to see how AI attempts to replicate such a subtle emotion.

```
   
    
    import numpy as np
    from PIL import Image as im
   
    base = [[white for i in range(100)] for j in range(100)]
    near_center = lambda x, y : dist(x-50,y-50) < 50
    add_circ(base, yellow, near_center)
    arr2img(base)
    
    eye1 = lambda x, y : dist(x-30,y-80) < 10
    black = [0,0,0]
    add_circ(base, black, eye1)
    arr2img(base)

    eye2 = lambda x, y : dist(x-30,y-20) < 10
    black = [0,0,0]
    add_circ(base, black, eye2)
    arr2img(base)

    mouth = lambda x, y : dist(x-60,y-50) < 15
    red = [128,0,0]
    add_circ(base, red, mouth)
    arr2img(base)

    eyebrow1 = lambda x, y : dist(x-15,y-80) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow1)
    arr2img(base)

    eyebrow1 = lambda x, y : dist(x-15,y-85) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow1)
    arr2img(base)

    eyebrow1 = lambda x, y : dist(x-15,y-75) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow1)
    arr2img(base)

    eyebrow2 = lambda x, y : dist(x-5,y-25) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow2)
    arr2img(base)

    eyebrow2 = lambda x, y : dist(x-5,y-15) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow2)
    arr2img(base)

    eyebrow2 = lambda x, y : dist(x-5,y-20) < 3
    black = [0,0,0]
    add_circ(base, black, eyebrow2)
    arr2img(base)

    frown = lambda x, y : dist(x-75,y-50) < 15
    black = [255,255,0]
    add_circ(base, black, frown)
    arr2img(base)
   ```


