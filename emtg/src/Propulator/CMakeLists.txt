set(PROPULATOR_HEADERS ${PROPULATOR_HEADERS} ${CMAKE_CURRENT_SOURCE_DIR}/Propulator.h
                                             ${CMAKE_CURRENT_SOURCE_DIR}/PropulatorJourney.h)

set(PROPULATOR_SOURCE ${PROPULATOR_SOURCE} ${CMAKE_CURRENT_SOURCE_DIR}/Propulator.cpp
                                           ${CMAKE_CURRENT_SOURCE_DIR}/PropulatorJourney.cpp)
					
set(PROPULATOR_FILES ${PROPULATOR_FILES} ${PROPULATOR_HEADERS} ${PROPULATOR_SOURCE} ${CMAKE_CURRENT_SOURCE_DIR}/PropulatorDriver.cpp PARENT_SCOPE)

set(PROPULATOR_MODULE_FILES ${PROPULATOR_FILES} ${PROPULATOR_HEADERS} ${PROPULATOR_SOURCE} PARENT_SCOPE)