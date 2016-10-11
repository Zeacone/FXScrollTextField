# FXTextField

A subclass of UITextField which has some features as follow.

+ Supports moving cursor by pan gesture.
+ Supports floating label to show it's placeholder text.
+ To be continued.

# Usage

You can just use it as UITextField or change the class name as FXTextField in the storyboard or xib file.

**Code**

```objective-c
FXTextField *textfield = [[FXTextField alloc] initWithFrame:frame];
// Set properties like bottom line color, float label color etc.
[self.view addSubview:textfield];
```

**XIB/Storyboard**

Select your textfield control, go to the `inspector` =>`Custom Class` =>`Class` , Change it as `FXTextField`. OK, It's done.