# Copyright 2017 Tymoteusz Blazejczyk
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

set(HDL_LIBRARY virtio)
set(HDL_SYNTHESIZABLE TRUE)

set(HDL_INCLUDES
    "${STD_OVL_DIR}"
    "${CMAKE_CURRENT_SOURCE_DIR}/../../logic/rtl/logic/include"
)

add_subdirectory(packages)
add_subdirectory(available_ring)
