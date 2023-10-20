## A Cross Site Scripting vulnerabilty exists in JSPWiki 2.12

### Step to exploit:

1. Navigate to http://jspwiki.local/Upload.jsp.

<img src="xss1.PNG">

2. Upload html file with content: `<img src=1 onerror="alert(1)"/>` and click on Upload button.

<img src="xss2.PNG">

3. Go to file path.

<img src="xss3.PNG">
