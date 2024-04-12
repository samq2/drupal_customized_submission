Documentation for elements_list and what you can do (commands):
- Add the key in the order you want it to appear in the submission
- Any hidden elements and optional fields will automatically not be included, continue to add them in the order you want it to appear in the form as if it is going to be visible
- Add 'linebreak' to indicate 1 line break to give breathing room
- Add 'print_line' to print out a line (-----)

Commands:
*All commands follow the format of command | element_key*

linebreak | *numberofspaces*: add specified number of linebreak\n
print_text | *text here inside quotation marks*: print out customize text\n
print_line | bolded: prints \*\*\*\*\* instead of -----\n
print_section | *section element key*: Prints out the section of the form with the same order as it has on the user view of the form\n
print_section_title | *section element key*: Only prints out the title of the section\n
