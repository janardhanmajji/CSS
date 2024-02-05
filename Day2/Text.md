Positions:

Position is used to place something in a specific position...

There are basically 4 kinds of positions:

- fixed
- sticky
- absolute
- relative

Apart from these we have static which is the default one...

Q. How to create a button which must stay at a fixed position even though the content is moving?
A: use "position: fixed"

Q. What if we need to position an element from a specific direction (i.e., button must be on top-right etc.)
A: top:0, right:0 says that the position of button from top is 0 and position from right is 0. So it lies on top-right.

    If we keep position:fixed then it doesn't move even if we scroll. They remain fixed to that position

Q. Sticky vs Fixed..
A: Fixed is used when we want the content to be fixed all the time whereas sticky is used when we want the content to be fixed in a particular condition.

If we give absolute to any element it goes a level top...

When do we use absolute?
We use absolute when we want it to move along with the screen size but on one level top.
Whereas we use fixed when we want to fix it and donot want to move it wrt screen size
