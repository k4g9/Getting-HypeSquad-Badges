## Get HypeSquad Badges (really, not client-sided)

## Paste the code to `Console` in Discord
> For browser press `F12`  -  For desktop client press `Ctrl + Shift + I`
```js
let _mods = webpackChunkdiscord_app.push([[Symbol()], {}, (e) => e.c]);
webpackChunkdiscord_app.pop();

let findByProps=(...e)=>{for(let r of Object.values(_mods))try{if(!r.exports||r.exports===window)continue;if(e.every(e=>r.exports?.[e]))return r.exports;for(let t in r.exports)if(e.every(e=>r.exports?.[t]?.[e])&&"IntlMessagesProxy"!==r.exports[t][Symbol.toStringTag])return r.exports[t]}catch{}};

const api = findByProps("Jt", "tn").tn;
api.post({url: "/hypesquad/online",body:{house_id: 1}})
```
<details>
  <summary>What you should do if you can't paste the code?</summary>

### Type these 3 separately in the `Console`, it will allow you to paste the code into the console  

```
"allow pasting"
```
```
'allow pasting'
```
```
allow pasting
```
</details>
<details>
  <summary>How to remove the Badge?</summary>

### Paste this code into `Console` then your Badge gonna be removed

```js
let _mods = webpackChunkdiscord_app.push([[Symbol()], {}, (e) => e.c]);
webpackChunkdiscord_app.pop();

let findByProps=(...e)=>{for(let r of Object.values(_mods))try{if(!r.exports||r.exports===window)continue;if(e.every(e=>r.exports?.[e]))return r.exports;for(let t in r.exports)if(e.every(e=>r.exports?.[t]?.[e])&&"IntlMessagesProxy"!==r.exports[t][Symbol.toStringTag])return r.exports[t]}catch{}};

const api = findByProps("Jt", "tn").tn;
api.del("/hypesquad/online")
```
</details>

# You must change last part [{house_id: ...}](https://github.com/k4g9/Get-HypeSquad-Badges/blob/main/code.js) for different hypesquad badges
| Value | HypeSquad Hose | Badge |
|:------:|:---------:|:-------:|
| 1 | Bravery | ![Bravery](Bravery.png) |
| 2 | Brilliance | ![Brilliance](Brilliance.png) |
| 3 | Balance | ![Balance](Balance.png) |
---
![badges.png](badges.png)
