## Preparation:

    I start with adding an image of the initial layout that I am supposed to replicate.

    This, I do by adding a mock image (copy of the initial layout).
    Then I look at the image and figure out where I would use divs and boxes.

    After I figured that out, I start making divs with appropriate class names.
        -> I leave those divs empty for the moment
        -> I give those different classes a background color and dimentions to match the image. (css)
    This way i start to have a clear view on how my boxes will look.

## Interface 10

    Once the boxes have been aligned, I start Styling the setting in eacht box.
        -> Filling the html with text.
        -> Adjusting box paddings/margins/sizes
        -> Inserting the right fonts.
        -> Comparing the results with the copied image (using opacity)
    
    Mistakes:
        -> I made 3 different text boxes with the same class, because of that i had problems with the border radius.
            solution:   I moved the background color in the sub class to a parent class. and instead of a top margin, I used a horizontal line to separate the text boxes.
                        That way I could use the border radius on the parent class (in this case: class="text")
    
    remembering for next time:
        -> When having text or an image that needs to be vertically centered too, use: margin: auto;
        