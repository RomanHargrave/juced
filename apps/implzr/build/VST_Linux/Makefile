# Makefile autogenerated by premake
# Don't edit this file! Instead edit `premake.lua` then rerun `make`
# Options:
#   CONFIG=[Debug|Release]

ifndef CONFIG
  CONFIG=Debug
endif

export CONFIG

.PHONY: all clean implzr

all: implzr

Makefile: premake.lua
	@echo ==== Regenerating Makefiles ====
	@premake --file $^ --cc gcc --target gnu --os linux

implzr:
	@echo ==== Building implzr ====
	@$(MAKE) --no-print-directory -C . -f implzr.make

clean:
	@$(MAKE) --no-print-directory -C . -f implzr.make clean
