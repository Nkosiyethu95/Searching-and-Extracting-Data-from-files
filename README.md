# Searching-and-Extracting-Data-from-files

## Key Knowledge Areas
- **Command line pipes** (`|`)
- **I/O redirection** (`>`, `>>`, `<`)
- **Basic Regular Expressions**:
  - `.` (matches any character)
  - `[ ]` (matches any character inside the brackets)
  - `*` (matches zero or more occurrences of the previous character)
  - `?` (matches zero or one occurrence of the previous character)

## Commands and Utilities Covered
- `grep` - Search for patterns in files
- `less` - View file content page by page
- `cat` - Concatenate and display file content
- `head` - Display the first few lines of a file
- `tail` - Display the last few lines of a file
- `sort` - Sort lines of text
- `cut` - Extract sections of lines from files
- `wc` - Count words, lines, and characters in a file

## Usage Examples
### 1. Searching for a pattern in a file
```bash
grep "error" /var/log/syslog
```
### 2. Viewing file content
```bash
less /etc/passwd
```
### 3. Displaying the first 10 lines of a file
```bash
head -10 file.txt
```
### 4. Displaying the last 10 lines of a file
```bash
tail -10 file.txt
```
### 5. Sorting a file alphabetically
```bash
sort file.txt
```
### 6. Extracting the first column of a CSV file
```bash
cut -d',' -f1 data.csv
```
### 7. Counting words in a file
```bash
wc -w file.txt
```

## Contributing
Feel free to submit issues or pull requests to improve this repository.
