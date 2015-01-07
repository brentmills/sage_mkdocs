CIP (Cataloging-in-Publication) records can be identified by these three features:
•	encoding level (position 17) in the 000 or leader = 8
•	presence of projected publication date in 263 tag
•	300 tag with no pagination or dimensions – only “page cm.”
Additionally RDA-based records can be identified by the presence of ‡e rda in 040 field & an “i” under Desc in fixed fields table.  
[Note regarding transcription in RDA records:  RDA cataloging follows the principle of “Take what you see and accept what you get.” This means you should transcribe exactly what is found on the resource, & accept copy in records as supplied. However, in many instances RDA gives a range of options in how fully to record information, & also allows for establishing local guidelines.  This means we may find that records will reflect a variety of cataloging practices & still fall within the rules.]

These records are created prior to the publication of the materials, therefore the records contain incomplete and sometimes inaccurate information.  It is very important to verify the LCCN (tag 010 ‡a) and the ISBN (tag 020) to be sure the record matches your item.  Updating these CIP records involves several important steps.

1)	Add your Library code to 040 in subfield ‡d.  (See list of “040 MARC Tag - OCLC Codes sorted by…” in the Sage Cataloging Standards Manual for your library code.)  This notates who the modifying agency of the record is.  [If you are using OCLC this is done for you.]

2)	1XX tag:  Be sure the entry is accurate & any 7XX fields, as well.  Also note the order of authors in the statement of responsibility (245 ‡c) as changes here affect the 1XX & 7XX tags.

3)	245 tag:  Very frequently the title proper (subfield ‡a) and/or, especially, the subtitle (subfield ‡b) changes between the time the CIP cataloging is done and the time the item is published.  There may be subtle differences that can be easily overlooked.  Please be sure to correct the title and/or subtitle according to the title page (or other preferred source of information) of the piece in hand. With RDA transcription is key, so be sure you have exactly what is on the piece in hand.  Also check the indicators for this tag.

4)	264 tag: Compare the publication information & date on the record to the piece in hand. If they aren’t the same, change the 264 field to match the piece in hand.
[MARC21 recently introduced/defined the 264 field for use with RDA-based bib records, replacing the 260 field.  The 264 statement relates to the publication, printing, distribution, issue, release, or production of a work.  Indicators & subfield codes are listed below.]
     Indicators
 
          First - Sequence of statements
               # [blank] - Not applicable/No information
                         provided/Earliest
               2 - Intervening
               3 - Current/latest

Second - Function of entity
     0 - Production
     1 - Publication
     2 - Distribution
     3 - Manufacture
     4 - Copyright notice date
 
                  Subfield Codes      [R=Repeatable ; NR=Not Repeatable]
                       ‡a - Place of production, publication, distribution, manufacture (R)
                       ‡b - Name of producer, publisher, distributor, manufacturer (R)
                       ‡c - Date of production, publication, distribution, manufacture, or copyright notice (R)
                       ‡3 - Materials specified (NR)
                       ‡6 - Linkage (NR)
                       ‡8 - Field link and sequence number (R)

5)	263 tag:  Delete this tag as it contains projected publication date which is of no value to us now.

6)	300 tag:  Add pagination information (including any preliminary pagination) in subfield ‡a, illustrative information in subfield ‡b (if applicable), and dimension information in subfield ‡c.  (Measure and input as height x width if the book is wider than it is tall; otherwise include only height.)   [Remember, if you added information in subfield ‡b, there also needs to be a code in the fixed fields for illustrations (Ills in fixed fields table) to reflect that as well.] 

•	RDA based standards are different than AACR2 in that there are no longer abbreviations used, so please spell out page, pages, leaf, leaves, volume, volumes, illustrations, etc.  Also, do not use a square bracket with the number of counted pages, instead use the counted number with the statement “unnumbered pages” or continue to use 1 volume (unpaged).  Also, cm is not considered an abbreviation in RDA but a symbol so continue to use cm for measurement as appropriate.

