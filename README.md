## acessiblity

This project is to get the website acessible as possible for screenreaders, deaf people etc. Things were considered such as using semantic HTML, high contrast colors, photo description, aria features, audio description and dylexia friendly font.This website is about bears.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

then open it in browser to see 

## Development

It is recommended to use the VSCode Live Server extension to run the project locally. This will allow you to see changes in real-time as you make them. There is no need to run a build process or refresh the page manually. Additionally, you do not need to setup a local server to run the project.

With this website you are able to use tab button to go to each interactive option and use pacebar to scroll down instead of using a mouse. click on three dots in audio to download the mp3 and click on audio-description to get transcript of the audio. If unable to use audioplayer yo ucan click on the three dots to download the clip. The links in navbar and related leads to nowhere as it is a test webage.


## Accessibility Lab Answers

  ### Color
        To tests for aceessiblity with color one can compare contrast with using website such as webAim contrast checker and check the ratio of background and foreground/text color. typically the ration should be 7.5:1 for regular and 4.5:1 for large text. Find the contrast checker here https://webaim.org/resources/contrastchecker/. 

  ### Semantic HTML
    to make the webpage acessible, semantic HTML should be used which tells the the meaning to both the browser and developer. This allows screen readers to tell a blind person what part of the text or whatever it is such as <h1> indicates its a heading. some semantic HTML is <main>, <p>, <nav>. <div> and <br> are not semantic so should be changed to <nav> for nav bar and <p> for the paragraphs. The font class from this orginal given html should bechanged to diffrent levels of heading and fixed in css accordingly.

 ### The Images
    Images are great to show and designa website. However it is not acessible to lov vison or blind poeple. to do make it more acessible, the alt ="description of photo" should be added to the image tag. That way screen readers can describe what the photo looks like.

 ### The Audio Player
    1. The deaf community can acess the audio file. ONe way to make it acesssible is to add a audio transcript. Possibly by using a button or a drop down description.

    2. Sometime it isnt acessible to older browser. To make it morecesssible, you can make it downloadable using the download html rule. that way older browsers can download the video and play it.

 ### The Forms
    1. To add a invisiable text label only acessible to screen readers, they can use aria-label = " description" so that it remains invisible to sighted users but allow screen readers to read them.

    2. the input elments in the comment form can be associated with ther labels using the <label> tag for your name and your comment. this tag is semantic html tag, which screenreaders can tell users that it is a  input label.

 ## The table 
    To make the table more acessible to screen readers, the td can be replaced with <th> tag which defines a header cell in an HTML table. and <scope> to tell what part it relates to like col for column or row for row. You can also use headers to tie one header to another. 

## Testing

No tests currently

## sources used

“ARIA Guides - ARIA | MDN.” MDN Web Docs, 6 Mar. 2025, https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Guides.

HTML a Download Attribute. https://www.w3schools.com/tags/att_a_download.asp .

HTML a Download Attribute. https://www.w3schools.com/tags/att_a_download.asp .

HTML Details Tag. https://www.w3schools.com/tags/tag_details.asp .

HTML Th Tag. https://www.w3schools.com/tags/tag_th.asp .

WebAIM: Contrast Checker. https://webaim.org/resources/contrastchecker/ .
