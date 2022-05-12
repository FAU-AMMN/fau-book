![fau-book](https://user-images.githubusercontent.com/44805883/168063836-31c37534-f796-4722-be0a-93f2f132e482.png)



:green_book: fau-book
================
A LaTex template for theses and lecture notes connected to te Friedrich--Alexander-Universität Erlangen--Nürnberg.

# 	:toolbox: What does ```fau-book``` do?
The provided class and style files set up a convinient environment that 
allows students to create a good looking thesis. Additionally it can be employed to typeset lecture notes.

# :gear: How can I use ```fau-book```?

## 	:octocat: Getting the template to your machine and GitHub workflow

:one: If you are not familiar with GitHub or version control systems in general you 
can just click the "Clone or download" button which will create a local copy 
of the files you see here. After this you are good to go and can start working.

:two: The easiest way to directly obtain an independent repository of your own, 
is to click on "Use this template". This is a great feature of GitHub 
that will set up a repository for you including all the files you see here. 

:three: Or you can of course just fork the repository.

## :briefcase: Working with fau-math-thesis

:spiral_notepad: The example file provided within this repo gives a short overview of the functionality. 

:calendar: There may appear an additional guide soon.

:paperclip: If you have questions about specific features or found an error you can either write an email to the author (see below) or raise an issue here.

## :framed_picture: Logo files

The logo files for the title page are **not** provided in this repo, since we do not have the rights to distribute them. In order to download the logo files please visit the website of [FAU corporate](https://www.intern.fau.de/kommunikation-marketing-und-corporate-identity/corporate-identity/fau-logo/#collapse_58) and download the neccessary files there. This is only possible if you are connected to the university network.

### Example

Let's say you are writing your thesis at the mathematics department and want to create the following title page.

<img src="https://user-images.githubusercontent.com/44805883/168069022-0ded3cd5-00cc-486c-917c-3f1d49a0baf9.png" align="right" width="500px"/>
Then you would download [fau-logo-quer](https://www.doc.zuv.fau.de//M/FAU-Logo/05_FAU_NatFak/Print/Quer/CMYK/FAU_NatFak_Q_CMYK_blue.pdf) put in your folder and specify the path, when you load the class in the preamble:

```
\documentclass[WordMark=<path-to-file>,
	       ExtraLogo=<path-to-file>,
	      ]{fau-book}
```

The option ```ExtraLogo```

<br clear="right"/>


# :beer: Credit

The ```fau-book``` class and the template was created by [Tim Roith](https://timroith.github.io/).

# License
License is MIT. We are aware of more specific solutions for LaTeX documents, 
but not o their benefits. If you have experience with this topic, 
feel free to suggest a better solution.
# ToDo
This section is currently not maintained.
