# LineField ![](https://img.shields.io/badge/license-GPL%203.0-blue.svg)

# Screenshot

![](http://7xlzdc.com1.z0.glb.clouddn.com/LineField.gif)

# Installation

Just drag the file in `Classes` into your project.

# Usage

You can just use it as UITextField or change the class name as LineField in the storyboard or xib file.

**Code**

```objective-c
LineField *textfield = [[LineField alloc] initWithFrame:frame];
// Set properties like bottom line color, float label color etc.
[self.view addSubview:textfield];
```

```swift
let field = LineField()
// ...
self.view.addSubview(field)
```

**XIB/Storyboard**

Select your textfield control, go to the `inspector` =>`Custom Class` =>`Class` , Change it as `LineField`. OK, It's done.