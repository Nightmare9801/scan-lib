## Scan-Lib
## Description
It is a library version of the original program, TurboScan.

## Installation
To install scan-lib in your project type the following command in the terminal
```bash
  cargo add scan-lib
```
## Usage
To use scan-lib in your project, first, create an object of type DirectorySearcher
```bash
  let mut searcher = DirectorySearcher::new();
```

To search for a string in a Directory
```bash
  let searched_objects = searcher.search("F:", "java");
```

## Contributing

If you would like to contribute to scan-lib, feel free to fork the repository and submit a pull request. We welcome any improvements or new features that can enhance the tool.

## License

scan-lib is licensed under the MIT License. See the `LICENSE` file for more information.


