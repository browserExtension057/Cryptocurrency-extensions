# Cryptocurrency-extensions
This repository contains data and code for SIGMETRICS 2022 submission: Characterizing Cryptocurrency-themed Malicious Browser Extensions

## Malicious extensions
There are 134 malicious extensions in total located in the directory:

```shell
./malicious_extensions
```

Five subdirectories divide those extensions into five categories: phishing, mining, scam, adware and gambling.

## Whole dataset
There are 2975 cryptocurrency-themed browser extensions in 6 official web stores(chrome, firefox, opera, edge, 360, whale) and 3 third-party extension stores(crx4chrome, guge, haoyong), located in the directory:

```shell
./all_extensions/[store name]
```

Besides, we maintain a set of extensions which are all removed by official auditting and checking, located in the directory:

```shell
./all_extensions/[store_name]_removed_by_store
```
## Source code
We open the source code for the detection of malicious extensions including crawlers, preliminary analysis, static analysis and dynamic analysis.

### Crawlers
There are 6 crawlers running in the server while 3 in official extension stores (chrome, firefox, opera) and 3 in third-party extension stores (guge, crx4chrome, haoyong), located in the directory:
```shell
./source_code/crawlers
```
### Preliminary analysis
Preliminary analysis includes VirousTotal scanning, and filtering by download numbers, negative reviews and low ratings, located in the directory:
```shell
./source_code/preliminary_analysis
```

### Static analysis
Static analysis includes permission and AST feature extraction, located in the directory:
```shell
./source_code/static_analysis
```

### Dynamic analysis
Dynamic analysis includes automatical collection of runtime behavior features (system-level behaviors and network-level behaviors), located in the directory:
```shell
./source_code/dynamic_analysis
```
