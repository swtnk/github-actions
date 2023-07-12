SELF_DIR := $(dir $(lastword $(MAKEFILE_LIST)))
include $(SELF_DIR)/../../base.mk

echo-version:
	@echo $(VERSION)

test:
	./test.sh
