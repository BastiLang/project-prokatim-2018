################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := c:/ti/ccsv6/tools/compiler/c6000_7.4.7

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./my_first_project2018cfg_c.obj" \
"./my_first_project2018cfg.obj" \
"./main.obj" \
-l"libc.a" \
-l"C:\ti\C6xCSL\lib_3x\csl6713.lib" \
-l"C:\ti\DSK6713\c6000\dsk6713\lib\dsk6713bsl.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
my_first_project2018.out \

EXE_OUTPUTS__QUOTED += \
"my_first_project2018.out" \

BIN_OUTPUTS += \
my_first_project2018.hex \

BIN_OUTPUTS__QUOTED += \
"my_first_project2018.hex" \


# All Target
all: my_first_project2018.out

# Tool invocations
my_first_project2018.out: $(OBJS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: C6000 Linker'
	"c:/ti/ccsv6/tools/compiler/c6000_7.4.7/bin/cl6x" -mv6700 --abi=coffabi -g --define=c6713 --define=CHIP_6713 --display_error_number --diag_warning=225 --diag_wrap=off -z --stack_size=0x800 -m"my_first_project2018.map" --heap_size=0x800 -i"c:/ti/ccsv6/tools/compiler/c6000_7.4.7/lib" -i"c:/ti/ccsv6/tools/compiler/c6000_7.4.7/include" -i"C:/ti/bios_5_42_01_09/packages/ti/rtdx/lib/c6000" -i"C:/ti/bios_5_42_01_09/packages/ti/bios/lib" --reread_libs --warn_sections --display_error_number --diag_wrap=off --xml_link_info="my_first_project2018_linkInfo.xml" --rom_model -o "my_first_project2018.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

my_first_project2018.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: C6000 Hex Utility'
	"c:/ti/ccsv6/tools/compiler/c6000_7.4.7/bin/hex6x"  -o "my_first_project2018.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(GEN_HDRS__QUOTED)$(GEN_MISC_FILES__QUOTED)$(EXE_OUTPUTS__QUOTED)$(GEN_FILES__QUOTED)$(BIN_OUTPUTS__QUOTED)$(GEN_CMDS__QUOTED)
	-$(RM) "main.pp" "my_first_project2018cfg_c.pp" 
	-$(RM) "my_first_project2018cfg.pp" 
	-$(RM) "main.obj" "my_first_project2018cfg.obj" "my_first_project2018cfg_c.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

