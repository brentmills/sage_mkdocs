RECOMMENDED STANDARDS FOR BIBLIOGRAPHIC RECORDS – SPECIFIC TO SOUND RECORDINGS
Developed by Cataloging Committee, 2004

Notes:	
1) The chief sources of information for each field for sound recordings records are listed in AACR2R. The chief source of information for each major type of sound recording  is set out here. 
		TYPE					CHIEF SOURCE
		Disc					Disc and label*
Tape (open reel-to-reel)		Reel and label
Tape cassette				Cassette and label
Tape cartridge				Cartridge and label
Roll					Label
*Label means any permanently affixed paper, plastic, etc. label as opposed to the container itself, which may have data embossed or printed on it.
Treat accompanying textual material or a container as the chief source of information if
it furnishes a collective title and the parts themselves and their labels do not.  In this 
case make a note indicating the chief source of information.  If information is not 
available from the chief source, take it from the following sources (in order of 
preference):
accompanying textual material
container (e.g. sleeve, box)
other sources
Prefer textual data to sound data.  For example, if a sound disc has a label and also 
information presented in sound form on the disc, prefer the label information. 

The prescribed source(s) of information for each area of the description of sound 
recordings is set out below.  Enclose information taken from outside the prescribed 
source(s) in square brackets.
	AREA					PRESCRIBED SOURCES OF INFORMATION
	Title and statement of responsibility	Chief source of information
	Edition					Chief source of information, accompanying
textual material, container
	Publication, distribution, etc.		Chief source of information, accompanying
textual material, container
		Physical description			Any source
	Series					Chief source of information, accompanying
textual material, container
		Note					Any source
		Standard number & terms of		Any source
			availability
2) Although shown for clarity, subfield |a sometimes does not show on MARC record in initial instance of use. 
3) Some subfields are repeatable and some are not. Check AACR2R if in doubt.
 
4) Colon space and Semicolon space precede some fields and are required formatting.
5) In some cataloging utilities subfield delimiters take the place of spaces when shown and additional spaces to meet AACR2R requirements should not be added; in other words, without subfields the space it occupied remains in the visible record.  (This is how the Pioneer Library System automation handles this and so the examples throughout this document follow this principle.)  OCLC records are an exception: when the subfield delimiters are suppressed in the display they do not leave the space they occupied behind.  
For example,  300 p. :|bill. ;|c25 cm. and  300 p. : |bill. ; |c25 cm. (OCLC) 
would both display as  300 p. : ill. ; 25 cm.  
Check out your own utility to see how they handle this.
6) The symbol | (pipe) represents the subfield delimiter in these standards. In OCLC records you see the symbol $ (dollar sign).


020	ISBN NUMBER (Optional)		
An ISBN is a unique number assigned to an item by its publisher.  Each ISBN number is a ten-digit number and has four parts.  Enter without hyphens and add any qualifiers that describe the item.
		|a1590868188
		|a1559351500 (set)

Note:  Although this number is supposed to be unique, it often is not, so caution should be exercised in using this as a match point.

024	OTHER STANDARD IDENTIFIER (Optional)
	A standard number or code published on an item which cannot be accommodated in 
	another field.  The type of standard number or code is identified in the first indicator 
	position or in subfield |2 (Source of number or code).

	1st indicator – Type of standard number or code
		0 – International Standard Recording Code (ISRC)	
		1 – Universal Product Code (UPC)
		2 – International Standard Music Number (ISMN)
		3 – International Article Number (EAN)
		4 – Serial Item and Contribution Identifier (SICI)
		7 – Source specified in subfield |2
		8 – Unspecified type of standard number or code
	2nd indicator – Difference indicator
		blank – No information provided
		0 – No difference
		1 – Difference
	Subfield Codes:
		|a – Standard number or code
		|c – Terms of availability
		|d – Additional codes following the standard number or code
		|z – Canceled/invalid standard number or code
		|2 – Source of number or code

		024 1_ |a5794368779
		024 3_ |a9781578155293
		024 3_ |a9780553528152|d52595

