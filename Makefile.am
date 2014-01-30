ACLOCAL_AMFLAGS = -I ../fintp_utils/m4

bin_PROGRAMS = RoutingEngine

RoutingEngine_CPPFLAGS = -DUNIX -DDEBUG_ENABLED -DXALAN_1_9 	\
@CPPFLAGS@	\
@PTHREAD_CFLAGS@	\
@BOOST_CPPFLAGS@	\
@XERCES_CPPFLAGS@	\
@XALAN_CPPFLAGS@	\
-I$(FINTP_HOME)/fintp_utils/src	\
-I$(FINTP_HOME)/fintp_log/src	\
-I$(FINTP_HOME)/fintp_transport/src	\
-I$(FINTP_HOME)/fintp_udal/src	\
-I$(FINTP_HOME)/fintp_base/src	\
-I$(FINTP_HOME)/fintp_base/src/DB	\
-I$(FINTP_HOME)/fintp_ws/src

AUTOMAKE_OPTIONS = foreign

RoutingEngine_LDFLAGS = @LIBS@ @LDFLAGS@	\
@PTHREAD_LIBS@	\
@BOOST_LDFLAGS@ @BOOST_REGEX_LIB@ -lboost_regex \
@XERCES_LDFLAGS@ @XALAN_LDFLAGS@ -lxerces-c -lxalan-c	\
-L$(FINTP_HOME)/fintp_utils/.libs -lfintp_utils	\
-L$(FINTP_HOME)/fintp_log/.libs -lfintp_log	\
-L$(FINTP_HOME)/fintp_transport/.libs -lfintp_transport	\
-L$(FINTP_HOME)/fintp_udal/.libs -lfintp_udal	\
-L$(FINTP_HOME)/fintp_base/.libs -lfintp_base	\
-L$(FINTP_HOME)/fintp_ws/.libs -lfintp_ws

RoutingEngine_SOURCES = src/RoutingActions.cpp	\
src/RoutingActions.h	\
src/RoutingAggregationManager.cpp	\
src/RoutingAggregationManager.h	\
src/RoutingCOT.cpp	\
src/RoutingCOT.h	\
src/RoutingDbOp.cpp	\
src/RoutingDbOp.h	\
src/RoutingEngine.cpp	\
src/RoutingEngine.h	\
src/RoutingEngineMain.cpp	\
src/RoutingEngineMain.h	\
src/RoutingEvaluators.cpp	\
src/RoutingEvaluators.h	\
src/RoutingExceptions.cpp	\
src/RoutingExceptions.h	\
src/RoutingJob.cpp	\
src/RoutingJob.h	\
src/RoutingJobExecutor.cpp	\
src/RoutingJobExecutor.h	\
src/RoutingMessage.cpp	\
src/RoutingMessage.h	\
src/RoutingPlan.cpp	\
src/RoutingPlan.h	\
src/RoutingRule.cpp	\
src/RoutingRule.h	\
src/RoutingSchema.cpp	\
src/RoutingSchema.h	\
src/RoutingStructures.cpp	\
src/RoutingStructures.h	\
src/VersionInfo.cpp

SUBDIRS = .
