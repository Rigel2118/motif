# motif
Simple tool for storing file templates (motifs) and create files with them anytime.
# Installation
Add the script to your path.
# Usage
## Create new motif
```bash
motif -n template_name file_name 
```
## Using a motif to create a file
```bash
motif template_name file_name
```
## Remove a motif
```bash
motif -r template_name
```
## Edit a motif
Just override it as if creating a new one.
## Show list of stored motifs
```bash
motif -l 
```
