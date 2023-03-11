* README_EN.txt
* 2023.03.11
* rapidxml

1. DESCRIPTION
2. SOURCES
3. PATCHES
4. DEPENDENCIES
5. EXTERNALS
6. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
`rapidxml` library fork

-------------------------------------------------------------------------------
2. SOURCES
-------------------------------------------------------------------------------
https://sourceforge.net/projects/rapidxml

-------------------------------------------------------------------------------
3. PATCHES
-------------------------------------------------------------------------------
The original library patched to fix these issues:

1. The `flags` function in the `xml_node` class to, for example, remember
   self-closed tags.
2. Use the same flag to enable print self closed tag by a user choice
3. The `print_node` function visibility fix.

-------------------------------------------------------------------------------
4. DEPENDENCIES
-------------------------------------------------------------------------------
N/A
-------------------------------------------------------------------------------
5. EXTERNALS
-------------------------------------------------------------------------------
To checkout externals you must use the
[vcstool](https://github.com/dirk-thomas/vcstool) python module.

NOTE:
  To install the module from the git repository:

  >
  python -m pip install git+https://github.com/dirk-thomas/vcstool

-------------------------------------------------------------------------------
6. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
