# Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0

HARNESS_FILE=skipOneHexEscape_harness
PROOF_UID=skipOneHexEscape

CBMC_FLAG_UNWINDING_ASSERTIONS = 

APPLY_LOOP_CONTRACTS = 1

include ../Makefile-json.common

# Substitution command to pass to sed for patching core_json.c. The
# characters " and # must be escaped with backslash.
CORE_JSON_SED_EXPR = s/^static //
