[JSON Schema](https://json-schema.org/) for validating [Splunk Phantom app configurations](https://docs.splunk.com/Documentation/Phantom/latest/DevelopApps/Metadata).

## Usage

To use, add a reference to `splunk-phantom.json` in your app JSON.

```json
{ 
    "$schema": "https://raw.githubusercontent.com/KeiranY/json-schema-splunk-phantom/master/splunk-phantom.json",
    "...continue your app JSON"
}
```

Alternatively use the git.io shortened URL:

```json
{ 
    "$schema": "https://git.io/JtkAD",
    "...continue your app JSON"
}
```