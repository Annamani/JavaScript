## BOM : Browser Object Model
    It gives access to the different functionalities that is available in the form of objects.


## Screen
    The window.screen object contains information about the user's screen.
    The window.screen object can be written without the window prefix.
    PROPERTIES:
    
    1. screen.width :
        returns the width of the visitor's screen in pixels.
    2. screen.height : 
        returns the height of the visitor's screen in pixels.
    3. screen.availWidth : 
        returns the width of the visitor's screen, in pixels, minus interface features like the Windows Taskbar.
    4. screen.availHeight : 
        returns the height of the visitor's screen, in pixels, minus interface features like the Windows Taskbar.
    5. screen.colorDepth : 
        property returns the number of bits used to display one color.
    6. screen.pixelDepth : 
        returns the pixel depth of the screen.



## History
    history.back() - same as clicking back in the browser
                    method loads the previous URL in the history list.
    history.forward() - same as clicking forward in the browser
                    method loads the next URL in the history list.

## Navigate
    object contains information about the visitor's browser.

    navigator.cookieEnabled : returns true if cookies are enabled, otherwise false
    navigator.appCodeName : returns the application code name of the browser
    navigator.platform   :returns the product name of the browser engine
    navigator.appVersion : returns version information about the browser
    navigator.userAgent : returns the user-agent header sent by the browser to the server
    navigator.platform : returns the browser platform (operating system)
    navigator.language : returns the browser's language
    navigator.onLine : returns true if the browser is online
    navigator.javaEnabled : method returns true if Java is enabled