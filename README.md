# misis2025-24-02-baskakov-i-v

1. Create a new repository on GitHub for lab work. I cloned the created repository to my local computer.

2. Created the src and include directories in the root of the repository.
Create two files in the src directory: main.cpp and utils.cpp .
main.cpp contains the main function, which uses
functions from utils.cpp . In utils.cpp contains addition and subtraction functions.
In the include directory, I created the utils.h header file, which describes the functions used.
Created a file CMakeLists.txt at the root of the repository, which
will assemble the project, including main.cpp and utils.cpp .
The project is being successfully assembled - VS displays the message "CMake creation completed"

3. Initialized the Git repository in the root of the project via the terminal (just in case).
I added all the files to the repository and made the first commit with the message "Initial commit: CMake project setup".
Added a file to the repository.gitignore and wrote a commit: "make gitignore".
Create a new branch named feature-utils.
In the feature-utils branch, addbk to utils.cpp the multiplication function and updated main.cpp to use this feature as well.
I have committed changes in the feature-utils branch with the message "feat: Add multiplication function to utils".
Switched back to the main branch.
In the main branch, I made changes to main.cpp : changed the text when outputting the results of calculating functions to the console. Commit the changes with the message
"fix: Update main output message in main branch".
Merged the feature-utils branch into the main branch using the GitHub Desktop toolkit.
Resolved 4 conflicts that arose when merging branches: left the implementation main.cpp from the main branch main; implementation utils.cpp I left it from the feature-utils branch
I have committed the result of the merge.

4. I sent all branches and commits to the remote repository via Push to GitHub Desktop.