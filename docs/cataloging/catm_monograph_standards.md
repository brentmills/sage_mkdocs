RECOMMENDED STANDARDS FOR BIBLIOGRAPHIC RECORDS – SPECIFIC TO BOOKS (MONOGRAPHS)
Developed by Cataloging Work Team, 2002; rev. 2004; rev. 2007

Notes:	
1) The chief sources of information for each field for book records are listed in AACR2R. The chief source of information for printed monographs is the title page or, if there is no title page, the source from within the publication that is used as a substitute for it.  For printed monographs published without a title page, or without a title page applying to the whole work (as in the case of some editions of the Bible and some bilingual dictionaries), use the part of the item supplying the most complete information, whether this be the cover (excluding a separate book jacket), caption, colophon, running title, or other part.  Specify the part used as a title page substitute in a note.  If no part of the item supplies data that can be used as the basis of the description, take the necessary information from any available source.  If the information traditionally given on the title page is given on facing pages or on pages on successive leaves, with or without repetition, treat those pages as the title page.

The prescribed source(s) of information for each area of the description of printed 
monographs is set out below.  Enclose information taken from outside the prescribed 
source(s) in square brackets.
	AREA					PRESCRIBED SOURCES OF INFORMATION
	Title and statement of responsibility	Title page*
Edition					Title page, other preliminaries, colophon**
Publication, distribution, etc.		Title page, other preliminaries, colophon
		Physical description			The whole publication
	Series					Series title page, monograph title page, 
cover, rest of publication
		Note					Any source
		Standard number & terms of		Any source
			availability
*Title page includes a substitute.
**[Colophon: an inscription placed at the end of a book or manuscript usually with facts relative to its production; an identifying device used by a printer or a publisher]
2) Although shown for clarity, subfield |a sometimes does not show on MARC record in initial instance of use. 
3) Some subfields are repeatable and some are not. Check AACR2R if in doubt.
4) Colon space and Semicolon space precede some fields and are required formatting.  (Refer to note that follows.)
5) In some cataloging utilities subfield delimiters take the place of spaces when shown and additional spaces to meet AACR2R requirements should not be added; in other words, without subfields the space it occupied remains in the visible record.  (This is how the Sage Library System automation handles this and so the examples throughout this document follow this principle, though the punctuation section lists the AACR2R rules.)  OCLC records are an exception: when the subfield delimiters are suppressed in the display they do not leave the space they occupied behind.  
For example, 300 p.:|bill. ;|c25 cm. and  300 p. : |bill. ; |c25 cm. (OCLC) 
would both display as  300 p. : ill. ; 25 cm.  
Check out your own utility to see how they handle this.
6) The symbol | (pipe) represents the subfield delimiter in these standards. In OCLC records you see the symbol $ (dollar sign).
7) If an item is a continuation that is updated regularly (could be annually or more frequently) then attach to a bib with an “open entry” nature (serials, etc., e.g. Fodor’s).  (Refer to “Serials” for additional instructions.)


010	LCCN NUMBER (Optional)
Library of Congress control numbers (LCCN) (formerly called Library of Congress Card Number) are assigned by the Library of Congress and are supposed to be unique.  They are therefore one of the most important match keys when trying to detect duplicate bibliographic records.  However, publishers do not understand that LCCN are supposed to be unique.  They print the same LCCN on different editions of a work, therefore caution should be exercised in using this as a match point.

LCCN’s must be entered “normalized” according to one of the two formats below.  If you are using OCLC, it does the normalization for you.

There are two LCCN structures: structure A for numbers formed from 1898 through 2000, in which the year portion consists of two digits; and structure B for numbers formed beginning in 2001, in which the year portion consists of four digits.

Structure A LCCN “normalization”:
•	a lower case, left-justified, alphabetic prefix to a maximum of three characters or three blank spaces – these prefixes and leading spaces are very important and must be retained
•	two digits meaning the year in which the item was cataloged
•	a six digit, zero-filled, sequential serial number
•	a blank space
•	variable suffixes/alphabetic identifier and revision dates, preceded by slashes
•	total length should be 8 digits (plus any prefixes and/or suffixes)

The number in printed form may look like these:
	85-8191	agr23-452	46-8246 /MN/AC	
