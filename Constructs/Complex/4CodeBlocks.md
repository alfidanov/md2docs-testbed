---
title: Markdown Code Blocks
---

# Markdwn Code Block Use Cases

## Code Phrase

At the command prompt, type `nano`.

``Use `code` in your Markdown file.``

## Code Blocks

Code block indented with 4 spaces:

    <html>
      <head>
      </head>
    </html>

Fenced Code block with specified type (JSON)

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Code Blocks in List

 Code blocks in lists have to be indented with at least 8 spaces (4 tabs) and separated with a blank line from other content

1. Open the file.
1. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

1. Update the title to match the name of your website.

    ``` shell
      $ echo 'Prague,Jan,101,4875.33
      Rome,Mar,86,1557.39
      Bangalore,May,317,8936.99
      Beijin,Jul,411,11600.67' > /tmp/pxf_hdfs_simple.txt
    ```

    Note the use of comma `,` to separate the four data fields

## Blockquotes:

> This is an example of blockquote

> This is an example
>
> of blockquote
>
> on multiple lines

