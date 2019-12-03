# HTML Links

## Getting Started

Links allow us to connect our pages and sites to each other. Arguably 
they give the world wide web its power by simply allowing one document 
to lead to the next. In this lesson, we’ll take a look at the structure of a link 
and how it works.

## What's Covered in This Lesson 

- HTML standard and named anchor links
- Relative and absolute paths

## Links

```html
<a href="http://example.com">This is a text link</a>
```

An anchor link `<a>` accepts an `href` (hypertext reference) attribute, 
which points to the location of the page or content we are linking to.

```html
<a href="http://example.com">
  <img src="myimage.jpg" alt="Alternate text">
</a>
```

Anchor links can also wrap images as well as text. In fact, anything we 
wrap a `<a>` around becomes a clickable linked item.

```html
<a href="mailto:webmaster@example.com">This is an email link</a>
```

```html
<a href="tel:555-555-5555">This is a phone number link</a>
```

Special prefixes in the `href` can trigger specific actions.`mailto:` allows 
us to open an email editor; `"tel:"` tells cellular devices to dial a number.

```html
<p id="tips">Useful Tips Section</p>
<a href="#tips">Jump to Useful Tips Section</a>
```

We can also create named anchor links that will scroll to content elsewhere 
on the same page. This is done by giving an `id` attribute to one element, 
and then setting the `href` of a link to `#id` where the ids match.

## Relative and Absolute File Paths

There are two ways to express where we want to go. We can use either a 
relative file path or an absolute file path.

__Relative__

`about.html`

Relative paths describe the location of resources within the same file system.

__Absolute__

`http://example.com/about.html`

Absolute paths describe the location of resources on the entire internet at large.

You should use the relative path when linking to content within your own website. 
Then use absolute paths when linking to content on other remote websites.

## Summary

We can link to other pages either on our own website or on the internet as a whole 
by using the `a` tag and a `href` attribute, which specifies where we want the link 
to go. We use either a __relative__ or __absolute__ file path to determine the link 
destination.

## Key Terms to Review

* Anchor links
* Relative file path
* Absolute file path

## Resources

* [Mozilla Developer Network a tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)

## What's Next

Now that we’ve covered the basics of HTML, let’s move on to HTML’s best 
friend: CSS, which will let us start making our HTML look much more interesting.

<p class='util--hide'>View <a href='https://learn.co/lessons/html-link'>Understanding Links in HTML</a> on Learn.co and start learning to code for free.</p>
