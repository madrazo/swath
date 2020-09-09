cmake_minimum_required(VERSION 3.13)
project(cmake_swath)

set(SOURCES "conv/conv.cxx" "conv/conv.h" "conv/convfact.cxx" "conv/convfact.h" "conv/convkit.h" "conv/tis620.cxx" "conv/tis620.h" "conv/tischar.h" "conv/unichar.h" "conv/utf8.cxx" "conv/utf8.h" "src/abswordseg.cpp" "src/abswordseg.h" "src/convutil.cpp" "src/convutil.h" "src/dict.cpp" "src/dict.h" "src/filefilter.cpp" "src/filefilter.h" "src/filterhtml.cpp" "src/filterhtml.h" "src/filterlambda.h" "src/filterlatex.cpp" "src/filterlatex.h" "src/filterrtf.cpp" "src/filterrtf.h" "src/filterx.h" "src/longwordseg.cpp" "src/longwordseg.h" "src/maxwordseg.cpp" "src/maxwordseg.h" "src/utils.h" "src/worddef.h" "src/wordseg.cpp" "src/wordstack.h" )

add_executable(cmake_swath src/wordseg.cpp)
