# Example files

This directory contains example files for the mutation_test program.

## Example configuration 1

This command produces the example [outputs](https://domohuhn.github.io/mutation-test/output/config-report.html).
```bash
# Run the tests in directory "example":
# Write output to docs/output
# produce all report file formats
./mutation_test example/config.yaml -o doc/output -f all
```
A YAML config (`config.yaml`) and an equivalent XML config (`config.xml`) are both provided in this directory.

## Example configuration 2

This command would perform the mutation tests on itself. Requires about 30min to complete.
```bash
# Run the tests in directory "example":
# output defaults to directory ./mutation-test-report
# report format defaults to html
./mutation_test example/config2.xml
```
Note: config files can be YAML (`.yaml`/`.yml`) or XML (`.xml`).
