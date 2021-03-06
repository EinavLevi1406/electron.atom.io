---
version: v1.7.5
permalink: /docs/api/webview-tag/
category: API
redirect_from:
  - /docs/v0.37.8/api/webview-tag/
  - /docs/v0.37.7/api/webview-tag/
  - /docs/v0.37.6/api/webview-tag/
  - /docs/v0.37.5/api/webview-tag/
  - /docs/v0.37.4/api/webview-tag/
  - /docs/v0.37.3/api/webview-tag/
  - /docs/v0.37.1/api/webview-tag/
  - /docs/v0.37.0/api/webview-tag/
  - /docs/v0.36.12/api/webview-tag/
  - /docs/v0.36.11/api/webview-tag/
  - /docs/v0.36.10/api/webview-tag/
  - /docs/v0.36.9/api/webview-tag/
  - /docs/v0.36.8/api/webview-tag/
  - /docs/v0.36.7/api/webview-tag/
  - /docs/v0.36.6/api/webview-tag/
  - /docs/v0.36.5/api/webview-tag/
  - /docs/v0.36.4/api/webview-tag/
  - /docs/v0.36.3/api/webview-tag/
  - /docs/v0.36.2/api/webview-tag/
  - /docs/v0.36.0/api/webview-tag/
  - /docs/v0.35.5/api/webview-tag/
  - /docs/v0.35.4/api/webview-tag/
  - /docs/v0.35.3/api/webview-tag/
  - /docs/v0.35.2/api/webview-tag/
  - /docs/v0.35.1/api/webview-tag/
  - /docs/v0.34.4/api/webview-tag/
  - /docs/v0.34.3/api/webview-tag/
  - /docs/v0.34.2/api/webview-tag/
  - /docs/v0.34.1/api/webview-tag/
  - /docs/v0.34.0/api/webview-tag/
  - /docs/v0.33.9/api/webview-tag/
  - /docs/v0.33.8/api/webview-tag/
  - /docs/v0.33.7/api/webview-tag/
  - /docs/v0.33.6/api/webview-tag/
  - /docs/v0.33.4/api/webview-tag/
  - /docs/v0.33.3/api/webview-tag/
  - /docs/v0.33.2/api/webview-tag/
  - /docs/v0.33.1/api/webview-tag/
  - /docs/v0.33.0/api/webview-tag/
  - /docs/v0.32.3/api/webview-tag/
  - /docs/v0.32.2/api/webview-tag/
  - /docs/v0.31.2/api/webview-tag/
  - /docs/v0.31.0/api/webview-tag/
  - /docs/v0.30.4/api/webview-tag/
  - /docs/v0.29.2/api/webview-tag/
  - /docs/v0.29.1/api/webview-tag/
  - /docs/v0.28.3/api/webview-tag/
  - /docs/v0.28.2/api/webview-tag/
  - /docs/v0.28.1/api/webview-tag/
  - /docs/v0.28.0/api/webview-tag/
  - /docs/v0.27.3/api/webview-tag/
  - /docs/v0.27.2/api/webview-tag/
  - /docs/v0.27.1/api/webview-tag/
  - /docs/v0.27.0/api/webview-tag/
  - /docs/v0.26.1/api/webview-tag/
  - /docs/v0.26.0/api/webview-tag/
  - /docs/v0.25.3/api/webview-tag/
  - /docs/v0.25.2/api/webview-tag/
  - /docs/v0.25.1/api/webview-tag/
  - /docs/v0.25.0/api/webview-tag/
  - /docs/v0.24.0/api/webview-tag/
  - /docs/v0.23.0/api/webview-tag/
  - /docs/v0.22.3/api/webview-tag/
  - /docs/v0.22.2/api/webview-tag/
  - /docs/v0.22.1/api/webview-tag/
  - /docs/v0.21.3/api/webview-tag/
  - /docs/v0.21.2/api/webview-tag/
  - /docs/v0.21.1/api/webview-tag/
  - /docs/v0.21.0/api/webview-tag/
  - /docs/v0.20.8/api/webview-tag/
  - /docs/v0.20.7/api/webview-tag/
  - /docs/v0.20.6/api/webview-tag/
  - /docs/v0.20.5/api/webview-tag/
  - /docs/v0.20.4/api/webview-tag/
  - /docs/v0.20.3/api/webview-tag/
  - /docs/v0.20.2/api/webview-tag/
  - /docs/v0.20.1/api/webview-tag/
  - /docs/v0.20.0/api/webview-tag/
  - /docs/latest/api/webview-tag/
  - /docs/api/web-view-tag/
