---
title: "A Year with SwiftUI & 2 Production Apps"
layout: post
date: 2020-06-15 12:00
tag: swiftui
headerImage: false
description: "A year on from the release of SwiftUI and having shipped two apps built with the framework, I reflect on the good and bad areas of the framework."
category: blog
author: stephenmcmillan
---

It’s been a little over a year since Apple unveiled SwiftUI at WWDC 2019. The announcement was certainly unexpected and surprised many developers, myself included. In the weeks that followed the initial beta, things were changing extremely quickly as Apple fixed issues and responded to developer feedback. At times, parts of SwiftUI felt unusable.

However, after a year of iteration and having gone all in with SwiftUI in two of my personal apps, I thought it would be good to share my experience working with the evolving framework and reflect on some additions I’d like to see next week. 

![Markdowm Image][0]
<figcaption class="caption">FiveK is available on Apple Watch.</figcaption>

In the last year, I have built two personal projects using SwiftUI. FiveK is an independent Apple Watch app that helps users go from Couch to 5K without needing to take their phone out on their run. Another SwiftUI app that I created, PPL Exam Preparation, is an app for aspiring private pilots that utilises Mac Catalyst - the technology that allows apps developed for iPad to run on the Mac.  These two apps are quite different in that one is developed solely with the limited screen real estate of the Apple Watch in mind whereas my other app scales up to run on the Mac. Working with SwiftUI on this range of devices has really allowed me to get to grips with what the framework has to offer.

## This is Magic
I am really excited about independent apps on Apple Watch and that’s why I created FiveK. After following the tutorials and building a simple Todo app, I decided to create what would later become ‘FiveK’ using SwiftUI. In the beginning it felt like magic. For so many reasons:

1. Having never really experimented with something like React Native, I was blown away by *Live Previews*. Suddenly I was in a world where I could design an app and see my views re-draw in real time. This is a massive producitvity boost and eliminates the risk of getting distracted while your code is building. This distraction is something I experience a lot when working on a large, professional codebase.

2. Faster feedback started resulting in greater attention to detail. I’ll hold my hands up and admit that in UIKit, the slow feedback loop from changing a value to rebuilding sometimes resulted in me adopting a ‘that’ll do’ attitude. However I truly believe that the fast feedback loop in SwiftUI has made me pay a lot more attention to the little details such as spacing and shadows.

3. Creating more delightful animations is more accessible than ever. Over time I think we’re going to see this come through in the quality of apps on the App Store. When building both these apps, I put a lot more attention into small but delightful animations because SwiftUI made it so painless.

4. SwiftUI is intuitive and the syntax is easy to follow. Composing a complex view from small and understandable components is a breeze.

![Markdowm Image][1]{: .center-image }
<figcaption class="caption">A chart from PPL Exam Preparation.</figcaption>

## Okay. Maybe it isn’t magic.
I really could go on about all the parts of SwiftUI that I love but with all the greatness comes a lot of pain points. Obviously this is natural given that the framework is still in its infancy but I think it’s beneficial to share some of them and with that how I’d like to see them disappear this year.

1. Common UI elements are still missing from the framework. Yes - there are ways to pull them in via UIKit but that kind of defeats the purpose. I have no doubt we’ll see a lot of these added this year at Dub Dub.

2. A lot of the tutorial / reference material that exists online is very basic so architecting something with SwiftUI can be a little bit of a guessing game which could be confusing for those folks new to developing on Apple platforms.

3. Error messages are often completely unrelated to what is actually wrong with your code. More often than not, I’ve found myself commenting out lines I’ve added to find where the actual error is in my SwiftUI code. 

When you notice the issues with SwiftUI, they are very frustrating. Unlike when you stumble across an issue in UIKit, which has existed for a long time and is thus well-documented online, when you stumble across a complicated problem in SwiftUI there is a not of lot of guidance on sites like Stack Overflow. On that note however, the issues are to be expected and this is natural given its infancy.

When the framework first dropped, a lot of developers were hesitant and held firm that Apple shouldn’t have released it in its initial state. I’d disagree with this. I think SwiftUI has always had a huge amount to offer and ultimately it was smart of Apple to release it early. Releasing early reduces the steepness of the learning curve  and the longer lead time makes it easier for developers, especially larger companies, to transition to what is ultimately the future of development on Apple platforms. Can you imagine how daunting it would have felt if Apple dropped a fully fledged replacement for UIKit with all the bells and whistles of UIKit? 🤯

Overall, I love working in SwiftUI. It’s fast and allows me to quickly compose beautiful, interactive interfaces with ease. It’s going to be a huge win for developers and businesses.

Thanks for reading. Feel free to keep up with my SwiftUI journey on [Twitter](https://twitter.com/stevowevo77). 

[0]: ../assets/images/fivek.jpeg
[1]: ../assets/images/pplexam1.gif