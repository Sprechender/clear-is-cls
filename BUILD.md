## Building the Executable

To build the script into an executable:

1. Ensure Python is installed on your system.
2. Install the necessary build requirements by running:
```bash
pip install -r build_requirements.txt
```
3. Navigate to the `build` folder in your command prompt.
4. Execute the `build.bat` file.
5. The script will be compiled into `main.exe` then renamed to `clear.exe`.
6. Find the compiled executable in the `dist` folder.

### Build Folder Structure
- `build`
- `dist`
    - `clear.exe`: Compiled executable file.
- `build.bat`: Builds the script into clear.exe.

## Notes
- No additional packages are required to run the script only for building.
- Ensure Python is properly installed on your system to execute the Python script (non .exe version).
- The `os.system('cls')` command is specific to Windows systems for clearing the console.
- THIS IS ONLY SUPPORTED ON WINDOWS!!!

Feel free to modify and enhance the script as needed!