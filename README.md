# Extension

-------------------------------------------------------------------------------------------------------------------------------
# What is Extension? #
Extensions are simply files that work in combination with software to achieve a certain task that neither the extension nor the software can provide individually. Extensions are most commonly used with a programming language in the form of DLL libraries that extend the functionality of the programming language, making it understandable on a number of platforms. Similarly in Web browser applications, extensions make it easy for the program to open and play a number of different formats that it would otherwise be unable to read. In a case such as this, the Web browser is called a primary program.

-------------------------------------------------------------------------------------------------------------------------------

# Easy language: # 
Extension is a small program which customizes the browsing experience of the user.

-------------------------------------------------------------------------------------------------------------------------------

It mainly consists of 4 types:
1) Background script 
2) Content script
3) Options page
4) UI elements

-------------------------------------------------------------------------------------------------------------------------------

# Manifest File Format #
Every extension has a JSON-formatted manifest file, named manifest.json, that provides important information.
[Link] <https://developer.chrome.com/extensions/manifest>

-------------------------------------------------------------------------------------------------------------------------------

# Manage Events with Background Scripts #
Extensions are event based programs used to modify or enhance the Chrome browsing experience. Events are browser triggers, such as navigating to a new page, removing a bookmark, or closing a tab. Extensions monitor these events in their background script, then react with specified instructions.
[Link] <https://developer.chrome.com/extensions/background_pages>

-------------------------------------------------------------------------------------------------------------------------------

# Design User Interface #
The extension user interface should be purposeful and minimal. Just like extensions themselves, the UI should customize or enhance the browsing experience without distracting from it.
[Link] <https://developer.chrome.com/extensions/user_interface>

-------------------------------------------------------------------------------------------------------------------------------

# chrome storage #
This API has been optimized to meet the specific storage needs of extensions. It provides the same storage capabilities as the localStorage API.
[Link]  <https://developer.chrome.com/extensions/storage>

-------------------------------------------------------------------------------------------------------------------------------
