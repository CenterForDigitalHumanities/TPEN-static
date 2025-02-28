This directory contains the following project and transcription artifacts

- 1 TPEN3 Project
- 1 Group of Users
- 3 Distinct Users with different roles
- 1 IIIF Manifest that is a good use case for Transcription (inbound and outbound).
- 2 IIIF Canvases each using 1 public IIIF Fixture Image.  The Canvases are included for resolvability.  
- 2 W3C Annotation Collections (TPEN3 Layers).  One for Transcription, one for Translation.
- 4 W3C Annotation Pages (TPEN3 Pages).  2 pages of transcribed text, 2 pages of translated text. (inbound and outbound)
- 8 W3C Annotations (TPEN3 Lines).  Two lines per page. (inbound and outbound)

This project is an example of a TPEN Transcription project.  It has multiple Layers, Pages, and Lines one must render and navigate through.  You can load the [manifest.json](https://static.t-pen.org/transcription-project/manifest.json) link in your preferred IIIF viewer.

The Manifest, Canvases, Annotation Collections, Annotation Pages, and Annotations are included as discrete objects and are individually resolvable.  In some cases objects are referenced as opposed to embedded.  Ex. https://static.t-pen.org/transcription-project/transcription-layer.json.  It is assumed that the Annotations sent in are processed and preserved so they can be presented on the way out.
  