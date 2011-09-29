COMPONENT=MultihopOscilloscopeAppC

# This is for us to use our version of CTP
CFLAGS += -I../tos/lib/net/ctp_lb
CFLAGS += -I../tos/lib/net/
CFLAGS += -I$(TOSDIR)/lib/net/
CFLAGS += -I$(TOSDIR)/lib/net/4bitle
CFLAGS += -I$(TOSDIR)/lib/printf
CFLAGS += -DCC2420_DEF_RFPOWER=2

# This is the orgional line using the TOS CTP
#CFLAGS += -I$(TOSDIR)/lib/net/ -I$(TOSDIR)/lib/net/ctp  -I$(TOSDIR)/lib/net/4bitle

include $(MAKERULES)
