# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is a system divided into two main parts: the application tier and the database tier. Each tier has a specific responsibility and communicates with the other tier to provide the complete application.

## Web/Application Tier

The Web/Application Tier handles the application that users interact with. In this activity, the Nextcloud container acts as the application tier. It provides the web interface, receives HTTP requests, and processes user actions.

## Database Tier

The Database Tier stores persistent information required by the application. In this activity, MariaDB is used to store Nextcloud data such as user accounts and other application metadata.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container can be updated, restarted, or scaled independently without putting both services into one container.
