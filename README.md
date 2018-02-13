# nowUseeMe
**Vanilla JavaScript: this JavaScript will detect whether an element is visible or not.
For the webdocumenary case, 2nd semester Multimedia Designer, spring 2018.**

* [Online version](https://asathoor.github.io/nowUseeMe/)
* See the result in the JavaScript console.

Use the `nowuseeme.js` in order to detect whether a tag in `index.html` is visible or not. The tag is defined in [this line](https://github.com/asathoor/nowUseeMe/blob/master/js/nowuseeme.js#L7).

The video is added via an iframe. If you want it to play when visible make sure to set autoplay to 1, as in this line of the function playVideo(). Note autoplay=1 in the src:

~~~~
 a.innerHTML = '<iframe id="ytplayer" type="text/html" width="720" height="405" src="https://www.youtube.com/embed/M7lc1UVf-VE?autoplay=1&cc_load_policy=<1></1>" frameborder="0"  allowfullscreen>';   
~~~~

If you want to load your own video file, then use a HTML5 video tag as your innerHTML.

## What is a webdocumentary?
From the perspective of the designer og communicator a webdocumentary is a visual genre related to storytelling, e.g. in online journalism. From the perspective of the web developer a webdocumentary is just a long html document enhanced by the usual suspects: JavaScript and CSS. Basicly a webdocumentary behaves in the same way as the scrolls from ancient cultures. The Egyptian "Book of the Dead" and the Hebrew "Tora" are samples of a the storytelling tradition that precedes the modern books. 

![Wikimedia: Scene from the Papyrus of Hunefer](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Weighing_of_the_heart3.jpg/256px-Weighing_of_the_heart3.jpg)

But the web scroll can do thing, that was not possible in the scrolls of antiquity. By JavaScript and CSS the webdocumentary comes to life. You can detect where the mouse is, if the arrow hover a certain element, clicks and even if some element is visible or not. Events are the keys to the art.

So the webdocumentary is a way to tell a story by by means of human interactions with your scroll.

## Sources

* [Samuel L. Ipsum](http://slipsum.com/)
* [Tell if a dom element is visible](https://stackoverflow.com/questions/123999/how-to-tell-if-a-dom-element-is-visible-in-the-current-viewport/)

## Other Vanilla Solutions

* [Duckduckgo query](https://duckduckgo.com/?q=vanilla+javascript+detect+if+element+is+visible&atb=v71-6__&ia=qa&iax=qa)
