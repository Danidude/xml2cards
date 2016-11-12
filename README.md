# About

xml2cards converts item descriptions in the [DnD App Files](https://github.com/ceryliae/DnDAppFiles) format to the JSON
format required by [RPG cards](https://crobi.github.io/rpg-cards/generator/generate.html).

The script automatically maps item types to card colors and icons and adds all the properties for you. 

# Requirements

The Python module *pyphen* is used for hyphenation.

# Usage

1. Type in the items your group has in a text file (one per line)
2. Run the script:
   ```
   ./xml2cards.py items.xml party.txt output.json
   ```
3. Open the JSON file in RPG cards and edit as you see fit