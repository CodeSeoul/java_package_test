# Java Package Example

This demonstrates how packages work in Java without an IDE.

## Steps
1. Make sure your command line is in `java_package_test` (this directory)
2. Run `javac afolder/Main.java bfolder/Other.java`
3. Run `java afolder.Main`
4. Do a dance.

## Why?
Because `Main` and `Other` have their packages listed as `afolder` and `bfolder`, respectively, they're treating `java_package_test` as the root source directory. As long as you do any package references from this folder that they both recognize as the source root, everything will work.
