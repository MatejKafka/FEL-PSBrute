# PSBrute

Functions to interface with the BRUTE evaluation system at FEE CTU in Prague.

## Installation

Clone this repository to a directory that's in your `$env:PSModulePath`. Note that the cloned directory **must be called `BRUTE`**, which is also the module's name.

```
git clone https://github.com/MatejKafka/FEL-PSBrute BRUTE
```

Now, the module should be importable by calling `Import-Module BRUTE`, or just invoking one of the exported functions.

## Troubleshooting

If you get an error like `"Forwarded input field with 'name="manual_score"' not found in the AE page."`, your PowerShell is probably too old. Try installing a newer/preview version (it works on PowerShell 7.3.0-preview.2 and newer).