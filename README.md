# TXT to Sheets Converter v0.2

A tool for converting structured text files into Google Sheets format.

## Usage

```
process @filename.txt
```

For detailed format specifications and examples, see:
- Format rules: `.cursor/rules/txt_to_sheets.mdc`
- Input example: `examples/example_businessTrip_input.txt`
- Output example: `examples/example_businessTrip_output.csv`

## Features

- Convert structured text files to Google Sheets
- Support for various text file formats
- Easy-to-use interface

## Format

The converter expects input text files in a free-form format and converts them into a structured CSV/spreadsheet format:

Input: Free-form text with sections, lists, and nested data (see `examples/example_businessTrip_input.txt`)
Output: Structured spreadsheet with:
- Emoji section markers (e.g. 💰, 📊, ✅)
- Clear hierarchy using empty cells and indentation
- Proper column alignment
- Notes and calculations in square brackets
See `examples/example_businessTrip_output.csv` for the expected output format.

## Development

This project uses GitWorkflow for standardized git operations.
- ALWAYS use `.git_workflow/git_workflow.ps1` for git operations
- NEVER use raw git commands unless explicitly approved

## License

MIT License - see the LICENSE file for details. 