# mylinks
JavaScript library for mylinks.top
# main
```js
async function main(){
    const {mylinks} = require('./mylinks');
    const links= new mylinks();
    let req=await links.short_url("url")
    console.log(req)
}
main()
```
