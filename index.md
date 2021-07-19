## Welcome to The Jade001 Map!

 *journey of jade001*

[Click to view the Chinese Emperor's Hindustan Jades in the Forbidden City](https://thefcmapsearchsample.netlify.app/)

<iframe src="https://mapjade001.netlify.app/" height="600" width="800"></iframe>

Other Methods to host html file:

Method 1:

<object data="https://htmltesttt.netlify.app" width="600" height="400">
    <embed src="https://htmltesttt.netlify.app" width="600" height="400"> </embed>
    Error: Embedded data could not be displayed.
</object>

Method 2:

<object data="https://htmltesttt.netlify.app"
width="600"
height="400"
type="text/html">
    Alternative Content
</object>

Method 3:
<iframe src="https://mapjade001.netlify.app/" height="600" width="400"></iframe>

Method 4:
<embed src="https://htmltesttt.netlify.app"
width=600
height=400
onerror="alert('URL invalid !!');" />

Method 5:
<!-- Resources on other origins must be CORS-enabled. -->
<link rel="import" href="https://htmltesttt.netlify.app">

Method 6:
xhr = new XMLHttpRequest();
xhr.onreadystatechange = function() {
  if(xhr.readyState == 4 && xhr.status == 200) {
    document.getElementById('displayDiv').innerHTML = xhr.responseText;
  }
};
xhr.open('GET', 'https://htmltesttt.netlify.app', true);
xhr.send();
