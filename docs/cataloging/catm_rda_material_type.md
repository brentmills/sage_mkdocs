MARC fields for RDA material description (vs. GMD)
NOTE: The general material designation (GMD) is expressed in MARC for AACR2r as 245 $h.  MARC for RDA replaces this subfield with a “triple” of fields (336/7/8) identifying content, media format and carrier or physical format of the cataloged item.  This allows the given work to be distinguished by the RDA categories of “expression” and “manifestation” in catalog search with greater precision than before.   These fields can be repeated to describe multi-format items (e.g. kits) – and individually repeated for complex description (see “Video Game” below).
It is the policy of the Sage Cataloging Committee to retain subfield 245 $h where found as an aid to patrons, and to create/populate field 999 based on its value or the values of fields 336/7/8, as available. 

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
•	RDA Content Terms (336 $a): http://www.loc.gov/standards/valuelist/rdacontent.html
•	RDA Media Terms (337 $a): http://www.loc.gov/standards/valuelist/rdamedia.html
•	RDA Carrier Terms (338 $a): http://www.loc.gov/standards/valuelist/rdacarrier.html

