# CSS Layout Summary

**Layouts:**

**Building Blocks:**

In HTML we either have a block-level box or inline box.

Block-level boxes start on a new line, while inline boxes flow between surrounding text.

**Containing Elements:**

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. 



**Controlling the Position of Elements:**

You can specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
>
**z-index:**

It allows you to control which box appears on top.

**position: relative:**  moves an element in relation to where it would have been in normal flow.)

>


**There are different position values:**

* **static:** it is always positioned according to the normal flow of the page . 
>
*   **relative:** it is positioned relative to its normal position.
>
* **fixed:** it is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
>
* **absolute:**  is taken out of the box of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)   float: allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.


![](https://stuyhsdesign.files.wordpress.com/2016/02/z-index1.png)


[MDN Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)



>


**Clearing Floats :**

The clear property allows you to say that no element (within the same containing element) should touch the left or right-hand sides of a box.

**Screen Sizes:**
Your screen has a different-sized screen. so you should make the design work on different sized screens. 

**Screen Resolution:**

Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and,
 most operating systems allow users to adjust the resolution of their screens.

 **Page Sizes:**

 the sizes and display resolutions of a page may vary, that's why web designers create pages of around 960-1000 pixels round.


**Fixed width layout designs** do not change size as the user increases or decrease the size of their browser window. 


**Liquid layout designs stretch** and contract as the user increases or decrease the size of their browser window.

**Grids** help create professional and flexible designs.

**CSS Frameworks** provide rules for common tasks.

You can include **multiple CSS files** on one page.







