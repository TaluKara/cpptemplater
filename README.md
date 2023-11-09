# cpptemplater command usage guide

The `cpptemplater` command is a custom script that makes c++ files with templates in it. This guide explains how to set up and use the `cpptemplater` command.

## Installation

1- Clone or download the repository to your local machine.

```bash
git clone https://github.com/h7yt0p/cpptemplater.git
```

2- Navigate to the directory containing the `cpptemplater` script using the terminal:

```bash
cd cpptemplater
```

3- Make the script executable:

```bash
chmod +x cpptemplater
```

4- Create a symbolic link to make the `cpptemplater` command available globally (optional):

```bash
sudo cp cpptemplater /usr/local/bin/
```

Now, you can use the `cpptemplater` command globally in your terminal.

## Usage

To use the `cpptemplater` command, follow these steps:

1. Open a terminal.
2. Type `cpptemplater` followed by the name of the file you want to change permissions on and execute. For example:

   ```bash
   cpptemplater main
   ```
3. The script will create a file named "main.cpp" and then place the template
   in "cpptemplater" inside the file it created. If you want, you can
   customize the template in the "cpptemplater" file to make it your own!The script will create a file named "main.cpp" and then going to Troubleshooting

If you encounter any issues, double-check the file path and permissions.
Ensure that you have the necessary privileges to execute files in the chosen directory.
