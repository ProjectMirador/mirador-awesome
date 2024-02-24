
# mirador-awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome list for Mirador's projects and plugins.

## Plugins

Creating your own plugin? Label it with ["mirador-plugins"](https://github.com/search?q=topic%3Amirador-plugins&type=Repositories). `M3` between brackets indicates support for Mirador 3, where known. 

- Project Mirador:
    - [Annotations Plugin](https://github.com/ProjectMirador/mirador-annotations) (M3)
    - [Annotot Endpoint Plugin](https://github.com/ProjectMirador/mirador-annotot-endpoint-plugin)  (M3)
    - [Download Plugin](https://github.com/ProjectMirador/mirador-dl-plugin) (M3)
    - [Image Tools](https://github.com/ProjectMirador/mirador-image-tools) (M3)
    - [Share Plugin](https://github.com/ProjectMirador/mirador-share-plugin) (M3)
    - [See also the plugin demos](https://github.com/ProjectMirador/mirador-plugin-demos) (M3)
- Bavarian State Library
    - [Mirador 2 plugins](https://github.com/dbmdz/mirador-plugins) - A repository of Mirador plugins, including
        - CanvasLink: Lets you get a link to currently shown canvas
        - ImageCropper: Adds an overlay to the canvas for retrieving the image url for the selected area
        - PhysicalRuler: Adds a ruler with metric or imperial units
        - ShareButtons
        - ViewFromUrl: Lets you update the URL to reflect the current view type, manifest and canvas
    - Mirador 3 Plugins:
        - [CanvasLink](https://github.com/dbmdz/mirador-canvaslink)
        - [CanvasNavigation](https://github.com/dbmdz/mirador-canvasnavigation)
        - [DownloadDialog](https://github.com/dbmdz/mirador-downloaddialog)
        - [ImageCropper](https://github.com/dbmdz/mirador-imagecropper)
        - [KeyboardShortcuts](https://github.com/dbmdz/mirador-keyboardshortcuts)
        - [TextOverlay](https://github.com/dbmdz/mirador-textoverlay)
- [Annotation Tooltip](https://github.com/2SC1815J/mirador-annotation-tooltip-plugin) (M3)
- [LDN Plugin](https://github.com/jeffreycwitt/mirador-ldn-plugin) (M2) - An experimental plugin for incorporating supplemental IIIF content into Mirador via Linked Data Notifications.
- [Jump-to-page](https://github.com/sul-dlss/mirador-jump-to-page) (M2) - A Mirador plugin that allows users to select a page from a dropdown.
- [Metadata Tab plugin](https://github.com/Daniel-KM/Mirador-plugin-MetadataTab) (M2) - developed for Omeka S. 

### Archived
- From UCLA Library (all archived): 
    - [Disable Zoom](https://github.com/UCLALibrary/mirador-disable-zoom) (M2) - A Mirador plugin that allows users to disable (and re-enable) zoom controls per window.
    - [Sync Windows](https://github.com/UCLALibrary/mirador-sync-windows) (M2) - A Mirador plugin that allows users to mirror actions performed in one window in one or more other windows.
    - [Share Workspace](https://github.com/UCLALibrary/mirador-share-workspace) (M2) - A Mirador plugin that allows users to share workspaces across workstations.
    - [Ruler](https://github.com/UCLALibrary/mirador-ruler) (M2) - A Mirador plugin that allows users to overlay a configurable ruler on any window.

## Mirador-Based Tools

- [IIIF Toolkit with Mirador](https://github.com/utlib/IiifItems) - Embeds Mirador into Omeka Classic with a built-in annotator, a manifest generator and importer, Simple Pages shortcodes and Exhibit Builder blocks for a rich IIIF-compliant presentation experience.
- [Mirador extension for MediaWiki](https://github.com/a-g-van-hamel-foundation/Mirador/) - offers a parser function to make a build of Mirador 3, including four plugins, available for use in MediaWiki. Developed by CODECS.

## Packages
- [mirador_rails](https://github.com/sul-dlss/mirador_rails) - A Ruby gem useful for including Mirador into Ruby on Rails applications

## Tutorials

- [Tutorial Mirador Viewer](http://heron-net.be/libisplus/themes/LIBIS_PLUS/images/Docs/Tutorial_Mirador.pdf) - PDF explaining how to use many Mirador features. Accessible only after login authentication.

## Implementations

Have a Mirador implementation? Label it with ["mirador"](https://github.com/search?q=topic%3Amirador&type=Repositories)

- [SCTA Mirador Instance](http://mirador.scta.info) (M3) - A Mirador instance dedicated to viewing manuscripts collected and curated by the Scholastic Commentaries and Texts Archive.
- [Archaeology of Reading](http://archaeologyofreading.org/viewer/) (M2) - A Mirador instance for displaying and studying annotations in early printed books.
- [Harvard Art Museums](http://apps.harvardartmuseums.org/mirador/) (M2) - A Mirador instance of random objects in the Harvard Art Museums collection.
- [Harvard Library Viewer](https://iiif.lib.harvard.edu/manifests/view/drs:5981093$9b) (M2) - Mirador is the native viewer for page-turned objects in the Harvard Digital Repository System.
- HarvardX [CellXplorer](https://courses.edx.org/courses/course-v1:HarvardX+MCB64.1x+2T2016/d16e07a5cec442eeb7cd9dfcb695dce0/) (M2) and [The Book: Histories Across Time and Space](https://www.edx.org/book-histories-across-time-space-0).
- [Hacking Mirador Workshop @ Harvard](http://darthcrimson.org/hacking-mirador/) (M2) - Introduce users to IIIF and Mirador and understand Mirador's capabilities.
- [Biblissima Portal](http://biblissima.fr) (M3) - Mirador as an embedded viewer displaying digitized medieval manuscripts and early printed books (either a single item or a collection of items). Mirador as a configurable workspace that gives users the ability to save persistently and share their viewing environment through a permalink.
- Biblissima Demos (use cases focused on manuscripts studies)
  - [Grandes Chroniques de France - Châteauroux BM ms. 5](http://demos.biblissima-condorcet.fr/chateauroux/demo/) (M2) - A slightly customized Mirador instance displaying the virtual reconstruction of the original state of a damaged French medieval manuscript (illuminations cuttings).
  - [Proto-BBMN 1713](http://demos.biblissima-condorcet.fr/bbmn-1713/mirador/) (M2) - A Mirador instance showing a virtual reconstruction of the primitive state of the Bibliotheca bibliothecarum manuscriptorum nova (in 1713).
  - [Codex Florus "dispersus"](http://demos.biblissima-condorcet.fr/florus/florus-dispersus/mirador/) (M2) - A Mirador 2 instance showing the virtual reconstruction of a dispersed manuscript of letters and sermons by Augustine (Paris, Geneva, St. Petersburg).
- [UCLA Digital Library: Flexible Workspace](https://github.com/UCLALibrary/mirador/tree/flexible-workspace) (M2) - A fork of Mirador that replaces the default window layout manager with a more flexible one, allowing for finer-grained positioning and resizing of windows, and for combining windows into groups that can be dragged as one.
  - Demo: https://mirador.library.ucla.edu
- [vHMML](https://www.vhmml.org) (M2) - Mirador as an embedded viewer that provides access to [The Hill Museum & Manuscript Library's](http://hmml.org/) (HMML) digital and microfilm collections. 
- [Art Institute of Chicago](https://www.artic.edu/) (M2) - An in-gallery implementation of Mirador with custom design work and added swipe capabilities. This implementation was designed and developed specifically for an iPad Pro using Kiosk Pro. An example [here](http://media.artic.edu/charleswhite/). Check out our 'inGallery' branch here: [https://github.com/art-institute-of-chicago/mirador](https://github.com/art-institute-of-chicago/mirador).
- [Irish Script on Screen](https://www.isos.dias.ie) (M3) - The largest digital repository of Irish manuscripts by the [School of Celtic Studies](https://www.dias.ie/celt/) at the Dublin Institute for Advanced Studies
