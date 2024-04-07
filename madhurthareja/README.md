## Shell Script Utility README

This shell script utility provides several functions to perform common tasks such as backup, file manipulation, encryption/decryption, and word count in a file. Below is a brief overview of each function and how to use them.

### Functions:

#### 1. Backup a directory
- **Function Name:** `backup_directory`
- **Usage:** `backup_directory <source_directory> <backup_directory>`
- **Description:** This function backs up the contents of a source directory to a specified backup directory using `rsync`.

#### 2. Unzip a file
- **Function Name:** `unzip_file`
- **Usage:** `unzip_file <zip_file>`
- **Description:** This function unzips a specified zip file.

#### 3. Encrypt and decrypt a file
- **Function Name:** `encrypt_decrypt_file`
- **Usage:** `encrypt_decrypt_file <file_path>`
- **Description:** This function allows encryption and decryption of a specified file using OpenSSL. It requires a password to perform the encryption/decryption.

#### 4. Count the number of occurrences of a specific word in a file
- **Function Name:** `count_word_occurrences`
- **Usage:** `count_word_occurrences <file_path> <search_word>`
- **Description:** This function counts the number of occurrences of a specific word in a given file.

### How to Use:

1. **Clone the repository:** Clone this repository to your local machine.

2. **Navigate to the directory:** Open your terminal and navigate to the directory containing the shell script utility.

3. **Run the script:** Execute the script by running the following command:
   ```
   bash utility_script.sh
   ```

4. **Choose an option:** Select an option from the provided menu:
   - Option 1: Backup a directory
   - Option 2: Unzip a file
   - Option 3: Encrypt and decrypt a file
   - Option 4: Count the number of occurrences of a specific word in a file

5. **Follow the prompts:** Depending on the option chosen, the script will prompt you to provide necessary inputs such as source directory, backup directory, file path, operation (encrypt/decrypt), and search word.

6. **View the results:** After providing the required inputs, the script will execute the selected function and display the results.

### Note:

- Ensure that you have necessary permissions to execute the script and access the specified directories/files.
- For encryption and decryption, make sure to remember the password used, as it will be required to decrypt the file later.
- This script assumes basic familiarity with shell scripting and command-line usage.