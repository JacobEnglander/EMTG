set(COASTPHASE_HEADERS ${COASTPHASE_HEADERS} 
                       ${CMAKE_CURRENT_SOURCE_DIR}/SundmanCoastPhase.h)

set(COASTPHASE_SOURCE ${COASTPHASE_SOURCE} 
                      ${CMAKE_CURRENT_SOURCE_DIR}/SundmanCoastPhase.cpp)

set(COASTPHASE_FILES ${COASTPHASE_FILES} 
                     ${COASTPHASE_HEADERS} 
                     ${COASTPHASE_SOURCE} PARENT_SCOPE)
