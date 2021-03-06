
### Getting started

To get started, install the emailizer module. I recommend installing it globally so you can simply call it from anywhere and watch a specific folder:

```npm install emailizer -g```


### Creating an email from scratch

You can also use emailizer as a framework to start a basic email template (this will create a folder called NAME in the current directory and copy a sample email - based on Ink, and open an http server to show the email in the browser):

```emailizer create NAME```


### Watching a directory


You can then use emailizer to watch an html email which has its CSS linked in the head and auto-render to an output folder:

```emailizer watch ./SOURCE ./DEST```

*Note: You can use both relative and absolute paths.*



### Dependencies

* Ink [http://zurb.com/ink/]
* Juice2 [https://www.npmjs.com/package/juice2]
* node-watch [https://www.npmjs.com/package/node-watch]
* node-static (could be removed, but allows to quickly display the email the browser)
* fs-extra

### Domani

This module was brought to you by [Sam](http://samueldelesque.me) at [Domani Studios](http://domanistudios.com)