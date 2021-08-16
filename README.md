# Popcat auto click
Auto click on popcat click meme (popcat.click)

# Code
Slow but savety
``
const ev = new KeyboardEvent(
  'keydown',
  {
    key:'g',
    ctrlKey:true
  }
);
setInterval(() => {
  document.dispatchEvent(ev)
}, 60);

``

# How to use
1. Go to popcat.click
2. Press F12 (Open development tool of web browser)
3. Switch to tab `Console` in development tool
4. Paste the `Code` above and press `Enter`
5. Enjoy

# Tips and tricks
1. If you run auto click very fast **or** run auto click on multi tab/multi browser, the result **will not** commit to the server
