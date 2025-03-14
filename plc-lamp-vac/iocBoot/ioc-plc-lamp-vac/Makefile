IOC_TOP=/reg/g/pcds/epics/ioc/common/ads-ioc/R0.8.0
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := plc-lamp-vac
PROJECT_PATH := ../../plc-lamp-vac/plc-lamp-vac.tsproj
PLC := plc_lamp_vac

PYTMC_OPTS := 
PREFIX := PLC:LAMP:VAC

# With two $$, as in $$(IOCNAME) below, this will be expanded in the
# environment of st.cmd:
#DB_PARAMETERS := 'PREFIX=$(PREFIX):,IOCNAME=$$(IOCNAME)'

include $(IOC_TOP)/iocBoot/templates/Makefile.base
