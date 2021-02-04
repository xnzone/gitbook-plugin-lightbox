# gitbook-plugin-lightbox
 this repository is forked from [gitbook-plugin-lightbox](https://github.com/vongola12324/gitbook-plugin-lightbox.git). but the origin repository can not control some image don't use lightbox, i add an attr in <img>, so that i can ignore lightbox according attr value

## Requirement
-  Gitbook >= 3.0.0

## Installation
Add the below to your book.json file, then run gitbook install :
```json
{
  "plugins": ["lightbox@git+https://github.com/xnzone/gitbook-plugin-lightbox.git#0.0.1"]
}
```

## Usage
all config can be same as [gitbook-plugin-lightbox](https://github.com/vongola12324/gitbook-plugin-lightbox.git), if you want to ignore lightbox, you can use in you markdown using html as this:
```html
<img src="https://badgen.net/github/stars/xnzone/csnote?icon=github" title="no-lightbox">
```
or like this(if you prefer markdown)
```md
![wechat](https://gitee.com/ixnzone/img-bed/raw/master/wechat.jpg "no-lightbox")
```
