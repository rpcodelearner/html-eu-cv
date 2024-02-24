# html-eu-cv
European Style Curriculum Vitae (Résumé) Template, in HTML+CSS

## Motivation
Different aspects of your CV may be more or less relevant to different prospective employers, or to employers in differect sectors. Maintaining different versions of your CV becomes burdensome if you need to compare versions tailored to different purposes.
An obvious approach would be to maintain a ver comprehensive master CV, and then remove parts unrelevant to each prospective employer to create a customized copy. However, this approach may not work for you, for example if you needs to rephrase entire sentences.
Since HTML source is textual, comparison of different versions should be easy, at least for the coding-inclined person.

## How-To
### If you know a lot about HTML and CSS
You probably know *more* than I do, so skip the rest, download the files and use them as you prefer. To compare different version, use a file comparison tools.
### If you know just a little about HTML and CSS
That little you know about HTML is probably enough to make use of the template. Download the **html** and **.css** into the same directory, edit the **.html** file, replacing the default values with your details and duplicating HTML elements as required. As others before me, I recommend keeping styling issues to the **.css** file as much as practical.
When you are done, my idea was that one would *print* the result to a PDF file.
To compare different versions of your CV, you a [file comparison tool](https://en.wikipedia.org/wiki/File_comparison) is very useful. I am not recommending any in particular, but since the task is not very complex, you won't need a sophisticated tool. Use it to compare the **.html** files as text files.
### If you don't know anything at all about HTML
Well... I didn't really expect you to come here. That said, what follows is a short guide to make use of the template. It should give you the gist of how to proceed, but to avoid getting lost you should really learn at least some HTML (several tutorials can be found on the Internet, some are good and easy to follow).  
Begin with downloading the **.css** file and the **.html** file in a directory (aka "folder") of your choice. You can rename the **.html** file but don't rename the **.css** file. Basically, the **.css** file includes styling information, like the thickness and colour of lines, font to use for each item and so on. Leave it alone for now: you need to be better at HTML+CSS to make changes there. Also, remember to keep the two files in the same directory, because the **.html** file includes a reference to the **.css** file.  
Open the **.html** in a *text* editor, even a simple one. You will notice several... *things* that look like `<h2>Personal Information</h2>`, or `<td class="...">0, Empty Str., Noname City</td>`. Those are "HTML elements." **Do not touch** the text between angular brackets (`h2` or `td class=...` in the previous example); those are meaningful to your browser and other apps that interpret HTML. Focus instead on the content that looks meaningful to you: those are the parts that will show up in the rendered result.  
To see what I mean, keep the text editor open, but also open the **.html** file in a browser: you will recognize the same words.  
Try some editing in the text editor, for example change the address from "0, Empty Str., Noname City" to something else, save the file (no need to exit the text editor) and refresh the browser: you should see the updated address. Going on like this you should be able to modify all the parts already there.
However, sooner or later you will have to *add* items to the template, for example to add your skills, since the template only contains an example.
To add a line in a table. Look for something like the following, just above the place where  
`<tr>`  
`   <td class="...">role</td>`  
`   <td class="...">developer</td>`  
`</tr>`  
Then duplicate *the entire block* - from 4 rows to 8 rows - and modify accordingly. The above action will duplicate *a single line*. If you need to insert a whole new table, e.g. to describe a past placement, you will have to duplicate an entire table: copy everything between `<table> ... </table>`, including the two delimiters, paste it where you need it, and modify it.  
When you are done, and your CV looks OK as rendered in the browser, my suggestion is to *print* it to PDF, which means the browser will *pretend* to print, and it will actually save the result in a **.pdf** file of your choice.
