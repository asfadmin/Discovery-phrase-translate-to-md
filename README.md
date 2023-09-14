# phrase-translate-to-md

The 'phrase-translate-to-md.py' is used to create .md files from .key files.
Pass the source directory or file as an argument to the script, and 
it will process recursively through the directory and process .key files and create 
.md files for each of locales in the phrase strings project.

The 'phrase_strings.py' script is used for interfacing
to the Phrase API to get locales and translations for a project. The
script expects the Phrase access token to be stored in the environment.