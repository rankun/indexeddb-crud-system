# IndexedDB CRUD System

This project is a complete CRUD (Create, Read, Update, Delete) system for managing IndexedDB databases through a user-friendly front-end. It allows users to easily create and edit databases, object stores, and entries using an intuitive web interface. This application serves as a helpful tool for understanding and interacting with IndexedDB, the low-level API for client-side storage in the browser.

## Features

- **Manage Databases**: Create, load, and delete IndexedDB databases.
- **Manage Object Stores**: Create, load, and delete object stores within a database.
- **Manage Entries**: Add, edit, load, and delete entries within an object store.
- **Navigation System**: Seamlessly navigate between databases, stores, and entries.
- **Loading Indicator**: Visual loading indicators display current operations in a footer section, ensuring a clear understanding of background processes.
- **Edit Screens**: Dedicated edit screens for updating fields, ensuring an improved user experience when modifying entries.
- **Back Button for Navigation**: Easily navigate to previous contexts with a back button for enhanced usability.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/rankun/ndexeddb-crud-system.git
   ```

2. Navigate to the project directory:
   ```sh
   cd indexeddb-crud-system
   ```

3. Open `index.html` in your browser to start the application.

## Usage

- **Creating a Database**: Enter the database name and click on "Create Database".
- **Loading Databases**: Click on "Load Databases" to view all available databases.
- **Managing Object Stores**: Navigate into a database to create, load, or delete object stores.
- **Managing Entries**: Navigate into an object store to add, load, edit, or delete entries.
- **Edit Entries**: Click the "Edit" button to open a dedicated edit screen with current values.
- **Back Navigation**: Use the "Back" button to return to the previous context.

## Technology Used

- **HTML/CSS**: For the layout and styling of the front-end.
- **JavaScript**: To interact with IndexedDB and manage CRUD operations.
- **IndexedDB**: A low-level API for client-side storage of significant amounts of structured data, including files.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any feature improvements or bug fixes.

1. Fork the repository.
2. Create your feature branch:
   ```sh
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```sh
   git commit -m 'Add your feature description'
   ```
4. Push to the branch:
   ```sh
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) for comprehensive IndexedDB documentation and examples.

