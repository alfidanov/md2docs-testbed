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


## Very Long Code Block

    What is Lorem Ipsum?
    Lorem Ipsum is 
    simply dummy text 
    of the printing and 
    typesetting industry. 
    Lorem Ipsum has been the industry's 
    standard dummy text ever since the 1500s, 
    when an unknown printer 
    took a galley of type and scrambled 
    it to make a type specimen book. 
    It has survived not only five centuries, 
    but also the leap into electronic 
    typesetting, remaining essentially unchanged. 
    It was popularised in the 1960s 
    with the release of Letraset sheets 
    containing Lorem Ipsum passages, 
    and more recently with desktop publishing 
    software like Aldus PageMaker 
    including versions of 
    Lorem Ipsum.
    Why do we use it?
    It is a long established fact that a 
    reader will be distracted by the readable content 
    of a page when looking at its layout. The point of using 
    Lorem Ipsum is that it has a more-or-less normal distribution 
    of letters, as opposed to using 'Content here, content here', making it look 
    like readable English. Many desktop publishing packages and web page editors 
    now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' 
    will uncover many web sites still in their infancy. Various 
    versions have evolved 
    over the years, sometimes by accident, sometimes on purpose 
    (injected humour and the like).
    Where does it come from?
    Contrary to popular belief, Lorem Ipsum is not simply random text. 
    It has roots in a piece of classical Latin literature from 45 BC, making 
    it over 2000 years old. Richard McClintock, a Latin professor at 
    Hampden-Sydney College in Virginia, looked up one of the more obscure 
    Latin words, consectetur, from a Lorem Ipsum passage, and going through 
    the cites of the word in classical literature, discovered the 
    undoubtable source. Lorem Ipsum comes from sections 
    1.10.32 and 1.10.33 of "de 
    Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, 
    written in 45 BC. This book is a treatise on the theory of ethics, 
    very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem 
    ipsum dolor sit amet..", comes from a line in section 1.10.32.
    The standard chunk of Lorem Ipsum used since the 1500s is reproduced 
    below for those interested. Sections 1.10.32 and 1.10.33 from "de 
    Finibus Bonorum et Malorum" by Cicero are also reproduced in their 
    exact original form, accompanied by English versions from the 1914 
    translation by H. Rackham.
    Where can I get some?
    There are many variations of passages of Lorem Ipsum available, 
    but the majority have suffered alteration in some form, by injected 
    humour, or randomised words which don't look even slightly believable. 
    If you are going to use a passage of Lorem Ipsum, you need to be sure there 
    isn't anything embarrassing hidden in the middle of text. All the 
    Lorem Ipsum generators on the Internet tend to repeat predefined 
    chunks as necessary, making this the first true generator on the 
    Internet. It uses a dictionary of over 200 Latin words, combined 
    with a handful of model sentence structures, to generate Lorem 
    Ipsum which looks reasonable. The generated Lorem Ipsum is therefore 
    always free 
    from repetition, injected humour, or non-characteristic words etc.

## Other examples of code block