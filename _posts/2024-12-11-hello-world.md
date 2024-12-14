---
title: Hello, World!
date: 2024-12-07 00:00:00 +0000
categories:
  - poc
tags:
  - poc
---

# Hello, World!

This is my personal blog. There should be a picture underneath this text.

![image](/assets/img/tree.jpg)

This seems to work!

How about some math?

#### 1.4 Hyperbolic Trig Functions

$$\begin{align}

\cosh{x} = \frac{1}{2}(e^x + e^{-x})
\\ \\
\sinh{x} = \frac{1}{2}(e^x - e^{-x})

\end{align}$$


### Make InBetween Areas Selectable
If several elements in SwiftUI need to act like a single element, add `.contentShape()` to the Layout containing those elements. 

```swift
VStack {
	Image(...)
	Text(...)
}
.contentShape(Rectangle())
```

Did the code example work? 
