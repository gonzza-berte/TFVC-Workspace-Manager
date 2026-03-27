# TFVC Workspace Manager

TFVC Workspace Manager is a tool designed to simplify the operational management of TFVC workspaces in Azure DevOps.

It provides a centralized way to:

- browse Team Projects
- inspect TFVC workspaces
- review pending changes
- inspect locks
- execute undo operations on pending changes
- execute unlock operations when permissions allow it
- keep technical logs and functional audit records

## Purpose

The main goal of this project is to provide a reusable and configurable tool for organizations working with TFVC in Azure DevOps, without hardcoded dependencies on a specific company, environment, or Azure DevOps organization.

The application is intended to be adaptable to different installations and connection profiles.

## Main characteristics

- .NET Framework 4.8 based
- configurable connection to Azure DevOps
- workspace and pending changes exploration
- lock inspection and management
- undo support for pending changes
- logging and auditing
- neutral and reusable design

## Project status

This project is currently focused on an MVP that includes:

- Team Project listing
- workspace listing
- pending changes inspection
- lock inspection
- undo for pending changes
- unlock operations
- audit trail and logging

## Configuration principles

This tool is designed to avoid hardcoded references to a specific company or environment.

Examples of configurable values include:

- Azure DevOps collection URL
- authentication mode
- tf.exe path
- log directory
- audit directory
- command timeout
- saved connection profiles

## License

This project is licensed under the Apache License 2.0.

See the [LICENSE](LICENSE) file for details.

## Notice

This project includes attribution information in the [NOTICE](NOTICE) file.

## Author

Originally created by Gonzalo Berterame.

## Disclaimer

This software is provided "AS IS", without warranties or conditions of any kind, express or implied.
Use it at your own risk and validate its behavior in your own Azure DevOps / TFVC environment before using it in production or administrative scenarios.
