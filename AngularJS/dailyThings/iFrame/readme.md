This is for resizing the iframe.
Instead of having the div, include for ie:

    <iframe ng-src="{{::controller.data.iframeUrl}}"
        width="{{::controller.data.moduleConfig.iframe.width}}"
        frameborder="0" scrolling="yes" align="middle"
        ng-style="style()"
        load-iframe-dimensions
    >




from: http://jsfiddle.net/jaredwilli/SfJ8c/
