[dark]: https://katalysatorn.github.io/MSEdge-StartPage/dark/
[darkImg]: https://katalysatorn.github.io/MSEdge-StartPage/docs/dark.png
[light]: https://katalysatorn.github.io/MSEdge-StartPage/light/
[lightImg]: https://katalysatorn.github.io/MSEdge-StartPage/docs/light.png

# MSEdge-StartPage
This is a start page designed specifically to look nice with Microsoft Edge. It has two flavours:
* Dark (Meant for use with App Mode set to Dark)
* Light (Meant for use with App Mode set to Light)

## Contents
* [Install](#Install)

* [New Tab Behaviour](#New-Tab-Behaviour)

---

## Install
1. Clone the repository `git clone https://github.com/katalysatorn/MSEdge-StartPage`.
2. Unzip it, and copy either (or both) dark/light folders to a location you can access easily, but won't accidentally delete.
3. Open Microsoft Edge.
4. Click the three dots in the top right corner.
5. Open the start page in Microsoft Edge (Right click, open with).
6. Copy the URL in the address bar.
7. Select **Settings**.
8. Where it says **Choose a theme** pick the one that matches your startpage flavour.
9. Where it says **Open Microsoft Edge with** select *A specific page or pages* and paste the URL where it says *Enter a URL*.
10. Hit save.

---
### New Tab Behaviour
Since [here](https://github.com/katalysatorn/MSEdge-StartPage/commit/46ebff255ac01fdd4392b46ce113bcd8fe56512c), I have made it so that the links open it in a new tab. I did this because you cannot set a new tab page to a file, so I wanted it to act as a 'Home' of sorts. You can remove this by:
1. Opening the `index.html` file in whatever folder your Start Page is in
2. Hit `Ctrl + H`
3. In **Find What:** type ` target="_blank"`
4. Hit **Replace All**
5. Save the file and it should now open in the current tab.

***Note:*** *These instructions are for Sublime Text 3 and may depend on what text editor you use*


---
### Dark
![MSEdge-StartPage in its dark flavour][darkImg]
##### [View Live][dark]
---
### Light
![MSEdge-StartPage in its light flavour][lightImg]
##### [View Live][light]
