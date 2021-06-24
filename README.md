# jsbash
API for interpreting Bash code in a Buildroot Linux VM.

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
