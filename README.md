This is a branch created solely for using Github Pages to publish webpages using my code.

Here's the GH Page: https://kennethzhg.github.io/CS50-Assignment-HTML-CSS/

The reason why this is necessary is that somehow GH Pages has a slightly different syntax for filepaths and file names, resulting in my images not being rendered if I were to use the original codes that I developed using Visual Studio Code, which worked just fine why I tested on localhost.

The changes I made to the original codes are (1) taking away the first forward slash when I am using the src and href attributes, and (2) ensuring file names do not contain underscore.

(1) Taking away forward slash:
- Original code: img src="/images/Logo.png"
- Code edited to make GH Pages work: img src="images/Logo.png" (notice the first forward slash is removed)

(2) Ensuring flie names do not contain underscore 
- Original file name: zhou_riding-a-dragon.jpg
- Code edited to make GH Pages work: zhou-riding-a-dragon.jpg (notice the underscore is replaced by hyphen)
