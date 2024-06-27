
# Testing Phase and details**

## I. Testing During Development 
- Manual Testing
- Bugs and Fixes

 ## II. Testing Phase**

[**Validators**](https://github.com/sowmya1283/handmadehobbies/blob/main/TESTING_PHASE.md#Validators)

- HTML
- CSS

[**Lighthouse Scores**](https://github.com/sowmya1283/handmadehobbies/blob/main/TESTING_PHASE.md#lighthouse-scores)

- Desktop Version
- Mobile Version

## I. Testing During Development

During development phase manual testing is done.

Using a VSCode and an extension for live server simulation, manually tested each element's responsiveness and appearance.

Once the website was published in github, asked my fellow students to test.

### Manual Testing:

To guarantee cross-browser compatibility, tested the application using the below four browsers on desktop.

-   Opera
-   Edge
-   Chrome
-   Firefox

Several screen resolutions were emulated using devtools in the browser to range between 320px and upto 4000px. 

And also some of friends and family members tested the website in their iphones and macbook.

### Bugs and Fixes:

During development phase some of the bugs were identified by myself and has been fixed while testing over a live server. over multiple screen resolution simulated the scenarios where a user will try to use the website.

Bugs discovered when testing using VSCode's live server addon is provided below. I experimented with every element to see how it would appear to potential consumers on a variety of screen widths, ranging from 320px to 4000px:

 #### 1. Expected Outcome
Logo on the ‘Welcome Home!’ should be responsive enough based on the screen resolution.

**_Issue Found:_**

-   Logo on the Mobile resolution less than 466px was cropped off.

**_Solution Used:_**

- Used CSS media query to fix the problem by defining max width and reduced img width to lesser than the 466px.

#### 2. Expected Outcome
Navigation menu Items should be underlined when hover overed to click along with the current active screen text highlighted.

**_Issue Found:_**

- Menu items were not underlined when hover over on them and only Welcome Home page was getting highlighted

**_Solution Used:_**

- Resolved this issue by adding Active class to the respective pages to meet the expected behaviour.

#### 3. Expected Outcome
Nav bar items should have space between them so that user can differentiate them easily.

**_Issue Found:_**

- Nav items were not spaced properly. And user could not see where one nav element is ending

**_Solution Used_**:

- Solved the problem by adding justify-content with value space-around

#### 4. Expected Outcome
Hero image should cover the page width and should be responsive enough.

**_Issue Found:_**

- Complete hero image was not getting displayed

**_Solution Used:_**

- Increased the height property and width to 100% resolved the issue. And also position is made relative.

#### 5. Expected Outcome
On all gallery pages space between the nav bar and photos should not be too much.

**_Issue Found:_**

- There was lot of space between the photos and the nav bar.

**_Solution Used:_**

- Issue is fixed by reducing the margin top property to adjust a bit.

#### 6. Expected Outcome
On mobile screens, Welcome Home page content should be readable

**_Issue Found:_**

- On the mobile screens the text content was not readable and was very narrow.

**_Solution Used:_**

- Reduced the padding for mobile screen to 1em.

#### 7. Expected Outcome
Social media link displayed in a line side by side in the footer.

**_Issue Found:_**

- One of my fellow student noted there was an underscore between elements. The underscore was due to the way I wrote the HTML with the parents and child elements onto separate lines to improve the readability of my documents.

**_Solution Used:_**

- By placing the anchor tag and the font awesome "i" tag on the same line, the underscore disappeared.

## II. Testing Phase

**1. Validators**

**_HTML_** **-** [**https://validator.w3.org/nu/**](https://validator.w3.org/nu/)

**_Issue Found:_**

- Some of the meta tags , links and hr had / at the ending in html pages. Which created warning or info messages on html validator

**_Solution Used:_**

- Removed the '/' at the end of the tags specified by the HTML validator

![HTML info and warning](https://github.com/sowmya1283/handmadehobbies/blob/main/docs/screenshots/HTML_info_warnings.png)

**_CSS_** **-** [**https://jigsaw.w3.org/css-validator/**](https://jigsaw.w3.org/css-validator/)

- No CSS issues were there.

![No css issue screenshot](https://github.com/sowmya1283/handmadehobbies/blob/main/docs/screenshots/CSS_noerror.png)

  
[<![if !vml]>![CSS validator badge](file:////Users/sowmyaankamahadeva/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image003.png)<![endif]>](https://camo.githubusercontent.com/670b7edf040247729106e1d47807221159973c6406a36607949e50a7f37d5ef1/68747470733a2f2f6a69677361772e77332e6f72672f6373732d76616c696461746f722f696d616765732f76637373)

**2. Lighthouse Scores**

**_Issue Found:_**

- Performance values are coming too low (below <60)

**_Solution Used:_**

- Resized all the images using 'tinypng.com' to improve the performance scores.

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