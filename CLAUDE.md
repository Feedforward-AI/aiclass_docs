# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static documentation website for "AI Class Resources" by Feedforward. It hosts course materials for an AI training class built around a fictional business case study at "Meridian Industries" - a $10B industrial distributor navigating AI transformation.

## Repository Structure

- `index.html` - Main landing page with download links for course materials
- `docs/` - Primary course documents (~36 markdown files) including memos, reports, and case study materials
- `doc-summary/` - Condensed summaries of key documents (~8 markdown files)

## Architecture

This is a simple static site with no build system:
- Single HTML file with embedded CSS and vanilla JavaScript
- Course materials are markdown files intended for direct download
- The HTML references ZIP files (`docs.zip`, `doc-summary.zip`) that should be generated separately
- No server-side components

## Deployment

Files can be served directly by any static file server or hosted on GitHub Pages.

## Content Context

The case study follows Jordan Torres (Head of AI Initiative) responding to executive concerns about AI investment ROI. Documents include internal memos, Slack exports, usage reports, and stakeholder profiles spanning January 2025 - January 2026.
