# Copyright (c) 2021 Nordic Semiconductor ASA
# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20.0)
zephyr_library()
zephyr_library_sources(ky_038.c)
target_include_directories(app PUBLIC "./")
