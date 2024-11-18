# Web Archive Backup - Webarchive Saver

## Description

**Web Archive Backup** is an application that allows you to automatically archive URLs on the **Wayback Machine** using the public **Web Archive API**. The project provides a secure and permanent way to save web pages over time, making them accessible in the future even if the original content is removed or modified.

The application was developed with the aim of simplifying the website backup process by providing an automated solution that interacts with the Wayback Machine API. This archiving process allows for the preservation of important content and increases the visibility of specific URLs over the long term.

## Technologies and Requirements

- **PHP**: Programming language used to develop the application.
- **cURL**: Used to send HTTP requests to the Web Archive API.
- **Web Archive API**: The public API of [Wayback Machine](https://web.archive.org/save/) to archive URLs on the platform.
- **Web Server**: The project is designed to run on servers that support PHP (e.g., Apache, Nginx).

## Features

- **URL Archiving**: Allows users to send any URL to the Web Archive service for archiving in their historical archive.
- **Interaction with the Web Archive API**: The application interacts with the Web Archive API using cURL to send a save request.
- **Real-time Feedback**: Once the URL has been archived, the user is given a direct link to the archived page, allowing access at any time in the future.

## How to Use

1. **Clone the Repository**:
   To get started, clone the repository to your local machine:
   ```bash
   git clone https://github.com/1r0n3d3v3l0per/wayback-saver.git
   cd wayback-saver
