# CLI Contact Manager

A simple command-line interface application for managing contacts. This Node.js application allows you to add, remove, list, and find contacts using simple commands.

## Features

- Add new contacts with name, phone, and email
- Remove existing contacts
- List all saved contacts
- Find contacts by name, phone, or email

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/renerroll/goit-node-cli.git
cd goit-node-cli
npm install
```

## Usage

### List all contacts

```bash
node index.js --action list
```

### Get contact by ID

```bash
node index.js --action get --id vza2RIzNGIwutCVCs4mCL
```

### Add new contact

```bash
node index.js --action add --name John --email john@example.com --phone 123-456-7890
```

### Remove contact

```bash
node index.js --action remove --id drsAJ4SHPYqZeG-83QTVW
```

## Project Structure

```
goit-node-cli/
├── contacts.js     # Functions for managing contacts
├── db/
│   └── contacts.json  # Storage file for contacts
├── index.js        # Main application entry point
├── package.json    # Project dependencies
└── README.md       # This file
```

## Dependencies

- commander - Command line argument parsing
- nanoid - Generating unique IDs

## License

This project is licensed under the MIT License.