# `µfox`
Make Firefox less visually intrusive.


### Principles and Goals 📝
`µfox` is for users that do not like

- unnecessary or draining interface items, positioning, and use of space
- animation and jitter

The overall goal of these styles is to eliminate or improve a lot of instances of these distractions in the Firefox interface. The subgoals below discuss how I am currently approaching these principles.


#### Findbar
`Goal`: reduce the cognitive load of using the findbar by

1. taking it away from the edge of the screen and bringing it closer to the rest of the content in the browser
2. Minimally styling it, eliminating buttons and trying to use sane default options

![findbar](https://user-images.githubusercontent.com/59481467/208356626-edeb6131-917b-42ae-b419-702217fc32cc.gif)


#### Toolbar
`Goal`: increase valuable screen real estate and minimize visual interference by making the toolbar

1. hidden when it is not focused
2. minimally styled by
    - reducing movement, for example by eliminating borders that change color or expand
    - removing buttons which can have their features accessed by the URL bar, for example, using `about:downloads` instead of a dedicated button

![toolbar](https://user-images.githubusercontent.com/59481467/208356699-c298a4b9-cb29-47a1-8e62-16d6dd1186cb.gif)


### Warnings and Tips ⚠️
1. `µfox` eliminates the tab bar completely. You **will** need an alternative. Try Tree Style Tab or Sideberry.
2. See [Firefox's shortcuts list](https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly?redirectslug=Keyboard+shortcuts&redirectlocale=en-US#firefox:linux:fx108) and choose your operating system to see keybindings that you can use to access the UI elements that you wish to see. 


### Suggestions 💁
For a more keyboard-driven or minimal experience, try

1. [Vimium](https://github.com/philc/vimium)
2. [Tree Style Tab](https://github.com/piroor/treestyletab)


### Credits 🏆
- [Firefox CSS](https://www.reddit.com/r/FirefoxCSS/)
