# Documentation
This allows our team to customize the output of the questions in UW Connect. To use this,
1. Open index.twig
2. Open an AST form in Drupal as an editor (Structure > Webforms > *Form*)
3. Go to Settings
4. Go to Email/Handlers tab
5. Create or edit an email handler
6. In the Message section, click on the dropdown of Body and select "Twig template..."
7. Copy and paste the code from index.twig into the field
8. Change the elements_list with the element keys or commands
  - Add the key in the order you want it to appear in the submission
  - Any hidden elements and optional fields will automatically not be included, continue to add them in the order you want it to appear in the form as if it is going to be visible
  - Add 'linebreak' to indicate 1 line break to give breathing room
  - Add 'print_line' to print out a line (-----)


## Additional Commands
*All commands follow the format of: command | input*

| Command    | Savings |
| -------- | ------- |
| linebreak \| *numberofspaces*  | add specified number of linebreak     |
| print_text \| *"text here inside quotation marks"* | print out customize text |
| print_line \| bolded   | prints \*\*\*\*\* instead of ----- |
| print_section \| *section element key* | Prints out the section of the form with the same order as it has on the user view of the form |
| print_section_title \| *section element key* | Only prints out the title of the section |
