include $(top_srcdir)/config/automake.common

TESTS_ENVIRONMENT = eval H5DUMP=@H5DUMP@ SRCDIR="$(abs_srcdir)" BUILDDIR="$(abs_builddir)" \
		EXECDIR="$(abs_builddir)" CP=${CP} CPYMED="no" 
#TESTS_ENVIRONMENT += UPDATE="yes"
#TESTS_ENVIRONMENT += OUTPUT="yes" CHECKER="libtool\ --mode=execute\ valgrind\ --error-limit=no"
#TESTS_ENVIRONMENT += OUTPUT="yes" 
#CHECKER="valgrind"

usescasesdir= $(bindir)/usescases

SUFFIXES=  _Rd.sh _Wr.sh

.c_Rd.sh: testRd.sh
	${LN_S} -f $(srcdir)/testRd.sh $@
.c_Wr.sh: testWr.sh
	${LN_S} -f $(srcdir)/testWr.sh $@

##check_PROGRAMS
##bin_PROGRAMS

AM_CFLAGS = -DDEF_LECT_ECR
#-DUSER_INTERLACE=MED_FULL_INTERLACE
#-DDEF_LECT_AJOUT

if INSTALLTEST

usescases_PROGRAMS = UsesCase_MEDfile_1 \
UsesCase_MEDmesh_1 \
UsesCase_MEDmesh_2 \
UsesCase_MEDmesh_3 \
UsesCase_MEDmesh_4 \
UsesCase_MEDmesh_5 \
UsesCase_MEDmesh_6 \
UsesCase_MEDmesh_7 \
UsesCase_MEDmesh_8 \
UsesCase_MEDmesh_9 \
UsesCase_MEDmesh_10 \
UsesCase_MEDmesh_11 \
UsesCase_MEDmesh_12 \
UsesCase_MEDmesh_13 \
UsesCase_MEDmesh_14 \
UsesCase_MEDmesh_15 \
UsesCase_MEDmesh_16 \
UsesCase_MEDstructElement_1 \
UsesCase_MEDstructElement_2 \
UsesCase_MEDstructElement_3 \
UsesCase_MEDfield_1 \
UsesCase_MEDfield_2 \
UsesCase_MEDfield_3 \
UsesCase_MEDfield_4 \
UsesCase_MEDfield_5 \
UsesCase_MEDfield_6 \
UsesCase_MEDfield_7 \
UsesCase_MEDfield_8 \
UsesCase_MEDfield_9 \
UsesCase_MEDfield_10 \
UsesCase_MEDfield_11 \
UsesCase_MEDfield_12 \
UsesCase_MEDfield_13 \
UsesCase_MEDfield_14 \
UsesCase_MEDfield_15 \
UsesCase_MEDfield_15b \
UsesCase_MEDfield_16 \
UsesCase_MEDfield_17 \
UsesCase_MEDfield_18 \
UsesCase_MEDinterp_1 \
UsesCase_MEDinterp_2 \
UsesCase_MEDinterp_3

else

check_PROGRAMS = UsesCase_MEDfile_1 \
UsesCase_MEDmesh_1 \
UsesCase_MEDmesh_2 \
UsesCase_MEDmesh_3 \
UsesCase_MEDmesh_4 \
UsesCase_MEDmesh_5 \
UsesCase_MEDmesh_6 \
UsesCase_MEDmesh_7 \
UsesCase_MEDmesh_8 \
UsesCase_MEDmesh_9 \
UsesCase_MEDmesh_10 \
UsesCase_MEDmesh_11 \
UsesCase_MEDmesh_12 \
UsesCase_MEDmesh_13 \
UsesCase_MEDmesh_14 \
UsesCase_MEDmesh_15 \
UsesCase_MEDmesh_16 \
UsesCase_MEDstructElement_1 \
UsesCase_MEDstructElement_2 \
UsesCase_MEDstructElement_3 \
UsesCase_MEDfield_1 \
UsesCase_MEDfield_2 \
UsesCase_MEDfield_3 \
UsesCase_MEDfield_4 \
UsesCase_MEDfield_5 \
UsesCase_MEDfield_6 \
UsesCase_MEDfield_7 \
UsesCase_MEDfield_8 \
UsesCase_MEDfield_9 \
UsesCase_MEDfield_10 \
UsesCase_MEDfield_11 \
UsesCase_MEDfield_12 \
UsesCase_MEDfield_13 \
UsesCase_MEDfield_14 \
UsesCase_MEDfield_15 \
UsesCase_MEDfield_15b \
UsesCase_MEDfield_16 \
UsesCase_MEDfield_17 \
UsesCase_MEDfield_18 \
UsesCase_MEDinterp_1 \
UsesCase_MEDinterp_2 \
UsesCase_MEDinterp_3

endif

LDADD = $(top_builddir)/src/libmedC.la

nodist_EXTRA_UsesCase_MEDfile_1_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_1_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_2_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_3_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_4_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_5_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_6_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_7_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_8_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_9_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_10_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_11_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_12_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_13_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_14_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_15_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDmesh_16_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_1_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_2_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_3_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_4_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_5_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_6_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_7_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_8_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_9_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_10_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_11_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_12_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_13_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_14_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_15_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_15b_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_16_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_17_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDfield_18_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDstructElement_1_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDstructElement_2_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDstructElement_3_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDinterp_1_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDinterp_2_SOURCES = dummy.cxx
nodist_EXTRA_UsesCase_MEDinterp_3_SOURCES = dummy.cxx


