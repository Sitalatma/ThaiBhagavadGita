# ThaiBhagavadGita

There are several text files here:

en-bg.txt is the text of Bhagavad Gita in English. It's formatted for easy import into Vedabase and I followed the same formatting rules for all other files as well. 

th-bg-original.txt should be the exact copy of the existing Thai book with minimal changes - corrected wrongly split paragraphs etc.

th-bg-template.txt is the main file for proofreading and editing. It contains Thai translations but Sanskrit words are left in English. When editing these words can be deleted or edited or new ones added when necessary but they should all contain correct Sanskrit-English transliteration for automatic processing.

th-bg-translitPali.txt is automatically transliterated from the "template" file above. Automatic transliteration using the method in the existing book is being prepared and when I'm done it will be called "th-bg-translitThai.txt". Any new transliteration method will be added in the same way. 

When that is done I'll upload Perl scripts as well so that other people can automate this process on their own computers.

There's also "www" directory which contains all the files for the website (with Pali-Sanskrit transliteration). They were created automatically from "th-bg-translitPali.txt". 

Within that "www" directory there's directory "0", it contains all the files for the same website but with transliteration method used in the existing book. It was automatically created from "th-bg-original.txt". 

Both websites rely on "vedabase.css" to display properly. It's included but needs to be placed correctly relative to the website's root - look inside html code to see where it should be on your computer.

Both websites can be viewed on

https://sitalatma.github.io/bg

and

https://sitalatma.github.io/bg0

Whoever wants to work on this can copy this repository and start his own or ask me for admin/editing rights to this one or download files and use them in any Krishna conscious way. As an example, I'm making daily Bhagavad Gita quotes:

https://www.facebook.com/Thai-Bhagavad-Gita-Quotes-2100478970266576/

Please, find some use for this text. In digital form it's very easy to share. 

BBT devotees can start editing or proofreading with th-bg-template.txt. Or they can look into ways of creating an ebook. Amazon has this webstie with instructions on how to turn text into an ebook, even a paperback, all for free:

https://kdp.amazon.com/en_US/

There's also "ITweb" folder which containes files for ISKCON Thailand Website with its own readme there.

The folder named "html" contains plain html files - "full.html" has the entire Bhagavad Gita in it but it's too large to be processed easily. There's "index.html" file instead which contains the first chapter. This "index.html" then has been converted to "index.epub" and "index.pdf" to demonstrate that, in principle, it's possible to generate e-books and even actual books from the original text file automatically. I used html as intermediary format between text and .pdf and .epub. 

When BBT decides on a particular software to be used for book production these files can be tweaked so that working on final presentation is kept to the minimum and does not affect the actual text content of the book, which is an important principle - separation of content from presentation.

If this principle is not followed then lots of problems will pop up later on, like inability to manage several output formats at once - because changing one little comma in one place would require manually changing it in several other places and not forgetting anything. This snowballs very fast if the entire editing is done in InDesign, for example. It would be hard to copy paste text from one application to another, too - word (or rather sentence) breaks will present a particular problem for Thai language. As of now, I have no way to say whether current breaks in the existing text files are correct or not. Most of the time new line in the printed book means continuation of the previous sentence but sometimes it isn't and these cases cannot be caught programmatically because in InDesign they all look the same. This wouldn't be a problem if text is created in text file first and wrapping up long lines is done by the viewing software - browsers, text editors, even InDesign itself. If you are reading this on the computer, then this paragraph is over 1,000 characters long but it has been wrapped up without me manually inserting line breaks anywhere.



I'm very new to Github so I'm only vaguely aware of all its features, all these merges, commits, and branches. Will gradually learn as I go along.
