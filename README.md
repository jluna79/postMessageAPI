postMessageAPI
==============

An HTML5 postMessage API test

The example has two parts: the "parent" page and the "child" page (also mentioned as the "main" and "iframe" pages). The parent page has an iframe that loads the contents
of the "child" page and sends messages between them.

The purpose is to test the postMessage API that enables for messages to be sent between different domains so,
Obvious but IMPORTANT: Place in a different domain than the child (iframe) page.

The example is fully functional, you just need to configure	the appropiate domains (look for the TODO comments)

This example is based on: http://davidwalsh.name/window-postmessage
