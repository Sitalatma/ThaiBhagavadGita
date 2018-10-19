# ThaiBhagavadGita

There are several text files here:

th-bg-original.txt should be the exact copy of the existing book with minimal changes - corrected wrongly split paragraphs etc.

th-bg-template.txt is the main file for proofreading and editing. It contains Thai translations but Sanskrit words are left in English. When editing these words can be deleted or edited or new ones added when necessary but they should all contain correct Sanskrit-English transliteration for automatic processing.

th-bg-translitPali.txt is automatically transliterated "template" file above. Automatic transliteration using the method in the existing book is in the works. It will be called "th-bg-translitThai.txt". Any new transliteration method will be added in the same way. 

When that is done I'll upload Perl scripts as well so that other people can automate this process on their own computers.

There's also "www" directory which contains all the files for the website (with Pali-Sanskrit transliteration). They were created automatically from "th-bg-translitPali.txt". 

Within that "www" directory there's directory "0", it contains all the files for the same website but with transliteration method used in the existing book. It was automatically created from "th-bg-original.txt". 

Both websites rely on "vedabase.css" to display properly. It's included but needs to be placed correctly relative to the website - look inside html code to see where it should be on your computer.

Whoever wants to work on this can copy this repository and start his own or ask me for admin/editing rights to this one. I'm very new to Github so I'm only vaguely aware of all its features, will gradually learn as needed.
