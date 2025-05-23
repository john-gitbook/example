# javascript

"javascript": {\
"onRequestScript": "response.headers.remove('X-Powered-By');",\
"onResponseScript": "response.headers.set('X-Gravitee-Gateway-Version', '0.14.0');",\
"onRequestContentScript": "" // Not executed if empty\
"onResponseContentScript": "" // Not executed if empty\
}



```
"javascript": {
    "onRequestScript": "response.headers.remove('X-Powered-By');",
    "onResponseScript": "response.headers.set('X-Gravitee-Gateway-Version', '0.14.0');",
    "onRequestContentScript": "" // Not executed if empty
    "onResponseContentScript": "" // Not executed if empty
}
```
