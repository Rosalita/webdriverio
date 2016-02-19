# webdriverio-example
working example of webdriver.io a javascript testing frame work which uses Mocha and Chai

based on a git clone from https://github.com/stevejhiggs/webdriverio-example.git

Setup
install node.js then:
git clone this repo
npm install -g webdriverio
npm install -g wdio-mocha-framework
npm install -g chai
npm install --save-dev chai
npm install --save-dev chai-as-promised
npm install -g webdriver-manager
webdriver-manager update --standalone
webdriver-manager start

Then to start the test type:
wdio
