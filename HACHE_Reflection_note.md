
# Reflection note

In Assignment 1, the structure defined in my DTD was very limited. The whole encoding project was contained in a parent element called "Myletters", whose children element "letter" identified each letter, and contained the whole encoding of each one. The encoding was only composed by elements dedicated to the author and the destination of the letters, by a "body" element which aimed at containing the different paragraphs of the text, and by elements linked to the informations that appear at the end of the letters, such as the place and the date where they were written. At the end, the "url" element aimed at containing the link of the sources.  

The TEI_all encoding project permitted me to go further in the encoding and analysis of the texts, and it can be noticed through three points. 
Firstly, the TEIHeader contains sources' metadata, which was not really possible in my DTD. For instance, the element "biblStruct" can be used to distinguish the different editions of the books used in the project. 
Secondly, we can use, with TEI_all, a specific structure dedicated to the encoding of letters. Indeed, thanks to the attribute "type", in the element "div", we can specify that the text is a letter, and it allows us to use elements in keeping with this type of text. For instance, I used "opener" to encode the informations above the text, such as the author or the destination, and I used "dateline" for the descriptions of place and date in each letter. 
Lastly, TEI_all provided elements, such as "listPerson" or "listPlace", which send back to clarifications concerning the people and places mentioned in the sources. It is particularly useful in these texts, in which there are lots of characters' names mentioned, and lots of places involved. Therefore, I used these two elements to add precisions about the most famous characters, and the places involved in the letters. 

However, I wonder if I could use a customized schema only dedicated to the encoding of letters, because the TEI_all was not always fluid for this type of text. 
