set(ImageCoordinates_SOURCE ImageCoordinates.cxx)
GENERATECLP(ImageCoordinates_SOURCE ImageCoordinates.xml)

add_executable(ImageCoordinates_${MYHAWKID} ${ImageCoordinates_SOURCE})
target_link_libraries(ImageCoordinates_${MYHAWKID} ${ITK_LIBRARIES})
