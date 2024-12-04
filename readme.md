# callisto

DNS config for `andref.app`.

## Usage

To add a new record, modify `octodns-config-template/andref.app.yaml`. Do not modify anything in `octodns-config-build`, as those files are overwritten by the build process.

## Architecture

To avoid hardcoding IP addresses, the yaml files undergo a preprocessing step, which replaces placeholders with the actual IP addresses. This is done by a script in Jupiter (private repo).