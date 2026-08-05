
# SQL for Text Analytics

A working guide for incorporating **SQL and SQLite into R-based text
analytics workflows** within the **NYC Open Data Lab Text Analytics &
Computational Social Science Track**.

## About

This repository contains a Quarto book designed to support students who
are already familiar with R but are new to working with SQL and
relational databases.

The goal is not to provide a comprehensive SQL textbook. Instead, the
guide introduces SQL through real project workflows, with R remaining
the primary working environment.

Students learn how to use:

- **R** for data preparation, web scraping, and analysis;
- **SQL** for querying, filtering, summarizing, and managing data;
- **SQLite** for storing project data;
- **DBI** and **RSQLite** for connecting R to SQLite; and
- **Quarto** for documenting reproducible workflows.

## Guide Structure

The guide currently contains two primary chapters:

### Databases, SQL, and R

An introduction to databases, SQL, SQLite, and working with relational
data directly from R.

Topics include database connections, SQL queries, filtering, sorting,
aggregation, joins, creating databases, and working with primary and
foreign keys.

### Text Analysis Project

A working project that applies these concepts to a collection of online
articles.

The workflow moves through:

    Excel Article List
            ↓
    Import into R
            ↓
    Create SQLite Database
            ↓
    Retrieve URLs into R
            ↓
    Extract Article Text
            ↓
    Update SQLite Database
            ↓
    Retrieve Data into R

The resulting data can then be used for subsequent text analysis.

## A Working Guide

Project chapters are designed to be completed alongside the actual work.

They contain:

- project goals
- task checklists
- working code sections
- checkpoints
- space for notes
- links to relevant SQL documentation
- summaries of important functions and commands

Students are encouraged to document their code, decisions, problems, and
solutions as they work.

The goal is for the completed guide to become a **reusable reference for
future projects**, allowing students to reproduce similar workflows with
increasing independence.

## Development

This guide is intended to grow alongside projects within the Text
Analytics & Computational Social Science Track. Additional chapters may
be added as new SQL techniques, database structures, or reusable
workflows become relevant.

## NYC Open Data Lab

The **NYC Open Data Lab** develops open tools, reproducible research
workflows, educational resources, and public-facing data projects.

This guide was developed as part of the Lab’s internship program to
support hands-on technical learning through real projects.
