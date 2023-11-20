## Setting Up Environment Variables

To run this project locally, you need to set up environment variables for database connections. Follow these steps:

1. Create two environment files in the project root directory:
   - **.env.test:** This file is for the test environment.
   - **.env.development:** This file is for the development environment.

2. Open each file and add the following line with the correct database name for that environment (refer to `/db/setup.sql` for the database names):

    ```plaintext
    PGDATABASE=your_database_name
    ```

   Replace `your_database_name` with the appropriate database name for the environment.

3. Ensure that these environment files are added to the `.gitignore` file to prevent sensitive information from being pushed to GitHub.

4. Save the changes to the environment files.

Now, you can run the project locally with the configured database connections.

**Note:** If you are cloning this repository, you'll need to follow these steps to set up your local environment properly.



