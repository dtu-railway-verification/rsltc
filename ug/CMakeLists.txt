FILE(GLOB HTML_FILES RELATIVE "${CMAKE_CURRENT_SOURCE_DIR}" "${CMAKE_CURRENT_SOURCE_DIR}/*.html" "${CMAKE_CURRENT_SOURCE_DIR}/*.png")

INSTALL(FILES ${HTML_FILES} DESTINATION ug/html)

FILE(GLOB PDF_FILES RELATIVE "${CMAKE_CURRENT_SOURCE_DIR}" "${CMAKE_CURRENT_SOURCE_DIR}/*.pdf")

INSTALL(FILES ${PDF_FILES} DESTINATION ug)
