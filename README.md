# TPEN-static
This repo is designed as an intermediate cache for users' files that would otherwise be generated dynamically. The 
existence of the document in RERUM (store.rerum.io) does not mean it cannot be here as well, but this is designed 
for the more assembled documents in the TPEN API.

## File types
The expectation of these files is that common exported or viewed documents will be included here:

* JSON(-LD): Project info, project as Manifest, and fully embedded Annotation Collections and Pages
* HTML: Viewers of projects, snips of annotations
* TXT: Strings and String arrays of transcriptions
* XML: Potential structured document output of project
* PDF: Generated exports from an internal tool, prepared for the user

## Structure
This repo follows the old user images structure for user projects. At the root are the directories for individual 
projects as id hash or project stub (if defined). The file name will be constructed from what it actually is.

Examples: 
* `/423f23ee23b599d0/manifest.jsonld` IIIF Manifest derivative for viewers
* `/nocap-slug/f-12v.txt` Text blob for page label "f-12v" in the project with "nocap-slug" as a slug

This designed only to be written to programmatically and updated by replacement when the modification is
requested by the user request or by internal trigger.
