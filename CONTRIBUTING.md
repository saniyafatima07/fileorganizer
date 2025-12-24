# Contributing to FileOrganizer

Thank you for your interest in contributing to **FileOrganizer**, a project designed to help organize files into structured folders automatically based on their types. This guide explains how you can contribute, set up the development environment, and follow best practices.

## 🛠️ Development Setup

### 1. Clone the Repository

```bash
git clone https://github.com/saniyafatima07/fileorganizer.git
cd fileorganizer
```
### 2. Install Dependencies

```bash
go mod tidy
```
### 3. Run the Development Server

```bash
go run .
```
Visit the application in your browser:
http://localhost:3000

### 4. Testing FileOrganizer

- Place files in the test folder.
- Run the program.
- Ensure files move to appropriate folders based on their extensions.
- Confirm that errors and unsupported types are handled gracefully.

### Code Contributions

Follow these steps to contribute code:

1. Fork the Repository
   
3. Click the Fork button on the top right of the repository page.
   
5. Create a New Branch
```bash
git checkout -b feature/your-feature-name
```

4. Make Changes
   
6. Write clean, well-documented code and ensure existing functionality is not broken.
   
8. Commit Changes
```bash
git commit -m "Add meaningful commit message"
```

7. Push to Your Branch
```bash
git push origin feature/your-feature-name
```

8. Submit a Pull Request
  - Go to the original repository and click New Pull Request.
  - Provide a clear description of the changes you’ve made.

### Code Style Guidelines

- Follow idiomatic Go coding standards.
- Use meaningful variable and function names.  
- Ensure code is modular and well-commented.  
- Handle errors properly and thoroughly. 
