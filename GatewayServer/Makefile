#############################################################################
# Makefile for building: GatewayServer
# Generated by qmake (2.01a) (Qt 4.6.2) on: Sun Jul 4 06:54:26 2010
# Project:  GatewayServer.pro
# Template: app
# Command: /usr/bin/qmake-qt4 -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile GatewayServer.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DDEBUG -DGLIBCXX_DEBUG
CFLAGS        = -pipe -g -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -g -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4 -I../Blowfish/include -I../SRNL/include -I.
LINK          = g++
LFLAGS        = 
LIBS          = $(SUBLIBS)  -L/usr/lib -L../SRNL -lSRNL -L../Blowfish -lBlowfish -lboost_system-mt -lboost_thread-mt -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake-qt4
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = state_master.cpp \
		state_handshake.cpp \
		server_state_version.cpp \
		server_state_login.cpp \
		server_state_handshake.cpp \
		server_connection.cpp \
		server.cpp \
		main.cpp \
		client_connection.cpp \
		packet/packet_gateway.cpp \
		packet/packet_information.cpp 
OBJECTS       = state_master.o \
		state_handshake.o \
		server_state_version.o \
		server_state_login.o \
		server_state_handshake.o \
		server_connection.o \
		server.o \
		main.o \
		client_connection.o \
		packet_gateway.o \
		packet_information.o
DIST          = /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		GatewayServer.pro
QMAKE_TARGET  = GatewayServer
DESTDIR       = 
TARGET        = GatewayServer

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: GatewayServer.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf
	$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile GatewayServer.pro
/usr/share/qt4/mkspecs/common/g++.conf:
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/debug.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/share/qt4/mkspecs/features/include_source_dir.prf:
qmake:  FORCE
	@$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile GatewayServer.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/GatewayServer1.0.0 || $(MKDIR) .tmp/GatewayServer1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/GatewayServer1.0.0/ && $(COPY_FILE) --parents state_master.hpp state_handshake.hpp server_state_version.hpp server_state_login.hpp server_state_handshake.hpp server_connection.hpp server.hpp opcodes_client.hpp client_connection.hpp packet/packet_gateway.hpp packet/opcodes_gateway_server.hpp packet/packet_information.hpp packet/opcodes_gateway_client.hpp .tmp/GatewayServer1.0.0/ && $(COPY_FILE) --parents state_master.cpp state_handshake.cpp server_state_version.cpp server_state_login.cpp server_state_handshake.cpp server_connection.cpp server.cpp main.cpp client_connection.cpp packet/packet_gateway.cpp packet/packet_information.cpp .tmp/GatewayServer1.0.0/ && (cd `dirname .tmp/GatewayServer1.0.0` && $(TAR) GatewayServer1.0.0.tar GatewayServer1.0.0 && $(COMPRESS) GatewayServer1.0.0.tar) && $(MOVE) `dirname .tmp/GatewayServer1.0.0`/GatewayServer1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/GatewayServer1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: 

####### Compile

state_master.o: state_master.cpp state_master.hpp \
		server.hpp \
		client_connection.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o state_master.o state_master.cpp

state_handshake.o: state_handshake.cpp state_handshake.hpp \
		client_connection.hpp \
		packet/packet_gateway.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o state_handshake.o state_handshake.cpp

server_state_version.o: server_state_version.cpp server_state_version.hpp \
		server_connection.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o server_state_version.o server_state_version.cpp

server_state_login.o: server_state_login.cpp server_state_login.hpp \
		server.hpp \
		server_connection.hpp \
		packet/packet_gateway.hpp \
		packet/packet_information.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o server_state_login.o server_state_login.cpp

server_state_handshake.o: server_state_handshake.cpp server_state_handshake.hpp \
		server_connection.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o server_state_handshake.o server_state_handshake.cpp

server_connection.o: server_connection.cpp server_connection.hpp \
		server.hpp \
		server_state_handshake.hpp \
		server_state_version.hpp \
		server_state_login.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o server_connection.o server_connection.cpp

server.o: server.cpp server.hpp \
		server_connection.hpp \
		client_connection.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o server.o server.cpp

main.o: main.cpp server.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

client_connection.o: client_connection.cpp client_connection.hpp \
		state_handshake.hpp \
		state_master.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o client_connection.o client_connection.cpp

packet_gateway.o: packet/packet_gateway.cpp packet/packet_gateway.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o packet_gateway.o packet/packet_gateway.cpp

packet_information.o: packet/packet_information.cpp packet/packet_information.hpp
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o packet_information.o packet/packet_information.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

