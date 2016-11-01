<center>
# Cataloging Materials Migrated from Sage Wiki
</center>
<hr size=2>
<center><i>Last Updated: 4/20/2015</i></center>

* [Electronic Resources 856](#catm_856)
* [999 Values for Sage](#catm_999)
* [Cataloging and Advanced Reader Copy](#catm_arc)
* [Authority Records](#catm_authority_records)
* [Cancel Control Numbers](#catm_cancel_control_numbers)
* [Sage Cataloging Policy](#catm_cat_policy)
* [CIP (Cataloging in Publication) Records](#catm_cip_records)
* [ISBN FAQ](#catm_isbn_faq)
* [Evergreen Keyboard Shortcuts When Editing MARC Records](#catm_keyboard_commands)
* [Sage Standards for Matching MARC Records](#catm_matching_standards)
* [Sage Cataloging Standards for Monographs (Books)](#catm_monograph_standards)
* [Adding Monograph Parts (needs update)](#catm_multipart_holdings)
* [MARC fields for RDA Material Description](#catm_rda_material_type)

<b>Required & Recommended MARC Fields For Records within Sage</b>

* [Required Fields for Serial Record](#catm_required_fields_serial)
* [Required Fields for Books](#catm_required_fields_book)
* [Required Fields for Sound Recordings](#catm_required_fields_sound_rec)
* [Recommended Fields for Serials](#catm_serial_standards)
* [Recommended Fields for Sound Recordings](#catm_sound_rec_standards)
* [Recommended Fields for Video Recordings](#catm_video_rec_standards)
* [Cataloging Support and Online Help](#catm_support_and_online_help)
<hr size=2>

<a name="catm_856"></a>
### Adding 856 field to existing bibliographic record

This document is not intended to explain cataloging of electronic resources, but only give guidance on providing access to an electronic version of an existing item by enhancing the bibliographic record.  For the sake of brevity I will only discuss http resources (856 4_) see appropriate documentation for other access methods (identified by IND 1 of 856 tag). Spacing is for readability; do not use spaces when actually entering a URL via the 856 tag.

For additional information see:

- Link: [Online Resources for Serials Catalogers](http://lcweb.loc.gov/acq/conser/resource.html)
- Link: [Guidelines for the Use of the 856 Field](http://lcweb.loc.gov/marc/856guide.html)

Nancy Olsen – Cataloging Internet Resources. 2nd ed.

- Link: [Cataloging Internet](http://www.purl.org/oclc/cataloging-internet)
- Link: [OCLC Table of Contents](http://www.oclc.org/oclc/man/9256cat/toc.htm)


The three common types of URLs added are:

	856 40  Resource
	856 41  Version of resource
	856 42  Related resource

Subfields used are:

	|3 Materials specified (NR)
	|u Uniform Resource Identifier (R)
	|z Public note (R)

Examples:

	856 40 |u http://0-search.epnet.com.eos.eou.edu/login.asp |z connect to this resource online –BMCC only
	856 41 |u http://hereisnewyork.org/gallery/ |z connect to the Here is New York Gallery website
	856 41 |u http://lcweb2.loc.gov/ammem/ead/jackson.pdf |z connect to this title online in PDF format
	856 41 |3 Table of Contents |u http://lcweb.loc.gov/catdir/toc/98050755.html |z connect to the table of contents online
	856 42 |u http://www.nationalgeographic.com/ |z connect to an online version of this magazine 
	856 42 |u http://www.roalddahl.com |z connect to the author's website
	856 42 |3 Publisher description |u http://www.loc.gov/catdir/description/hol021/9989052.html |z connect to the publisher's description online

#### 530 Note fields used with 856

##### 530 - ADDITIONAL PHYSICAL FORM AVAILABLE NOTE (R)
-Indicators blank-

Subfields:

	|a - Additional physical form available note (NR)
	|u - Uniform Resource Identifier (R) 

Examples:

	530		|a Online version available via The New Bartleby Library
			|u http://www.bartleby.com/99/index.html
	530		|a Also available online
	530		|a Online version of print publication


#### 538  - SYSTEM DETAILS NOTE (R) 
-indicators blank-

Subfield Codes:

	|a - System details note (NR)

Examples:

	538		|a Data in extended ASCII character set.
	538		|a Mode of access: Internet
	538		|a Requires Adobe Acrobat Reader
 
In addition to adding the appropriate 856, 530, and 538 tags, you may want to look at identifying information in the item record for future use in creating reports. 

Notes are not necessary for table of contents, publisher descriptions and related websites such as the author's homepage.

BMCC has an itype and location for Internet resources.  This allows us to identify web-based holdings such as subscription databases and online Government Documents.

At this time I am using a call number of "Available online" or "Available online – BMCC only"
Example titles you may want to look at are:

- Gaming [electronic resource] : selected resources from UNLV
- Vital statistics of the United States [electronic resource]
- Contemporary authors [electronic resource]

<a name="catm_999"></a>
### 999 Fields in Sage MARC Records

The 999 field sets the “material type” icon that appears in OPAC search results.  The item type is preceded by $e, and the code itself by $f.  These examples of item types and codes are written here exactly as they should appear in the Evergreen MARC editor.  Where necessary to avoid confusion, a note on proper usage has been placed after the field itself.

Most common material types and codes (listed alphabetically):

	999 \\$eAudiobook Cassette $fy
	999 \\$eAudiobook CD $fz
	999 \\$eBlu-ray $f5
	999 \\$eBook $fa
	999 \\$eMusic Cassette $f1
	999 \\$eMusic CD $f2
	999 \\$eDVD $fh
	999 \\$eEbook $fx
	999 \\$eKit $fo
	999 \\$eLarge Print $fb 
	999 \\$eMagazine/Journal $fs
	999 \\$eToys/Games $fw
	999 \\$eVideocassette $fg

Less common material types: 

	999 \\$eMap $fe
	999 \\$eMicrofiche $fu
	999 \\$eMicrofilm $fv
	999 \\$eMP3 $f3
	999 \\$eCassette $fi	    			[Note: This code only for cassettes that are NEITHER audiobooks nor music]
	999 \\$eCD $fl							[Note: This code only for CDs that are NEITHER audiobooks nor music]
	999 \\$eOregon Document $f8				[Note: for state publications]
	999 \\$eOnline Oregon Document $f6		[Note: for state publications online]
	999 \\$eUS Document $f0
	999 \\$eOnline US Document $7			[Note: for federal publications online] 
	999 \\$eUS Doc CD $f9					[Note: for federal publications on disc]
	999 \\$eE-Reader $fer					[Note: this is for the device itself, not a downloadable file]
	999 \\$eThesis $ft

<a name="catm_arc"></a>
### Cataloging an “Advanced reader copy” or “Uncorrected proof”

Advanced reader copies, uncorrected proofs, and galley proofs are generally copies released prior to publication for editing and/or reviewing proposes.  If your library should choose to add these to your collection and thus to the Sage System you need be sure to notate the record appropriately so that the bib is not used for a regular copy since sometimes pagination, dimensions, or publication information will vary.  To do this you need to invalidate the 010 and/or 020 (using subfield |z) and use the edition/history note field (500) to identify it as such.  [Don’t place the information in the 250 field, as the information is not really an edition statement.]

Examples:

		010 __ |z9999000000
		020 __ |z9781111111111
		500 __ “Advanced reader copy”–Cover.
		500 __ “Uncorrected proof”–Cover.

<a name="catm_authority_records"></a>
### Authority Records and their use within Sage
<i>(Compiled from Final Report submitted by Anne Uhl 7/20/02)</i>

In order for the online catalog to be used to retrieve all items by a given author or on a given subject, the access points must be normalized and standardized.  Authority control is the process of determining: 

1.  The form of a name, title, or subject concept that will be used as a heading in a bibliographic record 
2.  The cross references needed for that form.
3.  The relationships between the heading and other authoritative headings. 

- Authority work is documented in an authority record and stored in an authority file.  

Examples of an authority file are the Name Authority File in OCLC and the LC Authority file in DRA.  Authority files represent records of decisions made about the manner in which cataloging rules have been interpreted.  Authority headings are defined by organizations that provide officially approved terms for headings that may be used in bibliographic records.  In the United States, the Library of Congress serves as this organization.  Records for an author’s name, a subject or a title have a correct form that is established as an authority record.

- Authority records serve two purposes: 

1. Reference source for an established heading 
2. Provides guidance for the creation of a new heading 

Authority records are created for names, subjects, uniform titles and series.  These terms may be used in records in a database as needed or can be used to send a user to another related term with the use of see and see also cross references.

- Authority files online

On July 1, 2002, the Library of Congress opened a website which lists their authority files.  This includes Name Authorities, Title Authorities and Name/Title Authorities.  It also includes authorized LC Subject Heading.  This is an important tool for catalogers. Now small sites without the large five volume set of LC Subject Headings can browse and select authorized Subject Headings.  The website is: [http://authorities.loc.gov/](http://authorities.loc.gov/)


<a name="catm_cancel_control_number"></a>
### Cancel Control Number

Subfield z (|z) in the ISBN tag and LCCN tag is for canceled or invalid numbers.  Some systems are able to identify an invalid number in the ISBN tag when the last digit or check digit does not properly compute, thus it is an invalid ISBN number.  The Pioneer system does not identify such numbers.  An ISBN and/or a LCCN should not be listed in subfield a (|a) in more than one record.

If you have two or more records with the same LCCN it is easy to identify which is correct by checking the Library of Congress catalog at [http://catalog.loc.gov/](http://catalog.loc.gov/).  The LCCN is the Library of Congress’ control number or system number, thus any number is unique to one record at LC.  Because of this uniqueness it is one of the most important match keys for trying to detect duplicate records.  Unfortunately publishers do not understand this uniqueness and often you will find that publishers list the same LCCN in subsequent editions of books.  (Note: mass market paperbacks are never cataloged by LC.)  If you find a LCCN that is not correct but is listed in an item in hand you can list the LCCN in a bib by using subfield z (|z) to identify it as being in an item but not being correct or being invalid – thus it can still be a “match point.”

ISBNs are assigned by publishers and are supposed to be unique.  Unfortunately not all publishers understand this and will print the same ISBN in different editions or sometimes simply make a mistake and print it in two completely different works.  Publishers also print multiple ISBNs in items (often for different formats).  Multiple records with the same ISBN are a bit trickier than LCCNs as there is no definitive database or catalog to check these against.  If completely different records are found with the same ISBN then the safest way is to change each instance to subfield z (|z) to reflect the incorrectness of this ISBN.  [If you are cataloging an item and want to include the ISBN for other formats (e.g. large print, sound recordings, etc.) on the bib then you need to also list them as subfield z (|z) to reflect that they are not correct for this particular bib and item.]
 
It is important to also note that you made a change in a record by adding your code (e.g. OCLC code) to the 040 tag in subfield d (|d).  

The importance and key to correctly coding subfield z (|z) in the ISBN & LCCN is for matching purposes, both by hand and by machine.

<a name="catm_cat_policy"></a>
### Sage Library System Cataloging Policy

- approved by Sage Library System User Council , November 20, 2012

#### Introduction

The Sage Library System consortium is committed to developing and coordinating a database of high-quality bibliographic records for collective use by member libraries, our library patrons and colleagues. Maintaining the quality and integrity of each bibliographic record is an interest and a responsibility shared by all member libraries. Bibliographic records added to the Sage database become the shared property of the consortium.

Sage Library System emphasizes voluntary and cooperative efforts to maintain database quality, accurate bibliographic  information and elimination of duplicate records. For the integrity of the database, Sage catalogers must comply with standards for full bibliographic records and perform functions only according to one’s authorized permission and certification level.
Sage Library System will make reasonable efforts to facilitate training opportunities and resources for all members. The Sage Cataloging Committee is responsible for monitoring quality assurance, coordinating regular training, and recommending measures for policy enforcement to the Sage User Council. Core guidance documents for catalogers include this Cataloging Policy, the Sage Cataloging Procedures Guide and the Sage Cataloging Manual. Only Sage certified catalogers may perform cataloging functions in the Sage Library System. In extreme cases, Sage Library System reserves the right to restrict cataloging privileges of any member library if the requirements of this policy are not met, including revocation of cataloging permissions.

#### Cataloging Standards

1. Requirements
	- Any person performing permanent cataloging functions in the Sage Library System database must obtain prior authorization from the Sage Cataloging Committee unless operating under direct supervision of a Certified Sage Cataloger.

	- All libraries must have someone certified at least at the “Basic” level (CAT3) in order to add items to the Sage Library System. It is advisable to have someone trained at the “Mid-level” (CAT2) so that a library is able to at least bring in some of their needed records or they must make arrangements with another library (with staff that has the appropriate level of training [CAT2 or CAT1]) to do this for them.

	- New Sage member libraries must present cataloging qualifications to the Cataloging Committee to certify cataloging proficiency at the CAT3 “Basic” level of cataloger or higher within the first three (3) months after migration.

	- At least one person from each member library must monitor the Sage-Cat-group email list.Sage Library System Cataloging Policy

##### Permission Levels – CAT3, CAT2, CAT1

Catalogers will be certified at one of three skill levels according to proficiency.

###### CAT3 “Basic” level cataloger [barcoder]

1. <b>Training requirements</b>
	- Elementary understanding of Evergreen & cataloging practices.
	- Fundamental understanding of MARC bibliographic records and familiarity with AACR2 cataloging rules.
	- Ability to search Sage Evergreen catalog efficiently and accurately
	- Compliance with established matching criteria for any item types to be attached

2. <b>Functional abilities</b>
	- "Match & attach" - attach holdings to existing bib records
	- Edit volume & copy level data (holdings/items)
	- Does NOT import or edit bibliographic records
	
###### CAT2 “Middle” level cataloger [copy cataloger]

1. <b>Training requirements</b>
	- Must have same basic level training as CAT3
	- Complete an advanced MARC21 training provided by Sage, or provide documentation of equivalent training/experience.

2. <b>Functional abilities</b>
	- Do everything allowed by “basic” level (CAT3) catalogers
	- Import records via Z39.50
	- Update CIP records
	- Create “stub” (placeholders) or “temp” bibliographic records
	
###### CAT1 “Certified” cataloger [full level cataloger]

1. <b>Training requirements</b>
	- Must have achieved CAT3 and CAT2 proficiency
	- Able to document advanced cataloging training, either from college level courses or through a recognized professionaltraining service, as approved by the Sage Cataloging Committee.

2. <b>Functional abilities</b>
	- Do everything allowed by CAT2 “mid-level” “copy catalogers”
	- Import records via batch loading
	- Overlay existing “stub”/“temp” bibliographic records
	- Overlay existing bibliographic records
	- Create original bibliographic records
	- Add new fields to bibliographic records Sage Library System Cataloging Policy
	- Merge bibliographic records
	- Update bibliographic records
	- Delete existing bibliographic records
	- Delete fields in existing bibliographic records prior to or after import
	
##### Cataloging Support
- Regional Cataloging Mentors
	- Sage Library System has volunteer regional cataloging mentors who serve as “go-to” people for cataloging questions/issues in each area. The mentors will coordinate cataloging training and quality in their regions as time permits.

##### Permanent Record Standards

- Sage Library System is committed to maintaining a database of high quality bibliographic records for collective use by member libraries.

- All bibliographic records contributed to the Sage catalog must contain specific mandatory elements and meet a minimum level of completeness.

- Bibliographic records must:
	1. Use MARC Format for Bibliographic Data
	2. Contain core level fields as defined by Library of Congress’s BIBCO Core Record Standards
	3. Comply with AACR2R (and LCRI rules)
	4. Not be imported unless 1) there is no existing matching record as defined in the Procedures Guide or 2) the existing matched record is being overlaid.
	5. Use standard GMD terminology
	6. Contain only bibliographic-level data, not holding specific information
	7. Contain at least one Library of Congress Subject Heading (LCSH) if item is nonfiction
	8. Be compared with the item in hand

- Temporary brief records will not be subject to the same standards as full records, including content, style, and authority work.

##### Maintenance standards
- Member libraries are expected to:

1. Keep holdings current
2. Designate a staff member to monitor the Sage-Cat-Group email list
3. Resolve problems as reported to them by the Sage Cataloging Committee and mentors
4. Respond to staffing surveys conducted by the Sage Cataloging Committee Sage Library System Cataloging Policy
5. Maintain awareness of current Sage cataloging policy and procedures

##### Communications
1. The Sage Cataloging Committee will meet regularly. Regular Committee meetings are open to the participation of all Sage members. The schedule and agenda of regular meetings shall be accessible to Sage member libraries.
2. All notices coming from the Sage Cataloging Committee will be given via the Sage-CatGroup email list and documented on the Sage Wikispaces.

##### Reporting and resolving problems

Inquiries or problems are generally reported directly to the library(ies) that contributed the record(s). For an issue that may have broader implications for a union catalog, the inquiry may be directed to the Catalog Committee Chair who will review it and follow up as appropriate.

##### Sanction of Privileges
1. With recommendations from the Sage Cataloging Committee, the Sage User Council may restrict or revoke cataloging privileges of any individual or Sage member library if work repeatedly fails to meet with the established standards set by the consortium or if the cataloging training requirements are not maintained.
2. Cataloging privileges will not be sanctioned prior to consultation with the affected library’s director, other cataloging staff, and if necessary, the library board of directors.
3. Libraries under cataloging sanctions may appeal for restoration:
	- At any regular or special meeting of the Cataloging Committee
	- At any regular or special meeting of the Sage User Council
4. Restoration of privileges may be granted by the Sage User Council, with recommendations from the Cataloging Committee.

<a name="catm_cip_records"></a>
##### CIP (Cataloging-in-Publication) records can be identified by these three features:

1. encoding level (position 17) in the 000 or leader = 8
2. presence of projected publication date in 263 tag
3. 300 tag with no pagination or dimensions – only “page cm.”

Additionally RDA-based records can be identified by the presence of ‡e rda in 040 field & an “i” under Desc in fixed fields table.  

[Note regarding transcription in RDA records:  RDA cataloging follows the principle of “Take what you see and accept what you get.” This means you should transcribe exactly what is found on the resource, & accept copy in records as supplied. However, in many instances RDA gives a range of options in how fully to record information, & also allows for establishing local guidelines. This means we may find that records will reflect a variety of cataloging practices & still fall within the rules.]

These records are created prior to the publication of the materials, therefore the records contain incomplete and sometimes inaccurate information.  It is very important to verify the LCCN (tag 010 ‡a) and the ISBN (tag 020) to be sure the record matches your item.  Updating these CIP records involves several important steps.

1. Add your Library code to 040 in subfield ‡d.  (See list of “040 MARC Tag - OCLC Codes sorted by…” in the Sage Cataloging Standards Manual for your library code.)  This notates who the modifying agency of the record is.  [If you are using OCLC this is done for you.]

2. `1XX` tag:  Be sure the entry is accurate & any 7XX fields, as well.  Also note the order of authors in the statement of responsibility (245 ‡c) as changes here affect the 1XX & 7XX tags.

3. `245` tag:  Very frequently the title proper (subfield ‡a) and/or, especially, the subtitle (subfield ‡b) changes between the time the CIP cataloging is done and the time the item is published.  There may be subtle differences that can be easily overlooked.  Please be sure to correct the title and/or subtitle according to the title page (or other preferred source of information) of the piece in hand. With RDA transcription is key, so be sure you have exactly what is on the piece in hand.  Also check the indicators for this tag.

4. `264` tag: Compare the publication information & date on the record to the piece in hand. If they aren’t the same, change the 264 field to match the piece in hand.

[MARC21 recently introduced/defined the 264 field for use with RDA-based bib records, replacing the 260 field.  The 264 statement relates to the publication, printing, distribution, issue, release, or production of a work.  Indicators & subfield codes are listed below.]

Indicators:
 
<b>First</b> - Sequence of statements

	# [blank] - Not applicable/No information
				provided/Earliest
	2 - Intervening
	3 - Current/latest

<b>Second</b> - Function of entity:

     0 - Production
     1 - Publication
     2 - Distribution
     3 - Manufacture
     4 - Copyright notice date
 
<b>Subfield Codes</b> R=Repeatable ; NR=Not Repeatable:

	‡a - Place of production, publication, distribution, manufacture (R)
	‡b - Name of producer, publisher, distributor, manufacturer (R)
	‡c - Date of production, publication, distribution, manufacture, or copyright notice (R)
	‡3 - Materials specified (NR)
	‡6 - Linkage (NR)
	‡8 - Field link and sequence number (R)

1. `263` tag: Delete this tag as it contains projected publication date which is of no value to us now.

2. `300` tag: Add pagination information (including any preliminary pagination) in subfield ‡a, illustrative information in subfield ‡b (if applicable), and dimension information in subfield ‡c. (Measure and input as height x width if the book is wider than it is tall; otherwise include only height.)   [Remember, if you added information in subfield ‡b, there also needs to be a code in the fixed fields for illustrations (Ills in fixed fields table) to reflect that as well.]

	- RDA based standards are different than AACR2 in that there are no longer abbreviations used, so please spell out page, pages, leaf, leaves, volume, volumes, illustrations, etc.  Also, do not use a square bracket with the number of counted pages, instead use the counted number with the statement “unnumbered pages” or continue to use 1 volume (unpaged).  Also, cm is not considered an abbreviation in RDA but a symbol so continue to use cm for measurement as appropriate.

3. `33X` tags: 336, 337, & 338 tags now take the place of GMDs and are newly defined in MARC21.  336 field is for content types (or form of communication in which the content is expressed), 337 field is for media types (or type of device required to access content), & 338 field is for carrier types (or type of carrier used to convey content).  See the term and code lists on Library of Congress website for RDA Content Types at www.loc.gov/standards/valuelist/rdacontent.html, RDA Media Types, at www.loc.gov/standards/valuelist/rdamedia.html, & RDA Carrier Types at www.loc.gov/standards/valuelist/rdacarrier.html.  A regular print book would be coded similar to this:

		336 ‡atext‡2rdacontent
		337 ‡aunmediated‡2rdamedia
		338 ‡avolume‡2rdacarrier

4. `490` tag: Does it need attention (or a companion 8XX field added, which would mean a change of 1st indicator in 490)?

5. `504` tag:  If the bibliography note is incomplete update it with the correct pagination.  

6. `505` tag:  Check the contents listed (if applicable).

7. Change Rec Stat code (position 5) in 000 or leader to “p” (meaning encoding level increase from CIP record) [generally this will be a “n” for new record in a CIP record].

8. Change the Encoding level code from 8 (CIP record) to a space (full level). 

9. Add the abbreviation for illustrations into the fixed field for books (008 – positions 18-21, or Ills in fixed fields table).  The codes used here describe the illustrative matter of the book and correspond to the illustrations listed in the 300 tag (which will also be added).  If there are no illustrations, leave Ills in the fixed field blank.  Up to 4 single character codes can be used:

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

10.	Check the date in the fixed field (008 – positions 07-10 for Date1 & 11-14 Date2).  This date(s) should match the publication date of the piece in hand and the date(s) entered in tag 264 ‡c.  If there is not a match, correct the fixed field date(s) and the date(s) in the 264 tag to match the date(s) of the piece in hand.  The date is a 4-digit year – no month designation included.  Also be sure to double check the country and make sure it matches 264 ‡a.

11.	Although GMDs are no longer allowed under RDA standards, until the 33X fields are usable in the ILSs the GMDs are still allowable if a library finds need of them, so please use it as needed.  [“It is recommended that the 245 subfield ‡h GMD be retained for a period of time & not deleted, even though this element will eventually be replaced in function by the 336, 337, and 338 fields. The Task group recommends that the GMD be considered for removal no earlier than March 31, 2016.” -- PCC-Hybrid-Bib-Rec-Guidelines-TG-Report, p.8: www.loc.gov/aba/pcc/rda/RDA Task groups and charges/PCC-Hybrid-Bib-Rec-Guidelines-TG-Report.docx] -- If the piece in hand is a large print book add a GMD “[text (large print)]” to the 245 (see example below).  [Remember that subfield ‡h precedes subfield ‡b.]  Check to make sure the form of item in fixed field for books (008 – position 23 ; Form in fixed fields table) is coded d for large print.  In 300 tag if “(large print)” is present remove it.

		245 10 ‡aBetty‡h[text (large print)] :‡ba glad awakening /‡cBetty Ford with Chris Chase.

	> <b>Note:</b></br>
	*Dea Nowell at Umatilla County Special Library District uses encoding level of 1 when she updates a CIP record.  The encoding level 1 is for “Full level, material not examined.”  Dea uses this because she generally does not have the piece in hand but is relying on the information provided by the libraries that she works with.  Feel free to make corrections to the bib record if you need to > and be sure to add your code to the 040 and change the encoding level as appropriate.*

<a name="catm_isbn_faq"></a>
####ISBN Questions and Answers
revised 2007

- What is an ISBN?

ISBN stands for International Standard Book Number – a unique identifier assigned to each edition of every published book and book-like product published internationally.  The ISBN was originally developed as a 10-digit number (ISBN-10).  In January 2007, the ISBN was redefined from a 10-digit (ISBN-10) to a 13-digit number (ISBN-13).
 
- What is the purpose of an ISBN?

The purpose of the ISBN is to establish and identify one title or edition of a title from one specific publisher and it is unique to that edition, allowing for more efficient marketing of products by booksellers, libraries, universities, wholesalers and distributors.  [Be aware that some publishers reuse ISBN’s making them not so unique.]

- How is the ISBN constructed?

An ISBN-10 consists of 10 digits and whenever it is printed it is preceded by the letters ISBN.  The 10-digit number is divided by hyphens into 4 parts of variable length.  The four parts of an ISBN are as follows: 1) Group or country identifier; 2) Publisher identifier; 3) Title identifier; 4) Check digit. 

An ISBN-13 contains 13 digits which are divided into five parts of variable length, each part separated by a hyphen.  The five parts of an ISBN are as follows: 1) prefix; 2) Group or country identifier; 3) Publisher identifier; 4) Title identifier; 5) Check digit. 

- What do the four/five parts of the ISBN mean?
	1.	Prefix:  The first ISBN-13’s will be prefixed by "978".  These ISBN-13’s beginning with 978 are constructed the same way as the ISBN-10 and have an equivalent ISBN-10.  When the supply of 978 numbers is exhausted the prefix will become 979.  (There will be no ISBN-10 equivalent for the ISBN-13’s beginning with 979.)

	2.	Group or Country Identifier:  This part of the ISBN identifies a national or geographic grouping of publishers that participates in the ISBN system. 

	3. Publisher Identifier:  This part of the ISBN identifies the publisher to whom the ISBN was originally allocated.  Each publisher is allocated their publishing prefixes.  If they go beyond their initial title allotment they will be issued an additional publishing prefix.  Therefore, a publishing agency might carry several publishing prefixes.  Keep in mind, however, that as publishers buy and sell various imprints (subsidiaries of a publishing house) or parts of imprints, this part of the ISBN becomes less and less reliable as a way to identify the publisher of the title. 

	4.	Title Identifier:  This part of the ISBN identifies a particular title or edition of a title.

	5.	Check Digit:  The check digit is the single digit at the end of the ISBN that ensures that each ISBN is valid, meaning that the number is correct.  The check digits are calculated based on the numbers contained within the ISBN.  (Note: Since the numbers contained within an ISBN-10 and a matching ISBN-13 are slightly different the check digits of each will almost always differ.)  A Roman numeral X is used when 10 would occur as the check digit.

- When should a new ISBN be issued?
A separate ISBN must be assigned to every title, or edition of a title by each publisher, but not to an unchanged impression or unchanged reprint of the same title in the same format by the same publisher.

- Where is an ISBN located on the book?
An ISBN is printed on the lower portion of the back cover of a book above the barcode and on the copyright page.  Each format or binding must have a separate ISBN.

- What is an ISSN?
International Standard Serial Number (ISSN) is the numbering system used for serial publications.  A serial is defined as any publication issued in successive parts, usually bearing numerical or chronological designations and intended to be continued indefinitely.  Serials include periodicals, year-books, and monographic series.

- Can a publisher have both an ISBN and an ISSN?
Both numbering systems are used for books in a series and with annuals or biennials.  The ISBN identifies the individual book in a series or a specific year for an annual or biennial.  The ISSN identifies the ongoing series, or the ongoing annual or biennial serial.  If a publication has both, each should be printed on the copyright page.


- Additional notes about ISBNs and Millennium:
Beginning with the 2006 Release Millennium has a translator that will translate an ISBN-10 to an ISBN-13 and visa versa.  This was added as a way deal with the changeover to ISBN-13’s that began in January 2007.  (It is important to note that the ISBN-10 has no equivalent to an ISBN-13 beginning with 979 and visa versa.)

Currently we are getting cover images of items displayed in the WebOPAC from Amazon through the use of the ISBN.  Unfortunately it only seems to work off the ISBN-10 at the current time, so in order for the cover image to show up in the WebOPAC the ISBN-10 needs to be the first listed 020.  (It is possible to move this up the list without retyping it by placing your cursor on the one you want to move and using the “Move Up” or “Move to Top of Group” found in the “Edit” menu.)

<a name="catm_keyboard_commands"></a>
#### Editing Commands for MARC Records

Keyboard commands

- To Add a Field/Row

		Control Enter
Position the cursor on the field that you want below the new field.

- To Add a Subfield Delimiter

		Control D
You must add the letter/number of the subfield yourself.

- To Remove Field/Row

		Control Delete

- To Remove a Subfield Delimiter and value

		Shift Delete

The system will not allow the final subfield to be deleted. You must delete entire field to delete.

- Right Click Commands

You can also add a blank field by right clicking on the field that would be below the new field and clicking on Add Field. To add a particular field, click on the value in the drop-down menu.

- To delete a field, right click on the field itself. 

- To Insert a Field/Row

		Control Shift Enter

This works particularly well when you want to insert a field between the 008 field and the next field (below the 008 field).

<a name="catm_matching_standards"></a>

####STANDARDS FOR MATCHING TO DATABASE RECORDS
*Developed by Cataloging Work Team, 2002*

- ISBN
This is a good way to search to find a possible match in the database.  Every other part of the record must then match to accept the record.  Sometimes ISBN’s may match what is in the book but the edition will still be a mismatch. Examples are: Large print books and book club editions. Then search by title.

- TITLE/AUTHOR
Title must match exactly up to the first five words. Also check the subtitle.  If present, it will be after the colon.  Following the forward slash is a statement of responsibility for the item.  It may be the author, an editor or a corporate body.  This name will also be listed in another tag as the author, alternate author or corporate body.  

- IMPRINT
This tag lists place of publication, publisher and date of publication.

Dates may not be the best indicator of a match because some catalogers inadvertently enter the date of printing rather than first publication date. However, if the dates do match, and the publisher is the same,  that is a good indication for matching.  If you have the item in hand, be sure you are looking at publishing date rather than date of printing.  The copyright date, if present, indicates the original date of publication, no matter what the publication date of the item in hand.  Later printings of an edition are a match; the printing date may or may not be part of the 260 field.

Place of publication should match if publishing dates are alike.  If there is a later printing date, the place and publisher may be different. If that place and publisher are a subgroup of the original publisher or bought out the original publisher; and if the edition essentially comes from the same set of printing plates, such that pages are completely interchangeable between them, then it is the same edition.  If it is a completely different publisher from the same set of printing plates, this would be a different edition, noted by “Reprint.  Originally published: [place] : [Publisher] ; [date]” in the 500 field.

- PHYSICAL DESCRIPTION
If the page numbers match, great.  If they don’t, it may be due to clerical error. For example, AACR2 states that the page number listed is the last page printed in the book.  If two or three pages follow, some catalogers may incorrectly add these to the last printed page number.  If you see numbers that are very close and all other criteria match, you should assume you have a match.  If numbers vary by more than a few, you probably don’t have a match.  The best example of this, where everything is the same except the number of pages, is a book club edition put out simultaneously by the publisher(s).  These editions are smaller, the type is smaller, the number of pages is usually smaller; this means that one cannot replace a page of one with the other, and in replacement the book club edition is significantly less valuable than the trade edition.  These editions should not be placed on the same record. 

<a name="catm_monograph_standards"></a>
##### RECOMMENDED STANDARDS FOR BIBLIOGRAPHIC RECORDS – SPECIFIC TO BOOKS (MONOGRAPHS)
- Developed by Cataloging Work Team, 2002; rev. 2004; rev. 2007

Notes:	

1. The chief sources of information for each field for book records are listed in AACR2R. The chief source of information for printed monographs is the title page or, if there is no title page, the source from within the publication that is used as a substitute for it.  For printed monographs published without a title page, or without a title page applying to the whole work (as in the case of some editions of the Bible and some bilingual dictionaries), use the part of the item supplying the most complete information, whether this be the cover (excluding a separate book jacket), caption, colophon, running title, or other part.  Specify the part used as a title page substitute in a note.  If no part of the item supplies data that can be used as the basis of the description, take the necessary information from any available source.  If the information traditionally given on the title page is given on facing pages or on pages on successive leaves, with or without repetition, treat those pages as the title page.

The prescribed source(s) of information for each area of the description of printed monographs is set out below.  Enclose information taken from outside the prescribed source(s) in square brackets.

---

| Area                                    	| Prescribed Sources Of Information                                   	|
|-----------------------------------------	|---------------------------------------------------------------------	|
| Title and statement of responsibility   	| Title page*                                                         	|
| Edition                                 	| Title page, other preliminaries, colophon**                         	|
| Publication, distribution, etc.         	| Title page, other preliminaries, colophon                           	|
| Physical description                    	| The whole publication                                               	|
| Series                                  	| Series title page, monograph title page, cover, rest of publication 	|
| Note                                    	| Any source                                                          	|
| Standard number & terms of availability 	|                                                                     	|

---

*Title page includes a substitute.
**[Colophon: an inscription placed at the end of a book or manuscript usually with facts relative to its production; an identifying device used by a printer or a publisher]

2. Although shown for clarity, subfield |a sometimes does not show on MARC record in initial instance of use. 
3. Some subfields are repeatable and some are not. Check AACR2R if in doubt.
4. Colon space and Semicolon space precede some fields and are required formatting.  (Refer to note that follows.)
5. In some cataloging utilities subfield delimiters take the place of spaces when shown and additional spaces to meet AACR2R requirements should not be added; in other words, without subfields the space it occupied remains in the visible record.  (This is how the Sage Library System automation handles this and so the examples throughout this document follow this principle, though the punctuation section lists the AACR2R rules.)  OCLC records are an exception: when the subfield delimiters are suppressed in the display they do not leave the space they occupied behind.

For example:

	300 p.:|bill. ;|c25 cm. and  300 p. : |bill. ; |c25 cm. (OCLC)

would both display as:  300 p. : ill. ; 25 cm.  

Check out your own utility to see how they handle this.

6. The symbol | (pipe) represents the subfield delimiter in these standards. In OCLC records you see the symbol $ (dollar sign).
7. If an item is a continuation that is updated regularly (could be annually or more frequently) then attach to a bib with an “open entry” nature (serials, etc., e.g. Fodor’s).  (Refer to “Serials” for additional instructions.)


`010`	LCCN NUMBER (Optional)
Library of Congress control numbers (LCCN) (formerly called Library of Congress Card Number) are assigned by the Library of Congress and are supposed to be unique.  They are therefore one of the most important match keys when trying to detect duplicate bibliographic records.  However, publishers do not understand that LCCN are supposed to be unique.  They print the same LCCN on different editions of a work, therefore caution should be exercised in using this as a match point.

LCCN’s must be entered “normalized” according to one of the two formats below.  If you are using OCLC, it does the normalization for you.

There are two LCCN structures: structure A for numbers formed from 1898 through 2000, in which the year portion consists of two digits; and structure B for numbers formed beginning in 2001, in which the year portion consists of four digits.

Structure A LCCN “normalization”:

- a lower case, left-justified, alphabetic prefix to a maximum of three characters or three blank spaces – these prefixes and leading spaces are very important and must be retained
- two digits meaning the year in which the item was cataloged
- a six digit, zero-filled, sequential serial number
- a blank space
- variable suffixes/alphabetic identifier and revision dates, preceded by slashes
- total length should be 8 digits (plus any prefixes and/or suffixes)

The number in printed form may look like these:

85-8191	agr23-452	46-8246 /MN/AC	

The above numbers normalized would look like these (^ represents a blank space):

	|a^^^85008191^	
	|aagr23000452^
	|a^^^46008246^/MN/AC

Structure B LCCN “normalization”:

- a lower case, left-justified, alphabetic prefix to a maximum of two characters or two spaces
- four digits meaning the year in which the item was cataloged
- a six digit, zero-filled, sequential serial number
- total length should be 10 digits (plus any prefixes)

The number in printed form may look like these:
	n2001-50284		2002-378	my2001-50268
The above numbers normalized would look like these (^ represents a blank space):

	|an^2001050284
	|a^^2002000378
	|amy2001050268

`020`	ISBN NUMBER (Optional)		
An ISBN is a unique number assigned to an item by its publisher.  Each ISBN number is a ten-digit number and has four parts, or a thirteen-digit number and has five parts.  If printed in a book, the four/five parts are separated by hyphens.  Enter without hyphens and add any qualifiers that describe the item.

	|a2214306080
	|a0842270884 (pbk.)
	|a9780545010221

Note:  Although this number is supposed to be unique, it often is not so caution should be exercised in using this as a match point.

`040`	CATALOGING SOURCE (Required)
Original source of the cataloging data (subfield |a), contributor of cataloging data, and if applicable, the modifier of cataloging data (subfield |d).  Use OCLC or USMARC code that uniquely identifies your location.  (See OCLC code list).  For example:

	|aOXU 
	|aUMT	|dLGRND

`092`	LOCALLY ASSIGNED DEWEY CALL NUMBER (Insert in item record to display in catalog)
Call numbers based on Dewey Decimal Classification.  

`099`	LOCALLY FREE-TEXT CALL NUMBER (Insert in item record to display in catalog)

`100`	MAIN ENTRY – PERSONAL NAME (Required if present)
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

`110` This field is used for Corporate Author main entry only if document is internal corporate document. To trace a corporate entity otherwise related to the work, generally use 610 field if subject and 710 field if not.

`245`	TITLE STATEMENT (Required)
The title statement is the title proper and may also include a general material designation (form if other than book, i.e. [text (large print)]), subtitle, other title information, and the statement of responsibility (name of author or editor).  If you need to use a general material designation, use subfield |h after subfield |a.  A list of approved designations is included in Attachment 1.

The first indicator should be 1 if MarcTag 100 (author) is used.  Otherwise use 0. For second indicator use 0 if title does not begin with an article.  Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

For title use subfield |a

	245 10 |aOrigins
	245 12 |aA field guide to wildflowers
	245 14 |aThe Clan of the Cave Bear
For general material designation use subfield |h.

	245 10 |aMathematics|h[kit]
	245 14 |aThe spirit horses|h[text (large print)]
For the subtitle use |b

	245 00 Records :|bfrom a summer day 

Note: Subfield |b follows subfield |h if used

For statement of responsibility (name of author or editor or corporation) use subfield |c.  

	245 14 |aThe life of the mind /|cHannah Arendt.
	245 10 |a American gospel|h[text (large print)] :|bGod, the founding fathers, and the making of a nation /|cJon Meacham
	245 00 |aApplication statistics /|cprepared by Research Council of Downstairs University ; edited by Russell White.

Note:  Subfield |c follows subfield |h if used.

Punctuation: 
subfield |b is preceded by space colon space
subfield |c (statement of responsibility) is preceded by space forward-slash space, each subsequent statement of responsibility is preceded by space semicolon space subfield |h is preceded by a space only and is enclosed in brackets. 245 field ends with a period. 

`246`	VARIANT TITLE (Optional) (prior to 1995, placed in 740 field).
Examples are caption titles, spine titles, running titles.

Punctuation: 
See rules for 245 field. No ending punctuation is added to a 246 field. 

`250`	EDITION STATEMENT (Required if applicable)
Refer to the edition statement proper and any other information up to the imprint.  Use only if the edition statement is self-defining, that is uses words such as edition, issue, version.  Numbers may appear with an edition statement. For items that use revised alone use abbreviation Rev. as in example.  If you are aware that an item is a revision but is not shown in book, you may put Rev. in square brackets per example.  Use subfield |a for edition statement

	|aEd. 1965-66.
	|a1st ed., corr. printing.
	|a3rd impression (with minor revisions).
	|aRev. ed.
	|a[Rev.].
	|a[Book club ed.].

Punctuation:  250 field always ends with a period.

`260`	PUBLICATION, DISTRIBUTION, IMPRINT (Required)
The imprint statement may include place of publication, publisher, place of distribution, distributor (if given), date of publication, copyright date.  Use square brackets to correct erroneous information or for clarification.  No indicators are assigned.

PLACE OF PUBLICATION
Use subfield |a for place of publication.  Supply the name of the country, or state or province for U.S. or Canadian publishers respectively, if it is considered necessary for identification or distinction and enclose in parentheses if not stated in chief source of information (see Note #1).  Use abbreviations supplied in Attachment 2.

	|aStony Brook, N.Y.
	|aLondon  (Ont).
	|aBelfast [i.e. Dublin]Ireland

If two places are recorded, enter each place name in separate subfield |a.  Enter first place given and one place in country of cataloging if they are different. Other places of publication may be omitted. 

	|aLondon ;|aNew York

If the probable place of publication cannot be determined, use the abbreviation [S.l.] which stands for sine loce, without place. 

	|a[S.l.]

The “S” is capitalized because it begins the field.

NAME OF PUBLISHER OR DISTRIBUTOR
Give publisher in shortest distinguishing form, omitting generic words such as Co., Inc. or Ltd.

Use subfield |b for name of publisher or distributor.

	|aNew York :|bWarner
	|aLondon :|bRoyal Geographical Society

If two publishers or distributors are named, enter each name in a separate subfield |b.

	|aNew York :|bAmerican Broadcasting Co. :|bReleased by Xerox Films

If probable publisher or distributor is unknown, use the abbreviation [s.n.] which stands for sine nominee, without name.

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
within 260 subfield |a (place of publication), space semicolon space precedes a second place name in a separate subfield |a space colon space precedes each subfield |b (publisher) comma space precedes subfield |c (date) end 260 subfield |c with a period, unless another mark of  punctuation (such as a bracket or hyphen) is present

`300`	PHYSICAL DESCRIPTION OF THE ITEM (Required)
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

`440`	SERIES STATEMENT  (Required if applicable)
Use for series statements to be traced by a series title.  A tracing refers to an access point in the catalog for the series title.  Look in Sage, Summit or Library of Congress databases under title to check for the correct form of the tracing (the authority record).  

(If you choose not to trace a series statement or to trace it differently use tag 490. A 490 tag is used if series author is listed or if entire series is known to be by the author of the book in hand.)

Use 440 tag if series does not list an exclusive author, e.g. the series is a publisher’s series and the series statement transcribed exactly as given on the resource matches the Library of Congress Authority file exactly..

The first indicator is blank.

For second indicator use 0 if title does not begin with an article. Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

Subfield |a contains the title portion of the series exclusive of any name, number of parts, volume numbering and ISSN.

	440  4	|aThe search series

Use subfield |v for the volume number or other sequential designations used in conjunction with the series statement.  Use the 642 field in the Authority record to determine the format, ie: no.1 or #1

	|aThis is America ;|vno. 1

Use subfield |x for ISSN number if available.  Subfield |x precedes subfield |v if present

	|aEarth Science series,|x4522-1277 ;|vv. 12

`490`	SERIES STATEMENT (Required if applicable)
Use 490 first indicator 0 if you do not trace; 490 first indicator 1 if you trace
differently.  If you use a 490 1, an 800 field for the correct form of the tracing is required.  

A first indicator of 0 indicates a series not traced. Use subfield |a for author or title.

	490 0  |aNonesuch geographical studies

Use indicator 1 if series traced by author.  Then add Marc Tag 800 per example that follows:

	490 1  |aGellerman effective supervision studies
	800 1  |aGellerman, Paul.|tGellerman effective supervision studies ;|vno. 12.

Punctuation:  
No ending punctuation is added to 440 or 490 fields.
440 or 490 subfield |v is always preceded by space semicolon space
440 or 490 subfield |x is always preceded by a comma space

`500`	GENERAL NOTES (If Needed)
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

`504`	BIBLIOGRAPHY NOTE (If needed)
Note about bibliography, discography, filmography, and/or other bibliographic references in an item.

Examples:

	|aIncludes bibliography.
	|aIncludes bibliographical references and index.
	|aDiscography: p. 150-152.

Punctuation:  Always end field with a period.

`505`	CONTENTS NOTE (Optional)
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
space hyphen hyphen space ( -- ) is entered between each item statements of responsibility are preceded by space forward slash space ( / ) end field with a period or other ending punctuation or > (angle bracket), but period after closing ] or ) – [but if note is incomplete or continues in the following 505 then none, unless the last word ends with its own punctuation]refer to AACR2 for punctuation for use of subfields |t, |r, and |g

`526`	STUDY PROGRAM INFORMATION NOTE (Optional)
This field contains information about any study program(s) which use the work that is described by the record.  The field is repeatable. First indicator 0 is for reading program; second indicator is blank

	|a Program name
	|b Interest level – assigned by the study program
	|c Reading level - assigned by the study program
	|d Title point value - assigned by the study program
	|5 Institution to which field applies
	526 0_ |aAccelerated Reader|b5.0|c4.0|d75.|5OMS

Punctuation:  
This field ends with a period unless another mark of punctuation is present.  If the final subfield is subfield |5, the mark of punctuation precedes that subfield.


`586`	AWARDS NOTE  (Optional)
This field contains information on awards associated with the described item. The field is repeated for each occurrence of an award.

The first indicator contains a value that controls the generation of a display constant preceding the note (a blank is used to generate the display constant Awards:, an 8 specifies no display constant is generated).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the awards note.

Punctuation:
No ending punctuation is added to 586 fields.

`6XX`   SUBJECT HEADINGS (At least one subject heading is required for non-fiction.)  

`600`	SUBJECT ADDED ENTRY-PERSONAL NAME
Use for personal names used as subject added entries such as:  names of persons who actually or probably lived, personal author/title subject added entries, and names of families. For example use for Burbank, Luther or Sacagawea.

The first indicator is 1 for a single surname and 3 for a family name  The second indicator refers to subject authority on which you base the subject entry.  Use 0 for Library of Congress (LC) subject headings. 

This Marc tag needs to follow LC standards. Try finding a match from the Sage, Summit or Library of Congress databases. Enter names selected in the subject search in database. Try different selections until you find a possible fit.  Another way is to identify another book by the same author that has already been cataloged.  Look in the cataloged record for possible Subject Heading-Personal Name that would fit. When you have chosen a match, convert the catalog entry to a Marc Record. Enter into tag 600 exactly as you view in Marc format with the same indicators, and subfields.

`650`	SUBJECT ADDED ENTRY – TOPICAL TERM
Use for topical subject entry assigned by LC or assigned by an agency based on LC or LC Annotated Card Program (Subject Headings for Children’s Literature).  This Marc tag needs to follow LC standards. Try finding a match from the Sage, Summit or Library of Congress databases. Enter words related to the subject of the book with the Subject search.  Try different words till you find a fit.  Another way is to identify another book by the same author that is similar in content and has already been cataloged.  Search for title and see if subject headings used will fit your item.  Convert chosen record to Marc Record.  Enter Marc tag indicator numbers and subfields exactly as you view them.  

`651`	SUBJECT ADDED ENTRY – GEOGRAPHIC NAME
Use for geographic subject entries actually assigned by Library of Congress Subject Headings.  This would include place names such as Yellowstone National Park or Portland (Or.).  As above, would suggest searching Sage, Summit or Library of Congress databases. Search under Subject for geographic names.  If you find suitable subject entry, convert the entry to Marc Record and copy the indicators and subfields exactly as found.  

Punctuation: 
A period is placed at the end of the last subfield, unless it ends with a hyphen or parenthesis. (The dashes normally shown preceding subfields v, x, y, and z are not carried in a MARC record. They are inserted by computer programs for public display of record.)

`655`	GENRE/FORM INDEX TERM (Optional)
This field contains a term indicating the genre, form or physical characteristic of a resource (what a resource is about). First indicator is typically left blank; second indicator Use 4 if the source is not specified (including local headings)

	655 _4 |aOregon authors.
Use 7 if the source is specified in |2

	655 _7 |aSuspense fiction.|2gsafd

Punctuation:  
Subfield |a is preceded by a period 

`700`	ADDED ENTRY – PERSONAL NAME  (Added title optional)
Make an added personal name entry under the heading for a prominently named editor or compiler of monographic work.  Make an added personal name entry for an illustrator if the illustrations are considered to be an important feature of the work.  Make an added personal name entry for any other name that would provide an important access point not treated in another entry. It is best to match names to authority files already in use.  To do this, you can search the Sage, Summit, or Library of Congress databases. Using the author search selection choose the individual listed in item being cataloged.  Convert selected record to Marc Record and follow spelling and dates given there to fill in this Marc tag. 
	
For first indicator, use 0 for a recognized forename such as Plato.  Use 1 for usual surname entries.  Use second indicator if adding a title, using 2. Use subfield |a for name and use subfield |d for dates if known

	700 1	|aHemingway, Ernest,|d1899-1961.
	700 0	|aHomer.	
Use subfield |t to add a title to this field which will be traced by author in the database.    

	700 12  |aBeethoven, Ludwig van,|d1770-1827.|tC major symphony.

Punctuation:  End field with a period.

`740`	TITLE ADDED ENTRY (Optional)
Variant titles appear in field 246.
Use for tracing specific titles in 505 contents note.
Use for titles recorded in 245 subfield |b if desired.

Punctuation:  End field with a period unless other form of punctuation is present.

`800`	SERIES ADDED ENTRY – PERSONAL NAME/TITLE (Required if 490 1  field present)
This field is used when all books in a series are written by the same author. Follow all rules for entry of author in 100 field. Title is added in subfield |t.  (It will be traced in online catalog). If volume number is present it is added in subfield |v.

	800 1  |aGellerman, Paul.|tGellerman effective supervision studies ;|vno. 12.

Punctuation:  
Subfield |t is preceded by a period space.
Subfield |v is preceded by space semicolon space.
Field ends with a period.

`9XX`	LOCAL USE TAGS
Check with Sage System staff if you choose to use any of these fields. 

Use the following for tagging incomplete bib records.
999   |aFLAGGED

<a name="catm_multipart_holdings"></a>

- Moved from 2.1 to more recent 2.5 information:
	- [Adding Monograph Parts](http://docs.evergreen-ils.org/2.5/_monograph_parts.html)


<a name="catm_rda_material_type"></a>
MARC fields for RDA material description (vs. GMD)

NOTE: The general material designation (GMD) is expressed in MARC for AACR2r as 245 $h.  MARC for RDA replaces this subfield with a “triple” of fields (336/7/8) identifying content, media format and carrier or physical format of the cataloged item.  This allows the given work to be distinguished by the RDA categories of “expression” and “manifestation” in catalog search with greater precision than before.   These fields can be repeated to describe multi-format items (e.g. kits) – and individually repeated for complex description (see “Video Game” below). It is the policy of the Sage Cataloging Committee to retain subfield 245 $h where found as an aid to patrons, and to create/populate field 999 based on its value or the values of fields 336/7/8, as available. 

Book or Magazine (N.B. Large Print, Juvenile, etc. not distinguished):

	=336 \\$a text $2 rdacontent
	=337 \\$a unmediated $2 rdamedia
	=338 \\$a volume $2 rdacarrier

Audiobook (CD):

	=336 \\$a spoken word $2 rdacontent
	=337 \\$a audio $2 rdamedia
	=338 \\$a audio disc $2 rdacarrier

Audiobook (Cassette tape):

	=336 \\$a spoken word $2 rdacontent
	=337 \\$a audio $2 rdamedia
	=338 \\$a audio cassette $2 rdacarrier

Recorded Music (CD):

	=336 \\$a performed music  $2 rdacontent
	=337 \\ $a audio $2 rdamedia
	=338 \\$a audio disc $2 rdacarrier

DVD or Blu-Ray Video (n.b. not distinguished):

	=336 \\ $a two-dimensional moving image $2 rdacontent
	=337 \\$a video $2 rdamedia
	=338 \\$a videodisc $2 rdacarrier

VHS Video:

	=336 \\ $a two-dimensional moving image $2 rdacontent
	=337 \\$a video $2 rdamedia
	=338 \\$a video cassette $2 rdacarrier

E-book or Web site (e.g. OverDrive title):

	=336 \\$a text $2 rdacontent
	=337 \\$a computer $2 rdamedia
	=338 \\$a online resource $2 rdacarrier

Computer Disc (CD-ROM)

	=336 \\$a text $2 rdacontent
	=337 \\$a computer $2 rdamedia
	=338 \\$a  computer disc $2rdacarrier

Video Game:

	=336 \\$a two-dimensional moving image  $2 rdacontent
	=336 \\$a computer program $2 rdacontent
	=337 \\$a computer $2 rdamedia
	=338 \\$a computer disc $2 rdacarrier

It can be seen that by using appropriate values in these fields, a wide range of “material types” (AACR2r) can be established (e.g. “Recorded Music – Cassette” substitutes “audio cassette” in 338 $a).  These values for $a are drawn from controlled vocabularies, which can be found at the following links:

- [LOC RDA Content Terms (336 $a)](http://www.loc.gov/standards/valuelist/rdacontent.html)
- [LOC RDA Media Terms (337 $a)](http://www.loc.gov/standards/valuelist/rdamedia.html)
- [LOC RDA Carrier Terms (338 $a)](http://www.loc.gov/standards/valuelist/rdacarrier.html)

<a name="catm_required_fields_book"></a>

#####Required MARC fields for biblographic records

- Type: Book (Monograph)

TAG				CONTENTS

	008*			Fixed-length data elements (see in Appendices)
	010				LCCN number
	020				ISBN number
	040*			Code for source of cataloging
	100*			Name of author from statement of responsibility/editor goes in 700 
	245*			Title : subtitle / statement of responsibility
	246				Variant title
	250*			Edition information if available
	260*			Imprint information:  Place of publication ; Publisher ; date(s)
	300*			Physical description:  pagination, illustration types, size in cm.
	440* or 490*	Series statement if needed
	500				General notes
	504				Bibliography note
	505				Contents note
	586				Awards note
	6XX’s*			For non-fiction, at least one subject entry is required
	700				Added personal name entry i.e. editor or illustrator if significant
	740				Title added entry
	8XX*			Series added entry - if 490 1 is present


All fields are important and preferred if the information is available.
The starred fields are required.

<a name="catm_required_fields_serial"></a>

- Type: Serial

TAG				CONTENTS

	008*			Fixed-length data elements (see in Appendices)
	010				LCCN number
	022				ISSN number
	040*			Code for source of cataloging
	100*			Name of author from statement of responsibility/editor goes in 700 
	245*			Title : subtitle / statement of responsibility
	246				Variant title
	250*			Edition information if available
	260*			Imprint information:  Place of publication ; Publisher ; date(s)
	300*			Physical description:  pagination, illustration types, size in cm.
	310				Frequency
	440* or 490*	Series statement if needed
	500				General notes
	504				Bibliography note
	505				Contents note
	6XX’s*			For non-fiction, at least one subject entry is required
	700				Added personal name entry i.e. editor or illustrator if significant
	740				Title added entry
	8XX*			Series added entry - if 490 1 is present


All fields are important and preferred if the information is available.
The starred fields are required.

<a name="catm_required_fields_sound_rec"></a>

- Type: Sound Recording

TAG				CONTENTS

	007*			Physical description fixed field (see in Appendices)
	008*			Fixed-length data elements (see in Appendices)
	020				ISBN number
	024				Other standard identifier
	028				Publisher number
	040*			Code for source of cataloging
	100*			Name of author from statement of responsibility/editor goes in 700 
	245*			Title : subtitle / statement of responsibility
	246				Variant title
	250*			Edition information if available
	260*			Imprint information:  Place of publication ; Publisher ; date(s)
	300*			Physical description: Extent (# of physical units), other physical details, dimensions
	306				Playing time
	440* or 490*	Series statement if needed
	500				General notes
	505				Contents note
	511*			Participant or Performer note
	586				Awards note
	6XX’s*			For non-fiction, at least one subject entry is required
	700				Added personal name entry i.e. editor or illustrator if significant
	740				Title added entry
	8XX*			Series added entry - if 490 1 is present


All fields are important and preferred if the information is available.
The starred fields are required.

<a name="catm_video_rec_standards"></a>

- Type: Video Recordings

TAG				CONTENTS

	007*			Physical description fixed field (see in Appendices)
	008*			Fixed-length data elements (see in Appendices)
	020				ISBN number
	024				Other standard identifier
	028				Publisher number
	040*			Code for source of cataloging
	100*			Name of author from statement of responsibility/editor goes in 700 
	245*			Title : subtitle / statement of responsibility
	246				Variant title
	250*			Edition information if available
	260*			Imprint information:  Place of publication ; Publisher ; date(s)
	300*			Physical description: Extent (# of physical units), other physical details, dimensions
	440* or 490*	Series statement if needed
	500				General notes
	505				Contents note
	508				Credits note
	511*			Participant or Performer note
	520				Summary, etc. note
	538*			System details note
	546				Language note
	586				Awards note
	6XX’s*			For non-fiction, at least one subject entry is required
	700				Added personal name entry i.e. editor or illustrator if significant
	740				Title added entry
	8XX*			Series added entry - if 490 1 is present


All fields are important and preferred if the information is available.
The starred fields are required.

<a name="catm_serial_standards"></a>

##### Standards For Serial Records

1.	Search your bibliographic utility for the serial.  Seldom will you have to edit a serials record, as they are open ended so have no pagination information.

2.	Be sure that the record is in fact a serial.
		a.	The record may contain an 022 field, the ISSN number, indicating beyond a doubt that the record is a serial.
		b.	If you search by title, such as Fodor’s China, you will find a serials record without an ISSN.  The book in hand has an ISBN, and the record has no ISSN, but other clues indicate that this is indeed a serial.
		c.	A serials record is open ended.  There will be no pagination or publication date,  there will be a 222 field indicating the unique title assigned by the ISSN national center, and there will usually be information about frequency of publication,  previous editions, and previous publishers.

3.	Do not assume that because a book has regular updates that it is a serial.  For example, Moon Travel Guides publishes frequent editions, but these are not considered to be a serials.  Use the other clues.  Cataloging with AACR2 and USMARC provides detailed instruction for matching.

4.	If you cannot verify by either ISSN or other sources (Library of Congress, ORBIS, etc.) that your item is in fact a serial, it is recommended that you catalog as if it is a monograph.

5.	In some cases you will assume the record is a serial even without the verification.  This happens with the Fodor’s travel guides.  All Fodor’s travel guides are considered to be serials, but you may not be able to find an existing record for the particular country in question.  For example, Fodor’s Turkey does not have a record in the Library of Congress, but since all other Fodor’s are serials you can assume that this one is, too.  In this case you should create an original record.

6.	It is beyond the scope of this document to detail the original cataloging of serials.  If you need guidance, contact a member of the Cataloging Committee.

<a name="catm_sound_rec_standards"></a>
RECOMMENDED STANDARDS FOR BIBLIOGRAPHIC RECORDS – SPECIFIC TO SOUND RECORDINGS
Developed by Cataloging Committee, 2004

##### Standards For Sound Records

Notes:

1. The chief sources of information for each field for sound recordings records are listed in AACR2R. The chief source of information for each major type of sound recording  is set out here. 

		TYPE						CHIEF SOURCE
		Disc						Disc and label*
		Tape (open reel-to-reel)	Reel and label
		Tape cassette				Cassette and label
		Tape cartridge				Cartridge and label
		Roll						Label

Label means any permanently affixed paper, plastic, etc. label as opposed to the container itself, which may have data embossed or printed on it. Treat accompanying textual material or a container as the chief source of information if it furnishes a collective title and the parts themselves and their labels do not.  In this case make a note indicating the chief source of information.  If information is not available from the chief source, take it from the following sources (in order of preference): accompanying textual material container (e.g. sleeve, box)
other sources Prefer textual data to sound data.  For example, if a sound disc has a label and also information presented in sound form on the disc, prefer the label information. 

The prescribed source(s) of information for each area of the description of sound recordings is set out below.  Enclose information taken from outside the prescribed source(s) in square brackets.

	AREA									PRESCRIBED SOURCES OF INFORMATION
	Title and statement of responsibility	Chief source of information
	Edition									Chief source of information, accompanying textual material, container
	Publication, distribution, etc.			Chief source of information, accompanying textual material, container
	Physical description					Any source
	Series									Chief source of information, accompanying textual material, container
	Note									Any source
	Standard number & terms of				Any source availability
2. Although shown for clarity, subfield |a sometimes does not show on MARC record in initial instance of use. 
3. Some subfields are repeatable and some are not. Check AACR2R if in doubt.
 
4. Colon space and Semicolon space precede some fields and are required formatting.
5. In some cataloging utilities subfield delimiters take the place of spaces when shown and additional spaces to meet AACR2R requirements should not be added; in other words, without subfields the space it occupied remains in the visible record.  (This is how the Pioneer Library System automation handles this and so the examples throughout this document follow this principle.)  OCLC records are an exception: when the subfield delimiters are suppressed in the display they do not leave the space they occupied behind.  
For example,  300 p. :|bill. ;|c25 cm. and  300 p. : |bill. ; |c25 cm. (OCLC) would both display as  300 p. : ill. ; 25 cm. Check out your own utility to see how they handle this.

6. The symbol | (pipe) represents the subfield delimiter in these standards. In OCLC records you see the symbol $ (dollar sign).

`020`	ISBN NUMBER (Optional)		
An ISBN is a unique number assigned to an item by its publisher.  Each ISBN number is a ten-digit number and has four parts.  Enter without hyphens and add any qualifiers that describe the item.

	|a1590868188
	|a1559351500 (set)

Note:  Although this number is supposed to be unique, it often is not, so caution should be exercised in using this as a match point.

`024`	OTHER STANDARD IDENTIFIER (Optional)
A standard number or code published on an item which cannot be accommodated in another field.  The type of standard number or code is identified in the first indicator position or in subfield |2 (Source of number or code).

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

Examples:

	024 1_ |a5794368779
	024 3_ |a9781578155293
	024 3_ |a9780553528152|d52595

`028`	PUBLISHER NUMBER (Optional)
The formatted number used for sound recordings, printed music, and videorecordings. Publisher’s numbers that are given in an unformatted form are recorded in field 500 (General Note).  A print constant identifying the kind of publisher number may be generated based on the value in the first indicator position.

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

Examples:

	028 02 |aRH/2103|bRandom House Audio
	028 00 |aBDDAP 094|bBantam Audio

040	CATALOGING SOURCE (Required)
Original source of the cataloging data (subfield |a), contributor of cataloging data, and if applicable, the modifier of cataloging data (subfield |d).  Use OCLC or USMARC code that uniquely identifies your location.  (See OCLC code list).  For example:

	|aOXU 
	|aUMT
	|dLGRND

`092`	LOCALLY ASSIGNED DEWEY CALL NUMBER (Optional - This field does not show up on database)
Call numbers based on Dewey Decimal Classification.  

`099`	LOCALLY FREE-TEXT CALL NUMBER (Optional - This field does not show up on database)

100	MAIN ENTRY – PERSONAL NAME (Required if present)
A personal name is the name of the person responsible for the creation of the intellectual or artistic content of an item as prominently displayed.  Use of this field relates to the statement of responsibility as found following title.  For an editor, use Marc tag 700 rather than this tag.  Do not use this tag for a corporation or organization given in statement of responsibility.  Just use title entry instead and trace corporate authors in 710. It is best to match names to authority files already in use.  To do this, you can search the Pioneer, Orbis or Library of Congress databases using the author search selection for the author listed in item being cataloged.  Then select one record by author and convert to a Marc Tag display.  Fill in spelling and dates given. Use subfield |a for name, subfield |q for expanded name, and subfield |d for date, if available.

This field may be used only once.  Additional authors go in 700 field.

	|aGrisham, John.
	|Braddbury, Ray,|d1920-
	|aLewis, C. S.|q(Clive Staples),|d1893-1963.
	|aJohn Paul|bII,|cPope,|d1920- 

Punctuation:

Subfield |b is preceded by a space only
subfield |c is preceded by a comma space 
subfield |d is preceded by a comma space
subfield |q is preceded by a space only and placed in parentheses
100 field ends with a mark of punctuation or a closing parenthesis “)”

`245`	TITLE STATEMENT (Required)
The title statement is the title proper and may also include a general material designation (form if other than book, i.e. sound recording), subtitle, other title information, and the statement of responsibility (name of author or editor).  If you need to use a general material designation, use subfield |h after subfield |a.  A list of approved designations is included in Attachment 1 of “Recommended Standards for Bibliographic Records: Developed by Cataloging Work Team, 2002.”

The first indicator should be 1 if MarcTag 100 (author) is used.  Otherwise use 0.
For second indicator use 0 if title does not begin with an article.  Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

For general material designation (GMD) use subfield |h.  

	245 10 |aEight cousins|h[sound recording]
	245 14 |aThe sounds of Christmas|h[sound recording]
For the subtitle use |b

	245 04 The Civil War|h[sound recording] :|bits music and its sounds 

Note: Subfield |b follows subfield |h. 

For statement of responsibility (name of author or editor or corporation) use subfield |c. 

Transcribe statements of responsibility relating to those persons or bodies credited with a major role in creating the intellectual content of the sound recording (e.g., as writers of spoken words, composers of performed music, collectors of field material, producers 
having artistic and/or intellectual responsibility) in the form in which they appear.  If the participation of the person(s) or body (bodies) named in a statement found in the chief source of information goes beyond that of performance, execution, or interpretation of a work (as is commonly the case with “popular,” rock, and jazz music), give such a statement as a statement of responsibility.  If however, the participation is confined to performance, execution, or interpretation (as is commonly the case with “serious” or classical music and recorded speech), give the statement in the note area.

Add a word or short phrase to the statement of responsibility, in brackets, if the relationship between the title and the person(s) or body (bodies) named in the statement is not clear. 

	245 14 |aThe land that time forgot|h[sound recording] /|cby Edgar Rice Burroughs.
	245 10 |aEndurance|h[sound recording] :|bShackleton’s incredible voyage /|cby Alfred Lansing.
	245 10 |aBorn to run|h[sound recording] /|c[written and performed by] Bruce Springsteen.

Note:  Subfield |c follows subfield |h.

Punctuation: 

subfield |b is preceded by space colon space
subfield |c (statement of responsibility) is preceded by space forward-slash space, each subsequent statement of responsibility is preceded by space semicolon space subfield |h is preceded by a space only and is enclosed in brackets. 245 field ends with a period. 

`246`	VARIANT TITLE (Optional) (prior to 1995, placed in 740 field).
Examples are other titles, caption titles, spine titles, running titles.

Punctuation: 
See rules for 245 field. No ending punctuation is added to a 246 field. 

`250`	EDITION STATEMENT (Required if applicable)
Refer to the edition statement proper and any other information found in the prescribed sources of information (see note #1 on page 1).  Use only if the edition statement is self-defining, that is uses words such as edition, issue, version.  Numbers may appear with an edition statement. For items that use revised alone use abbreviation Rev. as in example.  Use subfield |a for edition statement

	|aRev. ed.
	|a[Rev.].

Punctuation:  250 field always ends with a period.

`260`	PUBLICATION, DISTRIBUTION, IMPRINT (Required)
The imprint statement may include place of publication, publisher, place of distribution, distributor (if given), date of publication, copyright date.  Use square brackets to correct erroneous information or for clarification.  No indicators are assigned.

PLACE OF PUBLICATION
Use subfield |a for place of publication.  Supply the name of the country, or state or province for U.S. or Canadian publishers respectively, if it is considered necessary for identification or distinction and enclose in parentheses if not stated in prescribed sources of information (see note #1 on page 1).  Use abbreviations supplied in Attachment 2 of “Recommended Standards for Bibliographic Records: Developed by Cataloging Work Team, 2002.”

	|aAuburn, Calif.
	|aLondon (Ont).
	|aBelfast [i.e. Dublin] (Ireland)

If two places are recorded, enter each place name in separate subfield |a.  Enter first place given and one place in country of cataloging if they are different. Other places of publication may be omitted.

	|aWestmount, Quebec ;|aPlattsburgh, N.Y.

If the probable place of publication cannot be determined, use the abbreviation [S.l.] which stands for sine loce, without place. 

	|a[S.l.]

The “S” is capitalized because it begins the field.

NAME OF PUBLISHER OR DISTRIBUTOR
Give publisher in shortest distinguishing form, omitting generic words such as Co., Inc., or Ltd.

Use subfield |b for name of publisher or distributor.

	|aHampton, N.H. :|bChivers North America
	|aDon Mills, Ont. :|bFederation of Ontario Naturalists

If two publishers or distributors are named, enter each name in a separate subfield |b.

	|aLondon :|bGandalf Records :|bDistributed by Middle Earth

If probable publisher or distributor is unknown, use the abbreviation [s.n.] which stands for sine nominee, without name.

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
within 260 subfield |a (place of publication), space semicolon space precedes a second place name in a separate subfield |a space colon space precedes each subfield |b (publisher) comma space precedes subfield |c (date) end 260 subfield |c with a period, unless another mark of punctuation (such as a bracket or hyphen) is present

`300`	PHYSICAL DESCRIPTION OF THE ITEM (Required)
Use subfield |a for extent. Record the number of physical units of a sound recording by giving the number of parts in arabic numerals and one of the following terms as appropriate:

	sound cartridge
	sound cassette
	sound disc
	sound tape reel
	sound track film
	add reel, cassette, etc. as appropriate to sound track film.
<code>[name of instrument]</code> roll, as appropriate, for rolls.  e.g.  <code>2 piano rolls</code>
If none of these terms is appropriate, give the specific name of the item as concisely as possible.

Also give playing time of a sound recording in parentheses following number of physical units and the term as listed out here.  If it is given on the item, give it as stated.  If it is not stated on the item but is readily ascertainable, give it.  Optionally, if the playing time is neither stated on the item nor readily ascertainable, give an approximate time.  Optionally, if the parts of a multipart item have a stated uniform playing time or an approximate uniform playing time, give the playing time of each part followed by each.  Otherwise, give the total duration.

	|a1 sound disc (50 min.)
	|a1 sound track film reel (10 min.)
	|a2 sound cassettes (ca. 90 min.)
	|a31 sound cassettes (60 min. each)

Use subfield |b for other physical details (other than extent or dimensions) as follows, in order given:

<b>Type of recording:</b>

- for disc or tape: analog or digital
- for sound track film: optical or magnetic
- Playing speed: (only if non-standard) – i.e.you would give it for vinyl records
- Groove characteristics: (only if non-standard) – i.e. you would give it for vinyl records
- Track configuration: (only if non-standard)
- Number of tracks (sound track films)
- Number of sound channels:  mono., stereo., quad.
- Recording and reproduction characteristics (optional): – e.g. Dolby processed,NAB standard

		|a1 sound cassette (90 min.) :|banalog
		|a1 sound cassette (60 min.) :|bdigital
		|a1 sound disc (7 min.) :|banalog, 78 rpm, microgroove
		|a1 sound tape reel (ca. 60 min.) :|banalog, 7 1/2 ips, 2 track, mono.
		|a1 sound cassette (60 min.) :|banalog, stereo., Dolby processed	

Use subfield |c for dimensions as follows:
If the sound recordings in a multipart item differ in size, give the smallest or smaller and the largest or larger size, separated by a hyphen.

- Sound discs: give the diameter of a disc in inches
- Sound track films: give the gauge (width) of a film in millimeters
- Sound cartridges: give the dimensions of a cartridge in inches if other than the standard dimensions (5 1/4 x 3 7/8 in.), give the width of the tape in fractions of an inch if other than the standard width (1/4 in.)
- Sound cassettes: give the dimensions of a cassette if other than the standard dimensions (analog cassette: 3 7/8 x 2 1/2 in.), give the width of a tape if other than the standard width (analog tape is 1/8 in.) 
- Sound tape reels: give the diameter of a reel in inches, give the width of a tape in fractions of an inch if other than standards width (1/4 in.)
- Rolls: do not give any dimensions

		|a5 sound discs :|banalog, 33 1/3 rpm, stereo. ;|c10-12 in. 
		|a1 sound disc (50 min.) :|bdigital, stereo. ;|c4 3/4 in. 
		|a1 sound disc (45 min.) :|banalog, 78 rpm, microgroove, quad. ;|c12 in. 
		|a1 sound track film reel (10 min.) :|bmagnetic, 25 fps, centre track ;|c16 mm. 
		|a2 sound cassettes (90 min.) :|banalog, mono.
		|a1 sound cassette (85 min.) :|banalog, mono. ;|c7 1/4 x 3 1/2 in., 1/4 in. tape. 
		|a1 sound tape reel (60 min.) :|banalog, 7 1/2 ips, 2 tracks, mono. ;|c7 in., 1/2 in. tape. 

Give the details of accompanying material (in subfield |e) as follows:

- make a separate entry
or	- make a multilevel description (see AACR2R)
or	- make a note
or	- give the number of physical units in arabic numerals and the name of the accompanying material (using, when appropriate, a specific material designation) at the end of the physical description.  Optional addition: if more detail is desired, give the physical description of the accompanying materials in parentheses.

	|a4 sound discs (210 min.) :|bdigital ;|c4 3/4 in. +|e1 pamphlet (31 p. : col ill. ; 11cm.).

Punctuation:  
	space colon space precedes subfield |b
	space semicolon space precedes subfield |c
	space plus sign (+) space precedes subfield |e
	end 300 field with a period (usually already present) 

`306`	PLAYING TIME (Optional)
	This field contains a formatted numerical representation of the playing time of the item.  
	Indicator positions are undefined and left blank.

Use subfield |a for the playing time of an item.  The playing time is six characters in length and is formatted hhmmss (2 for hour, 2 for minute, and 2 for second).  If the recording is less than 1 hour, the hour is recorded as two zeros; if less than a minute, the minute is also recorded as two zeros.  Subfield |a is repeatable to allow the recording of the playing time of two or more pieces.

	|a002016
[for 20 min., 16 sec.]

	|a014500
[for 1 hour, 45 min.]
	
	|a003100|a001839
[durations: 31:00 ; 18:39]

Note:   If more than six playing times are recorded in a note field, field 306 is generally not used.  If the abbreviation ca. precedes an approximate playing time in a note, this abbreviation is disregarded when recording data in field 306.

Punctuation:  
No ending punctuation is added to the 306 field.

`440`	SERIES STATEMENT  (Required if applicable)
Use for series statements to be traced by a series title.  A tracing refers to an access point in the catalog for the series title.  You can look in Pioneer, Orbis or Library of Congress databases under title to check for the correct form of the tracing (the authority record).  

(If you choose not to trace a series statement or to trace it differently use tag 490. A 490 tag is used if series author is listed or if entire series is known to be by the author of the book in hand.)

Use 440 tag if series does not list an exclusive author, e.g. the series is a publisher’s series.

The first indicator is blank. 

For second indicator use 0 if title does not begin with an article. Use 1-9 to indicate an article, plus spaces, punctuation, diacritics and underscores that precede the first significant word.  

Subfield |a contains the title portion of the series exclusive of any name, number of parts, volume numbering and ISSN.

	440  0	|aCollection Musiques anciennes

Use subfield |v for the volume number or other sequential designations used in 	conjunction with the series statement.  

	|aThis is America ;|vno. 1

`490`	SERIES STATEMENT (Required if applicable)
Use 490 first indicator 0 if you do not trace; 490 first indicator 1 if you trace differently.  If you use a 490 1  you must also have an 800 field for the correct form of the tracing.  

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

`5XX`	NOTES 

Refer to AACR2R rules in chapter 6 for order.

`500`	GENERAL NOTES (If Needed)
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

`505`	CONTENTS NOTE (Optional)
Contents notes contain titles of separate works or parts of an item.  They may also include statements of responsibility associated with the works or parts of an item.  Volume numbers and other sequential designations are included in the note.  Use for analytical titles of independent works contained within the items and for titles of related items. This note may also contain statements of responsibility.

The first indicator is used to indicate type of contents note.  Use 0 for full contents.  Use 2 for partial contents.  Indicator 1 is used for incomplete contents, i.e., when all parts of a set are not published yet.  

Use subfield |a for formatted contents note.  When all information is in subfield |a, the second indicator is blank.
 	
	505 2   |aTaxman -- Eleanor Rigby -- Love you to -- Here, there and everywhere -- Yellow Submarine -- She said she said -- Good day sunshine.	

If statement of responsibility is included in subfield |a it is preceded by a space / space whenever it occurs:

	505 2   |aThe big sleep / Raymond Chandler -- The Maltese falcon / Dashiell Hammett -- Dead pool / Ross MacDonald.

If subfields other than |a are used, the second indicator is 0 to indicate enhanced contents. Use subfield |t for title entries; subfield |r for statement of responsibility; subfield |g for miscellaneous information.  Any or all may be used. These subfields are repeatable.

	505  0  |tThe fourth millennium /|rHenry Brant|g(9:00) --|tMusic for brass quintet /|rPhilip Glass.
	505  0  |tBig sleep --|tMaltese falcon --|tDead pool.

Note: second space is omitted after dashes when a subfield code follows 
(i.e. subfield takes the place of the space).  See Note #5 at beginning of manual.

Punctuation:  
space hyphen hyphen space ( -- ) is entered between each item 
statements of responsibility are preceded by space forward slash space ( / )
end field with a period or other ending punctuation or > (angle bracket), but period after closing ] or ) – [but if note is incomplete or continues in the following 505 then none, unless the last word ends with its own punctuation] refer to AACR2R for punctuation for use of subfields |t, |r, and |g

`511`	PARTICIPANT OR PERFORMER NOTE (Required)
This field contains a note giving information about the participants, players, narrators, presenters or performers.  This field is repeatable.

The first indicator contains a value that controls the generation of a display constant preceding the note in the OPAC (a 0 is used to generate no display constant, a 1 is used to generate the display constant Cast:).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the participant or performer note.

	511 0  |aNarrator: Burl Ives.
	511 0  |aVoices: Peter Ustinov, Cloris Leachman, Sally Kellerman, Andy Devine.
	511 1  |aColin Blakely, Jane Lapotaire.

Punctuation:
Always end field with a period, unless other punctuation is present.

`538`	SYSTEM DETAILS NOTE (Required if applicable)
Indicators are undefined, so should be blank.  Subfield |a contains the entire text of the note.

	538 |aSystem requirements: CD/MP3 player or PC with MP3-capable software.

Punctuation:  
end field with a period unless another mark of punctuation is present.

`586`	AWARDS NOTE  (Optional)
This field contains information on awards associated with the described item. The field is repeated for each occurence of an award.

The first indicator contains a value that controls the generation of a display constant preceding the note in the OPAC (a blank is used to generate the display constant Awards:, an 8 specifies no display constant is generated).  The second indicator position is undefined and contains a blank.  

Use subfield |a for the awards note.

Punctuation:
No ending punctuation is added to 586 fields.

`6XX`   SUBJECT HEADINGS (At least one subject heading is required for non-fiction.)  

`600`	SUBJECT ADDED ENTRY-PERSONAL NAME
Use for personal names used as subject added entries such as:  names of persons who actually or probably lived, personal author/title subject added entries, and names of families. For example use for Burbank, Luther or Sacagawea.

The first indicator is 1 for a single surname and 3 for a family name  The second 		indicator refers to subject authority on which you base the subject entry.  Use 0 for Library of Congress (LC) subject headings. 

This MARC tag needs to follow LC standards. Try finding a match from the Pioneer, Orbis or Library of Congress databases. Enter names selected in the subject search in database. Try different selections until you find a possible fit.  Another way is to identify another book by the same author that has already been cataloged.  Look in the cataloged record for possible Subject Heading-Personal Name that would fit. When you have chosen a match, convert the catalog entry to a Marc Record. Enter into tag 600 exactly as you view in Marc format with the same indicators, and subfields.

650     SUBJECT ADDED ENTRY – TOPICAL TERM
Use for topical subject entry assigned by LC or assigned by an agency based on LC or LC Annotated Card Program (Subject Headings for Children’s Literature).  This Marc tag needs to follow LC standards. Try finding a match from the Pioneer, Orbis or Library of Congress databases. Enter words related to the subject of the book with the Subject search.  Try different words till you find a fit.  Another way is to identify another book by the same author that is similar in content and has already been cataloged.  Search for title and see if subject headings used will fit your item.  Convert chosen record to Marc Record.  Enter Marc tag indicator numbers and subfields exactly as you view them.  

`651`	SUBJECT ADDED ENTRY – GEOGRAPHIC NAME
Use for geographic subject entries actually assigned by Library of Congress Subject Headings.  This would include place names such as Yellowstone National Park or Portland (Or.).  As above, would suggest searching Pioneer, Orbis or Library of Congress databases. Search under Subject for geographic names.  If you find suitable subject entry, convert the entry to Marc Record and copy the indicators and subfields exactly as found.  

Punctuation: 
A period is placed at the end of the last subfield, unless it ends with a hyphen or parenthesis.
(The dashes normally shown preceding subfields v, x, y, and z are not carried in a MARC record. They are inserted by computer programs for public display of record.)

`700`	ADDED ENTRY – PERSONAL NAME  (Added title optional)
Make an added personal name entry under the heading for a prominently named editor or compiler of monographic work.  Make an added personal name entry for an illustrator if the illustrations are considered to be an important feature of the work.  Make an added personal name entry for any other name that would provide an important access point not treated in another entry. It is best to match names to authority files already in use.  To do this, you can search the Pioneer, Orbis, or Library of Congress databases. Using the author search selection choose the individual listed in item being cataloged.  Convert selected record to Marc Record and follow spelling and dates given there to fill in this Marc tag. 

For first indicator, use 0 for a recognized forename such as Plato.  Use 1 for usual surname entries.  Use second indicator if adding a title, using 2.

Use subfield |a for name and use subfield |d for dates if known

	700 1	|aHemingway, Ernest,|d1899-1961.
	700 0	|aHomer.		

Use subfield |t to add a title to this field which will be traced by author in the database.    

	700 12  |aBeethoven, Ludwig van,|d1770-1827.|tC major symphony.

Punctuation:  End field with a period.

740	TITLE ADDED ENTRY (Optional)
Variant titles appear in field 246. Use for tracing specific titles in 505 contents note. Use for titles recorded in 245 subfield |b if desired.

Punctuation:  End field with a period unless other form of punctuation is present.

`800`	SERIES ADDED ENTRY – PERSONAL NAME/TITLE (Required if 490 1  field present)
This field is used when all books in a series are written by the same author. Follow all rules for entry of author in 100 field. Title is added in subfield |t.  (It will be traced in online catalog). If volume number is present it is added in subfield |v.

	800 1  |aKaron, Jan,|d1937-|tMitford years ;|v7.

Punctuation:  
Subfield |t is preceded by a period space.
Subfield |v is preceded by space semicolon space.
Field ends with a period.

`9XX`	LOCAL USE TAGS
Check with Pioneer System staff if you choose to use any of these fields. 

<a name="catm_support_and_online_help"></a>
#####Sage Cataloging Support and Online Help

- Support

	1. Systems Manager: Beth Longwell
	Phone: (541) 962-3867
	Email: <blongwel@eou.edu>
	
	2. Systems Librarian: Brent Mills
	Phone: (541) 610-8384
	Email: <brent@hoodriverlibrary.org>
	
	3. Sage Cataloging Specialist: David Sale
	Email: <sagecat@bakerlib.org>

If you have questions about cataloging in SAGE, you can always post it to the ListServ <sage-cat-group@eou.edu> or email individual Committee members.  Volunteer mentors for each region of SAGE are available to help any catalogers wanting extra help or training
 
- Ann Zuehlke <ann.zuehlke@hoodriver.k12.or.us>
- Carmen Wickam <cwickam@bakerlib.org> 541-523-5419
- Christina Trunnell <CTrunnell@tvcc.cc> 541-881-5928
- Dea Nowell <dea@ucsld.org> 406-952-4049
- Laurie O’Connor <laurie@harneycountylibrary.org> 541-573-6670
Cataloging questions can also be posted to the ListServ @ <sage-cat-group@eou.edu> or sent to David at <sagecat@bakerlib.org>. 


Other Online Catalaging Help

- [LC Name & Subject Authority (LCSH)](http://authorities.loc.gov/)
- [LC Online database](http://catalog.loc.gov/)
	- for searching to pull records into Pioneer use the MilCat “remote” button
- [Online Dictionary for Library and Information Science](http://lu.com/odlis)
- [US MARC Country Codes](http://www.loc.gov/marc/countries/)
	- or in MilCAT double click on the field for a popup list
- [US MARC Language Codes](http://www.loc.gov/marc/languages/langhome.html)
	- or in MilCAT double click on the field for a popup list
- [Idaho State Library's Alternative Basic Library Education (ABLE)](http://www.lili.org/forlibs/ce/able.htm)
- [Idaho State Library's Supplemental Alternative Basic Library Education (SABLE) Program](http://www.lili.org/forlibs/ce/sable.htm)
- [AcqWeb's Directory of Publishers and Vendors](http://www.acqweb.org/pubr.html)