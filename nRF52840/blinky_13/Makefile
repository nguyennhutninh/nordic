TEMPLATEROOT = ..

# compilation flags for gdb

CFLAGS  += -O0 -g
CFLAGS += -DBOARD_PCA10056
CFLAGS += -DSWI_DISABLE0
CFLAGS += -DNRF52840_XXAA
CFLAGS += -DBOARD_PCA10056
CFLAGS += -DCONFIG_GPIO_AS_PINRESET
ASFLAGS += -g 
ASMFLAGS += -DSWI_DISABLE0
ASMFLAGS += -DNRF52840_XXAA
ASMFLAGS += -DBOARD_PCA10056
ASMFLAGS += -DBSP_DEFINES_ONLY
ASMFLAGS += -DCONFIG_GPIO_AS_PINRESET

LDSCRIPT = $(TEMPLATEROOT)/blank_nrf52840_QFIA.ld

# object files

OBJS =  system_nrf52840.o main.o 

# include common make file

include $(TEMPLATEROOT)/Makefile.common