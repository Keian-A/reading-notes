# Read-11 notes

## Chapter 16 from HTML

#### You should always try to line up image elements with other elements on an HTML page (popular style)

You can control the size of images in CSS with `height: 0px;` and `width: 0px;`. This will create a static image within a parameter of height and width.

Using `margin: 0px` you can push elements (in this case img) away from the edge of the page or other elements.

The best usage of margin on an image element to center it is: `margin: 0 auto;` This will create a margin above and below the image element of 0 but will make the margin to the left and right the same.

If you have a specific image in mind you want the background of an element to appear as, you can use `background-image: url(either url or image path here)`.

You can stack this with `background-repeat: (repeat-x) ***OR*** (repeat-y)` to repeat an image either on the x or y axis, respectively.

A **Sprite** is a single image used many times within different parts of an interface.

A ton of other [properties](https://www.w3schools.com/cssref/pr_background-image.asp) can be used to the css attribute `background-image`.

## Chapter 19 from HTML

#### A big topic that should be kept in mind when making a website should be SEO - Search Engine Optimization.

SEO refers to how easily your site can be found when searched for on a search engine.

This entails figuring out what terms people will use to search for your site and using those terms to construct your site in different elements.

SEO is split into two groups: On-page techniques, and Off-page techniques:
- On-page techniques
  - This is the method of applying things to your page to increase visibility
  - The biggest idea behind this is putting keywords on your page itself to increase visibility among a search
  - Make sure images have appropriate "alt" tags to describe the image
- Off-page techniques
  - Search engines rank how important your site is by keeping tally of how many other sites link to yours
  - They are mostly interested in sites with similar content to yours
  - Search engines also look at the words between an opening and closing `a` tag on HTML files, if the text includes keywords and NOT just your site link, it might be considered more relevant 
  - Words that appear in links to your site should also appear in the text of the page that the site links to.

The seven places keywords should appear on your page:
1. Page Title
1. URL / Web Address
1. Headings
1. Text
1. Link Text
1. Image Alt Text
1. Page Description

How to identify keywords to identify your site:
1. Brainstorm
1. Organize
1. Research
1. Compare
1. Refine
1. Map

## Article notes

#### The `video` element allows us to embed video and audio into web pages

Within the `video` element, you can apply `source` tags to apply the video in that spot, and after the `source` tags you can add a `p` tag to tell the user that their browser doesn't support HTML5 video, and supply them with a link in an `a href=""` tag

It is standard to apply all video elements within a section or div tag to enable editing of the parent element which contains all the video elements.

[<-- Back](ToC.md)