# Friendbuy Platform Release Notes
This repository houses Friendbuy’s release notes feed, maintained in YAML format.

## Release Notes Structure
The Friendbuy release notes file (_feed.yaml_) is a hyphenated list of YAML release notes entries with the following properties:

- `date` in _yyyy-mm-dd_ format
- `title`: a nested object with `text` (title of What’s New entry) and `link` (URL to Friendbuy help page detailing that entry)
- `description`: Follow the field name with a `|` and enter the description of the new feature on the line below that one
