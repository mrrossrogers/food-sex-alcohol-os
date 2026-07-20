# Naming Standards

Version: 1.0

Status: Approved

Authority: Executive Office

Repository: food-sex-alcohol-os

Location: 03 Standards/Naming Standards.md

------------------------------------------------------------------------

# Purpose

This document defines the standard naming conventions used throughout
the Food Sex Alcohol Operating System (FSA OS).

Consistent naming improves clarity, traceability, searchability, and
long-term maintainability across repositories, projects, and governance
documents.

These standards apply unless the Executive Office explicitly approves an
exception.

------------------------------------------------------------------------

# Project Identifiers

Every approved project receives a unique identifier.

Format:

PREFIX-###

Examples:

WEB-003

SEO-001

AN-001

TECH-002

Project numbers are permanent.

Numbers are never reused.

Cancelled or deferred projects retain their assigned identifiers.

------------------------------------------------------------------------

# Executive Decisions

Executive decisions use:

EO-###

Examples:

EO-010

EO-011

EO-014

Executive decision numbers are sequential.

Numbers are never reused.

------------------------------------------------------------------------

# Department Documents

Department charters use the department name.

Examples:

Website Department.md

Technology Department.md

SEO Department.md

Analytics Department.md

Editorial Department.md

------------------------------------------------------------------------

# Standards Documents

Standards describe repeatable operating procedures.

Examples:

Website Project Lifecycle.md

GitHub Workflow.md

Naming Standards.md

------------------------------------------------------------------------

# Templates

Templates describe reusable document structures.

Examples:

Executive Decision Template.md

Website Acceptance Template.md

Technology Implementation Template.md

SEO Validation Template.md

Project Authorization Template.md

------------------------------------------------------------------------

# Repository Structure

Top-level folders begin with a numeric prefix.

Examples:

01 Executive Office

02 Departments

03 Standards

04 Templates

05 Backlog

Numeric prefixes preserve consistent ordering.

------------------------------------------------------------------------

# Git Branches

Branch names use:

project-number-description

Examples:

web-003-permanent-story-pages

web-004-reader-experience

web-005-reader-experience-polish

Use lowercase letters.

Separate words with hyphens.

Branch names should remain concise and descriptive.

------------------------------------------------------------------------

# Git Commits

Commit messages begin with the approved project identifier whenever
practical.

Examples:

WEB-003: Implement permanent story pages

WEB-004: Improve mobile reader experience

WEB-005: Improve homepage reader experience

Governance documents use:

FSA OS:

Examples:

FSA OS: Add Website Department Charter v1.0

FSA OS: Add GitHub Workflow v1.0

------------------------------------------------------------------------

# File Names

Use Title Case for governance documents.

Examples:

Project & Decision Register.md

Website Department.md

GitHub Workflow.md

Avoid abbreviations unless they are official project identifiers.

------------------------------------------------------------------------

# URLs

Website URLs use:

-   lowercase
-   hyphens
-   no file extensions
-   no trailing slash

Example:

/food/the-dinner-that-makes-time-disappear

------------------------------------------------------------------------

# Guiding Principles

Naming should be:

-   Consistent
-   Predictable
-   Human-readable
-   Searchable
-   Stable over time

Prefer clarity over brevity.

Avoid renaming established identifiers unless required by an Executive
decision.

------------------------------------------------------------------------

# Success Standard

Every project, document, branch, commit, and repository asset should be
identifiable from its name alone without requiring additional
explanation.

------------------------------------------------------------------------

# Revision History

  Version   Date        Description
  --------- ----------- ------------------------------------
  1.0       July 2026   Initial approved Naming Standards.
