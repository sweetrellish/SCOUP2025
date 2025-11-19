# COSC 425: Software Engineering Project 2025 - SCOUP
## Team Members
*  **Josh Ellis** - *Team Lead, client manager, back-end support, software dev*
*  **Ryan Ellis** - *Server Host, back-end dev, task master/meeting keeper*
*  **Ope Adegoke** - *Web dev, software dev, front-end*
*  **Aarti Patel** - *Web dev, software dev, front-end* 

## Project Description

This repository serves as a parent project (using Git submodules) for our team's work in COSC 425 at Salisbury University for the continuation of the SCOUP project. It houses two external project forks within its structure for sandboxed development, testing, and deployment to our Ubuntu server.

---

## Getting Started

### Prerequisites

*   Git installed locally
*   SSH access to the repository via GitHub (using SSH keys or PATs)

### Cloning the Project (Crucial Step!)

Because this repository uses submodules, you must use a specific command to clone it *and* initialize the submodules at the same time:

```bash
git clone --recursive git@github.com:sweetrellish/SCOUP2025.git
