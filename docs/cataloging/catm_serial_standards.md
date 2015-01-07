Serials



1.	Search your bibliographic utility for the serial.  Seldom will you have to edit a serials record, as they are open ended so have no pagination information.

2.	Be sure that the record is in fact a serial.

a.	The record may contain an 022 field, the ISSN number, indicating beyond a doubt that the record is a serial.
b.	If you search by title, such as Fodor’s China, you will find a serials record without an ISSN.  The book in hand has an ISBN, and the record has no ISSN, but other clues indicate that this is indeed a serial.
c.	A serials record is open ended.  There will be no pagination or publication date,  there will be a 222 field indicating the unique title assigned by the ISSN national center, and there will usually be information about frequency of publication,  previous editions, and previous publishers.

3.	Do not assume that because a book has regular updates that it is a serial.  For example, Moon Travel Guides publishes frequent editions, but these are not considered to be a serials.  Use the other clues.  Cataloging with AACR2 and USMARC provides detailed instruction for matching.

4.	If you cannot verify by either ISSN or other sources (Library of Congress, ORBIS, etc.) that your item is in fact a serial, it is recommended that you catalog as if it is a monograph.

5.	In some cases you will assume the record is a serial even without the verification.  This happens with the Fodor’s travel guides.  All Fodor’s travel guides are considered to be serials, but you may not be able to find an existing record for the particular country in question.  For example, Fodor’s Turkey does not have a record in the Library of Congress, but since all other Fodor’s are serials you can assume that this one is, too.  In this case you should create an original record.

6.	It is beyond the scope of this document to detail the original cataloging of serials.  If you need guidance, contact a member of the Cataloging Committee.





To Consolidate Pioneer Holdings under One Bib Record
Telnet instructions

1.	If an item does not have the volume (date of publication) in the item record, insert it.  Otherwise the date of publication for that item will be lost when you transfer it to the new serials record.

2.	Record the Bib number of that record.

3.	Record the Bib number of the new serials record.

4.	D> Catalog DATABASE maintenance

T> TRANSFER attached records

Do you want the source record deleted?  Y

5.	Enter as the source record the Bib number from #2.

6.	Enter as the destination record the Bib number from #3.

7.	The screen will split to show both records.  When you are certain that you want to complete the transfer, type “Y.”
