# Application Web Design

|                                             |                                                |
| ------------------------------------------- | ---------------------------------------------- |
| Name: Zurisaday Espadas Martínez            | Registration number: 2992362                   |
| Degree: Software Engineering                | Semester: Sixth semester                       |
| Name of the subject: Web Application Design | Name of the teacher: José Ricardo Zapata Solis |
|                                             |                                                |

## What Markdown is used for

Markdown is widely used for writing README files, documentation pages, blog posts, and other online content. We can use Markdown to create headings, lists, tables, links, images, code blocks, and more, using simple characters like asterisks, dashes, and brackets.

## Syntaxt

### Headings

| Markdown       |
| -------------- |
| # Level 1      |
| ## Level 2     |
| ### Level 3    |
| #### Level 4   |
| ##### Level 5  |
| ###### Level 6 |

### Paragraphs

| Markdown |
| -------- |
| Example  |

### Line Breaks

To create a line break or new line (<br>), end a line with two or more spaces, and then type return.

| Markdown                                                    |
| ----------------------------------------------------------- |
| This is the first line. `<br>` And this is the second line. |

### Emphasis (Bold and Italic)

You can add emphasis by making text bold or italic.

**Bold**
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

| Markdown                      |
| ----------------------------- |
| I just love `**bold text**`.  |
| I just love `__bold text__` . |

**Italic**
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

| Markdown                               |
| -------------------------------------- |
| Italicized text is the `*cat's meow*`. |
| Italicized text is the `_cat's meow_`. |

### Blockquotes

To create a blockquote, add a > in front of a paragraph.

| Markdown                                                                    |
| --------------------------------------------------------------------------- |
| `>` Dorothy followed her through many of the beautiful rooms in her castle. |

### Code

To denote a word or phrase as code, enclose it in backticks (` ).
|  Markdown  |
|------------------|
| At the command prompt, type  ```  `nano` ```. |

### Lists (Ordered and Unordered)

**Ordered**
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```markdown
1. First item
2. Second item
3. Third item
4. Fourth item.
```

**Unordered**
To create an unordered list, add dashes (-), asterisks (\*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

```markdown
- First item
- Second item
- Third item
- Fourth item
```

```markdown
- First item
- Second item
- Third item
- Fourth item
```

```markdown
- First item
- Second item
- Third item
- Fourth item
```

### Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses.

```markdown
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg 'San Juan Mountains')
```

## Git Commands

### Check the status of a local repository

`git status`

### Add individual files or globally

**To add individual files**
`git add filename`

**To add all changes globally**
`git add .`

### Add comments to the commit

`git commit -m "Here!"`

### Upload your changes to the remote repository

`git push`

### Create, browse, and delete branches

**Create**
`git branch branch_name`

**Browse**
`git branch`

**Delete**
`git branch -d branch_name`

### Roll back a repository to a specific commit

**To revert to a specific commit**
`git reset --hard commit_hash`

**To keep the changes as uncommitted modifications**
`git reset --soft commit_hash`
