# Two way iframe communication

Seamless communication between an iframe and a parent page.

## Demo

[http://pbojinov.github.io/iframe-communication](http://pbojinov.github.io/iframe-communication/)

The main difference between the code in the two pages (parent and iframe) is the method of sending messages. Recieving messages is done using the same code.

### parent

Send message to iframe using `iframeEl.contentWindow.postMessage`

Recieve message using `window.addEventListener('message')`

### iframe

Send message to parent window using `window.parent.postMessage`

Recieve message using `window.addEventListener('message')`

## License

MIT
