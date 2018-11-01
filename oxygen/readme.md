
# Using NIEM snippets with Oxygen XML Editor

For more information on snippets in Oxygen, please their page about [Code Templates](https://www.oxygenxml.com/doc/versions/20.0/ug-author/topics/code-templates-x-modes3.html).

- [Import snippets](#import-snippets)
- [Use a snippet](#use-a-snippet)
- [Modify a snippet](#modify-a-snippet)
- [Reload snippets](#reload-snippets)

## Import snippets

- Download the snippet file to any directory
- In Oxygen, click on menu item **Options** -> **Preferences...**
- In the Preferences panel on the left sidebar, click on **Editor** -> **Templates** -> **Code Templates**
- Click the Import button near the bottom right of the panel and select the downloaded snippets file

![Importing snippets](images/import.png)

## Use a snippet

Note: All NIEM snippets begin with "niem-"

- Type "niem" in an XML schema file
- Hit Ctrl/Cmd + Space
- Scroll down through the drop-down list to see all applicable snippets that begin with "niem".
  - Recently used snippets will appear at the top of the list
  - The snippet title and code will
- The more you type in the snippet name before hitting Ctrl/Cmd + Space, the narrower the list will be.
  - "niem-type" + Ctrl/Cmd + Space will bring up a list of all NIEM type snippets.
  - "niem-type-ccc" + Ctrl/Cmd + Space will automatically
- Hit "Tab" or "Enter" to load the snippet
- The snippet will be incomplete.
  - Fields like names and definitions may be partially provided or completely blank and must be filled in.
  - In some cases, defaults may be provided but can be changed as needed.

## Modify a snippet

- In Oxygen, click on "Options" / "Preferences" / "Editor" / "Templates" / "Code Templates"
- Select the snippet to modify
  - The snippet will begin with "niem-"
  - NIEM snippets will appear under "XSD Editor" and/or "JSON Editor" group
- Click the "Edit" button

![View snippets](images/view.png)

- Modify the snippet name, description, code, or add a keyboard shortcut.
- Notes:
  - The `${caret}` variable marks the position where the cursor will appear once the snippet is loaded.
  - It is not necessary to indent the snippet code; Oxygen will add indentation when the snippet is loaded.

![Edit a snippet](images/edit.png)

## Reload snippets

- To load an updated snippets file, simply go through the original import steps again.
- Snippets with the same name and editor group will be overwritten.
