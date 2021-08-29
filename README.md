# Popcat auto click
Auto click on popcat click meme (popcat.click)

## Code
Slow but savety, it will send 799 click to server every 30s.
```javascript

const ev = new KeyboardEvent('keydown',{key:'g',ctrlKey:true});
setInterval(() => {
  for (i=0;i<799;i++) {document.dispatchEvent(ev)}
},30000);

```

## How to use
1. Go to `popcat.click`
2. Press `F12` (Open `developer tool` of web browser)
3. Switch to tab `Console` in `developer tool`
4. Paste the `Code` above and press `Enter`
5. Enjoy

## Tips and tricks
1. If you run auto click very fast **or** run auto click on multi tab/multi browser, the result **will not** commit to the server.
2. After the `Code` ran, you may need to close the `developer tool` by press `F12` again. If don't, it is running out of RAM memory.
3. Max `PPS` is 800/30s, if over, the result **will not** commit to the server.
4. The result is count per IP address.
5. Recommended to use `Private window`.
6. If the Cat's eyes are `red`, you are blocked, let close current `Private window` and use a new once.
