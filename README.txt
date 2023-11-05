----------------------------------------------------
	Package:	affilauthor
	Author:		Selvam P.
	Mail:		selvamittex@gmail.com
	Licence: 	Released under the LaTeX Project Public License v1.3c or later, 
				see http://www.latex-project.org/lppl.txt					 
----------------------------------------------------

Customized fields(key-value style) to tag the author and affiliation informations in a structured format. Each field has a specific name within \author and \affil commands similar to bib format. We can customize the styles as per preferences for article.cls class layout. Instead of giving all information(author and affiliation) in single tag, we can split the information in a format of key-value style. 

Sample author tag:

\author
  {
    name={Author name},
    mail={author@gmail.com},
    phone={+111-222-33},
    affil={af1},
    note={Greeting to everyone}    
  }
  
Sample affiliation tag:

\affil
  {
    id = {af1},    
    div = {Department of Computer Science},    
    org = {University},    
    street = {1st cross street},    
    country = {India}    
  }
  
Sample formating tag:

\affilstyle
  {
    authfont = {\sf},
    affilfont = {\sf\small},
    mailfont = {\tt\small},
    urlfont = {\tt\small},
    phonefont = {\tt\small},
    notefont = {\tt\tiny},       
    notenum = { alpha },
    authspace = {\baselineskip},    
    affilspace = {\baselineskip}
  } 