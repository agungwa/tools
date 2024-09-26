# Tools Branch

Welcome to the **tools** branch of this repository. This branch contains a collection of utility scripts and tools designed to assist with various tasks, such as database migration, automation, and other development processes.

## Available Tools

### 1. **Database Migration Script (`migrate_database.sh`)**
   - **Purpose**: Automates the migration of schemas between PostgreSQL databases. The script can either migrate all schemas or a specific schema, based on user input.
   - **Key Features**:
     - Migrates schemas individually to minimize locks.
     - Optionally migrates a specific schema by passing its name as an argument.
     - Logs the entire migration process for later review.
     - Supports customization via environment variables.