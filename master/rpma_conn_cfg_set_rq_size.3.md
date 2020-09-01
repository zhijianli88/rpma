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

**rpma\_conn\_cfg\_set\_rq\_size** - set RQ size for the connection

SYNOPSIS
========

          #include <librpma.h>

          int rpma_conn_cfg_set_rq_size(struct rpma_conn_cfg *cfg, int rq_size);

DESCRIPTION
===========

ERRORS
======

**rpma\_conn\_cfg\_set\_rq\_size**() can fail with the following error:

-   XXX