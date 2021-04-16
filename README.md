# rmarkdown_presentation

I'm trying to set up a custom powerpoint template that works with RMarkdown nicely. 

The file wlu_slide_template.pptx works very nicely, except for the fact that the footers and the date and slide number fields at the bottom of each slide are *extremely* sensitive. 
Right now, I've hidden them putting them behind pictures and logos in the file, and setting the font color to be white. However, I'd like to learn why just touching the those boxes produces this error on compilation that says 

```PowerPoint found a problem with content in this_works_doesnt_work_after_touching_footers.pptx.
PowerPoint can attempt to repair the presentation.

If you trust the source of this presentation, click Repair.```

You can see the results by opening the file `this_doesnt_work_after_touching_footers.Rmd`. Notice that that file uses a different poiwerpoint template, i.e. one where I've modified the footers!

