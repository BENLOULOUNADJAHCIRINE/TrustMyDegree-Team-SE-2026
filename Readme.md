## Name of the project

TrustMyDegree

## Team Members

- Benloulou Nadjah Cirine
- Khelil Ikram
- Arar Bouchra Manel

## Type of software

Web application

## Description

TrustMyDegree is a platform that issues and verifies academic certificates on the blockchain, so anyone can check a degree's authenticity without relying on paper documents. Built with a Node.js/Express/PostgreSQL (Prisma) backend, a React frontend, and Ethereum JS for the blockchain layer. Features include certificate request handling, dashboards, and secure account flows like password recovery.

## Draw.io diagrams

To view the project diagrams in Visual Studio Code, install the **Draw.io Integration** extension.

## Project structure

```text
TrustMyDegree-Team-SE-2026/
|-- README.md
|-- TMD-backend/
|   |-- prisma/                    # Prisma schema and database migrations
|   `-- src/
|       |-- config/                # Database settings and contract ABIs
|       |-- controllers/
|       |-- middleware/
|       |-- routes/
|       |-- services/
|       |-- templates/
|       |-- uploads/
|       `-- utils/
|-- TMD-blockchain/
|   |-- contracts/                 # Solidity smart contracts
|   |-- ignition/modules/
|   |-- scripts/                   # Contract deployment
|   `-- test/                      # Smart contract tests
|-- TMD-frontend/
|   |-- public/                    # Static assets
|   `-- src/
|       `-- component/
|           |-- admin/
|           |-- home/
|           |-- login/
|           `-- student/
|-- activity-diagram/              # Activity diagram images
|-- class-diagram/                 # Class diagram images
|-- sequence-diagram/              # Sequence diagram images
`-- use-case-diagram/              # Use-case diagram images
```
