# virtualIP 
### The problem: 
Sometimes I need a server to test -or deploy- my projects but I do not want -or can afford- to pay for a hosting service. Nowadays with **domestic fiber speed connections**, you can host yourself your projects. There is a catch: The domestic internet connections usually means the end user will have a **dinamic ip**. I built this **low cost** solution so I could develop my apps without any 3 party services.
### Parts:
* The server
* The middleman 
* The clients
### How this works
* The server -the one with you server app logic-   
  1. get external ip  
  2. Encript the ip  
  3. Upload the ip to the middleman  
  _this 3 steps have to be done periodically, as the ip can change anytime_
* The client/s  
  1. Read the encripted ip from the middleman 
  2. Decript the ip  
  3. Connect  
  

## Pros:
* No domain needed
* No Dinamic ip service needed
* Free and easy to use
* Works everywhere
## Cons:
* You need a middleman - github (free)
## TODO
* Add new middlemen
