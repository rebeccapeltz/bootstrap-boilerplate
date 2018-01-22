# bootstrap-boilerplate
https://getbootstrap.com/

`npm init`
`npm  install --save bootstrap`
`npm install --save jquery`
`npm install --save popper.js`

I found a problem loading popper.js and after looking at SO I see that you can either use the CDN that Bootstrap provides on it's install page or copy the code from that CDN to your own Vendor file.  The index.html shows both.

Do forget to add a .gitignore and put node_modules/ init.