The above numbers normalized would look like these (^ represents a blank space):
	|a^^^85008191^	
	|aagr23000452^
	|a^^^46008246^/MN/AC

Structure B LCCN “normalization”:
•	a lower case, left-justified, alphabetic prefix to a maximum of two characters or two spaces
•	four digits meaning the year in which the item was cataloged
•	a six digit, zero-filled, sequential serial number
•	total length should be 10 digits (plus any prefixes)

The number in printed form may look like these:
	n2001-50284		2002-378	my2001-50268
The above numbers normalized would look like these (^ represents a blank space):
	|an^2001050284
	|a^^2002000378
	|amy2001050268
	
020	ISBN NUMBER (Optional)		
An ISBN is a unique number assigned to an item by its publisher.  Each ISBN number is a ten-digit number and has four parts, or a thirteen-digit number and has five parts.  If printed in a book, the four/five parts are separated by hyphens.  Enter without hyphens and add any qualifiers that describe the item.
		|a2214306080
		|a0842270884 (pbk.)
		|a9780545010221

Note:  Although this number is supposed to be unique, it often is not so caution should be exercised in using this as a match point.

040	CATALOGING SOURCE (Required)
Original source of the cataloging data (subfield |a), contributor of cataloging data, and if applicable, the modifier of cataloging data (subfield |d).  Use OCLC or USMARC code that uniquely identifies your location.  (See OCLC code list).  For example:
		|aOXU 
		|aUMT	|dLGRND

092	LOCALLY ASSIGNED DEWEY CALL NUMBER (Insert in item record to display in catalog)
Call numbers based on Dewey Decimal Classification.  

099	LOCALLY FREE-TEXT CALL NUMBER (Insert in item record to display in catalog)
	
100	MAIN ENTRY – PERSONAL NAME (Required if present)
A personal name is the name of the person responsible for the creation of the intellectual or artistic content of an item as prominently displayed.  Use of this field relates to the statement of responsibility as found following title.  For an editor, use Marc tag 700 rather than this tag.  Do not use this tag for a corporation or organization given in statement of responsibility.  Just use title entry instead and trace corporate authors in 710. (Field 110 is used for Corporate Author main entry only if document is internal corporate document.)  It is best to match names to authority files already in use.  To do this, you can search the Sage, Summit or Library of Congress databases using the author search selection for the author listed in item being cataloged.  Then select one record by author and convert to a Marc Tag display.  Fill in spelling and dates given. Use subfield |a for name, subfield |q for expanded name, and subfield |d for date, if available.

This field may be used only once.  Additional authors go in 700 field.

		|aCarroll, Lewis
		|aVan Buren, Martin,|d1850-1900.
		|aWhite, T. H.|q(Terence Hanbury),|d1906-1964.
		|aJohn|bXXXIII,|cPope,|d1881-1963. 

	Punctuation:
Subfield |b is preceded by a space only
subfield |c is preceded by a comma space 
subfield |d is preceded by a comma space
subfield |q is preceded by a space only and placed in parentheses
100 field ends with a mark of punctuation or a closing parenthesis “)”

110 	This field is used for Corporate Author main entry only if document is internal corporate document. To trace a corporate entity otherwise related to the work, generally use 610 field if subject and 710 field if not.
		
245	TITLE STATEMENT (Required)
The title statement is the title proper and may also include a general material designation (form if other than book, i.e. [text (large print)]), subtitle, other title information, and the statement of responsibility (name of author or editor).  If you need to use a general material designation, use subfield |h after subfield |a.  A list of approved designations is included in Attachment 1.

	The first indicator should be 1 if MarcTag 100 (author) is used.  Otherwise use 0.
	For second indicator use 0 if title does not begin with an article.  Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

	For title use subfield |a 
		245 10 |aOrigins
		245 12	|aA field guide to wildflowers
		245 14 |aThe Clan of the Cave Bear
	For general material designation use subfield |h.  
		245 10 |aMathematics|h[kit]
		245 14 |aThe spirit horses|h[text (large print)]
	For the subtitle use |b
		245 00 Records :|bfrom a summer day 

	Note:	Subfield |b follows subfield |h if used

	For statement of responsibility (name of author or editor or corporation) use subfield |c.  
