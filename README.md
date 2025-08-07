# gitsqliteqeax
A test Repo for https://github.com/danielsiegl/gitsqlite

## Prerequisites

This repository requires [gitsqlite](https://github.com/danielsiegl/gitsqlite) to be installed for proper functionality.

## Purpose

This repository showcases how SQLite databases can be stored as text in Git repositories. More specifically, it demonstrates this capability with models from Sparx Systems Enterprise Architect (.qeax files).

The text-based storage allows for version control of database contents without LFS.

## Important Limitations

**Note:** While the SQLite databases are stored as text and can be versioned in Git, these files are **not viable for merging with standard text tools**. The structured nature of the database content requires specialized tools for proper merging.

For merging these database files, you need a specific tool like [LieberLieber LemonTree](https://www.lieberlieber.com/lemontree/) that understands the database structure and can perform intelligent merges on the model data.
