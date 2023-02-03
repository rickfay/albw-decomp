# albw-decomp
Decomposition of A Link Between Worlds


# Importing

<u>Note</u>: You must supply your own `baserom.elf`.

Instructions:
1. Start Ghidra
2. Remove any existing work/analysis on the ELF file. To update, we will need an unaltered version of `baserom.elf`.
3. Goto `File` -> `Import File...` and import a fresh copy of your `baserom.elf`
4. Open `baserom.elf` in the CodeBrowser
5. Goto `File` -> `Add to Program...`
6. Select the `baserom.elf.xml` as provided from this repository and click `Add to Program`.


# Exporting

Instructions:
1. Start Ghidra
2. Right Click `baserom.elf` and choose `Export` from the Active Project window
3. Choose `XML` as the Format
4. Click `Options`:
   - Deselect `Memory Contents` so that the code binaries are NOT included.
5. Click `OK`
6. To submit changes, create a new branch off `master` and open a Pull Request for review.

![Export Guide](./images/export-guide.png)