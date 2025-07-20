# dm-data-source-attribution-eraser
Removes or modifies metadata associated with data sources (e.g., database server names, file paths, timestamps). Prevents attackers from easily mapping masked data back to its original source or inferring information about the data's lineage or update frequency. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-source-attribution-eraser`

## Usage
`./dm-data-source-attribution-eraser [params]`

## Parameters
- `-h`: Show help message and exit
- `--input`: Path to the input file/directory containing data source metadata.
- `--output`: Path to the output file/directory where anonymized data will be written.
- `--remove-timestamps`: Remove timestamp-related metadata.
- `--remove-filepaths`: Remove file path-related metadata.
- `--remove-servernames`: Remove server name-related metadata.
- `--custom-patterns`: Path to a file containing custom regex patterns to remove. Each pattern should be on a new line.
- `--dry-run`: Perform a dry run without modifying any data. Useful for testing the configuration.

## License
Copyright (c) ShadowGuardAI
