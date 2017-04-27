# prism-for-blogspot
Placeholder for [prism CSS and JS files](http://prismjs.com/download.html) needed for code highlighting http://corinnekrych.org/ 

In you Blogger, go yo Theme then Edit HTML, do a backup first and then

* include prism with in header link the CSS:
```
 <link href='https://cdn.rawgit.com/corinnekrych/prism-for-blogspot/master/prism.css' rel='stylesheet'/>
```
* and in body:
```
<script src="https://cdn.rawgit.com/corinnekrych/prism-for-blogspot/master/prism.js"></script>
```
you need to use `cdn.rawgit.com` isntead of `raw.githubusercontent.com` to [avoid MINE issue](http://stackoverflow.com/questions/17341122/link-and-execute-external-javascript-file-hosted-on-github).