source_url: 'https://github.com/electron/electron/blob/master/docs/api/webview-tag.md'
title: '&lt;webview&gt; Tag'
excerpt: Display external web content in an isolated frame and process.
sort_title: webview-tag
---



<!--


                                      ::::
                                    :o+//+o:
                                    +o    oo-
                                    :o+//oo/+o/
                                      -::-   -oo:
                                               /s/
                      -::::::::-                :s/  :::--
                  :+oo+////////+:        -:/+oo/ :s:-///++oo+:
                /o+:                -/+oo+/:-     +o-      -:+o:
               /s:              -:+o+/:           -o+         :s/
              -s/            -/oo/:                /s-         +s-
              -s/         -/oo/-                   -s/         /s-
               oo       :+o/-                       oo         oo
               -s/    :oo/                          /s-       /s-
                :s/ :oo:              -::-          /s-      /s:
                  -+o/               /ssss/         :s:    -+o-
                 :o+--               /ssss/         :s:   :o+-
                :s/  +o:              -::-          /s-   --
               -s/    :+o/-                         /s-
               oo       -+o+-                       oo
              -s/         -/oo/-                   -s/
             -+soo+:         -/oo/:                /s-      /oooo+-
             o+   :s:           -:+o+/:-          -o+      /s:  -oo
             oo:--/s:       ::      -:+oo+/:-     -/-      /s/--:o+
              :+++/-        :s:          -:/+ooo++//////++oo//+o+:
                             /s:                --::::::--
                              /s/              /s-
                               :oo:          :oo:
                                 /oo/-    -/oo/
                                   -/+oooo+/-





                   _______  _______  _______  _______  __
                  |       ||       ||       ||       ||  |
                  |  _____||_     _||   _   ||    _  ||  |
                  | |_____   |   |  |  | |  ||   |_| ||  |
                  |_____  |  |   |  |  |_|  ||    ___||__|
                   _____| |  |   |  |       ||   |     __
                  |_______|  |___|  |_______||___|    |__|


    This file is generated automatically, so it should not be edited.

    To make changes, head over to the electron/electron repository:

    https://github.com/electron/electron/blob/master/docs/api/webview-tag.md

    Thanks!

-->
# `<webview>` Tag

> Display external web content in an isolated frame and process.

