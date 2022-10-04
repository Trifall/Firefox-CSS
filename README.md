# Firefox-CSS

### This is my custom CSS to recreate the chromium experience.
#### *Note: this has only been tested on Windows 11 and on a 1920x1080 screen resolution.

__Instructions:__

Part 1: Installing the custom CSS

1. Open a new firefox tab and go to __about:config__ -> accept the risks.
2. Search for __toolkit.legacyUserProfileCustomizations.stylesheets__ and toggle it to __true__ (by double clicking on it).
3. Open a new firefox tab and go to __about:support__ -> Click *Open Folder* button for __Profile Folder__
4. Inside your profile folder, create a new folder named __chrome__ (All lowercase)
5. Inside the chrome folder, place the __userChrome.css__ file. You can download the latest version of this file from the [Releases Page.](https://github.com/Trifall/Firefox-CSS/releases/)


Part 2: Installing the color theme

6. Grab the theme from the following link: [Theme Link](https://color.firefox.com/?theme=XQAAAAJUAQAAAAAAAABBqYhm849SCia48_6EGccwS-xMDPr79BBH6_4EpD24jBgjl6kvKSCXh41NOn6Dx5fR2q-a75GjEsvqfeU3VCj6w31W5eXvnSPrqPMCrtBu4dvYAJ4HJEbQ5PR6LKabjxMeCqo8aMtZBZuZ1NU_n0yAIvmiUoNsngm5b2WcT5zFMVsiSkeHdE-YluAjB0nBaIxF6fJVIu-yMdBQQEeyMC93_Kkuhv69kKhxBArVpLCywAtf2Y2Sis2qAb_V_SLQHNU9LTSSxkUr1uBJ3_rmAi9_yUk7IL1DRBAriIn_5KplwA)
7. If it asks to 'Get Firefox Color' just click next a few times and the theme should automatically be applied if it hasn't already.
8. Restart Firefox

### Todo's
* inspect outer border on toolbar when in windowed mode
* sometimes the close button on hover of a tab is blocked by the underlying text of that tab
  * hover detection of the button is wrong if the tabs text is too long
* change the border color for the search bar when there is text selected but it is not focused from blue to something else
