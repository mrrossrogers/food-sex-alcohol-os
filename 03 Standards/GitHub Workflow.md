# GitHub Workflow

Version: 1.0

Status: Approved

Authority: Executive Office

Repository: food-sex-alcohol-os

Location: 03 Standards/GitHub Workflow.md

------------------------------------------------------------------------

# Purpose

This document defines the standard GitHub workflow for all Food Sex
Alcohol software projects.

Its purpose is to ensure every implementation follows a consistent,
reviewable, and auditable engineering process from approved requirements
through production deployment.

This standard applies to all software repositories owned by Food Sex
Alcohol.

------------------------------------------------------------------------

# Guiding Principles

Every change shall be:

-   Approved before implementation.
-   Implemented in an isolated branch.
-   Reviewed before production.
-   Verified after deployment.
-   Traceable through Git history.

Direct production edits are prohibited.

------------------------------------------------------------------------

# Standard Workflow

Executive Authorization

↓

Department Requirements

↓

Technology Implementation

↓

Feature Branch

↓

Commit

↓

Push to GitHub

↓

Pull Request

↓

Vercel Preview Deployment

↓

Department Acceptance

↓

Executive Release Approval

↓

Merge to `main`

↓

Production Deployment

↓

Production Verification

↓

Project Closure

------------------------------------------------------------------------

# Feature Branches

Every implementation shall begin from the current `main` branch.

Branch names should identify the project.

Examples:

-   web-003-permanent-story-pages
-   web-004-reader-experience
-   web-005-reader-experience-polish

Branches should remain focused on a single approved project.

------------------------------------------------------------------------

# Commits

Commits should:

-   Describe the approved work.
-   Remain limited to project scope.
-   Avoid unrelated changes.

Example:

WEB-005: Improve homepage reader experience

------------------------------------------------------------------------

# Pull Requests

Every implementation shall be submitted through a Pull Request.

The Pull Request serves as the review point for:

-   Website
-   Supporting Departments
-   Executive Office

No production merge occurs before Executive approval.

------------------------------------------------------------------------

# Preview Deployments

Every Pull Request should generate an isolated Vercel Preview
deployment.

Preview deployments exist to support:

-   Website acceptance
-   Supporting department validation
-   Executive review

Production is never used for acceptance testing.

------------------------------------------------------------------------

# Department Reviews

Departments review only within their authority.

Website: - Reader experience - Navigation - Layout - Acceptance

Technology: - Engineering - Validation - Production readiness

SEO: - Crawlability - Canonicals - Metadata - Search validation

Departments shall not expand project scope during review.

------------------------------------------------------------------------

# Executive Release

Only the Executive Office authorizes:

-   Merge
-   Production deployment
-   Project closure

Executive approval shall reference the applicable Executive Decision.

------------------------------------------------------------------------

# Production Deployment

After Executive approval, Technology directs Codex to:

-   Merge the approved Pull Request.
-   Deploy through Vercel.
-   Verify production.
-   Confirm deployment health.

------------------------------------------------------------------------

# Production Verification

Production verification confirms:

-   Successful deployment
-   Expected routing
-   Approved functionality
-   No critical regression
-   Production availability

Verification is recorded before project closure.

------------------------------------------------------------------------

# Emergency Fixes

Emergency production fixes follow the same workflow whenever practical.

If immediate production action is required:

-   Executive authorization may be expedited.
-   Department reviews may be condensed.

Emergency changes shall still be documented after deployment.

------------------------------------------------------------------------

# Scope Control

The GitHub workflow shall not be used to:

-   Introduce unrelated improvements.
-   Modify approved requirements.
-   Expand project scope.
-   Bypass departmental review.
-   Bypass Executive approval.

------------------------------------------------------------------------

# Success Standard

A GitHub workflow succeeds when:

-   Approved work is isolated.
-   Review is completed before release.
-   Production deployment succeeds.
-   Production verification passes.
-   Git history accurately records the implementation.

------------------------------------------------------------------------

# Revision History

  Version   Date        Description
  --------- ----------- --------------------------------------------
  1.0       July 2026   Initial approved GitHub Workflow standard.
