# Simple Pandoc Letter and Invoice

This is small script and template to create invoices and letters. The invoice table part is taken from [invoice-boilerplate](https://github.com/mrzool/invoice-boilerplate).

The repo contains a `zsh`-script `pandocletter`. Add this to your path.
If you want to create a letter/invoice in any place just call

```sh
$ pandocletter letter.md
```

which will create the `.md` file based on the `example.md` file or, if provided, a `private.md` file from the same directory as the file. The newly created markdown file will be transformed to pdf using pandoc and the `template.tex` template.

Now change the `letter.md` file to your needs and recreate the pdf output with the same `pandocletter` command.
If you don't need the invoice part just delete it. If there is no invoice part the output won't show tax id or bank account either.
The letters can be both in `ngerman` and `english`.
