Img Tag

Time to take some pictures!



Images

The <img> tag is used to display images on your webpage. GO FIGURE! However, it is important to note that there are two primary ways of using images:

- Locally
- From the Web (URL)


First, let's look at the image tag itself. This one is one of those special cases that DOES NOT have a closing tag! It also has something new that we haven't seen yet called attributes

<img src="" alt="">


Inside the tag we have the src and alt attributes. In between the quotes for the src attribute is where we put either the FILE PATH to our local image or the URL to our image we find on the web.

Example: <img src="/assets/ryu.png" alt="">


If you don't have your images stored locally (meaning they are in the same file structure as your html document), then you can pull images from the web. It's important to not though that you need a link to JUST THE IMAGE ITSELF, not the page that it is on. You can do this by right clicking on any picture you find on the web and selecting "Copy Image Address". You will now be able to paste the URL that is the direct link to the image in the src attribute.

Example: <img src="https://static.wikia.nocookie.net/vsbattles/images/5/55/BlankaIV.png/revision/latest?cb=20201022174321" alt="">


IT IS IMPORTANT TO NOTE that using a web link is not the most reliable way of displaying images on your site. If anything is done with the image on the host site (the one you took the URL from) then the image will no longer display on your page!

For instance, sometimes content like images are not sent or received correctly over a network. Think of it like a damaged or parts missing package. When that happens, we want to display AT LEAST a description of what image was supposed to be there. This is what the alt tag is for.

Example: <img src="/assets/ryu.png" alt="A picture of Ryu">



Steps

1. Follows the coment instructions in index.html.
2. Click the green "Run" button at the top of the screen to see your words appear on the webpage preview window and check your work.
3. Hit the submit button when you are done.