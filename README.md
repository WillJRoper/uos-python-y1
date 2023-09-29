# Introduction to Python

<p align="center">
  <img src="images/pythonxkcd.png">
</p>

The `Python` programming language is ubiquitous in science, especially in Physics. It is an extremely powerful tool that can be utilised for everything from making simple games to simulating the evolution of the Universe. In fact, "Big Tech" companies such as Google and Facebook use `Python` behind the scenes of many services you use daily. 

Whether or not you have programmed before this module will give you the tools you need to perform research, complete assignments, and most importantly will give you marketable skills that can help you get a job after your degree. If you're anything like the authors of this document it will also have the unintended consequence of giving you an **unhealthy coding addiction**, which will be impossible to kick.

## Module Structure

This module is run in tandem with Physics In Practice (PIP) but don't be fooled, it is just as important as many of the full-fat modules you'll do in your degree. As such, it is structured in much the same way as your other modules with teaching, assignments, and exercises within the lab book. The main difference is in **how** the material is taught; rather than traditional lectures you'll take part in lab sessions and work through notebooks focused on various Python features and uses. These lab sessions, starting with a very short introductory talk, will give you direct contact with the AT and the lecturers to help you with any problems.

I'd like to draw your attention to the discussions tab on Canvas, here you can post questions and one of us will get back to you as soon as we can or we can plan a full explanation for one of the workshops. This is a valuable way of getting quick feedback outside of the lab sessions, especially if you manage to highlight a shortcoming in the course content which we can fix!

In assessment weeks (weeks 4, 7, and 10) you will have the opportunity to work on assignments in the labs and ask for what help we can provide with the assessments. We **can not** do them for you or tell you the answer but we can help you if you have any misunderstandings leading to your troubles. In these assessment weeks, we do not expect you to work on the course content but you are free to if you complete the assignments. The assignments will be released **at least** 10 days prior to the assessment deadline to give you plenty of time to complete them.

The first (week 4) assignment is formative and will be peer-marked.
We will give you further details on this marking in the introduction sessions.
The second two assignments will be tutor-marked and contribute equally to the
portfolio mark, worth 30% of the PIP module mark.

We will repeat this again and again: do not take the low weighting of this sub-module as a reflection of its importance, `Python` is an essential skill. Failure to engage now **will** lead to troubles down the road when the weightings are far higher and contributory. We have seen it before and, sadly, will undoubtedly see it again when a student hits a `Python` related problem in a later module which was discussed during this module. 

## "Lab book"
You will find the entirety of this course housed in this repo (or uploaded to Canvas where any updates to the content will be uploaded when necessary). Each Notebook is numbered, unsurprisingly you should do these in order starting at 1 and continuing from there. 1_getting_setup.py is included as both a notebook and a pdf. **First open the pdf version or Notebooks/1_getting_setup.ipynb on GitHub. This notebook will tell you how to open notebooks for yourself!**.

You can take this module at your own pace, at the end there are bonus advanced concepts for those who progress fast and have an interest in going beyond the scope of the course. However, you should aim to keep to the general signposts within the worksheets. The earlier weeks will have multiple worksheets to do per session that cover the basics but as we delve into more complex features this will drop to a single notebook per session. 

Not everyone enjoys coding as much as we do, **so do not worry if you find yourself struggling a little**, please make sure to ask the lecturers or AT for help if you need it. Programming can be daunting for the uninitiated and it can take time to start thinking like a programmer, but when you do your increased understanding of logic will help you throughout your whole degree/life.

Each notebook will begin with a list of learning outcomes for that section followed by the content containing some worked examples. At the end of each section, there will be some exercises for you to complete to check your understanding of the chapter (remember to ask the ATs for help if you're stuck, they will **likely** have made all the same mistakes).

### Getting your own copy of the Notebooks

To get your copy of the notebooks to work on and edit as much as you like:
- Open a terminal. (On Mac this is called Terminal. On Windows the default is Powershell).
- Navigate to the location you would like to have the Python directory (repo) with the `cd` command (change directory). On my machine, I would store this in `Documents/University/` so I'd enter: `cd Documents/University` but feel free to put this anywhere as long as you know where it is.
- Now you can make a directory to hold your Python work. I'd call this `PIP-Python` so would run `mkdir PIP-Python` to make a new directory inside the `University` folder I moved to above. I'd then `cd PIP-Python` to get into that directory
- Once you are where you want to store your Python work all you have to do is "clone" the repository to get all its contents locally. To do this run `git clone https://github.com/WillJRoper/uos-python-y1.git` to copy the repo to your machine.
- You will now have a new directory called `uos-python-y1` inside this directory. Check by running `dir` on Windows or `ls` on Linux or Mac.

You should now be able to see all the files that make up this course on your own computer. This is your copy so you can edit freely. One thing I would say is I recommend not adding files inside `uos-python-y1` instead add them to the outside directory. This will make life easier down the line. 

Of course, I suspect all of the above is a very new concept to many, if not all, of you! Don't worry if you couldn't do the above. A copy of this repo is available on Canvas with up-to-date documents. I will go into detail about Git in due course.

## Assignments
The three assignments (the first of which is unweighted and peer-marked) will be marked on:

- The final answers you have.
- Coding style (including comments!!! More on this later!
- How logical and efficient your approach is.

The assignments will be uploaded to Canvas and should be submitted by the deadlines in weeks 4, 7 and 10. These assignments, like all others, should be completed and submitted on your own, containing only your own work.

## Python versions

This module uses `Python` 3, specifically I recommend >3.10 but >3.6 is sufficient. This is the newest version of `Python` (replacing `Python` 2) and the version that's installed on the University system. You may come across instances of `Python-2` throughout your degree (and beyond) since it is still used but official support has now ended (and thus its use should also have ended... but there are holdouts). There is little difference between the two versions on the surface, so don't worry about this too much. The main differences are the syntax of the \texttt{print} function and how the code behaves when dividing one integer by another.
