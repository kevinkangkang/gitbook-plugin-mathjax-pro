<blockquote style="background-color: #f7f7f7; border-left-color: #777777;border-radius: 3px; padding: 5px 15px 15px 15px;">
<b style="color: #777777; padding-left: 0px; line-height:40px">>&nbsp;Quote</b><br/>
<div style="padding-left: 0px; color: #000000; word-wrap: break-word;">
The plugin is based on the official mathjax plugin.<br/>
<a href="https://github.com/GitbookIO/plugin-mathjax">https://github.com/GitbookIO/plugin-mathjax</a><br/>
</div></blockquote>

<blockquote style="background-color: #f7f7f7; border-left-color: #777777;border-radius: 3px; padding: 5px 15px 15px 15px;">
<b style="color: #777777; padding-left: 0px; line-height:40px">>&nbsp;Note</b><br/>
<div style="padding-left: 0px; color: #000000; word-wrap: break-word;">
The official gitbook plugin has been closed and would not get the maintaince and the official mathjax plugin has some problem, so I want to change it.<br/>
</div></blockquote>

<blockquote style="background-color: #eef7fa; border-left-color: #428bca;border-radius: 3px; padding: 5px 15px 15px 15px;">
<b style="color: #428bca; padding-left: 0px; line-height:40px">▲&nbsp;Important</b><br/>
<div style="padding-left: 0px; color: #000000; word-wrap: break-word;">
Require GitBook >=2.0.0.<br/>
</div></blockquote>

# How to use it?

> The default version of mathjax is 2.7.7
>
> So the following steps will be based on this version.

- Install the mathjax

```bash
npm install mathjax@2.7.7
```

- Add it to your `book.json` configuration:

```json
{
    "plugins": ["mathjax-pro"]
}
```

- Install your plugins using:

```bash
gitbook install ./
```

And then you can use mathjax in you gitbook.

# Configuration

## Change the version

You can change the version of mathjax such as 2.7.5

- Install the mathjax

```bash
npm install mathjax@2.7.5
```

- Adding it to `book.json`:

```json
{
    "pluginsConfig": {
        "mathjax-pro":{
            "version": "2.7.5"
        }
    }
}
```

## Use of svg

You can force the use of svg pre-processed

- adding to your `book.json`:

```json
{
    "pluginsConfig": {
        "mathjax-pro":{
            "forceSVG": true
        }
    }
}
```