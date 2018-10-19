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

I'm very new to Github so I'm only vaguely aware of all its features, all these merges, commits, and branches. Will gradually learn as I go along.
