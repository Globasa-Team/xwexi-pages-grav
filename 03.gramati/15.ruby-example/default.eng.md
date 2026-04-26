---
title: 'Using HTML Ruby tags'
visible: false
published: true
---

Using <ruby> tags.

```
<ruby>term
    <rp>(</rp>
    <rt>English</rt>
    <rp>)</rp>
</ruby>
```
    
The `<rp>` tags hide punctuation used when copying and pasting the content. So it will look like:

> term (English)

<hr>
    
<b><i>
    <ruby>hin <rp>(</rp><rt>this</rt><rp>)</rp></ruby>
    <ruby>misu<rp>(</rp><rt>my</rt><rp>)</rp></ruby>
    <ruby>care <rp>(</rp><rt>four</rt><rp>)</rp></ruby>
    <ruby>daymo<rp>(</rp><rt>very</rt><rp>)</rp></ruby>
    <ruby>lama<rp>(</rp><rt>old</rt><rp>)</rp></ruby>
    <ruby>kitabu<rp>(</rp><rt>books</rt><rp>)</rp></ruby>
    </i></b>   
"these four very old books of mine"
    
<hr>

"The father kisses the mother."
* S-V-O: _<ruby>Patre<rp>(</rp><rt>father</rt><rp>)</rp></ruby> <ruby>mwa<rp>(</rp><rt>kisses</rt><rp>)</rp></ruby> <ruby>matre<rp>(</rp><rt>mother</rt><rp>)</rp></ruby>_.
* S-O-V: _<ruby>Patre<rp>(</rp><rt>father</rt><rp>)</rp></ruby> <ruby>el matre<rp>(</rp><rt>•mother</rt><rp>)</rp></ruby> <ruby>mwa<rp>(</rp><rt>kisses</rt><rp>)</rp></ruby>_.
* O-S-V: _<ruby>El matre<rp>(</rp><rt>•mother</rt><rp>)</rp></ruby> <ruby>patre<rp>(</rp><rt>father</rt><rp>)</rp></ruby> <ruby>mwa<rp>(</rp><rt>kisses</rt><rp>)</rp></ruby>_. 

<hr>
    
"The man doesn't dance too badly."
* _<ruby>Manyen<rp>(</rp><rt>man</rt><rp>)</rp></ruby> <ruby>no<rp>(</rp><rt>doesn't</rt><rp>)</rp></ruby> <ruby>godomo<rp>(</rp><rt>too</rt><rp>)</rp></ruby> <ruby>bur<rp>(</rp><rt>bad</rt><rp>)</rp></ruby> <ruby>danse<rp>(</rp><rt>dance</rt><rp>)</rp></ruby>_.
* or: _<ruby>Manyen<rp>(</rp><rt>man</rt><rp>)</rp></ruby> <ruby>danse<rp>(</rp><rt>dance</rt><rp>)</rp></ruby> <ruby>no<rp>(</rp><rt>not</rt><rp>)</rp></ruby> <ruby>godomo<rp>(</rp><rt>too</rt><rp>)</rp></ruby> <ruby>bur<rp>(</rp><rt>bad</rt><rp>)</rp></ruby>_.
    
<hr>
    
Single line template:

```
<ruby> <rp>(</rp><rt></rt><rp>)</rp></ruby> <ruby>
```