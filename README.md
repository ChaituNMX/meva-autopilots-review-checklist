# Software Reviewer Checklist

A structured checklist designed to assist software code reviewers during technical reviews of embedded automotive software. The checklist consolidates common review activities into a single document to ensure consistent, complete, and traceable reviews.

---

## Objective

The purpose of this checklist is to:

- Standardize software code reviews across projects.
- Improve review quality and consistency.
- Reduce the possibility of overlooking common implementation issues.
- Ensure implementation complies with project requirements and coding standards.
- Verify that all required testing activities have been completed before software integration.

---

## Checklist Structure

The checklist is divided into three review stages:

### 1. Requirements

Checks related to implementation against approved software requirements.

This section includes:
- Signal boundary value validation
- Data type conversion safety
- Signal Alive timeout configuration
- Signal range verification in the SE Tool

---

### 2. Verification

Checks related to software validation activities.

This section includes:
- Software-in-the-Loop (SIL) testing
- Hardware-in-the-Loop (HIL) testing
- Integrated testing
- Embedded testing
- Sanity testing

---

### 3. Implementation

Checks related to software quality and coding implementation.

This section includes:
- Compiler, build and static analysis warnings
- Unit Test (UT) coverage
- Signal interface compatibility (CRC/E2E)

---

## How to Use

For every Merge Request (MR) or software review:

1. Review each checklist item.
2. Mark the corresponding checkbox after verification.
3. Record comments or observations if required.
4. Any failed checklist item should be resolved before approval unless an approved technical justification exists.
