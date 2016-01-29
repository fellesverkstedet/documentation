
# Fellesverkstedet documentation guide

This is a guide for documentation at [Fellesverkstedet.no](http://fellesverkstedet.no),
with a focus on internal R&D projects.
It specifies *why documentation is important*, *what to document*, and *how to* do it.
It is a living draft, reflecting our current established practices.

If you just want to see our existing projects,
check out the Open Source section on [our website](http://fellesverkstedet.no/#open-source),
and our [Github](https://github.com/fellesverkstedet) organization.

## Motivation

Documentation serves multiple, complimentary purposes.

Awareness
Possibilities
Inspiration
Marketing, PR
Tips & Tricks, Best pratices

## What to document

One-offs versus generally-useful parts

## How to


### While you work

* Take pictures.
Most important is the finished part,
but in-progress/process photographs are always nice to have.
Use smartphone, or borrow camera from office.
* Take notes.
Learned something new in the process?
Something that did not work out as expected?
Got any ideas for further work?

### Complete documentation

Update the git repository under Fellesverkstedet [Github organization](https://github.com/fellesverkstedet).
For access, create your own Github user, then send your username to `Jon` or `Hans Christian` so they can invite you.
You must confirm the organization invite via email, then you can be added to either the `Members` or `Friends` team.

The Github repo should include:

- Project source files: `Sketchup`/`Rhino`/`FreeCAD`/`Illustator`/`Inkscape`/`Blender`/etc
- Exported cutsheet geometry. As `.DXF` file(s)
- 3d-model for visualization. As `.STL` file
- (optional) 3d-model for general reuse. As `.STEP`
- (optional) Toolpath/CAM project: VCarve .vcr

When you have added the files, include links to them in the `README.md` (using Markdown).
You can edit this with text editor, or use the online editor on Github.com.
To use the online editor, go to the project repository,
click README.md in webinterface, then the edit button on top.
It is nice because it has `Preview` feature, so it is easy to check.
When you're done with your changes in online editor,
add a description of changes (below edit field) to make a commit.

Add/update section on fellesverkstedet.no,
under ["Open Source"]((http://fellesverkstedet.no/#open-source)).
Currently only `Graham` can access.

### Spread the word

* Make a new post on Fellesverkstedet [Facebook page](https://www.facebook.com/fellesverkstedet/).
Include a picture, short description and *link to Fellesverkstedet.no and Github repo* for more details.
Ask `Graham` for access.
* Re-share the Fellesverkstedet FB post to the relevant groups, and on your personal feed.
Ask the people who contributed to project to do the same.
Examples can include: *Norske Skapere*, *Bitraf*, *Nordic Fablabs*, *CNC Users*.
* Upload the part(s) to Fellesverkstedet [Thingiverse account](http://www.thingiverse.com/fellesverkstedet/about).
Ask `Hans Christian` for access.
* Upload the part(s) to [GrabCAD user](https://grabcad.com/felles.verkstedet-1).
Put a copy of the basic project/part description, and *link to Github* for more details.
Ask `Hans Christian` for access.
* (optional) Upload the part to [Sketchup 3D Warehouse]() Fellesverkstedet account.
Mostly if it was made in Sketchup, but you should
Ask `Hans Christian` for access.


## Ideas

Ideas for how to improve our documentation process.
Both for R&D / internal purposes and for our user projects.

* Make a 'documentation station' at Fellesverkstedet.
Would contain all tools needed for documentation: a camera, computer.
Dedicating some physical space to the purpose also serves to raise it on the daily awareness.
Camera could be WiFi-enabled and automatically upload the images to docstation computer.
Also provide a photobox/lightbox, to help take nice pictures?
Challenge is big-ish things, which are quite common.
Could eventually have some screens that one can set up?
Maybe instead of basing on a desktop/laptop, use a tablet with docking station.
Benefits: Camera built-in, and is portable.
* Include some documentation items as part of the workshop rental agreement that users have.
A minimum could be couple of pictures, and 5-10 lines of description text.
If we ask people to use the docstation to do this before they leave, less likely to get forgotten.
Possible workflows: Send an email to `documentation@fellesverkstedet.no`, or put images+text in a specific folder.
Automatically extracts the content, builds a webpage and publishes it (possibly not indexed by default?).
Users can enter their own email, and will then be sent a (view) link to the webpage,
and an edit-link in case they want to add more information later. Like picture of the piece in its natural habitat.
Webpage should have proper meta-tags for social services. And email/webpage could include social sharing links.
Such a system should be built to be easily reusable, for adoptation across fablabs/makerspaces of the world.
Could also have one setup at Bitraf, to test/ensure it works across different settings.
* Make a gallery/display area, showing off existing works.

## Related

* QR-enabled [description tags](https://github.com/jonnor/projects/tree/master/displaycase#qr-description-tags)
for linking physical objects to online documentation.
Could be used in gallery. System could automatically create these. Docstation would have printer to make these easily.
Nice with some 'Made at Fellesverkstedet' branding on the template.

