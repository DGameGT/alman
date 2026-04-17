# DGXO Alias Manager

> **Author's Note:**
> An alias is like an ex. You create a *shortcut* to reach them faster, but when you actually need the real thing, you completely forget what it's called.
>
> Honestly, I don't know if this is *worth* it for a lot of people, but it might be needed :) so I built this.

## Overview

DGXO Alias Manager is a web-based management system designed for the efficient organization, storage, and retrieval of terminal commands (aliases). This solution is intended for developers and system administrators who require a centralized repository for complex scripts and commands to enhance workflow productivity.

## Key Features

  - **Local Data Persistence**: Utilizes browser LocalStorage optimization for data retention without requiring external database infrastructure.
  - **Localization Support**: Equipped with a language management system (ID/EN) for global user accessibility.
  - **Search Optimization**: Real-time search algorithm based on category, alias name, command, and description.
  - **Data Portability**: JSON-based export and import features for backup and restore procedures.
  - **Security Context Markers**: Automatic identification for commands requiring administrative privileges (SUDO) or high-risk commands (DANGER).

## Technical Specifications

  - **Architecture**: Single Page Application (SPA).
  - **Frontend Stack**:
      - HTML5 & CSS3 (Custom Properties & CSS Grid).
      - Vanilla JavaScript (ECMAScript 2021+).
  - **Typography**: JetBrains Mono (Technical) & Space Grotesk (Interface).
  - **Iconography**: Font Awesome 6.4.2 (CDN Service).

## Installation and Deployment

This application is portable and does not require server-side installation.

1.  Copy the entire source code into a single `.html` file.
2.  Open the file using any modern browser (Chrome, Firefox, Edge, or Safari).
3.  For intranet integration, host the file on a static web server such as Nginx or Apache.

## Data Governance

It is important to note that this system operates entirely on the client-side.

1.  **Storage**: Data is stored within the user's browser LocalStorage cache.
2.  **Risks**: Clearing the browser cache or changing devices will result in data loss if not backed up.
3.  **Backup Procedure**: Users are instructed to periodically use the 'Backup' button to save a copy of the data in JSON format.

## License

License: Apache 2.0

## Contact and Support

Developed and maintained by **DGXO (Dream & Driven Generation eXperience Operations)**.

  - Repository: [GitHub Repository](https://www.google.com/search?q=https://github.com/DGameGT/aliasmanager)
  - Website: [Official Link](https://alman.dgxo.my.id/)
  - Author Website: [Click:)!](https://dgxo.my.id/)