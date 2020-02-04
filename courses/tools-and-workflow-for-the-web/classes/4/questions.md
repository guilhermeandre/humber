## Part 1

## Introduction
Use this document as a starting point for Part 1 of the Class 4 exercise. Answer the each of the questions below and either:
  - Attach this document to your exercise submission email.
  - Or copy-and-paste the contents of this document into your submission email.

## Questions
1. Write the command (or commands) that will display the following message 'Hello from the command line.'
echo “Hello from de command line.”

2. Write the command (or commands) that will create a file named 'hello-world.txt'.
touch hello-world.txt

3. Write the command (or commands) that will create a folder named 'my-new-folder' in current directly.
mkdir my-new-folder

4. Write the command (or commands) that will attempt to delete a folder named 'my-nonexistent-folder' and display the following message when the commands fails: 'Whoops, cannot delete a folder that does not exist'.
rmdir my-nonexistent-folder | echo “Whoops, cannot delete a folder that does not exist”

5. Write the command (or commands) that will navigate to your desktop, and then to the parent folder.
cd desktop && cd ..

6. Write the command (or commands) that will tell you the location of the Z Shell.
which bash
