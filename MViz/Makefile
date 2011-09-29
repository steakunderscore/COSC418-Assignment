COMPONENT=MVizAppC

# This is for us to use our version of CTP
CFLAGS += -I.
CFLAGS += -I$(TOSDIR)/lib/net/
CFLAGS += -I$(TOSDIR)/lib/net/4bitle
CFLAGS += -I$(TOSDIR)/lib/printf
CFLAGS += -I../tos/lib/net/ctp_lb
CFLAGS += -I../tos/lib/net/
CFLAGS += -DCC2420_DEF_RFPOWER=4




BUILD_EXTRA_DEPS = MVizMsg.class

MVizMsg.java: MViz.h
	mig -target=null -java-classname=MVizMsg java MViz.h mviz_msg -o $@

MVizMsg.class: MVizMsg.java
	javac MVizMsg.java

include $(MAKERULES)
