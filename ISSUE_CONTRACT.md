# Issue contract — Local-Cloud Query Passport

## Problem
Hybrid local/cloud SQL needs an explicit data-residency and result-provenance passport.

## Desired outcome
A bounded, open, testable implementation of **Local-Cloud Query Passport** that demonstrates Stamp queries with residency class and result digests; refuse cross-boundary plans without passport.

## Non-goals
- MotherDuck affiliation or proprietary integration
- Portfolio-wide scale/performance claims
- UI marketing site

## Acceptance
1. Mechanism module implements allow + refuse with structured receipts
2. pytest behavioral suite green
3. operate.py cold-start produces JSON receipt
4. Non-affiliation disclaimer preserved
