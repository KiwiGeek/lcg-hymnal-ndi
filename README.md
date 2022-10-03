# LCG Hymnal NDI

Simple application that contains the LCG hymnal and acts as an NDI camera source, allowing an operator to page through the hymns as necessary to keep in time with live music. This can work better than sharing a screen, as it provides a clean source, and the pages are already split up as necessary to appear as large as possible on an outgoing stream.

The application requires .net runtime 6, and it will prompt you to install it if you don't already have it on first launch. It's only available for Windows (and only tested on Windows 11, although I would expect any version of windows that supports .net 6 to work just fine). Access the downloads via the releases link on the sidebar.

Your streaming software may require a plugin to allow it to access an NDI source. For instance, OBS requires the obs-ndi plugin (https://obsproject.com/forum/resources/obs-ndi-newtek-ndi%E2%84%A2-integration-into-obs-studio.528/). Note that if you're using the brand new v28 of OBS, you will need to use a pre-release of obs-ndi available from https://github.com/Palakis/obs-ndi/actions/runs/2977380826 (when signed in to GitHub).

For any questions, comments, suggestions, etc, please email me directly (joshua@penman.dev).

<b>If you end up using this in your congregation or FoT site, I'd love to hear about it, so let me know at that address too!</b>
