add_executable(docbook2mdoc docbook2mdoc.c macro.c main.c node.c parse.c reorg.c
  tree.c xmalloc.c)
target_link_libraries(docbook2mdoc ik-internal)