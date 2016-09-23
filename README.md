# xcode-services

A collection (hopefully) of tools for Xcode. I've started this mini-project as a set of tools that I'm using for my own productivity as a developer.

# Localize selection

 - Open Automator on your Mac
 - Create new Service
 - (Optional step) From the top, leave Service receives selected as "text" but choose Xcode as the application by selecting "Other..." from the list and selecting Xcode from the applications folder on that menu
 - From the left actions menu, select Run AppleScript
 - Copy the content of Localize selection file
 - Save the service, give it a meaningful name (I've named it "Localize selection for Objective-C")
 - Go to System Preferences -> Keyboard
 - Select Shortcuts tab from above
 - Select Services from the list on the left
 - Under Text section, find the service that you've just saved
 - Double click where it says "none" at the right, and give it an unused keyboard shortcut (I've did `option` + `````)
 
You are set!

Now, whenever you are coding, when you want to localize a string using the `NSLocalizedString` macro, just select the text *including the @ sign and the quotation marks*, and hit your keyboard shortcut. Type a description (this is imporant for the translator to understand the context, so make it clear) and your localized string is ready.

I've made extensive use of this shortcut on my own projects where there are *a lot* of strings for translation.
