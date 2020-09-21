---
layout: manual
Content-Style: 'text/css'
title: LIBRPMA
collection: librpma
date: rpma API version 0.0
...

[comment]: <> (SPDX-License-Identifier: BSD-3-Clause)
[comment]: <> (Copyright 2020, Intel Corporation)

NAME
====

**rpma\_peer\_cfg\_from\_descriptor** - create a peer configuration from
a descriptor

SYNOPSIS
========

          #include <librpma.h>

          int rpma_peer_cfg_from_descriptor(void *desc, size_t desc_size,
                          struct rpma_peer_cfg **pcfg_ptr);

DESCRIPTION
===========

ERRORS
======

**rpma\_peer\_cfg\_from\_descriptor**() can fail with the following
errors:

-   RPMA\_E\_INVAL - *desc* or *pcfg\_ptr* are NULL

-   RPMA\_E\_NOMEM - out of memory