# Two way iframe communication

The only thing different between the two pages is the method of sending message. Recieving messages is the same in both.

## Parent

Send messages to iframe using `iframeEl.contentWindow.postMessage`
Recieve messages using `window.addEventListener('message')`

## iframe

Send messages to parent window using `window.parent.postMessage`
Recieve messages using `window.addEventListener('message')`

## License

MIT
