# streamersonglist-songcheck
check streamersonglist with nightbot/streamelements command

Create a new project & Deploy as web app here https://script.google.com/


nightbot:  
```
$(user) $(urlfetch https://script.google.com/macros/s/YOURDEPLOYURL/exec?streamer=$(channel)&title=$(querystring))
```

streamelements:  
```
$(user) $(urlfetch https://script.google.com/macros/s/YOURDEPLOYURL/exec?streamer=$(channel)&title=${queryescape ${1:}})
```
