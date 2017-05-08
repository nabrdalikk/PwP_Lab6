cmake_minimum_required(VERSION 2.8.9)

project(KN_PwP_lab6)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "http://slicer.org/slicerWiki/index.php/Documentation/Nightly/Extensions/KN_PwP_lab6")
set(EXTENSION_CATEGORY "Examples")
set(EXTENSION_CONTRIBUTORS "John Doe (AnyWare Corp.), Karolina N")
set(EXTENSION_DESCRIPTION "Karolina N")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/KN_PwP_lab6.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/KN_PwP_lab6/Screenshots/1.png")
set(EXTENSION_DEPENDS "NA") # Specified as a space separated string, a list or 'NA' if any

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(modul1)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_CPACK})
