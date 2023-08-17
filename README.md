# Regex code to run on new notes before commit
- Run it on _notes to apply the replace to all notes
\b([#])(([^|]*)).*?(?=\||\]\])

It removes the header links from all notes
## License

Source code is available under the [MIT license](LICENSE.md).
