# G-CLI-ClearCache


This provides the ability to clear the internal LabVIEW caches from the command line.

This should eventually be integrated with G-CLI as part of https://github.com/JamesMc86/G-CLI/issues/116 however I'm building seperately to release before G-CLI 3.0.

## Development Requirements

This is built in LV2011 and should support all versions after that.

## Usage

Calling this with no arguments will clear both user and app builder caches.

Specify `--user-only` or `--app-builder-only` to clear only one or the other.