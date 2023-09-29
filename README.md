# ItemExtendedCost Tool README

## Introduction
The **ItemExtendedCost Tool** is a utility designed for TrinityCore World of Warcraft private servers. It allows you to create and manage custom item prices known as "ItemExtendedCost." These prices can represent various in-game resources such as honor, tokens, or other custom currencies.

## Functionality
The tool functions seamlessly with the Full SET Maker, providing an efficient way to organize items based on their ItemLevel. If your items have been generated using the Full SET Maker, this tool is an excellent fit for your needs.

## Important Precautions
Before using the ItemExtendedCost Tool, please consider the following precautions:

1. **Backup Your Database**: It's highly recommended to create a backup of your database before using this tool. This precaution ensures that you can revert to the previous state in case of any unexpected issues.

2. **StartID**: The "StartID" number should be carefully set to ensure uniqueness. It should be the next available number in the ItemExtendedCost table, typically one greater than the highest existing ID. This ensures that new entries do not conflict with existing ones.

3. **Convert ItemExtendedCost.dbc to CSV**: Before using the tool, you need to convert your ItemExtendedCost.dbc file to CSV format. You can do this using a tool like "WoW Parser CSV to DBC and DBC to CSV." This CSV file will be used as a reference for generating new ItemExtendedCost entries.

## How to Use
1. **Start the Tool**: Launch the ItemExtendedCost Tool.

2. **Set StartID**: Enter the appropriate StartID number in the designated field. Ensure it follows the guidelines mentioned above.

3. **Configure Database Connection**: Provide the necessary database connection details. This includes the server, port, database name, username, and password. Make sure the connection details are accurate.

4. **Customize SQL Query**: Customize the SQL query in the "SQL_Commando" field as needed to retrieve the items you want to include in the ItemExtendedCost. This query should return the necessary item data based on your requirements.

5. **Generate CSV Lines**: Click the "Generate CSV Lines" button to generate ItemExtendedCost entries based on the retrieved item data. The tool will create CSV lines that can be used to update your database.

6. **Review and Save**: Review the generated CSV lines in the "MultilineTextBox." Make any necessary adjustments, and then save these lines to your database.

7. **Update ItemExtendedCost**: If needed, you can also use the "Button1" functionality to generate SQL update statements for existing ItemExtendedCost entries. Review and save these statements as required.

## Contact and Support
If you encounter any issues or have questions about using the ItemExtendedCost Tool, please feel free to reach out for assistance. You can contact me on Discord : jadadev.

**Note**: This README provides a general overview of the ItemExtendedCost Tool's functionality and precautions. Be sure to consult the tool's documentation for specific usage instructions and troubleshooting information.
