# Introduction

FIXME: explain what PlentyFS is at a very high level, and what the
motivation is

# Requirements

FIXME: explain the high level requirements as bullet points, not as
scenarios

# Acceptance criteria and their verification

This chapter covers the detailed acceptance criteria for PlentyFS and
how they are verified in an automated manner.

## Smoke test

This scenario verifies that PlentyFS works at all.

~~~scenario
given a PlentyFS mounted at mnt
then there are 10000 files under mnt
~~~



---
title: PlentyFS - read-only, on-demand file system
author: Alexander Batischev
bindings:
- subplot/plentyfs.yaml
functions:
- subplot/plentyfs.py
- subplot/runcmd.py
- subplot/daemon.py
...