245 14 |aThe life of the mind /|cHannah Arendt.
245 10 |a American gospel|h[text (large print)] :|bGod, the founding fathers, and the making of a nation /|cJon Meacham
		245  00 |aApplication statistics /|cprepared by Research Council of Downstairs
 University ; edited by Russell White.

	Note:  Subfield |c follows subfield |h if used.

Punctuation: 
subfield |b is preceded by space colon space
subfield |c (statement of responsibility) is preceded by space forward-slash space, each subsequent statement of responsibility is preceded by space semicolon space 
subfield |h is preceded by a space only and is enclosed in brackets. 
245 field ends with a period. 

246	VARIANT TITLE (Optional) (prior to 1995, placed in 740 field).
	Examples are caption titles, spine titles, running titles.

        	Punctuation: 
See rules for 245 field. 
No ending punctuation is added to a 246 field. 

250	EDITION STATEMENT (Required if applicable)
Refer to the edition statement proper and any other information up to the imprint.  Use only if the edition statement is self-defining, that is uses words such as edition, issue, version.  Numbers may appear with an edition statement. For items that use revised alone use abbreviation Rev. as in example.  If you are aware that an item is a revision but is not shown in book, you may put Rev. in square brackets per example.  Use subfield |a for edition statement
		|aEd. 1965-66.
		|a1st ed., corr. printing.
		|a3rd impression (with minor revisions).
		|aRev. ed.
		|a[Rev.].
		|a[Book club ed.].

Punctuation:  250 field always ends with a period.

260	PUBLICATION, DISTRIBUTION, IMPRINT (Required)
The imprint statement may include place of publication, publisher, place of distribution, distributor (if given), date of publication, copyright date.  Use square brackets to correct erroneous information or for clarification.  No indicators are assigned.

