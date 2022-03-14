
# Code examples

### Wrap Markdown in `<div>` Tag
You can start using a div tag, but not really close it.

```
<div class="myDiv">
This is my text inside the image
![Yosemite]
(file:///home/lwi/Documents/lowdown-tests/dst/yosemite.png){.class #id}


<div class="anotherDiv">
... next content block
```

If their is not another opening `<div>` tag, it wraps everything that follows it. So you need to causisly wrap your content blocks.

[The LInk](https://www.gaultmillau.ch/life-style/die-besten-burger-der-schweiz)

### The Bite
Restaurant mit eigenem Charakter in der neben der Züricher Langstrasse.
- Die Burger waren sehr gut
- Die Con Carne Fries waren mir zu viel

Würde hier gerne wieder essen gehen. Aber dafür mit einer anderen Beilage. Die Con Carne Fries waren für den sehr guten Burger zu schwer.


#### What do i need?
- [ ] Markdown to html converter
- [ ] Server / Domain
- [ ] Deploy script => scp that boy to prod


<div class="myDiv">
This is my text inside the image
![Yosemite](file:///home/lwi/Documents/lowdown-tests/dst/yosemite.png){.class #id}


<div class="anotherDiv">
### THis is a h3
