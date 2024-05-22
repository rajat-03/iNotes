# iNotes

iNotes is a PHP CRUD application for efficient note-taking. With iNotes, you can create, read, update, and delete notes seamlessly. This README will guide you through the process of setting up and running iNotes on your local computer using XAMPP.

## Requirements

- XAMPP (Apache, MySQL, PHP, and Perl) installed on your local computer.

## Installation

1. **Download XAMPP**:

   - If you haven't already, download and install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

2. **Clone the Repository**:

   - Clone this repository to your local machine or download the ZIP file and extract it.

   ```sh
   git clone https://github.com/rajat-03/iNotes.git
   ```

   - Place the `inotes` folder in the htdocs directory inside your XAMPP installation directory. Typically, it is located at `C:\xampp\htdocs\`.

3. **Start XAMPP**:

    - Open the XAMPP Control Panel.
    - Start the Apache and MySQL modules.

4. **Create the Database**:

    - Open your web browser and navigate to `http://localhost/phpmyadmin`.
    - Click on the "Databases" tab and create a new database named inotes.
    - Import the database schema by selecting the inotes database, then go to the `Import` tab and choose the `notes.sql` file located in the project directory. Click "Go" to import the schema.

5. **Run the Application**:

    - Open your web browser and navigate to `http://localhost/inotes`.
    - You should see the iNotes application home page where you can start creating, reading, updating, and deleting notes.