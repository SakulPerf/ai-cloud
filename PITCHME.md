@title[Introduction]
# AI

### made easy on Cloud Platform

---

## Agenda

* AI
* Navigating AI Revolution
* Machine Learning
* Cloud AI Services
* Demo

---

## AI?

---?image=https://media.giphy.com/media/4yrXiUTCzPTeE/giphy.gif

@snap[east]
@size[2em](@color[white](What's AI?))
@snapend

---

## Artificial Intelligence

“The term "`Artificial Intelligence (AI)`" is applied when a machine mimics "cognitive" functions that humans associate with other human minds, such as "learning" and "problem solving".”

@snap[south-east]
-- Wikipedia
@snapend

+++

## Artificial Intelligence

“Artificial Intelligence is just whatever a computer can’t do yet…”

@snap[south-east]
-- Chris Bishop, Microsoft Research
@snapend

+++

## AI

“Artificial Intelligence is computers doing things that we would normally think of as intelligent in humans.”

@snap[south-east]
-- Rick Barazza, Microsoft DX
@snapend

---

![Google's AI Assistant Make Real Phone Calls](https://www.youtube.com/embed/JvbHu_bVa_g?start=5)

+++

![Tesla Model X, autopilot avoids a crash in The Netherlands](https://www.youtube.com/embed/FadR7ETT_1k)

+++

![AI plays Super Mario Bros](https://www.youtube.com/embed/QVyu9oVyh9Q?start=6)

---

## Navigating AI Revolution

+++?image=assets/image/ai-nav-01.png

+++?image=assets/image/ai-nav-02.png

+++?image=assets/image/ai-nav-03.png

+++

## AI Enablers

@ol
* New combo of Math
* Big data
* Massive Computation
@olend

---

## Machine Learning

![Machine Learning like a baby](https://media.giphy.com/media/QPsnos4tcLJaU/giphy.gif)

---

![MarI/O - Machine Learning for Video Games](https://www.youtube.com/embed/qv6UVOQ0F44)

---?code=sample/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---?image=assets/image/snowscape.jpg&size=auto 80%&color=#58b9f5

<!-- Sample slide background image scaling and custom color fill -->

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Images](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Background Image Scaling](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#scaling)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

## GitPitch Pro Features

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Questions?

@fa[twitter gp-contact](@tlaothong)

@fa[github gp-contact](tlaothong)

@fa[facebook gp-contact](@digitalthailandclub)
