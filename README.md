# AutoLayout-TextView

## Instructions

Check out the screenshots below. Your goal is to recreate the interface, using autolayout anchors in code. You'll need to make a project from scratch for this lab.

Here are some layout details:

1. The left button is 10 pts from the left of the screen, and the right is 10 pts from the right. Both are 10 pts from the bottom. Use the default width and height for the buttons.
2. There is one `UITextView` that is 20 pts from the top, 10 pts from the left, 10 pts from the right, and 20 pts from the top of the `UIButton`s.

After you've set things up, make sure your layout looks correct in both landscape and portrait. Ah, the magic of autolayout!

## Extra Credit

  1. In portrait mode, leave the padding between the `UIButton` and the `UITextField` at 20 pts. In landscape, decrease it 10 pts. *Hint:* you can listen for a rotation event and examine the new size class. Check out [Joe's blog post](http://blog.flatironschool.com/working-with-size-classes-in-code-with/) for details.
  2. For devices at least as large as an iPhone 6, increase the padding between the `UIButton` and the `UITextField` to 30 pts. 

## Screenshots
![Portrait](http://ironboard-curriculum-content.s3.amazonaws.com/iOS/autolayout-textview/Portrait.png)

![Landscape](http://ironboard-curriculum-content.s3.amazonaws.com/iOS/autolayout-textview/Landscape.png)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/autolayout-textview' title='AutoLayout-TextView'>AutoLayout-TextView</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/autolayout-textview'>Autolayout Textview (Layout Anchors)</a> on Learn.co and start learning to code for free.</p>
