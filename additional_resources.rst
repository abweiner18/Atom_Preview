Additional Resources
==========================
Find a HTML, Markdown, and RST comparison chart and links to online cheatsheets here.

.. _additional_resources_syntax_comparison:

Basic Syntax Comparison Chart
*********************************
Use this table as a quick reference for HTML, Markdown [#f1]_, and RST.

.. list-table:: **Basic Syntax Comparison**
  :widths: 25 25 25 25
  :header-rows: 1

  * - Syntax
    - HTML
    - Markdown (GFM)
    - RST
  * - Headings
    - ``<H1>YourHeading</H1>`` for top level heading. ``<H2>YourHeading</H2>`` for 2nd level heading, and so on through H6.
    - ``#`` before your heading. Add more hashtags to designate sub-level headings. You can use up to 6 hashtags, ``######``, for additional sub-level headings.
    - Type your heading. On the line below your heading, type a line of either ``*``, ``=``, or ``-`` repeating. The special character line must extend beyond the last letter of your heading. Use a different special character to denote a different level of heading.
  * - Bold
    - ``<strong>bold</strong>``
    - ``**bold**``
    - ``**bold**``
  * - Italics
    - ``<em>italics</em>``
    - ``*italics*``
    - ``*italics*``
  * - Ordered List
    - - Each ordered list starts with ``<ol>`` and ends with ``</ol>``.
      - Each list item: ``<li>List Item</li>``.
      - To sub-bullet: Insert a new ordered or unordered list, starting with ``<ol>`` or ``<ul>``, under the appropriate list item.
    - - Begin each item with ``1.``.
      - To sub-bullet, insert the sub-bullet directly below the first character of text of the parent bullet.
    - - Begin each item with ``#.``.
      - To sub-bullet: Start with your cursor at the beginning of the sub-bullet line. Space over and insert sub-bullet directly below the first character of text of the parent bullet.
  * - Unordered List
    - - Each unordered list starts with ``<ul>`` and ends with ``</ul>``.
      - Each list item: ``<li>List Item</li>``.
      - To sub-bullet: Insert a new ordered or unordered list, starting with ``<ol>`` or ``<ul>``, under the appropriate list item.
    - - Begin each item with ``-`` or ``*``.
      - To sub-bullet, insert sub-bullet directly below the first character of text of the parent bullet.
    - - Begin each item with ``-``, ``+``, or ``*``.
      - To sub-bullet: Start with your cursor at the beginning of the sub-bullet line. Space over and insert sub-bullet directly below the first character of text of the parent bullet.
  * - Image
    - ``<image src="source path" alt text= "alt text">``
    - ``![alt text](path)``
    - ``.. image::`` ``image path``
  * - Link
    - ``<a href="url">link text</a>``
    - ``[In-line text name] (url)``
    - ```link name <url>`_``


.. _additional_resources_cheatsheets:

Online Cheatsheets
*********************
There are a lot of online cheatsheets available. Below are links to just a few. Do your own searches to find the sites/cheatsheets that work best for you.

Markdown cheatsheets:

- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

RST cheatsheets:

- https://sublime-and-sphinx-guide.readthedocs.io/en/latest/index.html
- https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst

.. rubric:: Footnotes

.. [#f1] There are different "flavors" (variations) of Markdown. The syntax used here is for GitHub Flavored Markdown (GFM).
