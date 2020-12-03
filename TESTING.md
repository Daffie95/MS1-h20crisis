

# Milestone Project 1
## This page contains documentation for testing and debugging the project. Aswell as final testing.

### The H20 Crisis

Please forward questions to my [e-mail](patrik.svahnstrom@gmail.com)

1. <strong>Testing</strong> - Line 25.
2. <strong>Bugs & Errors</strong> - Line 63.
4. <strong>Final Testing</strong> - Line 75.
   - Testing index.html Links - Line 73.
   - Testing resources.html Links - Line 104.
   - Testing partner.html Links - Line 142.
   - Testing helpus.html Links - Line 189.
        - <strong>W3C CSS Validator</strong>
        - index.html. - Line 215.
        - resources.html. - Line 226.
        - partners.html. - Line 237.
        - helpus.html. - Line 249.
5. <strong>Web.Dev</strong>. - Line 263.
6. <strong>Network</strong>

# 1. Testing

Color codes:<br>
<span style="color:red;">Red is errors <br>
<span style="color:orange;">Orange is warnings<br>
<span style="color:green;">Green is fixed errors or warnings<br>

> <strong>#2020-12-02</strong> (~19:35) [Testing placeholder 404 page]
>
> > Expected result: 404 page to show when invalid link is selected.
> >
> > > Actual Result: <span style="color:red;">Custom 404 page shows instead of default 404 page</span>
> >
> > > Measure Taken: <span style="color:green;">Creating a custom 404 page is not a gradeable topic in this project. Removed</span>

> <strong>#2020-12-02 (~13:20)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:orange;">unknown supplier extension</span><br>
> >
> > > - -webkit-background-size
> > > - -moz-background-size
> > > - -o-background-size
> > >   > Measure Tanken:<span style="color:green;">No warnings found when removing webkit/moz/o-background-size.</span>

> <strong>#2020-12-01 (~18:30)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:red;">filepath errors across all pages.</span>
> >
> > > <span style="color: green;">Filepath errors across all pages (Fixed)</span>

> > <span style="color:red;">Background image slows down loading.</span>
> >
> > > <span style="color: green;">Backgrond image slows down loading (Fixed)</span>

> > <span style="color: orange;">Redundant code in css.style.</span>
> >
> > > <span style="color: red;">Redundant code in css.style </span>

# 2. Bugs & Errors

> <span style="color: orange;">Background Image does not load on my mobile phone (Iphone X). (2020-12-03)

> - <strong>Expected result:</strong>
>   > Background to be in place when loading the page on mobile.
>   >
>   > - <strong>Result:</strong>
>   >   > <span style="color: red;"> Background image is not active. </span>
>   > - <strong>Solution:</strong>
>   >   > <span style=": green;">-</span>
> >  comment: I dont know how to troubleshoot this error, the background image is in place while using the DevTools on the GitHub page.

> - <strong>Expected result:</strong>
>   > No padding to be present on main text container on index.html
>   >
>   > - <strong>Result:</strong>
>   >   > <span style="color: red;"> padding is in place on index.html </span>
>   > - <strong>Solution:</strong>
>   >   > <span style=": green;">-</span>
> >  comment: I dont know how to troubleshoot this error, the padding is not in place while using the DevTools on the GitHub page.

> <span style="color: orange;">Active link not showing correct color. (2020-11-30)

> - <strong>Expected result:</strong>
>   > "Help Us & Contacts" link to be correct color when active, and not green as it is in idle state.
>   >
>   > - <strong>Result:</strong>
>   >   > <span style="color: red;"> "Help Us & Contacts" link turns the wrong color on active but is being overwritten to turn back to green. </span>
>   > - <strong>Solution:</strong>
>   >   > <span style="color: green;">Targetting the correct class with proper selector</span>

# 3. Final Testing


Color schematic: <br>
- <span style="color:#007bff">Blue is Top Navigation Elements</span><br>
- <span style="color:#d39e00">Orange is In-page navigation Elements</span><br>
- <span style="color:#bf7272;">Red is Navigation Elements</span><br>
- <span style="color:#3e0e0e;">Burgundy is Anchor Element</span><br>
    * Prerequisite to being approved is that the anchor element opens in a new tab. <br>
    if the link references to an external page.
- <span style="color:#d300cd;">Magenta is Social Media icons Elements</span><br>
- <span style="color:#001ad3;">Ultramarine is Footer Navigation Elements</span><br>
- <span style="color:#00d3c9;">Cyan is Footer email Element</span><br>
- <span style="color:#04f343;">Poison green is Image Element</span><br>
<br>
### <strong>Links</strong>

> Testing index.html page

> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link</span>

> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Navigation "What is happening?"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Nav. "Why is it happening?"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">inpage Nav. "What can we do?" </span>

> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Water Scarcity Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Resouces Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">GWI Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UNECE Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UN SDG-6 Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Solar Desalination Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Smart Irrigation (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Partner's Link (Internal)</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Resources</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>

> <strong>Testing Resources Page</strong>
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link</span>

> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Navigation "Let's Learn"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Nav. "Water Facts"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">inpage Nav. "Formal Sources" </span>

> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Why is it happening (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">World Wildlife Foundation Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Ramsar Convention link(_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">68 Wetlands Links(_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UK Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Mexico Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">SDG-6 Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Water Footprint Network Link (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UNESCO-IHE (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">National Water Footprint Accounts link (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Yangtze link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 1 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 2 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 3 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 4 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 5 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 6 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 7 Links</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to The H2O Crisis</span>
> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Partners</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>

> <strong>Testing Partners Page</strong>
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link (internal)</span>

> > > - <span style="color:green;">[X]<span style="color:#04f343;"> WHO Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> WHO anchor link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#04f343;"> WFF Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> WFF anchor link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#04f343;"> WCN Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> WCN anchor link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#04f343;"> WWC Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> WWC anchor link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#04f343;"> NatGeo Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> NatGeo anchor link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#04f343;"> Circle of blue Image link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#3e0e0e;"> Circle of blue anchor link (_blank)</span><br>

> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WHO Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WHO Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WHO Instagram Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WWF Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WWF Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WWF Instagram Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WCN Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WCN Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WCN Instagram Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WWC Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> WWC Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> NatGeo Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> NatGeo Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> NatGeo Instagram Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> Circle of Blue Facebook Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> Circle of Blue Twitter Link (_blank)</span><br>
> > > - <span style="color:green;">[X]<span style="color:#d300cd;"> Circle of Blue Instagram Link (_blank)</span><br>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Resources</span>
> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Help us</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>

> <strong>Testing Help Us page</strong>
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link</span>

> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Embrace Relief's Donation page (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Donate & Save lifes (_blank)</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Partners (internal)</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link (external by default)</span>

## W3C CSS Validator Jigsaw 2020-12-03 (~12:25) 
<strong>Testing index.html</strong> [Link to result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

> Errors <br>
> > - <span style="color:red;">Property text-decoration-skip-inkdoes not exist: none</span> 
> > - <span style="color:red;">Property overflow-anchordoes not exist: none</span>
> > > - <span style="color:green;">Errors are from Bootstrap CDN</span>

> Warnings <br>
> > - <span style="color:orange;">750</span>
> > > - <span style="color:green;">Warnings are from Bootstrap CDN</span>

<strong>Testing resources.html</strong> [Link to Result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fresources.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

> Errors <br>
> > - <span style="color:red;">Property text-decoration-skip-inkdoes not exist: none</span> 
> > - <span style="color:red;">Property overflow-anchordoes not exist: none</span>
> > > - <span style="color:green;">Both errors are from Bootstrap CDN</span>

> Warnings <br>
> > - <span style="color:orange;">750</span>
> > > - <span style="color:green;">All warnings are from Bootstrap CDN</span>

<strong>Testing partners.html</strong> [link to result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fpartners.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

> Errors <br>
> > - <span style="color:red;">Property text-decoration-skip-inkdoes not exist: none</span> 
> > - <span style="color:red;">Property overflow-anchordoes not exist: none</span>
> > > - <span style="color:green;">Both errors are from Bootstrap CDN</span>

> Warnings <br>
> > - <span style="color:orange;">769</span>
> > > - <span style="color:green;">750 Warnings are from Bootstrap CDN</span>
> > > - <span style="color:green;">19 Warnings are from Font Awesome CDN</span>

<strong>Testing helpus.html</strong> [link to result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fhelpus.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

> Errors <br>
> > - <span style="color:red;">Property text-decoration-skip-inkdoes not exist: none</span> 
> > - <span style="color:red;">Property overflow-anchordoes not exist: none</span>
> > > - <span style="color:green;">Both errors are from Bootstrap CDN</span>

> Warnings <br>
> > - <span style="color:orange;">769</span>
> > > - <span style="color:green;">750 Warnings are from Bootstrap CDN</span>


## 5. WebDev  
> 2020-12-02 (~22:49) [link to result](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2F)<br>
> 2020-12-03 (~12:23) [link to result](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Findex.html)

## 6. Nu Html Checker 2020-12-03 (~12:19)
> [link to result for index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2F)<br>
> [link to result for resoruces.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fresources.html)<br>
> [link to result for partners.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fpartners.html)<br>
> [link to result for helpus.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdaffie95.github.io%2FMS1-h20crisis%2Fhelpus.html)<br>

## 6. Network 
> [Link to DevTools Screenshot](https://gyazo.com/22e5b43c296c6a9c3553d89ec636f1dd)

## 7. Performance
> [Link to DevTools Screenshot](https://gyazo.com/7154b85736aca67242df3d7bdc98e126)