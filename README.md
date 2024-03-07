# How to Host a Resume

## Purpose
Hosting a site can be daunting, especially for those who have never done it before. The steps below describe how I hosted [my resume](https://n-a-y-a.github.io/) on GitHub Pages, and how you can do the same. I also describe the general principles of current Technical Writing, as explained in Andrew Etter's book *Modern Technical Writing* and how to apply them.

## Prerequisites 
Before hosting your resume on GitHub Pages, you need to have a resume! 
The resume should be formatted in Markdown which, if you're unfamiliar, is a lightweight markup language. In fact, according to Etter, it is the most commonly used lightweight markup language in the world. 
If you have never used Markdown or need a refresher, please see the *More Resources* section for helpful links.

## Instructions
1) Create a GitHub Account
2) Create a Repository
3) Upload Your Resume
4) Rename Your Resume
5) Add a Configuration File
6) Troubleshoot

## More Resources
* If you are unfamiliar with Markdown and would like to learn, try [this tutorial](https://www.markdowntutorial.com/) or [this one by Davarshi Shimpi](https://dev.to/devarshishimpi/complete-markdown-tutorial-for-beginners-1e#:~:text=Complete%20Markdown%20Tutorial%20for%20Beginners%201%201.%20Structuring,Separating%20Sections%20with%20Horizontal%20Lines%20...%20More%20items).
* If you have already familiarized yourself with Markdown, but would like reminders for how to implement some of the key formatting features, this [Cheat Sheet by Adam Pritchard](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is great.
* If you would like to see what your Markdown-formatted resume looks like before hosting it on GitHub Pages and without downloading any software, [Dillinger](https://dillinger.io/) is a great resource. You can type Markdown in your web browser and see what the formatting will look like in real time. 
* If you are interested in learning more about the principles of current Technical Writing, an e-copy of Andrew Etter's book *Modern Technical Writing* can be purchased on [Amazon](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) and is free to read if you have Kindle Unlimited.
* If you are interested in learning even more about technical writing, this [Blog by Tom Johnson](https://idratherbewriting.com/) and the [Write-The-Docs website](https://www.writethedocs.org/) are good resources.
* If you are interested in looking at the code for the theme I used for my resume, please see the [Slate Theme Repository](https://github.com/pages-themes/slate?tab=readme-ov-file).


## Authors and Acknowledgements
For my resume, I used the [Slate theme](https://github.com/pages-themes/slate?tab=readme-ov-file). It's a pretty cool theme and you can find the documentation and a list of contributors in the repository.

Many of the concepts discussed and implemented in this project come from Andrew Etter's book *Modern Technical Writing*, and a link to purchase the e-book is included in the *More Resources* section if you are interested in learning more. 

I would also like to say thank you to my group members (whose names will not be mentioned for privacy reasons) for their efforts to peer review this project.


## FAQs

### Why is my resume not showing up?
If you navigate to username.github.io (where username is replaced with your GitHub username) and it shows a 404 error, that means it can't find the file you're trying to display. First, check the name of your repository. It must be called sername.github.io and it can be changed in settings. Second, check what the file that holds your resume is called. It should be called index.rm and you cna change the name by clicking the file and then clicking the pencil icon in the top right hand corner. Lastly, check the branch name. Otherwise, Google is your friend.

### I like using my word processor. Why should I use Markdown instead?
Word processors are decent for making small PDFs. You might even find some kinds of formatting easier to do with a word processor rather than Markdown, but that's partially because you're accustomed to that software. As you become more familiar with Mardown, syntax and formatting will be easier. Additionally, if you make a file with Mardown, you can turn it into a website easily, which is not the case for files made using a word processor. These websites can be more user-friendly than sending out a PDF and are more condusive to version control, which is useful when a file needs to be changed several times or by several people.
