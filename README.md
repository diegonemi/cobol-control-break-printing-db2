# COBOL Control Break Printing with DB2

## Overview
This repository contains a COBOL model program that demonstrates a double control break routine with printing output, retrieving data directly from DB2 tables. It is designed as a reference model for hierarchical reporting, showing how to generate grouped summaries and totals across two levels of control breaks.

## Features
- Double control break routine with formatted printing output
- Integration with DB2 tables for data retrieval
- Modular COBOL structure for extensibility
- Clear separation of initialization, processing, and finalization
- Corporate-style documentation and comments for auditability
- JCL scripts included to run the program in a mainframe environment

## Usage
Compile the COBOL source in your mainframe or emulator environment. Provide DB2 tables as input datasets with hierarchical keys (for example, region and branch). The program will generate grouped summaries and totals at each control break level, producing formatted printed reports. Use the included JCL scripts to execute the program and validate results. Documentation explains prerequisites and execution notes.

## Purpose
This repository serves as a practical model for mainframe professionals and students, showcasing how to implement double control break logic in COBOL with DB2 integration, extensibility, and professional documentation standards. It is part of Diego Nemirovsky’s portfolio of mainframe and COBOL projects.