028	PUBLISHER NUMBER (Optional)
	The formatted number used for sound recordings, printed music, and videorecordings. 
Publisher’s numbers that are given in an unformatted form are recorded in field 500
(General Note).  A print constant identifying the kind of publisher number may be 
generated based on the value in the first indicator position.

1st indicator – 					2nd indicator –
Type of publisher number			Note/added entry controller
	0 – Issue number			0 – No note, no added entry
	1 – Matrix number			1 – Note, added entry
	2 – Plate number			2 – Note, no added entry
	3 – Other music number		3 – No note, added entry
	4 – Videorecording number
	5 – Other publisher number
Subfield Codes:
	|a – Publisher number
	|b – Source

	028 02 |aRH/2103|bRandom House Audio
	028 00 |aBDDAP 094|bBantam Audio

040	CATALOGING SOURCE (Required)
Original source of the cataloging data (subfield |a), contributor of cataloging data, and if applicable, the modifier of cataloging data (subfield |d).  Use OCLC or USMARC code that uniquely identifies your location.  (See OCLC code list).  For example:
		|aOXU 
		|aUMT	|dLGRND

092	LOCALLY ASSIGNED DEWEY CALL NUMBER (Optional - This field does not show up on database)
Call numbers based on Dewey Decimal Classification.  

099	LOCALLY FREE-TEXT CALL NUMBER (Optional - This field does not show up on database)
	
100	MAIN ENTRY – PERSONAL NAME (Required if present)
A personal name is the name of the person responsible for the creation of the intellectual or artistic content of an item as prominently displayed.  Use of this field relates to the statement of responsibility as found following title.  For an editor, use Marc tag 700 rather than this tag.  Do not use this tag for a corporation or organization given in statement of responsibility.  Just use title entry instead and trace corporate authors in 710. It is best to match names to authority files already in use.  To do this, you can search the Pioneer, Orbis or Library of Congress databases using the author search selection for the author listed in item being cataloged.  Then select one record by author and convert to a Marc Tag display.  Fill in spelling and dates given. Use subfield |a for name, subfield |q for expanded name, and subfield |d for date, if available.

This field may be used only once.  Additional authors go in 700 field.

		|aGrisham, John.
		|aBradbury, Ray,|d1920-
		|aLewis, C. S.|q(Clive Staples),|d1893-1963.
		|aJohn Paul|bII,|cPope,|d1920- 

	Punctuation:
Subfield |b is preceded by a space only
subfield |c is preceded by a comma space 
subfield |d is preceded by a comma space
subfield |q is preceded by a space only and placed in parentheses
100 field ends with a mark of punctuation or a closing parenthesis “)”

245	TITLE STATEMENT (Required)
The title statement is the title proper and may also include a general material designation (form if other than book, i.e. sound recording), subtitle, other title information, and the statement of responsibility (name of author or editor).  If you need to use a general material designation, use subfield |h after subfield |a.  A list of approved designations is included in Attachment 1 of “Recommended Standards for Bibliographic Records: Developed by Cataloging Work Team, 2002.”

	The first indicator should be 1 if MarcTag 100 (author) is used.  Otherwise use 0.
	For second indicator use 0 if title does not begin with an article.  Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

	For general material designation (GMD) use subfield |h.  
		245 10 |aEight cousins|h[sound recording]
		245 14 |aThe sounds of Christmas|h[sound recording]
	For the subtitle use |b
		245 04 The Civil War|h[sound recording] :|bits music and its sounds 

	Note:	Subfield |b follows subfield |h. 

	For statement of responsibility (name of author or editor or corporation) use subfield |c. 

