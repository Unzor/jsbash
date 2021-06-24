# jsbash
API for interpreting Bash code in a Buildroot Linux VM.

# Installation
Get from CDN:
```html
<script src="https://cdn.jsdelivr.net/gh/Unzor/jsbash/jsbash.js"></script>
```

# API
Example code:
```javascript
    jsbash.init({
    callback: function(a){
alert(a);
    },
    onReady: function(){
jsbash.run('echo Hello!');
    },
    os_messages: true
  });
  ```
  
  This code will run JSBash in a new VM instance, and when the VM has booted, it will alert "Hello!"