Process: [Renderer]({{site.baseurl}}/docs/tutorial/quick-start#renderer-process)

Use the `webview` tag to embed 'guest' content (such as web pages) in your Electron app. The guest content is contained within the `webview` container. An embedded page within your app controls how the guest content is laid out and rendered.

Unlike an `iframe`, the `webview` runs in a separate process than your app. It doesn't have the same permissions as your web page and all interactions between your app and embedded content will be asynchronous. This keeps your app safe from the embedded content. **Note:** Most methods called on the webview from the host page require a synchronous call to the main process.

## Example

To embed a web page in your app, add the `webview` tag to your app's embedder page (this is the app page that will display the guest content). In its simplest form, the `webview` tag includes the `src` of the web page and css styles that control the appearance of the `webview` container:

```html
<webview id="foo" src="https://www.github.com/" style="display:inline-flex; width:640px; height:480px"></webview>
```

If you want to control the guest content in any way, you can write JavaScript that listens for `webview` events and responds to those events using the `webview` methods. Here's sample code with two event listeners: one that listens for the web page to start loading, the other for the web page to stop loading, and displays a "loading..." message during the load time:

```html
<script>
  onload = () => {
    const webview = document.querySelector('webview')
    const indicator = document.querySelector('.indicator')

    const loadstart = () => {
      indicator.innerText = 'loading...'
    }

    const loadstop = () => {
      indicator.innerText = ''
    }

    webview.addEventListener('did-start-loading', loadstart)
    webview.addEventListener('did-stop-loading', loadstop)
  }
</script>
```

## CSS Styling Notes

Please note that the `webview` tag's style uses `display:flex;` internally to ensure the child `object` element fills the full height and width of its `webview` container when used with traditional and flexbox layouts (since v0.36.11). Please do not overwrite the default `display:flex;` CSS property, unless specifying `display:inline-flex;` for inline layout.

`webview` has issues being hidden using the `hidden` attribute or using `display: none;`. It can cause unusual rendering behaviour within its child `browserplugin` object and the web page is reloaded when the `webview` is un-hidden. The recommended approach is to hide the `webview` using `visibility: hidden`.

```html
<style>
  webview {
    display:inline-flex;
    width:640px;
    height:480px;
  }
  webview.hide {
    visibility: hidden;
  }
</style>
```

## Tag Attributes

The `webview` tag has the following attributes:

### `src`

```html
<webview src="https://www.github.com/"></webview>
```

Returns the visible URL. Writing to this attribute initiates top-level navigation.

Assigning `src` its own value will reload the current page.

The `src` attribute can also accept data URLs, such as `data:text/plain,Hello, world!`.

### `autosize`

```html
<webview src="https://www.github.com/" autosize minwidth="576" minheight="432"></webview>
```

When this attribute is present the `webview` container will automatically resize within the bounds specified by the attributes `minwidth`, `minheight`, `maxwidth`, and `maxheight`. These constraints do not impact the `webview` unless `autosize` is enabled. When `autosize` is enabled, the `webview` container size cannot be less than the minimum values or greater than the maximum.

### `nodeintegration`

```html
<webview src="http://www.google.com/" nodeintegration></webview>
```

When this attribute is present the guest page in `webview` will have node integration and can use node APIs like `require` and `process` to access low level system resources. Node integration is disabled by default in the guest page.

### `plugins`

```html
<webview src="https://www.github.com/" plugins></webview>
```

When this attribute is present the guest page in `webview` will be able to use browser plugins. Plugins are disabled by default.

### `preload`

```html
<webview src="https://www.github.com/" preload="./test.js"></webview>
```

Specifies a script that will be loaded before other scripts run in the guest page. The protocol of script's URL must be either `file:` or `asar:`, because it will be loaded by `require` in guest page under the hood.

When the guest page doesn't have node integration this script will still have access to all Node APIs, but global objects injected by Node will be deleted after this script has finished executing.

**Note:** This option will be appear as `preloadURL` (not `preload`) in the `webPreferences` specified to the `will-attach-webview` event.

### `httpreferrer`

```html
<webview src="https://www.github.com/" httpreferrer="http://cheng.guru"></webview>
```

Sets the referrer URL for the guest page.

### `useragent`

```html
<webview src="https://www.github.com/" useragent="Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; AS; rv:11.0) like Gecko"></webview>
```

Sets the user agent for the guest page before the page is navigated to. Once the page is loaded, use the `setUserAgent` method to change the user agent.

### `disablewebsecurity`

```html
<webview src="https://www.github.com/" disablewebsecurity></webview>
```

When this attribute is present the guest page will have web security disabled. Web security is enabled by default.

### `partition`

```html
<webview src="https://github.com" partition="persist:github"></webview>
<webview src="https://electron.atom.io" partition="electron"></webview>
```

Sets the session used by the page. If `partition` starts with `persist:`, the page will use a persistent session available to all pages in the app with the same `partition`. if there is no `persist:` prefix, the page will use an in-memory session. By assigning the same `partition`, multiple pages can share the same session. If the `partition` is unset then default session of the app will be used.

This value can only be modified before the first navigation, since the session of an active renderer process cannot change. Subsequent attempts to modify the value will fail with a DOM exception.

### `allowpopups`

```html
<webview src="https://www.github.com/" allowpopups></webview>
```

When this attribute is present the guest page will be allowed to open new windows. Popups are disabled by default.

### `webpreferences`

```html
<webview src="https://github.com" webpreferences="allowRunningInsecureContent, javascript=no"></webview>
```

A list of strings which specifies the web preferences to be set on the webview, separated by `,`. The full list of supported preference strings can be found in [BrowserWindow]({{site.baseurl}}/docs/api/browser-window#new-browserwindowoptions).

The string follows the same format as the features string in `window.open`. A name by itself is given a `true` boolean value. A preference can be set to another value by including an `=`, followed by the value. Special values `yes` and `1` are interpreted as `true`, while `no` and `0` are interpreted as `false`.

### `blinkfeatures`

```html
<webview src="https://www.github.com/" blinkfeatures="PreciseMemoryInfo, CSSVariables"></webview>
```

A list of strings which specifies the blink features to be enabled separated by `,`. The full list of supported feature strings can be found in the [RuntimeEnabledFeatures.json5](https://cs.chromium.org/chromium/src/third_party/WebKit/Source/platform/RuntimeEnabledFeatures.json5?l=62) file.

### `disableblinkfeatures`

```html
<webview src="https://www.github.com/" disableblinkfeatures="PreciseMemoryInfo, CSSVariables"></webview>
```

A list of strings which specifies the blink features to be disabled separated by `,`. The full list of supported feature strings can be found in the [RuntimeEnabledFeatures.json5](https://cs.chromium.org/chromium/src/third_party/WebKit/Source/platform/RuntimeEnabledFeatures.json5?l=62) file.

### `guestinstance`

```html
<webview src="https://www.github.com/" guestinstance="3"></webview>
```

A value that links the webview to a specific webContents. When a webview first loads a new webContents is created and this attribute is set to its instance identifier. Setting this attribute on a new or existing webview connects it to the existing webContents that currently renders in a different webview.

The existing webview will see the `destroy` event and will then create a new webContents when a new url is loaded.

### `disableguestresize`

```html
<webview src="https://www.github.com/" disableguestresize></webview>
```

When this attribute is present the `webview` contents will be prevented from resizing when the `webview` element itself is resized.

This can be used in combination with [`webContents.setSize`]({{site.baseurl}}/docs/api/web-contents#contentssetsizeoptions) to manually resize the webview contents in reaction to a window size change. This can make resizing faster compared to relying on the webview element bounds to automatically resize the contents.

```javascript
const {webContents} = require('electron')

// We assume that `win` points to a `BrowserWindow` instance containing a
// `<webview>` with `disableguestresize`.

win.on('resize', () => {
  const [width, height] = win.getContentSize()
  for (let wc of webContents.getAllWebContents()) {
    // Check if `wc` belongs to a webview in the `win` window.
    if (wc.hostWebContents &&
        wc.hostWebContents.id === win.webContents.id) {
      wc.setSize({
        normal: {
          width: width,
          height: height
        }
      })
    }
  }
})
```

## Methods

The `webview` tag has the following methods:

**Note:** The webview element must be loaded before using the methods.

**Example**

```javascript
const webview = document.querySelector('webview')
webview.addEventListener('dom-ready', () => {
  webview.openDevTools()
})
```

### `<webview>.loadURL(url[, options])`

*   `url` URL
*   `options` Object (optional)
    *   `httpReferrer` String (optional) - A HTTP Referrer url.
    *   `userAgent` String (optional) - A user agent originating the request.
    *   `extraHeaders` String (optional) - Extra headers separated by "\n"
    *   `postData` ([UploadRawData[]]({{site.baseurl}}/docs/api/structures/upload-raw-data) &#124; [UploadFile[]]({{site.baseurl}}/docs/api/structures/upload-file) &#124; [UploadFileSystem[]]({{site.baseurl}}/docs/api/structures/upload-file-system) &#124; [UploadBlob[]]({{site.baseurl}}/docs/api/structures/upload-blob)) - (optional)
    *   `baseURLForDataURL` String (optional) - Base url (with trailing path separator) for files to be loaded by the data url. This is needed only if the specified `url` is a data url and needs to load other files.

Loads the `url` in the webview, the `url` must contain the protocol prefix, e.g. the `http://` or `file://`.

### `<webview>.getURL()`

Returns `String` - The URL of guest page.

### `<webview>.getTitle()`

Returns `String` - The title of guest page.

### `<webview>.isLoading()`

Returns `Boolean` - Whether guest page is still loading resources.

### `<webview>.isWaitingForResponse()`

Returns `Boolean` - Whether the guest page is waiting for a first-response for the main resource of the page.

### `<webview>.stop()`

Stops any pending navigation.

### `<webview>.reload()`

Reloads the guest page.

### `<webview>.reloadIgnoringCache()`

Reloads the guest page and ignores cache.

### `<webview>.canGoBack()`

Returns `Boolean` - Whether the guest page can go back.

### `<webview>.canGoForward()`

Returns `Boolean` - Whether the guest page can go forward.

### `<webview>.canGoToOffset(offset)`

*   `offset` Integer

Returns `Boolean` - Whether the guest page can go to `offset`.

### `<webview>.clearHistory()`

Clears the navigation history.

### `<webview>.goBack()`

Makes the guest page go back.

### `<webview>.goForward()`

Makes the guest page go forward.

### `<webview>.goToIndex(index)`

*   `index` Integer

Navigates to the specified absolute index.

### `<webview>.goToOffset(offset)`

*   `offset` Integer

Navigates to the specified offset from the "current entry".

### `<webview>.isCrashed()`

Returns `Boolean` - Whether the renderer process has crashed.

### `<webview>.setUserAgent(userAgent)`

*   `userAgent` String

Overrides the user agent for the guest page.

### `<webview>.getUserAgent()`

Returns `String` - The user agent for guest page.

### `<webview>.insertCSS(css)`

*   `css` String

Injects CSS into the guest page.

### `<webview>.executeJavaScript(code, userGesture, callback)`

*   `code` String
*   `userGesture` Boolean - Default `false`.
*   `callback` Function (optional) - Called after script has been executed.
    *   `result` Any

Evaluates `code` in page. If `userGesture` is set, it will create the user gesture context in the page. HTML APIs like `requestFullScreen`, which require user action, can take advantage of this option for automation.

### `<webview>.openDevTools()`

Opens a DevTools window for guest page.

### `<webview>.closeDevTools()`

Closes the DevTools window of guest page.

### `<webview>.isDevToolsOpened()`

Returns `Boolean` - Whether guest page has a DevTools window attached.

### `<webview>.isDevToolsFocused()`

Returns `Boolean` - Whether DevTools window of guest page is focused.

### `<webview>.inspectElement(x, y)`

*   `x` Integer
*   `y` Integer

Starts inspecting element at position (`x`, `y`) of guest page.

### `<webview>.inspectServiceWorker()`

Opens the DevTools for the service worker context present in the guest page.

### `<webview>.setAudioMuted(muted)`

*   `muted` Boolean

Set guest page muted.

### `<webview>.isAudioMuted()`

Returns `Boolean` - Whether guest page has been muted.

### `<webview>.undo()`

Executes editing command `undo` in page.

### `<webview>.redo()`

Executes editing command `redo` in page.

### `<webview>.cut()`

Executes editing command `cut` in page.

### `<webview>.copy()`

Executes editing command `copy` in page.

### `<webview>.paste()`

Executes editing command `paste` in page.

### `<webview>.pasteAndMatchStyle()`

Executes editing command `pasteAndMatchStyle` in page.

### `<webview>.delete()`

Executes editing command `delete` in page.

### `<webview>.selectAll()`

Executes editing command `selectAll` in page.

### `<webview>.unselect()`

Executes editing command `unselect` in page.

### `<webview>.replace(text)`

*   `text` String

Executes editing command `replace` in page.

### `<webview>.replaceMisspelling(text)`

*   `text` String

Executes editing command `replaceMisspelling` in page.

### `<webview>.insertText(text)`

*   `text` String

Inserts `text` to the focused element.

### `<webview>.findInPage(text[, options])`

*   `text` String - Content to be searched, must not be empty.
*   `options` Object (optional)
    *   `forward` Boolean - (optional) Whether to search forward or backward, defaults to `true`.
    *   `findNext` Boolean - (optional) Whether the operation is first request or a follow up, defaults to `false`.
    *   `matchCase` Boolean - (optional) Whether search should be case-sensitive, defaults to `false`.
    *   `wordStart` Boolean - (optional) Whether to look only at the start of words. defaults to `false`.
    *   `medialCapitalAsWordStart` Boolean - (optional) When combined with `wordStart`, accepts a match in the middle of a word if the match begins with an uppercase letter followed by a lowercase or non-letter. Accepts several other intra-word matches, defaults to `false`.

Starts a request to find all matches for the `text` in the web page and returns an `Integer` representing the request id used for the request. The result of the request can be obtained by subscribing to [`found-in-page`]({{site.baseurl}}/docs/api/webview-tag#event-found-in-page) event.

### `<webview>.stopFindInPage(action)`

*   `action` String - Specifies the action to take place when ending [`<webview>.findInPage`]({{site.baseurl}}/docs/api/webview-tag#webviewtagfindinpage) request.
    *   `clearSelection` - Clear the selection.
    *   `keepSelection` - Translate the selection into a normal selection.
    *   `activateSelection` - Focus and click the selection node.

Stops any `findInPage` request for the `webview` with the provided `action`.

### `<webview>.print([options])`

*   `options` Object (optional)
    *   `silent` Boolean (optional) - Don't ask user for print settings. Default is `false`.
    *   `printBackground` Boolean (optional) - Also prints the background color and image of the web page. Default is `false`.
    *   `deviceName` String (optional) - Set the printer device name to use. Default is `''`.

Prints `webview`'s web page. Same as `webContents.print([options])`.

### `<webview>.printToPDF(options, callback)`

*   `options` Object
    *   `marginsType` Integer - (optional) Specifies the type of margins to use. Uses 0 for default margin, 1 for no margin, and 2 for minimum margin.
    *   `pageSize` String - (optional) Specify page size of the generated PDF. Can be `A3`, `A4`, `A5`, `Legal`, `Letter`, `Tabloid` or an Object containing `height` and `width` in microns.
    *   `printBackground` Boolean - (optional) Whether to print CSS backgrounds.
    *   `printSelectionOnly` Boolean - (optional) Whether to print selection only.
    *   `landscape` Boolean - (optional) `true` for landscape, `false` for portrait.
*   `callback` Function
    *   `error` Error
    *   `data` Buffer

Prints `webview`'s web page as PDF, Same as `webContents.printToPDF(options, callback)`.

### `<webview>.capturePage([rect, ]callback)`

*   `rect` [Rectangle]({{site.baseurl}}/docs/api/structures/rectangle) (optional) - The area of the page to be captured
*   `callback` Function
    *   `image` [NativeImage]({{site.baseurl}}/docs/api/native-image)

Captures a snapshot of the `webview`'s page. Same as `webContents.capturePage([rect, ]callback)`.

### `<webview>.send(channel[, arg1][, arg2][, ...])`

*   `channel` String
*   `...args` any[]

Send an asynchronous message to renderer process via `channel`, you can also send arbitrary arguments. The renderer process can handle the message by listening to the `channel` event with the `ipcRenderer` module.

See [webContents.send]({{site.baseurl}}/docs/api/web-contents#webcontentssendchannel-args) for examples.

### `<webview>.sendInputEvent(event)`

*   `event` Object

Sends an input `event` to the page.

See [webContents.sendInputEvent]({{site.baseurl}}/docs/api/web-contents#webcontentssendinputeventevent) for detailed description of `event` object.

### `<webview>.setZoomFactor(factor)`

*   `factor` Number - Zoom factor.

Changes the zoom factor to the specified factor. Zoom factor is zoom percent divided by 100, so 300% = 3.0.

### `<webview>.setZoomLevel(level)`

*   `level` Number - Zoom level

Changes the zoom level to the specified level. The original size is 0 and each increment above or below represents zooming 20% larger or smaller to default limits of 300% and 50% of original size, respectively.

### `<webview>.showDefinitionForSelection()` _macOS_

Shows pop-up dictionary that searches the selected word on the page.

### `<webview>.getWebContents()`

Returns [`WebContents`]({{site.baseurl}}/docs/api/web-contents) - The web contents associated with this `webview`.

## DOM events

The following DOM events are available to the `webview` tag:

### Event: 'load-commit'

Returns:

*   `url` String
*   `isMainFrame` Boolean

Fired when a load has committed. This includes navigation within the current document as well as subframe document-level loads, but does not include asynchronous resource loads.

### Event: 'did-finish-load'

Fired when the navigation is done, i.e. the spinner of the tab will stop spinning, and the `onload` event is dispatched.

### Event: 'did-fail-load'

Returns:

*   `errorCode` Integer
*   `errorDescription` String
*   `validatedURL` String
*   `isMainFrame` Boolean

This event is like `did-finish-load`, but fired when the load failed or was cancelled, e.g. `window.stop()` is invoked.

### Event: 'did-frame-finish-load'

Returns:

*   `isMainFrame` Boolean

Fired when a frame has done navigation.

### Event: 'did-start-loading'

Corresponds to the points in time when the spinner of the tab starts spinning.

### Event: 'did-stop-loading'

Corresponds to the points in time when the spinner of the tab stops spinning.

### Event: 'did-get-response-details'

Returns:

*   `status` Boolean
*   `newURL` String
*   `originalURL` String
*   `httpResponseCode` Integer
*   `requestMethod` String
*   `referrer` String
*   `headers` Object
*   `resourceType` String

Fired when details regarding a requested resource is available. `status` indicates socket connection to download the resource.

### Event: 'did-get-redirect-request'

Returns:

*   `oldURL` String
*   `newURL` String
*   `isMainFrame` Boolean

Fired when a redirect was received while requesting a resource.

### Event: 'dom-ready'

Fired when document in the given frame is loaded.

### Event: 'page-title-updated'

Returns:

*   `title` String
*   `explicitSet` Boolean

Fired when page title is set during navigation. `explicitSet` is false when title is synthesized from file url.

### Event: 'page-favicon-updated'

Returns:

*   `favicons` String[] - Array of URLs.

Fired when page receives favicon urls.

### Event: 'enter-html-full-screen'

Fired when page enters fullscreen triggered by HTML API.

### Event: 'leave-html-full-screen'

Fired when page leaves fullscreen triggered by HTML API.

### Event: 'console-message'

Returns:

*   `level` Integer
*   `message` String
*   `line` Integer
*   `sourceId` String

Fired when the guest window logs a console message.

The following example code forwards all log messages to the embedder's console without regard for log level or other properties.

```javascript
const webview = document.querySelector('webview')
webview.addEventListener('console-message', (e) => {
  console.log('Guest page logged a message:', e.message)
})
```

### Event: 'found-in-page'

Returns:

*   `result` Object
    *   `requestId` Integer
    *   `activeMatchOrdinal` Integer - Position of the active match.
    *   `matches` Integer - Number of Matches.
    *   `selectionArea` Object - Coordinates of first match region.
    *   `finalUpdate` Boolean

Fired when a result is available for [`webview.findInPage`]({{site.baseurl}}/docs/api/webview-tag#webviewtagfindinpage) request.

```javascript
const webview = document.querySelector('webview')
webview.addEventListener('found-in-page', (e) => {
  webview.stopFindInPage('keepSelection')
})

const requestId = webview.findInPage('test')
console.log(requestId)
```

### Event: 'new-window'

Returns:

*   `url` String
*   `frameName` String
*   `disposition` String - Can be `default`, `foreground-tab`, `background-tab`, `new-window`, `save-to-disk` and `other`.
*   `options` Object - The options which should be used for creating the new `BrowserWindow`.

Fired when the guest page attempts to open a new browser window.

The following example code opens the new url in system's default browser.

```javascript
const {shell} = require('electron')
const webview = document.querySelector('webview')

webview.addEventListener('new-window', (e) => {
  const protocol = require('url').parse(e.url).protocol
  if (protocol === 'http:' || protocol === 'https:') {
    shell.openExternal(e.url)
  }
})
```

### Event: 'will-navigate'

Returns:

*   `url` String

Emitted when a user or the page wants to start navigation. It can happen when the `window.location` object is changed or a user clicks a link in the page.

This event will not emit when the navigation is started programmatically with APIs like `<webview>.loadURL` and `<webview>.back`.

It is also not emitted during in-page navigation, such as clicking anchor links or updating the `window.location.hash`. Use `did-navigate-in-page` event for this purpose.

Calling `event.preventDefault()` does **NOT** have any effect.

### Event: 'did-navigate'

Returns:

*   `url` String

Emitted when a navigation is done.

This event is not emitted for in-page navigations, such as clicking anchor links or updating the `window.location.hash`. Use `did-navigate-in-page` event for this purpose.

### Event: 'did-navigate-in-page'

Returns:

*   `isMainFrame` Boolean
*   `url` String

Emitted when an in-page navigation happened.

When in-page navigation happens, the page URL changes but does not cause navigation outside of the page. Examples of this occurring are when anchor links are clicked or when the DOM `hashchange` event is triggered.

### Event: 'close'

Fired when the guest page attempts to close itself.

The following example code navigates the `webview` to `about:blank` when the guest attempts to close itself.

```javascript
const webview = document.querySelector('webview')
webview.addEventListener('close', () => {
  webview.src = 'about:blank'
})
```

### Event: 'ipc-message'

Returns:

*   `channel` String
*   `args` Array

Fired when the guest page has sent an asynchronous message to embedder page.

With `sendToHost` method and `ipc-message` event you can easily communicate between guest page and embedder page:

```javascript
// In embedder page.
const webview = document.querySelector('webview')
webview.addEventListener('ipc-message', (event) => {
  console.log(event.channel)
  // Prints "pong"
})
webview.send('ping')
```

```javascript
// In guest page.
const {ipcRenderer} = require('electron')
ipcRenderer.on('ping', () => {
  ipcRenderer.sendToHost('pong')
})
```

### Event: 'crashed'

Fired when the renderer process is crashed.

### Event: 'gpu-crashed'

Fired when the gpu process is crashed.

### Event: 'plugin-crashed'

Returns:

*   `name` String
*   `version` String

Fired when a plugin process is crashed.

### Event: 'destroyed'

Fired when the WebContents is destroyed.

### Event: 'media-started-playing'

Emitted when media starts playing.

### Event: 'media-paused'

Emitted when media is paused or done playing.

### Event: 'did-change-theme-color'

Returns:

*   `themeColor` String

Emitted when a page's theme color changes. This is usually due to encountering a meta tag:

```html
<meta name='theme-color' content='#ff0000'>
```

### Event: 'update-target-url'

Returns:

*   `url` String

Emitted when mouse moves over a link or the keyboard moves the focus to a link.

### Event: 'devtools-opened'

Emitted when DevTools is opened.

### Event: 'devtools-closed'

Emitted when DevTools is closed.

### Event: 'devtools-focused'

Emitted when DevTools is focused / opened.
