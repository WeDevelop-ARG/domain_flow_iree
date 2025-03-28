###################################################
# define the dfa-opt tool
set(DFA_OPT dfa-opt)
set(DFA_OPT_SRC dfa_opt.cpp)
add_executable(${DFA_OPT} ${DFA_OPT_SRC})
target_link_libraries(${DFA_OPT} PRIVATE ${LIBS})
set_target_properties(${DFA_OPT} PROPERTIES FOLDER "dfa/tools/opt")

