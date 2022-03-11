HTML/CSS Point Scoring

Racking up the Points!

Assigning rules to elements is great, but what if we want two instances of the same element to look different? Right now, we now how to apply styles to EVERY ELEMENT that matches our selector tag (when we use the h1 selector, then ALL h1 tags are that color). Let's begin learning how to separate tags into groups using HTML classes! We'll also learn a new HTML tag for creating lists :)



HTML 

Let's check out a new HTML tag first. It is the unordered list tag, or ul for short. It looks like this:

Image: http://www.vrremi.xyz/76ia.png

Notice how the ul tags are seperated in the same way that the body tag is. They are on different lines with the content in the middle. Each LINE ITEM is represented with the li tag, with it's corresponding content inbetween its opener and closer.

Unordered lists are a great way of quickly formatting and showing related content. Let's explore a little further and discover another way we can group content together!

There is an attribute that you can add to just about any HTML content tag called class. The name you give this class can be used when styling groups of elements in CSS.

Example: <h1 class="falcon">Captain Falcon</h1>

The attribute here is named "falcon". Let's see how we can use that in CSS now to target specific h1 tags!



CSS

Take a look at the two CSS rules below

h1{
  color: gray;
}

.falcon{
  color: darkblue;
}

According to the rules above, all VANILLA (basic) h1 tags are colored gray. However, any tags that have a class of "falcon" are overwritten with the rule that colors the text dark blue!

Notice how the selector is written. We can select a class simply by placing a dot before the class name!



Steps

1. Follow the coment instructions in index.html AND style.css
2. Click the green "Run" button at the top of the screen to see your words appear on the webpage preview window and check your work.
3. Hit the submit button when you are done.