PLACE OF PUBLICATION
Use subfield |a for place of publication.  Supply the name of the country, or state or province for U.S. or Canadian publishers respectively, if it is considered necessary for identification or distinction and enclose in parentheses if not stated in chief source of information (see Note #1).  Use abbreviations supplied in Attachment 2.
		|aStony Brook, N.Y.
		|aLondon  (Ont).
		|aBelfast [i.e. Dublin] (Ireland)

If two places are recorded, enter each place name in separate subfield |a.  Enter first place given and one place in country of cataloging if they are different. Other places of publication may be omitted. 
	
	|aLondon ;|aNew York

If the probable place of publication cannot be determined, use the abbreviation [S.l.] (which stands for sine loce, without place). 

	|a[S.l.]

The “S” is capitalized because it begins the field.

      	NAME OF PUBLISHER OR DISTRIBUTOR
Give publisher in shortest distinguishing form, omitting generic words such as Co., Inc. or Ltd.

	Use subfield |b for name of publisher or distributor.
		|aNew York :|bWarner
		|aLondon :|bRoyal Geographical Society
	
	If two publishers or distributors are named, enter each name in a separate 
	subfield |b.
		|aNew York :|bAmerican Broadcasting Co. :|bReleased by Xerox Films

If probable publisher or distributor is unknown, use the abbreviation [s.n.] (which stands for sine nominee, without name).

		|aMontreal :|b[s.n.]

DATE
Use the publishing date and/or copyright date on the title or preliminary pages.  If there is more than a year’s difference between publishing and copyright date, both need to be added to the record, newest date first. Avoid using the printing date, which is used only in the complete absence of any other data or guess.    

            Use subfield |c for date of publication
		|aSanta Ana, Calif. :|bDoubleday Multimedia,|c1973.
		|aLondon :|bMethuen,|c1976-

If date is estimated or deduced, place in square brackets with ? if guess and no ? if certain
|c[1990?]
		|c[1973]

	Enter multiple dates in the same subfield |c, separated by a comma space
		|c1967, c1965
		
	Note:  small c precedes a copyright date, not to be confused with subfield |c.	

Punctuation:
within 260 subfield |a (place of publication), space semicolon space precedes a second place name in a separate subfield |a
space colon space precedes each subfield |b (publisher)
comma space precedes subfield |c (date) 
end 260 subfield |c with a period, unless another mark of  punctuation (such as a bracket or hyphen) is present

300	PHYSICAL DESCRIPTION OF THE ITEM (Required)
Use subfield |a for pagination. Enter data in terms of paging and/or number of volumes.  Pagination includes last printed page number in book.  Do not count any additional unnumbered pages, unless they contain material mentioned in subfield |b, such as maps.  If no pages are numbered, you may count and put number in brackets [35] p., estimate number of pages and precede number with ca. (for circa) or state (unpaged) in parentheses after number of unpaged volumes. If Arabic numbered pages begin with 1 and are preceded by Roman numbered pages, list both sequentially, otherwise ignore Roman numbered pages.

		|a327 p.
		|a3 v.
		|a329 p., [4] leaves :|bmaps
		|a[35] p.
		|aca. 600 p.
		|a1 v. (unpaged)  
		|a1 v. (various paging) 
		|axviii, 323 p.

	Use subfield |b for other physical details as follows:

		|axi, 423 p. :|bill., maps, ports.

These refer to abbreviations for illustrations, maps and portraits. Other allowable designations are listed in AACR2.  Do not make any up.
		
You may use col. to qualify any of above that are in color. If partially in color, follow designation with notation: (some col.)
	
	|avi, 221 p. :|bcol. ill.
		|a42 p. :|bill. maps (some col.)
	
Use subfield |c for dimensions, the size of the item such as height.  This is 	measured in centimeters to the next whole centimeter up (e.g. if an item measures 17.2 centimeters, give as 18 cm.)  Any item that is wider than the height needs to have both dimensions with height listed first. 

		|a327 p. ;|c18 cm. 
		|axvi, 243 p. :|bill. ;|c10 x 12 cm. 
 
Note: If cataloging using CIP (Cataloging in Publication) record from LC, you must fill in the physical description area and change 8 in the leader to a blank space [or in SuperCat to a . (period)].  (Refer to “Updating CIP Records” for additional instructions.)

Punctuation:  
	space colon space precedes subfield |b
	space semicolon space precedes subfield |c
	end 300 field with a period (usually already present) 

440	SERIES STATEMENT  (Required if applicable)
Use for series statements to be traced by a series title.  A tracing refers to an access point in the catalog for the series title.  Look in Sage, Summit or Library of Congress databases under title to check for the correct form of the tracing (the authority record).  

(If you choose not to trace a series statement or to trace it differently use tag 490. A 490 tag is used if series author is listed or if entire series is known to be by the author of the book in hand.)

Use 440 tag if series does not list an exclusive author, e.g. the series is a publisher’s series and the series statement transcribed exactly as given on the resource matches the Library of Congress Authority file exactly..

	The first indicator is blank. 
	
For second indicator use 0 if title does not begin with an article.  Use 1-9 to 	indicate an article, plus spaces, punctuation, diacritics and underscores that 	precede the first significant word.  

	Subfield |a contains the title portion of the series exclusive of any name, number of parts, volume numbering and ISSN.
		440  4	|aThe search series

Use subfield |v for the volume number or other sequential designations used in conjunction with the series statement.  Use the 642 field in the Authority record to determine the format, ie: no.1 or #1
		|aThis is America ;|vno. 1

	Use subfield |x for ISSN number if available.  Subfield |x precedes subfield |v if present
	|aEarth Science series,|x4522-1277 ;|vv. 12

490	SERIES STATEMENT (Required if applicable)
Use 490 first indicator 0 if you do not trace; 490 first indicator 1 if you trace
differently.  If you use a 490 1, an 800 field for the correct form of the tracing is required.  

	A first indicator of 0 indicates a series not traced.
	Use subfield |a for author or title.
		490 0  |aNonesuch geographical studies

	Use indicator 1 if series traced by author.  Then add Marc Tag 800 per example that follows:
		490 1  |aGellerman effective supervision studies
	 	800 1  |aGellerman, Paul.|tGellerman effective supervision studies ;|vno. 12.

Punctuation:  
No ending punctuation is added to 440 or 490 fields.
440 or 490 subfield |v is always preceded by space semicolon space
440 or 490 subfield |x is always preceded by a comma space

500	GENERAL NOTES (If Needed)
General notes are notes for bibliographic data not present elsewhere in the record or information that is present elsewhere but must be repeated in field 500 to provide an intelligible note.   May be used for informal contents note.  General notes include: bibliographic history of the work, translation notes, enhancements to the physical description, program notes. A note must be added to identify source of a tracing if not otherwise in record.

Examples:
	|aBased on the screenplay: All my sons.
		|aSubtitle varies.
		|aOriginally issued in series : Sound effects.
		|aDescription based on: Vol., 3, no. 3 (May/June 1975).
		|aFor string quartet.
		|aTitle supplied from data abstract by producer.
		|aReprint of  2nd ed.
		|aAbridged.
		|a“Uncorrected proof”—cover
		|a“Advanced reader” —cover

	Punctuation:  Always end field with a period.

504	BIBLIOGRAPHY NOTE (If needed)
Note about bibliography, discography, filmography, and/or other bibliographic references in an item.
	
Examples:
		|aIncludes bibliography.
		|aIncludes bibliographical references and index.
		|aDiscography: p. 150-152.

	Punctuation:  Always end field with a period.

505	CONTENTS NOTE (Optional)
Contents notes contain titles of separate works or parts of an item.  They may also include statements of responsibility associated with the works or parts of an item.  Volume numbers and other sequential designations are included in the note, but chapter numbers are omitted.  Use for analytical titles of independent works contained within the items and for titles of related items. This note may also contain statements of responsibility

The first indicator is used to indicate type of contents note.  Use 0 for full contents.  Use 2 for partial contents.  Indicator 1 is used for incomplete contents, i.e., when all parts of a set are not published yet.  

Use subfield |a for formatted contents note.  When all information is in subfield |a, the second indicator is blank.
 	
505 2   |aTaxman -- Eleanor Rigby -- Love you to -- Here, there and everywhere -- Yellow Submarine -- She said she said -- Good day sunshine.
	
If statement of responsibility is included in subfield |a it is preceded by a space / space whenever it occurs:

505 2   |aThe big sleep / Raymond Chandler -- The Maltese falcon / Dashiell Hammett -- Dead pool / Ross MacDonald.

If subfields other than |a are used, the second indicator is 0 to indicate enhanced contents.

subfield |t for title entries; subfield |r for statement of responsibility; subfield |g 
for miscellaneous information.  Any or all may be used. These subfields are repeatable.

505  0  |tThe fourth millennium /|rHenry Brant|g(9:00) --|tMusic for brass quintet /|rPhilip Glass.

505  0  |tBig sleep --|tMaltese falcon --|tDead pool.
	
	Note: second space is omitted after dashes when a subfield code follows 
(i.e. subfield takes the place of the space).  See Note #5 at beginning of manual.

Punctuation:  
space hyphen hyphen space ( -- ) is entered between each item 
statements of responsibility are preceded by space forward slash space ( / )
end field with a period or other ending punctuation or > (angle bracket), but period after closing ] or ) – [but if note is incomplete or continues in the following 505 then none, unless the last word ends with its own punctuation]
refer to AACR2 for punctuation for use of subfields |t, |r, and |g

