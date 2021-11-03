# Safari-auto-refresh
Ruby script to automatically refresh the Safari tabs on the top when some files in the folder watching is changed

### use
in its directory, do
```zsh
ruby watch.rb <folder directory>
```
and also put the webpage that you want to refresh on top

### the way it works
the script now works like this: it brings the Safari window onto the top and send it "command + R"
this is to preserve the location you are at on the page

### modify the script to work with other browser
open it and change "Safari" into whatever you like

### code from
[Watch for file changes and refresh your browser automatically](https://brettterpstra.com/2011/03/07/watch-for-file-changes-and-refresh-your-browser-automatically/)
