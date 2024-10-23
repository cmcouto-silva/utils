# Scripts

A set of useful scripts for development.

## Python Scripts

### - `write_file_contents`

Usage:
```bash
# Basic usage (automatically ignores common directories like .venv, venv, etc.)
./save-file-contents /path/to/directory -e py yaml

# Ignore additional directories
./save-file-contents /path/to/directory -e py toml --ignore temp backup old

# Full example with all options
./save-file-contents /path/to/directory -e py yaml toml \
    --ignore custom_venv backup \
    --output output.txt \
    --encoding utf-8 \
    --debug
````
