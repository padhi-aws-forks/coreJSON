# Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0

HARNESS_FILE=skipCollection_harness
PROOF_UID=skipCollection

APPLY_LOOP_CONTRACTS=1

include ../Makefile-json.common

# Substitution command to pass to sed for patching core_json.c. The
# characters " and # must be escaped with backslash.
CORE_JSON_SED_EXPR = 1s/^/\#include \"core_json_annex.h\" /; s/^static //; s/(bool|void) skip(AnyLiteral|Number|Space|SpaceAndComma|String)\b/&_/
