---
layout: post
title:  "Confessions"
date:   2024-08-21 16:39:00 -0700
categories: update
---

## A confession

I have a confession to make. I haven't done my homework. I'm 3 weeks into **fast.ai**'s [excellent course](https://course.fast.ai) on deep learning, and I haven't done any of the exercises! I've watched the videos -- read the book but when it's come to shooting my ML shot, well, the shoot hasn't been shot at all.  

So let's shame me into it.  

This post will deal with the material covered in [Lesson 2](https://course.fast.ai/Lessons/lesson2.html) of the **fast.ai** online course. This -- perhaps not coincidentally -- coincides with Chapter 2 of [the book](https://a.co/d/0vP8mU3).  

This lesson covers the fundamentals of data curation and how the process weaves itself into the process of deep learning. It also deals with the process of deploying a simple deep learning application to free online services, which is done using [huggingface.co](https://huggingface.co). Their documentation is comprehensive, and I found the process to be simple and intuitive. As such, I've decided to skip out on that portion here and focus on the process of **gathering, loading, and refining data.**

## Bootstrapping

You may have noticed that this post is skipping over [Lesson 1](https://course.fast.ai/Lessons/lesson1.html) entirely. The practical material from **Lesson 1** is mostly covered again in **Lesson 2**, with the exception of how to use **Jupyter Lab**. **Fast.ai** recommends using an online notebook provider such as [Kaggle](https://www.kaggle.com/), but I've found the operating environment doesn't map particularly well to the shortcuts and tips given in the course. In lieu of this, I've gone ahead and installed **Jupyter Lab** on my local **MacOS** environment. This wasn't a particularly difficult thing to do and involved (in no particular order):

* Install [Homebrew](https://brew.sh)
* Install **xcode-select** tools. `xcode-select --install`
* Install **pyenv** `brew install pyenv` (and add the necessary lines to your `~/.zprofile` file)
* Install the latest stable version of **Python 3**. `pyenv install [version]`
* Install **Jupyter Lab** `pip install jupyterlab`
* Finally, run **Jupyter Lab** `jupyter lab`

At this point, you should have a tab in your favorite browser open to [http://localhost:8888/lab](http://localhost:8888/lab). You may need to install additional packages in python using `pip`, which can be performed as needed.

With that, we're ready to go!
