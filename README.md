
![fau-book](https://user-images.githubusercontent.com/44805883/168074199-828888ec-748f-4676-85d6-81e94a38a615.png)


:green_book: fau-book
================
A LaTex template for theses and lecture notes connected to te Friedrich--Alexander-Universität Erlangen--Nürnberg.

<a name="What"></a>
# :toolbox: What does ```fau-book``` do?
The provided class and style files set up a convinient environment that 
allows students to create a good looking thesis. Additionally it can be employed to typeset lecture notes.

<a name="How"></a>
# :gear: How can I use ```fau-book```?

## :octocat: Getting the template to your machine and GitHub workflow

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

<img src="https://user-images.githubusercontent.com/44805883/168069022-0ded3cd5-00cc-486c-917c-3f1d49a0baf9.png" align="right" width="400px"/>

Then you would download [fau-logo-quer](https://www.doc.zuv.fau.de//M/FAU-Logo/05_FAU_NatFak/Print/Quer/CMYK/FAU_NatFak_Q_CMYK_blue.pdf) put in your folder and specify the path, when you load the class in the preamble:

```
\documentclass[WordMark=<path-to-file>,
	       ExtraLogo=<path-to-file>,
	      ]{fau-book}
```

This puts the FAU logo on the left side. The option ```ExtraLogo``` dfines the logo of the department on the right. The PDF version of this file is unfortunately not available online, write an email to the author if you need it. Alternatively you can use the lower resolution [.jpg version](https://en.www.math.fau.de/wp-content/uploads/sites/3/2018/07/cropped-FAU_DMM_Logo_rgb_10cm-3.jpg).
<br clear="right"/>


# :beer: Credit

The ```fau-book``` class and the template was created by [Tim Roith](https://timroith.github.io/).

# :city_sunset: Projects that employ ```fau-book```

Here are some of the projects that employ the ```fau-book``` class. Feel free to suggest additions to this list.

* [MathPhysicsC](https://github.com/FAU-AMMN/MathPhysicsC)
* [Math for Data Scientists](https://github.com/FAU-AMMN/MathDataScience)
* [Math for Data Scientists 2](https://github.com/FAU-AMMN/MathDataScience2)
* [Diskretisierung und numerische Optimierung](https://github.com/FAU-AMMN/DnO)
* Master Thesis of [Tim Roith](https://timroith.github.io/)

# License
License is MIT, see the license file.