TESTS_LEC = UsesCase_MEDmesh_2_Rd.sh \
UsesCase_MEDmesh_3_Rd.sh \
UsesCase_MEDmesh_5_Rd.sh \
UsesCase_MEDmesh_7_Rd.sh \
UsesCase_MEDmesh_8_Rd.sh \
UsesCase_MEDmesh_11_Rd.sh \
UsesCase_MEDmesh_12_Rd.sh \
UsesCase_MEDmesh_14_Rd.sh \
UsesCase_MEDmesh_16_Rd.sh \
UsesCase_MEDstructElement_2_Rd.sh \
UsesCase_MEDstructElement_3_Rd.sh \
UsesCase_MEDfield_2_Rd.sh \
UsesCase_MEDfield_3_Rd.sh \
UsesCase_MEDfield_5_Rd.sh \
UsesCase_MEDfield_6_Rd.sh \
UsesCase_MEDfield_8_Rd.sh \
UsesCase_MEDfield_9_Rd.sh \
UsesCase_MEDfield_11_Rd.sh \
UsesCase_MEDfield_12_Rd.sh \
UsesCase_MEDfield_14_Rd.sh \
UsesCase_MEDfield_16_Rd.sh \
UsesCase_MEDfield_18_Rd.sh \
UsesCase_MEDinterp_2_Rd.sh \
UsesCase_MEDinterp_3_Rd.sh


TESTS_ECR = UsesCase_MEDfile_1_Wr.sh \
UsesCase_MEDmesh_1_Wr.sh \
UsesCase_MEDmesh_4_Wr.sh \
UsesCase_MEDmesh_6_Wr.sh \
UsesCase_MEDmesh_9_Wr.sh \
UsesCase_MEDmesh_10_Wr.sh \
UsesCase_MEDmesh_13_Wr.sh \
UsesCase_MEDmesh_15_Wr.sh \
UsesCase_MEDstructElement_1_Wr.sh \
UsesCase_MEDfield_1_Wr.sh \
UsesCase_MEDfield_4_Wr.sh \
UsesCase_MEDfield_7_Wr.sh \
UsesCase_MEDfield_10_Wr.sh \
UsesCase_MEDfield_13_Wr.sh \
UsesCase_MEDfield_15_Wr.sh \
UsesCase_MEDfield_15b_Wr.sh \
UsesCase_MEDfield_17_Wr.sh \
UsesCase_MEDinterp_1_Wr.sh 

BUILT_SOURCES=$(TESTS_ECR) $(TESTS_LEC)

TESTS = $(TESTS_ECR) $(TESTS_LEC)

EXTRA_DIST = testRd.sh testWr.sh


#check_local:
#	$(MAKE) check_test_ecr
#	$(MAKE) check_test_lec SRC_REP=$(srcdir)
#	$(MAKE) check_test_lec SRC_REP=$(srcdir)/2.3.1

#check_test_ecr: $(TESTS_ECR)
#	@for testfile in $1 \
#	do \
#	  $$testfile \
#	done

#check_test_lec: $(TESTS_LEC)
#	@for testfile in $1 \
#	do \
#	  dump.sh $$testfile @H5DUMP@ SRCDIR=$(srcdir) $(SRC_REP)\
#	done


CLEANFILES = \
./UsesCase_MEDfile_1.med \
./UsesCase_MEDmesh_1.med \
./UsesCase_MEDmesh_4.med \
./UsesCase_MEDmesh_6.med \
./UsesCase_MEDmesh_9.med \
./UsesCase_MEDmesh_10.med \
./UsesCase_MEDmesh_13.med \
./UsesCase_MEDmesh_15.med \
./UsesCase_MEDfield_1.med \
./UsesCase_MEDfield_4.med \
./UsesCase_MEDfield_7.med \
./UsesCase_MEDfield_10.med \
./UsesCase_MEDfield_13.med \
./UsesCase_MEDfield_15.med \
./UsesCase_MEDfield_15b.med \
./UsesCase_MEDfield_17.med \
./UsesCase_MEDstructElement_1.med \
./UsesCase_MEDinterp_1.med \
./UsesCase_MEDfield_7.dump \
./UsesCase_MEDmesh_4.dump \
./UsesCase_MEDmesh_1.dump \
./UsesCase_MEDmesh_9.dump \
./UsesCase_MEDmesh_10.dump \
./UsesCase_MEDmesh_6.dump \
./UsesCase_MEDmesh_13.dump \
./UsesCase_MEDmesh_15.dump \
./UsesCase_MEDfile_1.dump \
./UsesCase_MEDfield_1.dump \
./UsesCase_MEDfield_4.dump \
./UsesCase_MEDfield_10.dump \
./UsesCase_MEDfield_13.dump \
./UsesCase_MEDfield_14.dump \
./UsesCase_MEDfield_15.dump \
./UsesCase_MEDfield_15b.dump \
./UsesCase_MEDfield_17.dump \
./UsesCase_MEDstructElement_1.dump \
./UsesCase_MEDinterp_1.dump

CLEANFILES+= $(TESTS_ECR) $(TESTS_LEC)
CLEANFILES+= $(BUILT_SOURCES) *med.out *.out *.out.ref *.out.tmp

SUBDIRS = dumps.ref . 
