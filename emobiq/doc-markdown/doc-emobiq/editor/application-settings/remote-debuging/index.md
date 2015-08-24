#Remote Debugging

Emobiq debugging support by weinre (Web Inspector Remote), weinre is debugging for web pages , like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, toallow you debug web pages on a mobile device such as a phone.
Before use , make sure you have Node installed to install weinre : 

`npm -g install weinre`

To Set debugging on emobiq

On Global Setting, set value :

`http://<ipaddress:port>/target/target-script-min.js#anonymous`

set ip address:port Just replace the ip address with your own. 

after application build install on your smartphone. To start debugging start weinre on terminal :

`weinre --boundHost -all–`

Then, in your browser 

`http://<ip address>/target/target-script-min.js#anonymous`

Build the code on your phone or in an emulator and make sure your device is on the same network as your computer.

It’s pretty similar to Chrome Dev Tools, and in the Remote tab it gives a list of all targets connected. You can select one and it will turn green, then you can open up any of the other tabs and do things like view console.log messages, run js commands, inspect elements, change css styles (double-click to add or change the css), view localStorage and databases, run database queries, etc.

If you’re having trouble inspecting elements that are injected with ajax, refresh the page (on your computer) and then it should be there.

There are also more advanced features of Chrome Developer tools that you can’t turn use such as javascript breakpoints, but overall, it’s a very useful tool. 
