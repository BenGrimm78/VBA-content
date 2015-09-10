
# PageSize.VerticalGap Property (Publisher)

 **Last modified:** July 28, 2015

 _**Applies to:** Publisher 2013 | VBA_

Returns a  **Variant** that represents the distance in points between the bottom edge of one publication page and top edge of the publication page immediately below it for the blank page size represented by the parent **PageSize** object. This property applies only when multiple pages are printed on a single sheet of printer paper. Read-only.


## Syntax

 _expression_. **VerticalGap**

 _expression_A variable that represents a  **PageSize** object.


### Return Value

Variant


## Remarks

The blank page size represented by the parent  **PageSize** object corresponds to one of the icons displayed under **Blank Page Sizes** in the **Page Setup** dialog box in the Microsoft Publisher user interface.

Numeric values are evaluated as points. String values can be in any unit supported by Microsoft Publisher (for example, "2.5 in"). The valid range of possible values is from zero to the difference between the sheet height and the page height.
