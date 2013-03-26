RKCropImageController
=====================

This is modal-style crop image controller that supports zooming to select borders with more accuracy.

# How to use

``` objective-c

// in header
#import "RKCropImageController.h"

// in code
  RKCropImageController *cropController = [[[RKCropImageController alloc] initWithImage:imageView.image] autorelease];
  cropController.delegate = self;
  [self presentModalViewController:cropController animated:YES];
```

# Documentation
Check out each header file for a complete listing of each method.

# Questions
Feel free to contact renat.kurbanov@gmail.com if you need any help with RKCropImageController.

# License
Copyright (c) 2013 Renat Kurbanov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
