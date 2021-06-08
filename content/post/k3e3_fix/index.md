---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fixing Keychron K3 brown switch"
subtitle: "K3E3"
summary: "How I fixed Keychron K3 brown switch."
authors: []
tags: []
categories: []
date: 2021-02-25T11:14:05+01:00
lastmod: 2021-02-25T11:14:05+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "(c) keychron.com"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I backed Keychron K3 on Kickstarter and after a long wait, I received the keyboard with brown optical switches (K3E3 modification) which is pretty awesome except for one nasty tiny detail: the keystroke registers far before the tactile bump.

Here is the illustration of the fixing method which was also described on [reddit](https://www.reddit.com/r/Keychron/comments/lksey3/possible_fix_for_k3_optical_browns_being_too/).

The first switch took me some time to understand how it works. It is not very difficult to disassemble, but it's easy to lose some parts. So before the start, I highly recommend palcing the patient switch inside a highlighted cardboard box and keep it there while working on it.
Seriously, consider work inside the cardboard box. You might lose very tinny parts like spring or stem otherwise, they can jump away easily and the box will help to contain them.
{{< figure src="switch.jpg" title="Keychron brown optical switch" width="300">}}

1. Take a look at the bottom of the switch:
{{< figure src="stem1.jpg" title="Bottom of K3E3 switch" width="300">}}
The red circle shows where the stem which breaks the light beam when the key is pressed. We will remove it. You don't need to open the switch yet.

2. Press the switch.
{{< figure src="stem2.jpg" title="Pressed K3E3 switch" width="300">}}
The stem will move closer to the bottom of the switch.

3. Use tweezers or another appropriate tool to press the stem out of the housing.
{{< figure src="press1.jpg" title="Top of K3E3 switch" width="300">}}
{{< figure src="press2.jpg" title="Taking the stem out" width="300">}}
While taking the stem out keep the switch in your hand and make sure that the stem will fall out in a box / safe place.

4. Keep the stem in a safe place for a moment.
{{< figure src="stem3.jpg" title="Stem of K3E3" width="300">}}
{{< figure src="stem4.jpg" title="Stem and spring separated" width="300">}}

5. Now use tweezers to open the switch.
{{< figure src="opening1.jpg" title="Opening of K3E3" width="300">}}
{{< figure src="opening2.jpg" title="Opened of K3E3" width="300">}}
Don't move the spring that you see in the open switch, they need to be left in their places. The big spring is creating the actuation force. The small spring is responsible for creating a tactile bump.

6. Now take the stem without the spring and insert from the bottom of the switch.
{{< figure src="assembly1.jpg" title="Inserting the stem into K3E3" width="300">}}
{{< figure src="assembly2.jpg" title="Opened of K3E3" width="300">}}
Then place the small spring from the inner side of the switch bottom.

7. Now pre-insert the brown part back on the place, but do not press fully yet, we need to move the tactile spring to a correct position.
{{< figure src="assembly3.jpg" title="Preinsertion" width="300">}}
{{< figure src="assembly4.jpg" title="Placing the tactile spring" width="300">}}
{{< figure src="assembly5.jpg" title="Full press" width="300">}}
{{< figure src="assembly6.jpg" title="Closing" width="300">}}
When fully pressed and tactile spring on place secure the stem in the brown part pressing from the bottom side with tweezers.
And finally, close the switch fully. The upgrade is finished.

This post was typed on the upgraded K3E3. The fix took about 4 hours and improved typing speed by a factor of two and reduced the error rate by a factor of 6.
