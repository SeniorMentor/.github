
---

<img align="left" src="assets/gif/smgif.gif" width="100" height="100" />

<div align="center" > 
<h1><b> Seniormentor </b></h1>  
<i> Connect with peers in college, help and get help. </i>
</div> 


---

<br>

Checkout https://seniormentor.netlify.app/ 

Features 
---

> <ul>
> <li> Interact with posts added by peers and add your own posts </li>
> <li> Search anyone by skills, name, branch, skill, etc. </li>
> <li> Reach out to anyone via a chat interface</li>
> <li> Get all notifications on a separate tab </li>
> <li> Responsive UI </li>
> </ul>

Images and Demo
---

<div>
  <img src="assets/gif/gif1.gif" width="200" height="400"/>
  <img src="assets/gif/gif2.gif" width="200" height="400"/>
  <img src="assets/gif/gif3.gif" width="200" height="400"/>
</div>


Installation  `deprecated - will be updated in some time`
--- 
  Clone the repo

  ```bash 
  git clone https://github.com/ayushtom/Senior-Mentor.git
  ```

  Do npm install in both client and server folders

  ```bash 
  cd client 
  npm i 
  ```

  ```bash
  cd server 
  npm i 
  ```
  Change the name of .env.example file from each client and server folders to .env

High Level Design 
---
```
Use case diagram for Seniormentor
```

<img align="center" src="assets/img/hld.png" />

Low Level Design
---
```
UML diagram for Seniormentor
Note : Although it's a NoSQL db, the database design would be as shown below
if it were a relational database.
Collections are connected using refs. 
```
<img align="center" src="assets/img/uml.png" />