Transcribe statements of responsibility relating to those persons or bodies credited with a 
major role in creating the intellectual content of the sound recording (e.g., as writers of
spoken words, composers of performed music, collectors of field material, producers 
having artistic and/or intellectual responsibility) in the form in which they appear.  If the 
participation of the person(s) or body (bodies) named in a statement found in the chief 
source of information goes beyond that of performance, execution, or interpretation of a 
work (as is commonly the case with “popular,” rock, and jazz music), give such a 
statement as a statement of responsibility.  If however, the participation is confined to 
performance, execution, or interpretation (as is commonly the case with “serious” or 
classical music and recorded speech), give the statement in the note area.

Add a word or short phrase to the statement of responsibility, in brackets, if the 
relationship between the title and the person(s) or body (bodies) named in the statement is 
not clear. 

245 14 |aThe land that time forgot|h[sound recording] /|cby Edgar Rice 
Burroughs.
		245 10 |aEndurance|h[sound recording] :|bShackleton’s incredible voyage /|cby 
			Alfred Lansing.
		245 10 |aBorn to run|h[sound recording] /|c[written and performed by] Bruce 
			Springsteen.

	Note:  Subfield |c follows subfield |h.

Punctuation: 
subfield |b is preceded by space colon space
subfield |c (statement of responsibility) is preceded by space forward-slash space, each subsequent statement of responsibility is preceded by space semicolon space 
subfield |h is preceded by a space only and is enclosed in brackets. 
245 field ends with a period. 

246	VARIANT TITLE (Optional) (prior to 1995, placed in 740 field).
	Examples are other titles, caption titles, spine titles, running titles.

        	Punctuation: 
See rules for 245 field. 
No ending punctuation is added to a 246 field. 

