# Specify-the-directory-path

import os

# Specify the directory path
directory_path = 'D:\The Python Ultimate Course'

# Get the list of files and directories in the specified path
contents = os.listdir(directory_path)

# Print the contents with details
print("Contents of the directory:")
for item in contents:
        print(item)
