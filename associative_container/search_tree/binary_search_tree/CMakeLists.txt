add_subdirectory(AVL_tree)
add_subdirectory(red_black_tree)
add_subdirectory(scapegoat_tree)
add_subdirectory(splay_tree)
add_subdirectory(tests)

add_library(
        mp_os_assctv_cntnr_srch_tr_bnr_srch_tr
        include/binary_search_tree.h
        src/hhh.cpp)

target_include_directories(
        mp_os_assctv_cntnr_srch_tr_bnr_srch_tr
        PUBLIC
        ./include)

target_link_libraries(
        mp_os_assctv_cntnr_srch_tr_bnr_srch_tr
        PUBLIC
        mp_os_assctv_cntnr_srch_tr)