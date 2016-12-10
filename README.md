# xcode-services

A collection (hopefully) of tools for Xcode. I've started this mini-project as a set of tools that I'm using for my own productivity as a developer.

# Localize selection

 - Copy the service inside the "Localize selected string" to `~/Library/Services`
 - Go to System Preferences -> Keyboard
 - Select Shortcuts tab from above
 - Select Services from the list on the left
 - Under Text section, find the service that you've just saved
 - Double click where it says "none" at the right, and give it an unused keyboard shortcut (I've did `option` + `backtick`)
 
You are set!

Now, whenever you are coding, when you want to localize a string using the `NSLocalizedString` macro, just select the text *including the @ sign and the quotation marks*, and hit your keyboard shortcut. Type a description (this is imporant for the translator to understand the context, so make it clear) and your localized string is ready.

I've made extensive use of this shortcut on my own projects where there are *a lot* of strings for translation.
