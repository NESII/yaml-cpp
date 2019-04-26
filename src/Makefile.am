lib_LIBRARIES = libyaml-cpp.a

libyaml_cpp_a_SOURCES = \
	binary.cpp convert.cpp directives.cpp emit.cpp emitfromevents.cpp emitter.cpp emitterstate.cpp emitterutils.cpp \
	exceptions.cpp exp.cpp memory.cpp nodebuilder.cpp node.cpp node_data.cpp nodeevents.cpp null.cpp \
	ostream_wrapper.cpp parse.cpp parser.cpp regex_yaml.cpp scanner.cpp scanscalar.cpp scantag.cpp scantoken.cpp \
	simplekey.cpp singledocparser.cpp stream.cpp tag.cpp 

libyaml_cpp_a_SOURCES += \
	collectionstack.h directives.h emitterstate.h emitterutils.h exp.h indentation.h nodebuilder.h nodeevents.h \
	ptr_vector.h regeximpl.h regex_yaml.h scanner.h scanscalar.h scantag.h setting.h singledocparser.h \
	streamcharsource.h stream.h stringsource.h tag.h token.h

libyaml_cpp_a_CPPFLAGS = -I . -I $(top_srcdir)/include
