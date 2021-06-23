# HTML Links, CSS Layout, JS Functions summary

**Links :**

It allows us to move from one page to another. 

**Directory :**

Folders on a website are sometimes referred to as directories. 

**Relative URLs :**
They can be used when linking pages within your own website. 


**Relative Link Types Same Folder:**

To link to a file in the same folder, just use the file name.

**Child Folder:**
child folder, use the name of the child folder, followed by a forward slash, then the file name.
 
**Grandchild Folder:**
Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name. 

**Parent Folder:**
Use ../ to indicate the folder above the current one, then follow it with the file name.

**GrandParent Folder:**

Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

**Email Links:**

use mailto: when you want to create a link to an email address.

**Target:**

If you want a link to open in a new window, you can use the target attribute on the opening < a> tag. The value of this attribute should be _blank. 

**Linking to a Specific Part of the Same Page:**

use the < a> element again, but the value of the href attribute starts with the # symbol followed by the value of the id attribute of the the element you want to link to.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

**Layouts:**

 **Building Blocks:**

 In HTML we either have *a block-level box or inline box.*

 **Block-level boxes** start on a new line, while inline boxes flow between surrounding text.

 **Containing Elements:**

 If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

**Controlling the Position of Elements:**

You can specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

**z-index:**

It allows you to control which box appears on top.

**position: relative:**  moves an element in relation to where it would have been in normal flow.)

**There are different position values:**

* **static:** it is always positioned according to the normal flow of the page
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
* **relative:** it is positioned relative to its normal position.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

* **fixed:** it is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
* **absolute:**  is taken out of the box of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
  **float:** allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

  >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


  **Clearing Floats :**
The clear property allows you to say that no element (within the same containing element) should touch the left or right-hand sides of a box.

**Screen Sizes:**

Your screen has a different-sized screen. so you should make the design work on different sized screens. 

**Page Sizes:**
the sizes and display resolutions of a page may vary, that's why web designers create pages of around 960-1000 pixels round.



![layout]( https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/HTML-Layout-df.jpg)
.......................................................


## functions 

**what is the functions ??**

***A function is a set of statements. You can reuse functions within the same script,or in other documents.*** 

***You define functions at the beginning of a file (in the head section), and call them later in the document.***

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


**Declaring functions :**

The function declaration (function statement) defines a function with the specified parameters.

for Example : 
function calcRectArea(width, height)


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


**Invokes the Function :**

including the name of the function in the code somewhere, followed by parentheses.


![](https://dmitripavlutin.com/static/7035b35b8d8dce31376d9839065e58f7/19891/2-1.png )


[w3 scool]( https://www.w3schools.com/js/js_functions.asp)


.................................................................







