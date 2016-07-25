# Previewport
Have you ever wanted to see what a site looks like on a big wide desktop display but all you have is your phone? Me too, so I built this tool.

Put a URL in the text field and hit enter or click "Go" to render it into the iframe below. It's like the site on a desktop browser, only <sup>1</sup>&frasl;<sub>16</sub> the size.

## Why? Doesn't "Request Desktop Site" do this?
Sometimes "Request Desktop Site" just doesn't work. When it does work, sometimes the desktop site is responsive, so it looks just the same as the mobile site does when it's viewed on mobile.

###Tagline:
It's like having a little desktop in your pocket

###Unused taglines:
 * Any (view)port in a storm
 * Yo dawg I heard you like viewports so I put a viewport inside your viewport so you can beat this meme to death.
 
###TODO:
 * Fix padding beside iframe in some situations
 * Look at iframe height (site dependant)
 * Match zoom to device viewport (right now the widths are hard-coded to 1280 for the embedded iframe and 320 for the device)
 * Bypass Content Security Policy directives to allow navigating to sites like twitter and facebook and youtube
 * The design could use some spit and polish
 * The logic could use some validation
 * Test on browsers besides Chrome and Mobile Safari
 * Test on devices besides iPhone 5S (you can help if you have a different device!)
 * Split out style and logic from presentation
 * Add support for arbitrary viewport sizes
