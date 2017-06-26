.. _persons:

Persons
=======

.. _person-list:

Person List
-----------

The person list contains all the person entries organized by ID. For each entry, the person list shows the :ref:`ID <person-field-id>`, :ref:`Last name <person-field-last-name>`, :ref:`First name <person-field-first-name>`, :ref:`Gender <person-field-gender>`, :ref:`Date of birth <person-field-date-of-birth>`, and :ref:`Date of death <person-field-date-of-death>`.

Person fields
^^^^^^^^^^^^^

.. _person-field-id:

ID
  Unique ID number for this entry

.. _person-field-last-name:

Last name
  Person’s last name (preference will be given to the name by which he or she is most commonly known)

.. _person-field-first-name:

First name
  Person’s first name and where appropriate, full aristocratic title

.. _person-field-gender:

Gender
  Where appropriate, full aristocratic title

.. _person-field-date-of-birth:

Date of birth
  If known, YYYY-MM-DD

.. _person-field-place-of-birth:

Place of birth
  If known; geotagged

.. _person-field-date-of-death:

Date of death
  If known, YYYY-MM-DD

.. _person-field-place-of-death:

Place of death
  If known; geotagged

.. _person-field-titles:

Titles
  List of all works person is associated with including the role, :ref:`title <title-field-title>`, and :ref:`date <title-field-publication-date>`.
  
.. todo:: link to roles

.. _person-field-hand-checked:

Hand checked
  Definition here.

.. todo:: need hand check definition for person

.. _person-field-final-check:

Final check
  Definition here.
  
.. todo:: need final check definition for person

.. _person-search-label:

Person Search
-------------

The Person Search page defaults to a basic title search function with a custom search page available via the **options** button. It allows users to search for specific persons on fields associated with a person. Advanced person searches can also be filtered by 0 or more Title or Firm content-type searches. Search results return bibliographic entry for each title found.

Person Search parameters
^^^^^^^^^^^^^^^^^^^^^^^^

Name
  Text search for all or part of a personal name
 
Gender
  Search for persons by :ref:`gender <person-field-gender>`. Leave Gender field blank to include all genders.
 
Birth Year
  Search for person by :ref:`birth year <person-field-date-of-birth>` using a single year (e.g. :kbd:`1795`) or a range of years (:kbd:`1790-1800`) or partial range of years (:kbd:`*-1800`)

Death Year
  Search for person by :ref:`death year <person-field-date-of-death>` using a single year (e.g. :kbd:`1795`) or a range of years (:kbd:`1790-1800`) or partial range of years (:kbd:`*-1800`)

Birth Place
  Text search for person by :ref:`place of birth <person-field-place-of-birth>`

Death Place
  Text search for person by :ref:`place of death <person-field-place-of-death>`

Filter by Title
  Person search can be filtered by 0 or more complete Title searches. Click the **add** button to include 1 or more complete title searches. They can be removed from the search with the **remove** button. For more information about Title search parameters, see :ref:`title-search-label`.

Filter by Firm
  Person search can be filtered by 0 or more complete Firm searches. Click the **add** button to include 1 or more complete firm searches. They can be removed from the search with the **remove** button. For more information about the Firm Search parameters, see :ref:`firm-search-label`.

Order by
  Choose how search results will be displayed: by last name, first name, birth date, or death date.

Order direction
  Choose whether search results will be displayed in ascending order (A to Z, 1 to 9) or descending order (Z to A, 9 to 1).

Search results appear below the search fields. The search can be reset using the **reset** button. Search results include the person's :ref:`last name <person-field-last-name>`, :ref:`first name <person-field-first-name>`, :ref:`gender <person-field-gender>`, :ref:`date of birth <person-field-date-of-birth>`, and :ref:`date of death <person-field-date-of-death>`.