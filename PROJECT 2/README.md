# GIT PROJECT

## Initializing git repository

I initialized the git repository by launching term, created a new directory called "devops". I then proceeded to change directory to the new one i just created before initializing git, as seen below.

![alt text](<Images/Screenshot from 2024-02-08 17-10-23.png>)

## Making my first commit

I created a file called index.txt in the new devops directory. Then I tried to add to add text to index.txt using echo. I continued encountering 'permission denied'  errors and 'cannot overwrite existing file' errors. I tried using the sudo and the chmod command but it didn't work. Eventually, I assigned root permission (sudo) to both echo and tee command and that did the trick, as seen below.

![alt text](<Images/Screenshot from 2024-02-08 17-48-14.png>)
![alt text](<Images/Screenshot from 2024-02-08 18-15-02.png>)

I encontered another error while trying to do my git commit. An author indentity error which I resolved by setting a default identity for my account by ommiting "--" while configuring the "user.name" and "user.email".

![alt text](<Images/Screenshot from 2024-02-08 21-26-34.png>)

## Working with branches

### My first git branch

I created a new branch as seen below.

![alt text](<Images/Screenshot from 2024-02-08 21-33-52.png>)

### Listed out git branches

I listed out all the git branches I currently have.

![alt text](<Images/Screenshot from 2024-02-08 21-34-34.png>)

### Branch Changing

I switched from new branch I created back to my initial branch as seen below.

![alt text](<Images/Screenshot from 2024-02-09 02-20-52.png>)

### Branch Merging

I merged master branch and new branch together.

![alt text](<Images/Screenshot from 2024-02-09 02-24-03.png>)

### Branch Deleting

I deleted the new branch

![alt text](<Images/Screenshot from 2024-02-09 02-27-09.png>)

## Pushing local repository to remote repository

Fist step of pushing the local repo is as seen below.

![alt text](<Images/Screenshot from 2024-02-09 02-36-33.png>)

The next thing was to push

![alt text](<Images/Screenshot from 2024-02-09 02-41-07.png>)

## Cloning git repository

I encountered some errors while trying to clone but I rectified the issues.

![alt text](<Images/Screenshot from 2024-02-09 02-50-44.png>)

## Branch Management and tagging

### Headings

The hash symbol is used to create headings.

# Heading 1
## Heading 2
### Heading 3

### Emphasis

asterics or underscore are used to emphasise texts

*italic* or _italic_
**bold** or __bold__

### Unordered and Ordered lists

Unordered lists

- Item 1
- Item 2
- Item 3

Ordered lists

1. First item
2. Second item
3. Third item

### Links

Square brackets are used for link texts and parenthesis for the links.

[visit darey.io](https://www.darey.io)

### images 

Exlamation mark, followed by square brackets and then parenthesis are used to display images.

![Alt Text](https://example.com/image.jpg)

### code

Backticks are used to display codes, just enclose the code in them.

`console.log('Welcome to darey.io')`