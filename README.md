## kembang

![kembang](https://raw.githubusercontent.com/httpsecure/gambar-blog/main/images/screenshot.png)


I made this theme for learning purpose so maybe not perfect.

why this theme name kembang ? kembang = flowers.

## Demo

 Some text on demo site from wikipedia, flowers images unsplash, svg icon bootstrap.
 
 [kembang-theme.netlify.app](https://kembang-theme.netlify.app/)

## Features

* Fully responsive
* Bootstrap CSS only
* About, Tags, and List pages
* Easy to customize
* Lighthouse score 100%
* Local font jost
* Mozilla Observatory A+ click this [link](https://observatory.mozilla.org/analyze/kembang-theme.netlify.app)

This theme using bootstrap 5.2

Using BS for local development

```
custom_css = [ "/css/main.css", "/css/normalize.css", "/css/bootstrap.css"]
```
For production You can use CDN and delete this line parameters
```
"/css/bootstrap.css"
```
and add this inside **head.html**
```
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
```
## Lighthouse score

![Lighthouse](https://raw.githubusercontent.com/httpsecure/gambar-blog/main/light.png)

## Code highlighting

By default hugo using chroma to color your code syntax. All you need to do is to wrap you code like this:

<pre>
``` css
 your code here
```
</pre>
For style prefered you can try this :

[https://swapoff.org/chroma/playground/](https://swapoff.org/chroma/playground/)

For this theme using solarized-dark256

## Favicon

You can use favicon generator & put the favicon file inside **static** folder

## Installation

You can download the theme manually, extract & copy the examplesite go to themes directory
or

Navigate to the root directory of your Hugo site and clone this repository.
``` 
git clone https://github.com/httpsecure/kembang.git themes/kembang
```
Refer to the [Hugo docs](https://gohugo.io/getting-started/quick-start/) for more information.

## Note

If you manualy install hugo, you must install hugo extended version

If you using debian/ubuntu & install hugo from repo it will include **libsass1**

## Discussions

[Discussions](https://github.com/httpsecure/kembang/discussions)

## License

This theme released under the [MIT License](https://github.com/httpsecure/kembang/blob/main/LICENSE) same as bootstrap.