526	STUDY PROGRAM INFORMATION NOTE (Optional)
This field contains information about any study program(s) which use the work that is described by the record.  The field is repeatable.
	First indicator 0 is for reading program; second indicator is blank
		|a Program name
		|b Interest level – assigned by the study program
		|c Reading level - assigned by the study program
		|d Title point value - assigned by the study program
		|5 Institution to which field applies

		526 0_ |aAccelerated Reader|b5.0|c4.0|d75.|5OMS

Punctuation:  
This field ends with a period unless another mark of punctuation is present.  If the final subfield is subfield |5, the mark of punctuation precedes that subfield.


586	AWARDS NOTE  (Optional)
	This field contains information on awards associated with the described item.
	The field is repeated for each occurrence of an award.

The first indicator contains a value that controls the generation of a display constant preceding the note (a blank is used to generate the display constant Awards:, an 8 specifies no display constant is generated).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the awards note.
	
	Punctuation:
No ending punctuation is added to 586 fields.

6XX    SUBJECT HEADINGS (At least one subject heading is required for non-fiction.)  

600	SUBJECT ADDED ENTRY-PERSONAL NAME
Use for personal names used as subject added entries such as:  names of persons who actually or probably lived, personal author/title subject added entries, and names of families. For example use for Burbank, Luther or Sacagawea.

	The first indicator is 1 for a single surname and 3 for a family name  The second 		indicator refers to subject authority on which you base the subject entry.  Use 0 for
      Library of Congress (LC) subject headings. 

