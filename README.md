# Chapter 0 
## Introduction
This small project consists on picking the codes presented in the book *C++ Design Patterns and Derivatives Pricing* and coding them again in Python. Also the exercises at the end of each chapter are solved using Python. 

Chapters from 1 to 10 cover part of the original book. Then chapters 11 and 12 show material that the original book does not have. 

Chapter 11 shows how to make the code more efficient, making it "Pythonic". Chapter 12 shows how to use No-SQL databases as well as other mechanisms to store the options objects.

## Motivation

My interest in quantitative finance started after watching the TV-Documentary *Quants - The Alchemists of Wall Street*. After watching that documentary in my first year of college I started to learn more and more about quantitative finance.

At that time I was studying my bachelors in Aerospace Engineering. After realizing that finance was my passion I convinced one of the teachers of my university to start a double degree program consisting in Engineering with Economics. I was the first student to enroll on that program.

Much of the information about trading on the internet is absolutely irrelevant, just to say something, so to learn more about it I had to investigate a lot. 

After an unsuccesful recruitment process with a quantitative fund I realized that I needed to improve my coding skills (I pass the firsts rounds but then the coding project was quite a mess...). However the Head of Trading of that firm sent me links to books he considered good. One of them was the famous Hull.

I bought a second hand edition for 2€ on amazon. I read it several times until I firmly understood the concepts. After that I already understood the basics as well as how to price many derivatives, nevertheless I had no clue about how to implement it in real-life.

That is when I discovered this book: *C++ Design Patterns and Derivatives Pricing* from Mark Joshi. It described advanced and interesting concepts about how to implement derivative pricing in big production systems. Knowing the Black-Scholes hypothesis is one thing, being able to create a factory storing multiple pay-offs as well as having huge re-usability of the code is another totally different.

I had a background in C++ since I learnt to code with this programming language, however this book went far beyond the basic knowledge I had so it was a bit difficult to understand it totally the first time.

The second time I read it I thought it would be great to solve the exercises. Doing it in C++ was the most logical option, but since I wanted to improve my Python skills as well as use the Jupyter Notebook I picked Python. Being able to use notebooks makes the task of coding it easier and also allows to introduce text. In my opinion doing it with this tool was making the code format as close as the book by being able to combine code with text and outputs.

Although I started writting the code for myself I thought that it would be nice to share it. Many Quantitative Finance students might face the problem of having to implement their models in a more realistic and efficient manner than just using functions. I hope that this project might give them an idea about how to do that task.

This was a fun project to combine two of my hobbies: coding and quantitative finance. I have enrolled into a quantitative finance master program so I hope to continue publishing new projects.

## Disclaimer

I have not written any of the exercises. They come from the book authored by Mark Joshi.

The code may contain errors. I still work on it changing things and improving explanations.

The code is not suited and/or recommended for using it in production, it is only a free time project.

The code is mostly inefficient until Chapter 11 since using loops in Python is not the fastest way to calculate something. A faster way to do it is presented in Chapter 11.


## Review of the Book
The book is great to grasp the concepts and have an overall idea about how to implement a really big trading system. 

The book does not go into details on how to forecast volatility or know which assets are going to go up or down. If you are looking for this I do not recommend this book (in fact in regards predicting future values I can not recommend anything, at most books on quantitative portfolio management).

This books requires a good knowledge in C++ if you do not have it you can check my notebooks which cover the same but with python, making it more understandable. If you have a good C++ level (objects, templates, pointers...) then check the original book.

In my opinion the book covers very interesting concepts which are very overlooked in quantitative finance (how to build very robust code). However it does not present a totally complete system, just pieces and ideas about it. It would have been great if it included schemes or diagrams about the structure of the system.

Sometimes the explanations can be a bit cryptic and following everything might be difficult. The first chapters are super straight forward but then it gets complicated fast. It reminds me to the owl meme.

![Owl meme](owl.jpg)

In conclusion, this book shows very interesting concepts about development applied to trading systems, focusing on the Object Oriented Paradigm. However it is difficult if you are not an experienced developer. Another possible critic to this book is the fact that it shows a very small part of the system applied a kind of trivial example but covering something really complete would have required an immense manual not a book...

## More Information about the Book

You can buy the book here: https://www.amazon.com/Patterns-Derivatives-Pricing-Mathematics-Finance/dp/0521721628 .

There are other published books from Mark Joshi:
- The Concepts and Practice of Mathematical Finance
- Introduction to Mathematical Portfolio Theory
- More Mathematical Finance
- Quant Job Interview Questions and Answers

Unfortunately Mark Joshi will not publish more books. 




