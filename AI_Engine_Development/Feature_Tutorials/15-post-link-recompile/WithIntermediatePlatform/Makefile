#  (c) Copyright 2021–2022 Xilinx, Inc.
#
#  Licensed under the Apache License, Version 2.0 (the "License");
#  you may not use this file except in compliance with the License.
#  You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.


# Makefile input options
TARGET ?= hw_emu


.PHONY: all_phases

all_phases:
	make FILES_DIR=$(FILES_DIR) -C Phase1 phase1
	make FILES_DIR=$(FILES_DIR) -C Phase2 phase2

clean:
	make -C Phase1 clean
	make -C Phase2 clean
