# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a curated collection of hands-on Jupyter Notebooks exploring key concepts, algorithms, and applications in machine learning. The repository focuses on educational content and practical demonstrations of ML techniques.

## Architecture

- **Repository Structure**: Simple flat structure with topic-based directories
  - `Threat-Detection/` - Contains threat detection machine learning notebook
  - Root level contains repository documentation

- **Notebook Format**: All ML content is delivered through Jupyter Notebooks (.ipynb files)
  - Large, comprehensive notebooks with extensive content (30k+ tokens)
  - Self-contained implementations with embedded documentation
  - Focus on educational and demonstration purposes

## Development Workflow

### Working with Notebooks
- Use Jupyter Lab or Jupyter Notebook for interactive development
- Notebooks are the primary deliverable - no separate Python modules
- Each notebook is self-contained with all necessary imports and implementations

### Viewing Large Notebooks
- Notebooks may be very large (30k+ tokens)
- Use targeted searching with Grep tool when analyzing specific sections
- Focus on metadata, imports, and key sections rather than reading entire files

### Security Focus
- Repository contains defensive security implementations (threat detection)
- All ML applications are focused on defensive/protective use cases
- Maintain focus on legitimate security research and defense

## Common Commands

Since this is a pure Jupyter notebook repository with no package management files:
- Start Jupyter: `jupyter lab` or `jupyter notebook`
- Install dependencies as needed per notebook requirements
- No build, lint, or test commands - notebooks are self-executing

## Working with This Codebase

1. **Notebook Analysis**: Use Grep to search for specific content in large notebooks
2. **New Notebooks**: Follow the existing pattern of comprehensive, educational content
3. **Dependencies**: Install packages as needed - no centralized dependency management
4. **Security Content**: Ensure all implementations remain focused on defensive security applications