# TV Script Generator
This is the third project of the Udacity Deep Learning Nanodegree Program.  

## Problem statement
We want to build a **R**ecurrent **N**eural **N**etwork that can generate new, "fake" TV scripts.  

## Solution
We use parts of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from season 9. After some data pre-processing, a **Long** **S**hort-**T**erm **M**emory network with two layers is instantiated and trained. The modelling is mainly performed with the PyTorch library.

An example of a generated TV script:
>jerry: what about me?
>
>jerry: i don't have to wait.
>
>kramer:(to the sales table)
>
>elaine:(to jerry) hey, look at this, i'm a good doctor.
>
>newman:(to elaine) you think i have no idea of this...
>
>elaine: oh, you better take the phone, and he was a little nervous.
>
>kramer:(to the phone) hey, hey, jerry, i don't want to be a little bit.(to kramer and jerry) you can't.
>
>jerry: oh, yeah. i don't even know, i know.
>
>jerry:(to the phone) oh, i know.
>
>kramer:(laughing) you know...(to jerry) you don't know. 