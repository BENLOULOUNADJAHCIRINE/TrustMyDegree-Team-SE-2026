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

## Project structure

```text
TrustMyDegree-Team-SE-2026/
|
+-- README.md
|
+-- TMD-backend/
|   |-- .env.example
|   |-- .gitignore
|   |-- package.json
|   |-- package-lock.json
|   |-- prisma.config.ts
|   |-- prisma/
|   |   |-- schema.prisma
|   |   `-- migrations/
|   |       |-- migration_lock.toml
|   |       |-- 20260307165508_init/
|   |       `-- 20260426000000_add_avatar_to_user/
|   `-- src/
|       |-- server.js
|       |-- config/
|       |   |-- prisma.js
|       |   |-- universityDB.js
|       |   `-- abis/
|       |       |-- DiplomaRegistry.json
|       |       |-- DocumentRegistry.json
|       |       |-- InternshipRegistry.json
|       |       |-- RankRegistry.json
|       |       `-- StudyCertificateRegistry.json
|       |-- controllers/
|       |   |-- adminController.js
|       |   |-- authController.js
|       |   |-- contactController.js
|       |   |-- studentController.js
|       |   |-- superadminController.js
|       |   `-- verifyController.js
|       |-- middleware/
|       |   |-- auth.js
|       |   `-- validation.js
|       |-- routes/
|       |   |-- admin.js
|       |   |-- auth.js
|       |   |-- contact.js
|       |   |-- student.js
|       |   |-- superadmin.js
|       |   `-- verify.js
|       |-- services/
|       |   |-- blockchain.service.js
|       |   |-- cloudinary.service.js
|       |   `-- pinata.service.js
|       |-- templates/
|       |   |-- certificate.html
|       |   |-- internship.html
|       |   |-- rank.html
|       |   `-- scolarite.html
|       |-- uploads/
|       |   `-- uploaded-avatar-images
|       `-- utils/
|           |-- generatePDF.js
|           |-- logoensta.png
|           `-- sendEmail.js
|
+-- TMD-blockchain/
|   |-- .env.example
|   |-- .gitignore
|   |-- README.md
|   |-- package.json
|   |-- package-lock.json
|   |-- hardhat.config.js
|   |-- contracts/
|   |   |-- 1_Storage.sol
|   |   |-- 2_Owner.sol
|   |   |-- 3_Ballot.sol
|   |   |-- DiplomaRegistry.sol
|   |   |-- DocumentRegistry.sol
|   |   |-- InternshipRegistry.sol
|   |   |-- StudentRegistry.sol
|   |   `-- StudyCertificateRegistry.sol
|   |-- ignition/
|   |   `-- modules/
|   |       `-- Lock.js
|   |-- scripts/
|   |   `-- deploy.js
|   `-- test/
|       |-- Ballot_test.sol
|       |-- DiplomaRegistry.test.js
|       |-- DocumentRegistry.test.js
|       |-- InternshipRegistry.test.js
|       |-- StudentRegistry.test.js
|       `-- StudyCertificateRegistry.test.js
|
`-- TMD-frontend/
    |-- .env.example
    |-- .gitignore
    |-- README.md
    |-- package.json
    |-- package-lock.json
    |-- public/
    |   |-- index.html
    |   |-- manifest.json
    |   |-- favicon.ico
    |   |-- robots.txt
    |   `-- images-and-icons/
    `-- src/
        |-- App.js
        |-- App.css
        |-- App.test.js
        |-- api.js
        |-- index.js
        |-- index.css
        |-- logo.svg
        |-- reportWebVitals.js
        |-- setupTests.js
        `-- component/
            |-- home/
            |   |-- Layout.js
            |   |-- Home.js
            |   |-- Verify.js
            |   |-- creators.js
            |   `-- *.module.css
            |-- login/
            |   |-- login.js
            |   |-- Admin.js
            |   |-- Student.js
            |   |-- ForgotPassword.js
            |   `-- *.module.css
            |-- admin/
            |   |-- Navbar.js
            |   |-- add/
            |   |-- audit/
            |   |-- authori/
            |   |-- dashboard/
            |   |-- list/
            |   |-- param/
            |   |-- request/
            |   |-- static/
            |   |-- students/
            |   `-- verify/
            `-- student/
                |-- DashboardStudent.js
                |-- RequestStudent.js
                |-- Settings.js
                `-- *.module.css
```
