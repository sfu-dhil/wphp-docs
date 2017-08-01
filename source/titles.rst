.. _titles:

Titles
======

.. _title-list:

Title List
----------

The title list contains all the title entries organized by ID. For each entry, the title list shows the :ref:`ID <title-field-id>`, :ref:`Title <title-field-title>`, Author, :ref:`Firms <firm-field-name>` :ref:`(City) <firm-field-city>`, :ref:`Date <title-field-publication-date>`, and :ref:`Edition <title-field-edition>`.

.. Include all links to fields

Title fields
^^^^^^^^^^^^

.. _title-field-id:

Title ID
  Unique ID number for this entry

.. _title-field-title:

Title
  Full title as it appears on the title page, including subtitle, signed author, and edition statement where applicable

.. _title-field-signed-author:

Signed author
  Author attribution as it appears on the title page or at the end of the preface. (Ex. “By a lady,” “By the author of . . . “)

.. _title-field-contributors:

Contributors
  Linked to the :ref:`Person List <person-list>`. Contribution roles include name of author(s) (if known) and, where appropriate, editors, translators, authors of introductory material, engravers, and women involved in printing, publishing, bookselling, etc. If any of the roles are attributed to a woman whose name is unknown, they will be listed as “Unknown.”


.. _title-field-firms:

Firms
  Linked to the :ref:`Firm List <firm-list>`. Includes all printers, publishers, and booksellers listed in the imprint and colophon.
  
.. check list vs. table

.. _title-field-format:

Format
  The way that sheets have been folded and gathered into pages. For example, folio, quarto, octavo, duodecimo, sextodecimo, octodecimo, vicesimo-quarto, etc.
  
.. check formatting--sentence broken into paragraphs

.. _title-field-location-of-printing:

Location of printing
  Geotagged location as indicated by the imprint

.. _title-field-genre:

Genre
  Category that the work falls into.

.. todo:: Add descriptions for individual genres in future documentation. 

.. _title-field-source-1:

Source 1
  First source consulted to populate the entry fields. Source ID will vary according to the source, but will correspond to the to a unique identifier for the book or document consulted.

.. _title-field-source-2:

Source 2
  Second source consulted to populate the entry fields. Source ID will vary according to the source, but will correspond to the to a unique identifier for the book or document consulted.

.. _title-field-pseudonym:

Pseudonym
  If the author has signed the work with a name that has been proven false, it will be listed here.

.. _title-field-imprint:

Imprint
  Information about printers, publishers, booksellers as represented on the title page

.. _title-field-self-published:

Self published
  Indicates whether the title was published by the author or whether it was published by an external publishing firm.
  
.. _title-field-publication-date:

Publication date
  Date (year) as it appears in the imprint. Where imprint information is unavailable, this will reflect the best estimate we have.

.. _title-field-date-of-first-publication:

Date of first publication
  Date (year) that the work was first published.

.. _title-field-size-length:

Size (length)
  Length measured in cm.

.. _title-field-size-width:

Size (width)
  Width measured in cm.

.. _title-field-edition:

Edition
  Edition as it appears in the edition statement on the title page; 1st editions are not indicated on title pages so in the case of an earliest known printing 1st edition is assumed.

.. _title-field-volumes:

Volumes
  Number of volumes that the edition was published in, indicated in arabic numerals.

.. _title-field-pagination:

Pagination
  Pagination of each volume. Each volume indicated by a capital letter roman numeral, prefatory matter indicated by lowercase roman numerals, regular pagination indicated in arabic numerals.

.. _title-field-price-pound:

Price (pound)
  Portion of price (pounds) as listed on the title page or in catalogues and periodicals.

.. _title-field-price-shilling:

Price (shilling)
  Portion of price (shillings) as listed on the title page or in catalogues and periodicals.

.. _title-field-price-pence:

Price (pence)
  Portion of price (pence) as listed on the title page or in catalogues and periodicals.

.. _title-field-price-total:

Total price (in pence)
  Total price as listed on the title page or in catalogues and periodicals expressed in pence.

.. _title-field-shelf-marks:

Shelf marks
  Call numbers for location in various libraries.

.. _title-field-hand-checked:

Hand checked
  Indicates that a physical copy of the text has been consulted.

.. _title-field-final-check:

Final check
  Indicates that either two sources have been consulted or the text has been hand-checked.

.. _title-field-notes:

Notes
  Any important information that does not fit in the above fields will be indicated here, as well as links to sources that do not have a unique identifying number.

.. _title-search-label:

Title Search
------------

The Title Search page defaults to a basic title search function with a custom search page available via the **options** button. It allows users to search for specific titles on fields associated with a title. Advanced title searches can also be filtered by 0 or more Person or Firm content-type searches.

Title Search parameters
^^^^^^^^^^^^^^^^^^^^^^^

Title
  Text search for all or part of a title
  
Publication Year
  Search for year a title was published by a single year (e.g. :kbd:`1795`) or a range of years (:kbd:`1790-1800`) or partial range of years (:kbd:`*-1800`)
  
Printing Location
  Searches :ref:`Location of Printing <title-field-location-of-printing>` field

Format
  Can filter search on 0 or more title :ref:`Format <title-field-format>`

Genre
  Can filter search 0 or more title :ref:`Genres <title-field-genre>`

Signed author
  Text search for title by :ref:`Signed author <title-field-signed-author>` field

Imprint
  Text search for title by :ref:`Imprint <title-field-imprint>` field

Pseudonym
  Text search for title by :ref:`Pseudonym <title-field-pseudonym>` field

Filter by Person
  Title search can be filtered by 0 or more complete Person searches. Click the **add** button to include 1 or more complete person searches. They can be removed from the search with the **remove** button. For more information about the Person Search parameters, see :ref:`person-search-label`.

Filter by Firm
  Title search can be filtered by 0 or more complete Firm searches. Click the **add** button to include 1 or more complete firm searches. They can be removed from the search with the **remove** button. For more information about the Firm Search parameters, see :ref:`firm-search-label`.

Order by
  Choose how search results will be displayed: by title or publication date.

Order direction
  Choose whether search results will be displayed in ascending order (A to Z) or descending order (Z to A)

Search results appear below the search fields. The search can be reset using the **reset** button. A list of the entries generated by the search can be exported using the **export** button. Results can be exported with MLA, Chicago, APA formatting or as a BibTex file.