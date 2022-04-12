# Material Spring Theme

This is a material design theme for the [Mailspring](http://www.getmailspring.com/) email client.

![*Screenshot*](/screenshot/1.png)

- I have only tested it on Windows, which has the same accent color as I have in my Mailspring theme.


## How to install

From the Toolbar Menu icon in the top right corner, select `Install Theme...` and then
select the folder of this theme.


## How to Edit

This theme is fairly easy to edit. You can simply change the values of the
variables present in [ui-variables.less](/styles/ui-variables.less).

If you want more control or if you want to improve on this theme, the [index.less](/styles/index.less)
is where you can change the CSS of Mailspring.
To make this task easier, you can `Ctrl+Shift+I` to toggle the developer tools and inspect the elements
like in a browser.

To apply the changes: `Ctrl+Shift+R` to reload Mailspring


## To-Do

- set the pointer cursor on every clickable element
- message draft enabled options color (is the same as the accent-color, which is unnoticeable when the background of the message draft area is the same - when it's unfocused)
- treeview lines for every label that doesn't have an arrow (in the account sidebar)
- fix the background of html messages (if they have transparent background and a text color that is close to the @backround-primary, it will be hard to read)
	- I already have @message-content-background to set the background color of the message
   - I got the email-frame.less file from one of the default themes, but I have yet to see it working.
- I haven't done anything to:
	- the Participant's sidebar
	- notifitication area
	- .find-in-thread
	- date label when you grab the scroll handle in the threadlist
   - the quick actions in the thread-list (they could "light up" when the mouse hovers, or something similar)