250	EDITION STATEMENT (Required if applicable)
Refer to the edition statement proper and any other information found in the prescribed sources of information (see note #1 on page 1).  Use only if the edition statement is self-defining, that is uses words such as edition, issue, version.  Numbers may appear with an edition statement. For items that use revised alone use abbreviation Rev. as in example.  Use subfield |a for edition statement
		|aRev. ed.
		|a[Rev.].

Punctuation:  250 field always ends with a period.

260	PUBLICATION, DISTRIBUTION, IMPRINT (Required)
The imprint statement may include place of publication, publisher, place of distribution, distributor (if given), date of publication, copyright date.  Use square brackets to correct erroneous information or for clarification.  No indicators are assigned.

PLACE OF PUBLICATION
Use subfield |a for place of publication.  Supply the name of the country, or state or province for U.S. or Canadian publishers respectively, if it is considered necessary for identification or distinction and enclose in parentheses if not stated in prescribed sources of information (see note #1 on page 1).  Use abbreviations supplied in Attachment 2 of “Recommended Standards for Bibliographic Records: Developed by Cataloging Work Team, 2002.”
		|aAuburn, Calif.
		|aLondon (Ont).
		|aBelfast [i.e. Dublin] (Ireland)

If two places are recorded, enter each place name in separate subfield |a.  Enter first place given and one place in country of cataloging if they are different. Other places of publication may be omitted. 
	
	|aWestmount, Quebec ;|aPlattsburgh, N.Y.

If the probable place of publication cannot be determined, use the abbreviation [S.l.] (which stands for sine loce, without place). 

	|a[S.l.]

The “S” is capitalized because it begins the field.

      	NAME OF PUBLISHER OR DISTRIBUTOR
Give publisher in shortest distinguishing form, omitting generic words such as Co., Inc., or Ltd.

	Use subfield |b for name of publisher or distributor.
		|aHampton, N.H. :|bChivers North America
		|aDon Mills, Ont. :|bFederation of Ontario Naturalists
	
	If two publishers or distributors are named, enter each name in a separate 
	subfield |b.
		|aLondon :|bGandalf Records :|bDistributed by Middle Earth

If probable publisher or distributor is unknown, use the abbreviation [s.n.] (which stands for sine nominee, without name).
		|aMontreal :|b[s.n.]

DATE
Use the publishing date and/or copyright date from the prescribed sources of information (see note #1 on page 1).  Whenever the copyright date of the material (other than books and printed serials) is different from the date of publication, transcribe the phonogram copyright date preceded by a lowercase “p,” as this is the symbol, by international convention, since 1971, used to indicate the copyright date of recorded sound.  If there is more than a year’s difference between publishing and copyright date, both need to be added to the record, newest date first.    

            Use subfield |c for date of publication
		|aNew York :|bRCA,|c1987.
		|aLondon :|bBigbeat,|cp1986.

If date is estimated or deduced, place in square brackets with ? if guess and no ? if certain
|c[1967?]
		|c[1956]

	Enter multiple dates in the same subfield |c, separated by a comma space
		|c1967, c1965
	
	If the date of recording appears on a published sound recording, give it in a note.
	
	Note:  small c precedes a copyright date, not to be confused with subfield |c.	

Punctuation:
within 260 subfield |a (place of publication), space semicolon space precedes a second place name in a separate subfield |a
space colon space precedes each subfield |b (publisher)
comma space precedes subfield |c (date) 
end 260 subfield |c with a period, unless another mark of  punctuation (such as a bracket or hyphen) is present

300	PHYSICAL DESCRIPTION OF THE ITEM (Required)
Use subfield |a for extent. Record the number of physical units of a sound recording by giving the number of parts in arabic numerals and one of the following terms as appropriate:
	sound cartridge
	sound cassette
	sound disc
	sound tape reel
	sound track film
		add reel, cassette, etc. as appropriate to sound track film.
	Use [name of instrument] roll, as appropriate, for rolls.  e.g.  2 piano rolls
If none of these terms is appropriate, give the specific name of the item as concisely as possible.

Also give playing time of a sound recording in parentheses following number of physical units and the term as listed out here.  If it is given on the item, give it as stated.  If it is not stated on the item but is readily ascertainable, give it.  Optionally, if the playing time is neither stated on the item nor readily ascertainable, give an approximate time.  Optionally, if the parts of a multipart item have a stated uniform playing time or an approximate uniform playing time, give the playing time of each part followed by each.  Otherwise, give the total duration.

		|a1 sound disc (50 min.)
		|a1 sound track film reel (10 min.)
		|a2 sound cassettes (ca. 90 min.)
		|a31 sound cassettes (60 min. each)

Use subfield |b for other physical details (other than extent or dimensions) as follows, in order given:
		Type of recording:
for disc or tape: analog or digital
for sound track film: optical or magnetic
		Playing speed: (only if non-standard) – i.e.you would give it for vinyl records
		Groove characteristics: (only if non-standard) – i.e. you would give it for vinyl
records
		Track configuration: (only if non-standard)
		Number of tracks (sound track films)
		Number of sound channels:  mono., stereo., quad.
		Recording and reproduction characteristics (optional): – e.g. Dolby processed,
NAB standard
		
		|a1 sound cassette (90 min.) :|banalog
		|a1 sound cassette (60 min.) :|bdigital
		|a1 sound disc (7 min.) :|banalog, 78 rpm, microgroove
		|a1 sound tape reel (ca. 60 min.) :|banalog, 7 1/2 ips, 2 track, mono.
		|a1 sound cassette (60 min.) :|banalog, stereo., Dolby processed
	
Use subfield |c for dimensions as follows:
	If the sound recordings in a multipart item differ in size, give the smallest or 
		smaller and the largest or larger size, separated by a hyphen.
	Sound discs: give the diameter of a disc in inches
	Sound track films: give the gauge (width) of a film in millimeters
	Sound cartridges: give the dimensions of a cartridge in inches if other than the
standard dimensions (5 1/4 x 3 7/8 in.), give the width of the tape in 
fractions of an inch if other than the standard width (1/4 in.)
		Sound cassettes: give the dimensions of a cassette if other than the standard
dimensions (analog cassette: 3 7/8 x 2 1/2 in.), give the width of a tape if 
other than the standard width (analog tape is 1/8 in.) 
		Sound tape reels: give the diameter of a reel in inches, give the width of a tape in
 fractions of an inch if other than standards width (1/4 in.)
		Rolls: do not give any dimensions

		|a5 sound discs :|banalog, 33 1/3 rpm, stereo. ;|c10-12 in. 
		|a1 sound disc (50 min.) :|bdigital, stereo. ;|c4 3/4 in. 
		|a1 sound disc (45 min.) :|banalog, 78 rpm, microgroove, quad. ;|c12 in. 
		|a1 sound track film reel (10 min.) :|bmagnetic, 25 fps, centre track ;|c16 mm. 
		|a2 sound cassettes (90 min.) :|banalog, mono.
 		|a1 sound cassette (85 min.) :|banalog, mono. ;|c7 1/4 x 3 1/2 in., 1/4 in. tape. 
		|a1 sound tape reel (60 min.) :|banalog, 7 1/2 ips, 2 tracks, mono. ;|c7 in., 1/2 in. 
			tape. 

	Give the details of accompanying material (in subfield |e) as follows:
		- make a separate entry
	       or	- make a multilevel description (see AACR2R)
	       or	- make a note
	       or	- give the number of physical units in arabic numerals and the name of the
  accompanying material (using, when appropriate, a specific material
  designation) at the end of the physical description.  Optional addition: if 
  more detail is desired, give the physical description of the accompanying
  materials in parentheses.

|a4 sound discs (210 min.) :|bdigital ;|c4 3/4 in. +|e1 pamphlet (31 p. : col ill. ; 11
cm.).

Punctuation:  
	space colon space precedes subfield |b
	space semicolon space precedes subfield |c
	space plus sign (+) space precedes subfield |e
	end 300 field with a period (usually already present) 

306	PLAYING TIME (Optional)
	This field contains a formatted numerical representation of the playing time of the item.  
	Indicator positions are undefined and left blank.

	Use subfield |a for the playing time of an item.  The playing time is six characters in 
	length and is formatted hhmmss (2 for hour, 2 for minute, and 2 for second).  If the 
	recording is less than 1 hour, the hour is recorded as two zeros; if less than a minute, the 
	minute is also recorded as two zeros.  Subfield |a is repeatable to allow the recording of 
	the playing time of two or more pieces.

		|a002016
		      [for 20 min., 16 sec.]
		|a014500
		      [for 1 hour, 45 min.]
		|a003100|a001839
		      [durations: 31:00 ; 18:39]

	Note:   If more than six playing times are recorded in a note field, field 306 is generally
not used.  If the abbreviation ca. precedes an approximate playing time in a note, this
abbreviation is disregarded when recording data in field 306.

Punctuation:  
	No ending punctuation is added to the 306 field.

440	SERIES STATEMENT  (Required if applicable)
Use for series statements to be traced by a series title.  A tracing refers to an access point in the catalog for the series title.  You can look in Pioneer, Orbis or Library of Congress databases under title to check for the correct form of the tracing (the authority record).  

(If you choose not to trace a series statement or to trace it differently use tag 490. A 490 tag is used if series author is listed or if entire series is known to be by the author of the book in hand.)

Use 440 tag if series does not list an exclusive author, e.g. the series is a publisher’s series.

	The first indicator is blank. 
	
For second indicator use 0 if title does not begin with an article.  Use 1-9 to 	indicate an article, plus spaces, punctuation, diacritics and underscores that 	precede the first significant word.  

	Subfield |a contains the title portion of the series exclusive of any name, number of parts, volume numbering and ISSN.
		440  0	|aCollection Musiques anciennes

	Use subfield |v for the volume number or other sequential designations used in 	conjunction with the series statement.  
		|aThis is America ;|vno. 1

490	SERIES STATEMENT (Required if applicable)
Use 490 first indicator 0 if you do not trace; 490 first indicator 1 if you trace
differently.  If you use a 490 1  you must also have an 800 field for the correct form of the tracing.  

	A first indicator of 0 indicates a series not traced.
	Use subfield |a for author or title.
		490 0  |aCaedmon's self-help series

	Use indicator 1 if series traced by author.  Then add Marc Tag 800 per example that follows:
		490 1  |aMitford years ;|v7
	 	800 1  |aKaron, Jan,|d1937-|tMitford years ;|v7.

Punctuation:  
No ending punctuation is added to 440 or 490 fields.
440 or 490 subfield |v is always preceded by space semicolon space
440 or 490 subfield |x is always preceded by a comma space

5XX	NOTES 
	Refer to AACR2R rules in chapter 6 for order.

500	GENERAL NOTES (If Needed)
General notes are notes for bibliographic data not present elsewhere in the record or information that is present elsewhere but must be repeated in field 500 to provide an intelligible note.   May be used for informal contents note.  General notes include: bibliographic history of the work, translation notes, enhancements to the physical description, program notes. A note must be added to identify source of a tracing if not otherwise in record.  In the notes area, in addition to some special tags, tag 500 is used liberally for additional cataloging information.

If the title proper is not taken from the chief source of information or if it is taken from a container that is a unifying element, give the source of the title in a note.

Examples:
	|aBased on music by Franz Schubert.
		|aTitle on container: The four seasons.
		|aSubtitle: Songs of redemption.
		|aDigital recording.
			(For an analog disc or tape made from a digital original.)
		|aDurations: 17 min. ; 23 min. ; 9 min.
		|aLyrics on sheets in container.
		|aOriginally issued in the series: Sound effects.
		|aIssued also as cassette and as cartridge.

	Punctuation:  Always end field with a period.

505	CONTENTS NOTE (Optional)
Contents notes contain titles of separate works or parts of an item.  They may also include statements of responsibility associated with the works or parts of an item.  Volume numbers and other sequential designations are included in the note.  Use for analytical titles of independent works contained within the items and for titles of related items. This note may also contain statements of responsibility.

The first indicator is used to indicate type of contents note.  Use 0 for full contents.  Use 2 for partial contents.  Indicator 1 is used for incomplete contents, i.e., when all parts of a set are not published yet.  

Use subfield |a for formatted contents note.  When all information is in subfield |a, the second indicator is blank.
 	
505 2   |aTaxman -- Eleanor Rigby -- Love you to -- Here, there and everywhere -- Yellow Submarine -- She said she said -- Good day sunshine.
	
If statement of responsibility is included in subfield |a it is preceded by a space / space whenever it occurs:

505 2   |aThe big sleep / Raymond Chandler -- The Maltese falcon / Dashiell Hammett -- Dead pool / Ross MacDonald.

If subfields other than |a are used, the second indicator is 0 to indicate enhanced contents.
Use subfield |t for title entries; subfield |r for statement of responsibility; subfield |g 
for miscellaneous information.  Any or all may be used. These subfields are repeatable.

505  0  |tThe fourth millennium /|rHenry Brant|g(9:00) --|tMusic for brass quintet /|rPhilip Glass.

505  0  |tBig sleep --|tMaltese falcon --|tDead pool.
	
	Note: second space is omitted after dashes when a subfield code follows 
(i.e. subfield takes the place of the space).  See Note #5 at beginning of manual.

Punctuation:  
space hyphen hyphen space ( -- ) is entered between each item 
statements of responsibility are preceded by space forward slash space ( / )
end field with a period or other ending punctuation or > (angle bracket), but period after closing ] or ) – [but if note is incomplete or continues in the following 505 then none, unless the last word ends with its own punctuation]
refer to AACR2R for punctuation for use of subfields |t, |r, and |g

511	PARTICIPANT OR PERFORMER NOTE (Required)
	This field contains a note giving information about the participants, players, narrators, 
	presenters or performers.  This field is repeatable.

The first indicator contains a value that controls the generation of a display constant preceding the note in the OPAC (a 0 is used to generate no display constant, a 1 is used to generate the display constant Cast:).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the participant or performer note.
		511 0  |aNarrator: Burl Ives.
		511 0  |aVoices: Peter Ustinov, Cloris Leachman, Sally Kellerman, Andy Devine.
		511 1  |aColin Blakely, Jane Lapotaire.

	Punctuation:
Always end field with a period, unless other punctuation is present.

538	SYSTEM DETAILS NOTE (Required if applicable)
Indicators are undefined, so should be blank.  Subfield |a contains the entire text of the note.

	|aSystem requirements: CD/MP3 player or PC with MP3-capable software.

Punctuation:  
end field with a period unless another mark of punctuation is present.

586	AWARDS NOTE  (Optional)
	This field contains information on awards associated with the described item.
	The field is repeated for each occurence of an award.

The first indicator contains a value that controls the generation of a display constant preceding the note in the OPAC (a blank is used to generate the display constant Awards:, an 8 specifies no display constant is generated).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the awards note.
	
	Punctuation:
No ending punctuation is added to 586 fields.

6XX    SUBJECT HEADINGS (At least one subject heading is required for non-fiction.)  

600	SUBJECT ADDED ENTRY-PERSONAL NAME
Use for personal names used as subject added entries such as:  names of persons who actually or probably lived, personal author/title subject added entries, and names of families. For example use for Burbank, Luther or Sacagawea.

	The first indicator is 1 for a single surname and 3 for a family name  The second 		indicator refers to subject authority on which you base the subject entry.  Use 0 for
      Library of Congress (LC) subject headings. 

This Marc tag needs to follow LC standards. Try finding a match from the Pioneer, Orbis or Library of Congress databases. Enter names selected in the subject search in database. Try different selections until you find a possible fit.  Another way is to identify another book by the same author that has already been cataloged.  Look in the cataloged record for possible Subject Heading-Personal Name that would fit. When you have chosen a match, convert the catalog entry to a Marc Record. Enter into tag 600 exactly as you view in Marc format with the same indicators, and subfields.

650     SUBJECT ADDED ENTRY – TOPICAL TERM
Use for topical subject entry assigned by LC or assigned by an agency based on LC or LC Annotated Card Program (Subject Headings for Children’s Literature).  This Marc tag needs to follow LC standards. Try finding a match from the Pioneer, Orbis or Library of Congress databases. Enter words related to the subject of the book with the Subject search.  Try different words till you find a fit.  Another way is to identify another book by the same author that is similar in content and has already been cataloged.  Search for title and see if subject headings used will fit your item.  Convert chosen record to Marc Record.  Enter Marc tag indicator numbers and subfields exactly as you view them.  

651	SUBJECT ADDED ENTRY – GEOGRAPHIC NAME
Use for geographic subject entries actually assigned by Library of Congress Subject Headings.  This would include place names such as Yellowstone National Park or Portland (Or.).  As above, would suggest searching Pioneer, Orbis or Library of Congress databases. Search under Subject for geographic names.  If you find suitable subject entry, convert the entry to Marc Record and copy the indicators and subfields exactly as found.  

Punctuation: 
A period is placed at the end of the last subfield, unless it ends with a hyphen or parenthesis.
(The dashes normally shown preceding subfields v, x, y, and z are not carried in a MARC record. They are inserted by computer programs for public display of record.)

700	ADDED ENTRY – PERSONAL NAME  (Added title optional)
Make an added personal name entry under the heading for a prominently named editor or compiler of monographic work.  Make an added personal name entry for an illustrator if the illustrations are considered to be an important feature of the work.  Make an added personal name entry for any other name that would provide an important access point not treated in another entry. It is best to match names to authority files already in use.  To do this, you can search the Pioneer, Orbis, or Library of Congress databases. Using the author search selection choose the individual listed in item being cataloged.  Convert selected record to Marc Record and follow spelling and dates given there to fill in this Marc tag. 
	
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

	 	800 1  |aKaron, Jan,|d1937-|tMitford years ;|v7.

Punctuation:  
Subfield |t is preceded by a period space.
Subfield |v is preceded by space semicolon space.
Field ends with a period.

9XX	LOCAL USE TAGS
Check with Pioneer System staff if you choose to use any of these fields. 
