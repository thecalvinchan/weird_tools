# weird_tools

### AMEX Add All Offers Bookmarklet

This allows you to automatically claim all offers on AMEX.

<a href="javascript:(function()%7Bfunction%20main()%20%7Bconst%20bs%20%3D%20Array.from(document.getElementsByClassName('offer-cta')).filter(button%20%3D%3E%20button.getAttribute(%22title%22)%20%3D%3D%20%22Add%20to%20Card%22)%3Bif%20(bs.length%20%3E%200)%20%7Bconst%20b%20%3D%20bs.shift()%3Bconsole.log(b.getAttribute('title'))%3Bb.click()%3B%7Dif%20(bs.length%20%3E%201)%20%7Bconsole.log(bs.length)%3BsetTimeout(main%2C%20(4000))%3B%7D%7D%3Bmain()%7D)()">Drag this to bookmarks</a>
