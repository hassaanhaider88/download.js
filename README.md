# download.js

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url] [![Dependency status][david-dm-image]][david-dm-url] [![Dev Dependency status][david-dm-dev-image]][david-dm-dev-url]

# download.js

A simple, client-side utility for programmatic file downloads in web browsers. This library provides functions to trigger downloads from a URL, a Blob object, or plain text content directly in the user's browser.

## Tech Stack

*   **Languages:**
    *   TypeScript
*   **Tools:**
    *   [npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
    *   [TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

## Project Structure

```
.
├── lib/
│   ├── index.d.ts
│   └── index.js
├── src/
│   └── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Key Features

*   Programmatic file downloading within a web browser environment.
*   Download files directly from a specified URL.
*   Download files from a `Blob` object, useful for client-side generated content.
*   Download plain text content as a file.

## Setup Instructions

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/inker/download.js.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd download.js
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```

### Build the Project

To compile the TypeScript source code into JavaScript and generate type definitions:

```bash
npm run build
```
To download a blob, one may use the `downloadBlob` function.

[npm-url]: https://npmjs.org/package/download.js
[downloads-image]: http://img.shields.io/npm/dm/download.js.svg
[npm-image]: http://img.shields.io/npm/v/download.js.svg
[david-dm-url]:https://david-dm.org/inker/download.js
[david-dm-image]:https://david-dm.org/inker/download.js.svg
[david-dm-dev-url]:https://david-dm.org/inker/download.js#info=devDependencies
[david-dm-dev-image]:https://david-dm.org/inker/download.js/dev-status.svg
