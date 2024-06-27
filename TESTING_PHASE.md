<![endif]-->

**Testing Phase and details**

    **Testing During Development**

<![if !supportLists]>o<![endif]>_Manual Testing_

<![if !supportLists]>o<![endif]>_Bugs and Fixes_

<![if !supportLists]>· <![endif]>[**Testing**](https://github.com/dnlbowers/modern-buddhism/blob/main/TESTING.md#post-development-testing) **Phase**

<![if !supportLists]>o<![endif]>[**Validators**](https://github.com/dnlbowers/modern-buddhism/blob/main/TESTING.md#validators)

<![if !supportLists]>§ <![endif]>_HTML_

<![if !supportLists]>§ <![endif]>_CSS_

<![if !supportLists]>o<![endif]>[**Lighthouse Scores**](https://github.com/dnlbowers/modern-buddhism/blob/main/TESTING.md#lighthouse-scores)

<![if !supportLists]>§ <![endif]>_Desktop Version:_

<![if !supportLists]>§ <![endif]>_Mobile Version_

**Testing During Development**

During the development process, I was manually testing in the following ways:-

Using a VSCode and in that an extension (for server), manually tested each element's responsiveness and appearance on a live server simulation.

I used GitHub to publish the page, shared it with other students for testing, and asked for feedback.

**_Manual Testing:_**

To guarantee cross-browser compatibility, I tested using four browsers. The desktop browsers used were:

-   Opera
-   Edge
-   Chrome
-   Firefox

<![if !supportLists]>· <![endif]>  Next, I emulated several screen sizes and devices, ranging in width from 320 pixels to 4000 pixels, using the devtools.

<![if !supportLists]>· <![endif]>  In addition, I requested that a number of family and friends to test on iPhones and Apple Mac laptops or PC’s.

**_Bugs and Fixes:_**

Below is a list of bugs I found during the development process by testing myself via the live server extension on VSCode. I tried each element for how the browser would display the page to potential users on a range of different screen widths from 320px to 4000px:-

Bugs discovered when testing using VSCode's live server addon is provided below. I experimented with every element to see how it would appear to potential consumers on a variety of screen widths, ranging from 320px to 4000px:

<![if !supportLists]>1. <![endif]>**Intended Outcome** – Logo on the ‘Welcome Home!’ should be responsive enough based on the screen resolution.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

-   Logo on the Mobile resolution less than 466px was cropped off

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>Used CSS media query to fix the problem by defining max width and reduced img width to lesser than the 466px.

<![if !supportLists]>2. <![endif]>**Intended Outcome** - Navigation menu Items should be underlined when hover overed to click along with the current active screen text highlighted.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]> Menu items were not underlined when hover over on them and only Welcome Home page was getting highlighted

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>Resolved this issue by adding Active class to the respective pages to meet the expected behaviour.

<![if !supportLists]>3. <![endif]>**Intended Outcome** – Nav bar items should have space between them so that user can differentiate them easily.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]>Nav items were not spaced properly. And user could not see where one nav element is ending

<![if !supportLists]>o<![endif]>**_Solution Used_**:

<![if !supportLists]>§ <![endif]>Solved the problem by adding justify-content with value space-around

<![if !supportLists]>4. <![endif]>**Intended Outcome** – Hero image should cover the page width and should be responsive enough.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]>Complete hero image was not getting displayed

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>Increased the height property and width to 100% resolved the issue. And also position is made relative.

<![if !supportLists]>5. <![endif]>**Intended Outcome** – On all gallery pages space between the nav bar and photos should not be too much.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]>There was lot of space between the photos and the nav bar.

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>Issue is fixed by reducing the margin top property to adjust a bit.

<![if !supportLists]>6. <![endif]>**Intended Outcome** – On mobile screens, Welcome Home page content should be readable

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]>On the mobile screens the text content was not readable and was very narrow.

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>Reduced the padding for mobile screen to 1em.

<![if !supportLists]>7. <![endif]>**Intended Outcome** - Social media link displayed in a line side by side in the footer.

<![if !supportLists]>o<![endif]>**_Issue Found:_**

<![if !supportLists]>§ <![endif]>One of my fellow students noted there was an underscore between elements. The underscore was due to the way I wrote the HTML with the parents and child elements onto separate lines to improve the readability of my documents.

<![if !supportLists]>o<![endif]>**_Solution Used:_**

<![if !supportLists]>§ <![endif]>By placing the anchor tag and the font awesome "i" tag on the same line, the underscore disappeared.

**Testing Phase**

**Validators**

**_HTML_** **-** [**https://validator.w3.org/nu/**](https://validator.w3.org/nu/)

<![if !supportLists]>· <![endif]>**_Issue Found:_**

<![if !supportLists]>o<![endif]>Some of the meta tags , links and hr had / at the ending in html pages. Which created warning or info messages on html validator

<![if !supportLists]>· <![endif]>**_Solution Used:_**

<![if !supportLists]>o<![endif]>Removed the / at the end of the tags specified by the HTML validator

<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image001.png)<![endif]>

**_CSS_** **-** [**https://jigsaw.w3.org/css-validator/**](https://jigsaw.w3.org/css-validator/)

<![if !supportLists]>· <![endif]>No CSS issues were there.

<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image002.png)<![endif]>

  
[<![if !vml]>![CSS validator badge](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image003.png)<![endif]>](https://camo.githubusercontent.com/670b7edf040247729106e1d47807221159973c6406a36607949e50a7f37d5ef1/68747470733a2f2f6a69677361772e77332e6f72672f6373732d76616c696461746f722f696d616765732f76637373)

**Lighthouse Scores**

<![if !supportLists]>· <![endif]>**_Issue Found:_**

<![if !supportLists]>o<![endif]>Performance values are coming too low (below <60)

<![if !supportLists]>· <![endif]>**_Solution Used:_**

<![if !supportLists]>o<![endif]>Resized all the images using tinypng.com to improve the performance scores.

**Home page:**

**Desktop** **<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image004.png)<![endif]>**

**Mobile**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image005.png)<![endif]>**

**2. Crazy For Crochet:**

**Desktop** **<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image006.png)<![endif]>**

**Mobile**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image007.png)<![endif]>**

**3. Mosaic Art**

**Desktop**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image008.png)<![endif]>**

**Mobile**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image009.png)<![endif]>**

**4. Quilling Craft**

**Desktop:**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image010.png)<![endif]>**

**Mobile:**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image011.png)<![endif]>**

**5. Sign-Up Page**

**Desktop:**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image012.png)<![endif]>**

**Mobile:**

**<![if !vml]>![](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image013.png)<![endif]>**