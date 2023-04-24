# CardScrolling


# Introduction 
Two days ago, i was scrolling through a site and i saw this beautiful card scrolling effect 😁 it was so cool, i decided to actually figure out how to do it, took me some time but, i finally figured it out! 😫 Thanks to the internet and my little knowledge. (!the internet did most of the work)
Enjoy¬🙂 !ignore the pyscript tags and commands, also the python files, will add somethimg 😎 cool later

# html 
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script defer src="/pyscript.js"></script>
    <link rel="stylesheet" href="/index.css" />
    <title>Document</title>
  </head>
  <body>
    <header>CARD</header>
    <div class="container">
      <div class="page1">Home</div>
      <div class="page2">About</div>
      <div class="page3">Projects</div>
      <div class="page4">Contact</div>
    </div>
    <footer>FOOTER</footer>
  </body>
</html>

```


# css 



``` body {
  background-color: #eeee;
  font-family: "Inter";
}

.container {
  font-size: 1.3rem;
}

.page1 {
  width: 100%;
  height: 100vh;
  background: rgb(60, 87, 87);
  color: white;
  text-align: center;
  position: sticky;
  top: 0;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```


# DEMO
https://user-images.githubusercontent.com/60699279/233894042-89c292d4-dbe3-4ffb-8fdd-8e6f57d1c893.mp4


