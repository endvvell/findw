# findw

A script that recursively searches for the specified text in the files of the specified directory.

## Usage

```bash
findw -w "a word or a phrase to find" [-d ~/some/path]
```

```text
-w    used to specify the text to search for

-d    (pseudo-optional*) is used to specify the path of the directory which will be recursively searched.

      * you can specify the default directory path in the code itself, at the definition of the `dir_to_search` var, which would be overwritten if you were to provide the `-d` flag. This is useful if you are usually searching only in some one directory.
```

## Preview

(preview is of the old version of the script)

![findw_preview](https://user-images.githubusercontent.com/34137807/169920561-fae69420-24fc-4738-84c7-22b051f094cf.png)