7)	33X tags: 336, 337, & 338 tags now take the place of GMDs and are newly defined in MARC21.  336 field is for content types (or form of communication in which the content is expressed), 337 field is for media types (or type of device required to access content), & 338 field is for carrier types (or type of carrier used to convey content).  See the term and code lists on Library of Congress website for RDA Content Types at www.loc.gov/standards/valuelist/rdacontent.html, RDA Media Types, at www.loc.gov/standards/valuelist/rdamedia.html, & RDA Carrier Types at www.loc.gov/standards/valuelist/rdacarrier.html.  A regular print book would be coded similar to this:
336 ‡atext‡2rdacontent
337 ‡aunmediated‡2rdamedia
338 ‡avolume‡2rdacarrier

8)	490 tag: Does it need attention (or a companion 8XX field added, which would mean a change of 1st indicator in 490)?

9)	504 tag:  If the bibliography note is incomplete update it with the correct pagination.  

10)	505 tag:  Check the contents listed (if applicable).

11)	Change Rec Stat code (position 5) in 000 or leader to “p” (meaning encoding level increase from CIP record) [generally this will be a “n” for new record in a CIP record].

12)	Change the Encoding level code from 8 (CIP record) to a space (full level). 

13)	Add the abbreviation for illustrations into the fixed field for books (008 – positions 18-21, or Ills in fixed fields table).  The codes used here describe the illustrative matter of the book and correspond to the illustrations listed in the 300 tag (which will also be added).  If there are no illustrations, leave Ills in the fixed field blank.  Up to 4 single character codes can be used:
 
[blank] – no illustrations
a – illustrations
b – maps
c – portraits
d – charts
e – plans
f – plates
g – music
h – facsimilies
i – coats of arms
j – genealogical tables
k – forms
l – samples
m – phonodiscs, phonowire
o – photographs
p – illuminations 

14)	Check the date in the fixed field (008 – positions 07-10 for Date1 & 11-14 Date2).  This date(s) should match the publication date of the piece in hand and the date(s) entered in tag 264 ‡c.  If there is not a match, correct the fixed field date(s) and the date(s) in the 264 tag to match the date(s) of the piece in hand.  The date is a 4-digit year – no month designation included.  Also be sure to double check the country and make sure it matches 264 ‡a.

15)	Although GMDs are no longer allowed under RDA standards, until the 33X fields are usable in the ILSs the GMDs are still allowable if a library finds need of them, so please use it as needed.  [“It is recommended that the 245 subfield ‡h GMD be retained for a period of time & not deleted, even though this element will eventually be replaced in function by the 336, 337, and 338 fields. The Task group recommends that the GMD be considered for removal no earlier than March 31, 2016.” -- PCC-Hybrid-Bib-Rec-Guidelines-TG-Report, p.8: www.loc.gov/aba/pcc/rda/RDA Task groups and charges/PCC-Hybrid-Bib-Rec-Guidelines-TG-Report.docx] -- If the piece in hand is a large print book add a GMD “[text (large print)]” to the 245 (see example below).  [Remember that subfield ‡h precedes subfield ‡b.]  Check to make sure the form of item in fixed field for books (008 – position 23 ; Form in fixed fields table) is coded d for large print.  In 300 tag if “(large print)” is present remove it.
	   245 10 ‡aBetty‡h[text (large print)] :‡ba glad awakening /‡cBetty Ford with Chris 
Chase.


[Note:  Dea Nowell at Umatilla County Special Library District uses encoding level of 1 when she updates a CIP record.  The encoding level 1 is for “Full level, material not examined.”  Dea uses this because she generally does not have the piece in hand but is relying on the information provided by the libraries that she works with.  Feel free to make corrections to the bib record if you need to and be sure to add your code to the 040 and change the encoding level as appropriate.]



