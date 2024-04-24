0x01. Developer tools

# Developer Tools in Your Browser

This repository provides an overview of the developer tools available in popular web browsers and how to use them effectively.

## Opening Developer Tools

### Google Chrome
1. Right-click on a web page and select "Inspect" from the context menu.
2. Alternatively, use the keyboard shortcut:
   - Windows/Linux: `Ctrl + Shift + I`
   - Mac: `Command + Option + I`

### Mozilla Firefox
1. Right-click on a web page and select "Inspect Element" from the context menu.
2. Alternatively, use the keyboard shortcut:
   - Windows/Linux: `Ctrl + Shift + I`
   - Mac: `Command + Option + I`

### Safari
1. Go to "Preferences" in the Safari menu.
2. In the "Advanced" tab, enable the "Show Develop menu in menu bar" option.
3. Close the preferences window and select "Develop" from the menu bar.
4. Choose "Show Web Inspector" for the desired page.

### Microsoft Edge
1. Right-click on a web page and select "Inspect Element" from the context menu.
2. Alternatively, use the keyboard shortcut:
   - Windows: `Ctrl + Shift + I`
   - Mac: `Command + Option + I`

## Using the Elements Tab to Edit HTML and CSS
1. Open the Developer Tools in your browser.
2. Select the "Elements" (Chrome/Firefox/Edge) or "Elements" (Safari) tab.
3. Locate the HTML element you want to modify and right-click on it.
4. Choose "Edit as HTML" to modify the HTML code or "Edit as CSS" to modify the CSS rules.
5. Make the necessary changes and press Enter to apply them.

## Auditing a Page with Lighthouse
1. Open the Developer Tools in your browser.
2. Select the "Lighthouse" tab.
3. Click on "Generate report" or a similar button to start the audit.
4. Lighthouse will analyze the page and provide a report with suggestions for improvement.

## Creating and Running Snippets
1. Open the Developer Tools in your browser.
2. Select the "Sources" (Chrome/Firefox/Edge) or "Resources" (Safari) tab.
3. Choose the "Snippets" section.
4. Click on "New Snippet" and enter your code.
5. Right-click on the snippet and select "Run" to execute it.

## Getting Information about Files and Server Configurations
1. Open the Developer Tools in your browser.
2. Select the "Network" tab.
3. Refresh the page or perform an action to capture network requests.
4. Inspect the requests to gather information about files, server configurations, and response headers.

## Blocking Requests
1. Open the Developer Tools in your browser.
2. Select the "Network" tab.
3. Find the request you want to block and right-click on it.
4. Choose "Block Request URL" or a similar option.
5. The request will be blocked, and you can observe the behavior of the webpage without that request.

## Analyzing JavaScript and CSS Usage on a Page
1. Open the Developer Tools in your browser.
2. Select the "Coverage" (Chrome/Firefox/Edge) or "Storage" (Safari) tab.
3. Reload the page to collect coverage information.
4. The tool will display the percentage of JavaScript or CSS used by each file.

## Detecting 404 Issues
1. Open the Developer Tools in your browser.
2. Select the "Network" tab.
3. Reload the page or perform actions that trigger network requests.
4. Look for requests with a status code of 404 (Not Found).
5. The URL and relevant information of the 404 issues will be listed.

## Moving Elements on a Webpage
1. Open the Developer Tools in your browser.
2. Select the "Elements" tab.
3. Locate the HTML element you want to move.
4. Click and hold the element, then drag it to the desired position within the DOM structure.
5. Release the mouse button to drop the element in its new position.

