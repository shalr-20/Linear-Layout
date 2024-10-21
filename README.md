# LinearLayout 

It is a layout that arranges its child views (buttons, text, images, etc.) in a straight line, either **vertically or horizontally.**

## Key Features:

- Orientation: You can arrange the views in:
  
         * Vertical: One view below the other (like stacking).
         * Horizontal: One view next to the other (like a row).
  
- Attributes:
  
         * android:orientation: Sets whether the layout arranges views vertically (vertical) or horizontally (horizontal).
         * layout_weight: Used to proportionally distribute extra space between views.


## Difference between match_parent and wrap_content 
### 1) **match_parent:**
- The view will expand to take up all the available space of its parent layout in the specified dimension (width or height).
- Use this when you want the view to fill all available space.

### 2) **wrap_content:**
- The view will be just big enough to fit its content (text, image, etc.) without taking any extra space.
- Use this when you want the view to size itself based on its content.
