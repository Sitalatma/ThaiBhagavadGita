# ISKCON Thailand website files

seqC.txt is a sequence of chapters

seqV.txt is a sequence of verses

The last html file, either verse or chapter, points to the first verse or chapter as "next" and the first points to the last as "previous".

If verse numbers have dashes in them, like 1/16-18, then script producing html copies this file into index.html under 1/16, 1/17, and 1/18 in addition to 1/16-18 itself. All four files are identical and have 1/15 as "previous" and 1/19 as "next". They are created so that people manually typing verse numbers in the url always get something instead of "page not found" errors. 

These errors can be avoided with redirects, of course, but why process it on the fly and wait for results if we can have two-three small static files instead.

code2style.txt is a map of @codes in the main th-bg-original.txt to styles in vedabase.css. Some of them look exactly the same and do not make any apparent difference.

Second group in code2style.txt is what is used for current conversion into html. First value is a class name corresponding to classes in "it.css" (in "it" directory) and second value is tag. When this tag is absent my script automatically creates a <div> element. 

In the "it" directory there are chapter and verse files and it.css that goes with them. They look more or less okay already and include header and footer that obviously need to be replaced. I can generate same files without header and footer but they won't work in the browser anymore. As it is, the directory can be copied and then browsed locally.
