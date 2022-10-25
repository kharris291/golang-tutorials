Basics for importing an external package.

- First thing, a package must be in a place you're able to import from.
- Once you import a package you must insure it can be downloaded and used. Use the following command to import and authenticate the module.
```bash
go mod tidy
```
-   You can also do this by importign the package directly with the following command
```bash
go get rsc.io/quote
```
