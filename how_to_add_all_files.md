# How to Recombine Split Files on Windows

Follow these steps to recombine split files (`part_aa`, `part_ab`, etc.) into a single file:

## Steps

1. **Open Command Prompt:**
   - Press `Win + R`, type `cmd`, and hit Enter.

2. **Navigate to the Folder:**
   Use the `cd` command to navigate to the folder containing the parts:
   ```cmd
   cd C:\path\to\parts

`copy /b part_aa + part_ab + part_ac combined_file.zip`

`unzip combined_file.zip`