This Marc tag needs to follow LC standards. Try finding a match from the Sage, Summit or Library of Congress databases. Enter names selected in the subject search in database. Try different selections until you find a possible fit.  Another way is to identify another book by the same author that has already been cataloged.  Look in the cataloged record for possible Subject Heading-Personal Name that would fit. When you have chosen a match, convert the catalog entry to a Marc Record. Enter into tag 600 exactly as you view in Marc format with the same indicators, and subfields.

650     SUBJECT ADDED ENTRY – TOPICAL TERM
Use for topical subject entry assigned by LC or assigned by an agency based on LC or LC Annotated Card Program (Subject Headings for Children’s Literature).  This Marc tag needs to follow LC standards. Try finding a match from the Sage, Summit or Library of Congress databases. Enter words related to the subject of the book with the Subject search.  Try different words till you find a fit.  Another way is to identify another book by the same author that is similar in content and has already been cataloged.  Search for title and see if subject headings used will fit your item.  Convert chosen record to Marc Record.  Enter Marc tag indicator numbers and subfields exactly as you view them.  

651	SUBJECT ADDED ENTRY – GEOGRAPHIC NAME
Use for geographic subject entries actually assigned by Library of Congress Subject Headings.  This would include place names such as Yellowstone National Park or Portland (Or.).  As above, would suggest searching Sage, Summit or Library of Congress databases. Search under Subject for geographic names.  If you find suitable subject entry, convert the entry to Marc Record and copy the indicators and subfields exactly as found.  

Punctuation: 
A period is placed at the end of the last subfield, unless it ends with a hyphen or parenthesis.
(The dashes normally shown preceding subfields v, x, y, and z are not carried in a MARC record. They are inserted by computer programs for public display of record.)

655	GENRE/FORM INDEX TERM (Optional)
This field contains a term indicating the genre, form or physical characteristic of a resource (what a resource is about).
First indicator is typically left blank; second indicator
Use 4 if the source is not specified (including local headings)
		655 _4 |aOregon authors.
Use 7 if the source is specified in |2
		655 _7 |aSuspense fiction.|2gsafd

Punctuation:  
Subfield |a is preceded by a period 

	
700	ADDED ENTRY – PERSONAL NAME  (Added title optional)
Make an added personal name entry under the heading for a prominently named editor or compiler of monographic work.  Make an added personal name entry for an illustrator if the illustrations are considered to be an important feature of the work.  Make an added personal name entry for any other name that would provide an important access point not treated in another entry. It is best to match names to authority files already in use.  To do this, you can search the Sage, Summit, or Library of Congress databases. Using the author search selection choose the individual listed in item being cataloged.  Convert selected record to Marc Record and follow spelling and dates given there to fill in this Marc tag. 
	
For first indicator, use 0 for a recognized forename such as Plato.  Use 1 for usual surname entries.  Use second indicator if adding a title, using 2.
	
Use subfield |a for name and use subfield |d for dates if known
	700 1	|aHemingway, Ernest,|d1899-1961.
	700 0	|aHomer.
		
Use subfield |t to add a title to this field which will be traced by author in the database.    
	700 12  |aBeethoven, Ludwig van,|d1770-1827.|tC major symphony.

Punctuation:  End field with a period.

740	TITLE ADDED ENTRY (Optional)
Variant titles appear in field 246.
Use for tracing specific titles in 505 contents note.
Use for titles recorded in 245 subfield |b if desired.

Punctuation:  End field with a period unless other form of punctuation is present.

800	SERIES ADDED ENTRY – PERSONAL NAME/TITLE (Required if 490 1  field present)
This field is used when all books in a series are written by the same author.	
Follow all rules for entry of author in 100 field.
Title is added in subfield |t.  (It will be traced in online catalog).
If volume number is present it is added in subfield |v.

800 1  |aGellerman, Paul.|tGellerman effective supervision studies ;|vno. 12.

Punctuation:  
Subfield |t is preceded by a period space.
Subfield |v is preceded by space semicolon space.
Field ends with a period.

9XX	LOCAL USE TAGS
Check with Sage System staff if you choose to use any of these fields. 

Use the following for tagging incomplete bib records.
999   |aFLAGGED

