# org File Manager

**org** is a lightweight, fast, and user-friendly file manager built with C++ and Qt. Designed with simplicity in mind, it provides a clean interface to navigate and manage your filesystem efficiently.

## Features
- [ ] Simple and intuitive interface
- [ ] Basic file operations: create, delete, rename, move files and directories
- [ ] Detailed file properties display
- [ ] Support for multiple views (list view, icon view)
- [ ] Search functionality
- [ ] Fast and responsive

---

## Project Stages

1. **Initial Development**:
   - [x] Set up C++ project using **Qt** framework.
   - [ ] Implement basic file and directory navigation.
   - [ ] Basic file operations (create, rename, delete).

2. **Intermediate Development**:
   - [ ] Add multiple view modes (list view, grid view).
   - [ ] Improve UI with custom icons and layouts.
   - [ ] Implement search functionality.
   - [ ] File preview functionality (for text, images).

3. **Advanced Features**:
   - [ ] Add support for keyboard shortcuts.
   - [ ] Improve file operations (drag-and-drop, copy-paste).
   - [ ] Add configurable options (themes, preferences).
   - [ ] Optimize performance for handling large directories.

---

## Project Setup

### Prerequisites

To compile and run the project, make sure you have the following installed:

- **C++ compiler** (e.g., GCC or Clang)
- **Qt6 Framework** (including Qt6 base and development tools)
- **Qt Creator** (optional but recommended for development)

### Dependencies

You will need to install the following packages on your system:

- **Ubuntu | Debian**:
  ```bash
  sudo apt update
  sudo apt install build-essential qt6-base-dev qt6-qmake qt6-tools-dev-tools
  ```

- **Fedora** (if applicable):
  ```bash
  sudo dnf groupinstall "C Development Tools and Libraries"
  sudo dnf install qt6-devel qt6-qtbase-devel qt6-qmake
  ```

---

### Building and Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hizawye/org.git
   cd org
   ```

2. **Using Qt Creator** (Recommended):
   - Open **Qt Creator** and load the project (`.pro` file).
   - Click on "Configure Project" to set up the build environment.
   - Build the project by clicking the "Build" button or using `Ctrl + B`.
   - Run the project directly from Qt Creator with the "Run" button.

3. **Building from Terminal**:
   - Run **qmake** to generate the Makefile:
     ```bash
     qmake -qt=qt6
     ```
   - Compile the project:
     ```bash
     make
     ```
   - Run the executable:
     ```bash
     ./org
     ```


## Contributing

We welcome contributions from the open-source community. To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin feature/my-feature`).
5. Create a new Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

If you have any questions or suggestions regarding the project, feel free to reach out:

- **Email**: safou348@gmail.com.com
- **GitHub**: [Hizawye](https://github.com/hizawye)
