# ISKCON Thailand website files

seqC.txt is a sequence of chapters
seqV.txt is a sequence of verses

The last html file, either verse or chapter, points to the first verse or chapter as "next" and the first points to the last as "previous".

If verse numbers have dashes in them, like 1/16-18, then script producing html copies this file into index.html under 1/16, 1/17, and 1/18 in addition to 1/16-18 itself. All four files are identical and have 1/15 as "previous" and 1/19 as "next". They are created so that people manually typing verse numbers in the url always get something instead of "page not found" errors. 

These errors can be avoided with redirects, of course, but why process it on the fly and wait for results if we can have two-three small static files instead.

code2style.txt is a map of @codes in the main th-bg-original.txt to styles in vedabase.css. Some of them look exactly the same and do not make any apparent difference.

Second group in the same file is my proposal how to rename these styles in the new css. It follows "class,tag" format and it's only a starting point - there could be more classes needed to cover various weird cases. There are more classes in vedabase.css so they might be needed for something.
