# BugBoster

BugBoster is a vulnerability detection tool developed for cybersecurity specialists and penetration testers. It is written in C and supports multiple vulnerability detection methods such as SQL Injection and XSS (Cross-Site Scripting). Additionally, it features bulk scanning capabilities to search for vulnerabilities across multiple targets simultaneously.

## Features
- Detects SQL Injection vulnerabilities.
- Detects XSS (Cross-Site Scripting) vulnerabilities.
- Bulk scanning feature to scan multiple targets at once.

## Requirements
- **Operating System:** Kali Linux or any Linux-based system.
- **Compiler:** GCC (GNU Compiler Collection)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/eldaniz404wtf/bugboster.git
    ```
2. Navigate to the BugBoster directory:
    ```bash
    cd bugboster
    ```
3. Compile the code:
    ```bash
    gcc -o bugboster bugboster.c
    ```

## Usage
You can run the tool using the following command:
```bash
./bugboster [options] [target]
```
Example:
```bash
./bugboster -sql http://example.com
```

## Options
- `-sql` : Scans for SQL Injection vulnerabilities.
- `-xss` : Scans for XSS vulnerabilities.
- `-batch` : Scans multiple targets. Specify the target file.
- `-h`   : Displays help information.

## Contribution
We welcome contributions! Follow these steps to contribute to the project:
1. Fork the repository.
2. Create a new branch for your feature:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes and push them to your fork.
4. Open a pull request.

## License
This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

## Contact
For questions or suggestions, use the following contact information:
- **Developer:** eldaniz404wtf
- **Email:** eldaniz.ibrahimli.contact@gmail.com

---

*Wishing you success in hunting vulnerabilities!*
