## AnkiWebView Inspector

This add-on provides a panel with [Qt WebEngine Developer Tools](https://doc.qt.io/qt-5/qtwebengine-debugging.html#qt-webengine-developer-tools). It is similar to *Google chrome developer tools*. It makes it easy to inspect and debug the webviews of Anki. It might be useful when developing an add-on or creating complex card templates.

#### Requirements:
This add-on requires Qt version 5.11 or higher. To detect the Qt version, go to the Anki "Help" menu > "About...".

#### Usage:
This add-on adds an item `Inspect` to the right-click context menu on an instance of AnkiWebView, such as *main webview*, *top toolbar*, *bottom toolbar*, *editor*. When clicking the item, an **Inspector** panel will be shown. The panel can be docked inside the Anki main window. It moves when the title bar is dragged. It is docked or undocked when the title bar is double-clicked.

#### Note:
**Without** this add-on, you can debug the webviews using an external *Google Chrome* instance. For more information, see [Writing Anki 2.1.x Add-ons#Webview Changes](https://apps.ankiweb.net/docs/addons.html#_webview_changes).

#### Screenshots:
![image](/images/screenshot_01.png)
- - -
![image](/images/screenshot_02.png)
