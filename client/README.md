# PDF Viewer

This is the frontend part of the PDF Management System, a web-based application for managing and manipulating PDF documents. This README provides an overview of the frontend setup and usage.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- VS Code:[Download VS code](https://code.visualstudio.com/download)

- Node.js: [Download Node.js](https://nodejs.org/)

- MongoDB Atlas: [Create Account and get database url](https://www.mongodb.com/atlas/database)

### Installation

1. Clone the repository, Install dependencies and start frontend server:

```shell
git clone https://github.com/arunava-saha/pdffullMERN.git
cd client
npm i
npm run dev
```

The application should now be running at http://localhost:5173.

2. Open a new terminal and Install dependencies and start backend server

```shell
cd server
npm i
npm run dev
```

The server should now be running at http://localhost:5000.
if the server is not at 5000 port then rename the .env.sample file to .env and add MongoDB Atlas database link for port and database to work.
