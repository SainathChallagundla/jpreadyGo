<img src="https://github.com/JitenPalaparthi/readyGo/blob/master/assets/readyGoBlue.png" width=400>
# Overview

*The phylosophy behind readyGo is "A Simple configuration should give a working project.".*

- **readyGo** is a command line interface( probably the name of readyGo CLI would be readyGo itself) application, it is designed to scaffold creation of different types of go based projects.readyGo is designed for developers in mind. Ideally **readyGo** should provide ready to use application code. The code is generated based on configurations provided by the end user i.e "The great developer :)".

- By version 1 release, it will support **http**(as of v0.0.3 supported), **grpc**, **CloudEvents** template engines with various databases **(sql/nosql)**, **pub-sub** and **CloudEvents plugins** and probably even more.

- The present version of **readyGo** is **v0.0.3**. It supports **http+mongodb and http+sql** (Postgres but with simple tweaks ca make it work for others like MySQL, CockroachDb etc..)

- There are two types of users for **readyGo**

    1. Developers: Minds who develop plugins in the form of templates for **readyGo**.

    2. Developers: Minds who develop applications using readyGo.

- Interestingly both the users are developers and so **readyGo** is developer's companion.

- What **readyGo** gives you is based on your applied configuration(a separate section for [configurations](https://github.com/JitenPalaparthi/readyGo/wiki/Configurations)) it outputs a working project. Working project means you can directly use the project as it is. 


 *readGo cooks for you.As your business logic varies , you have to add the required spices according your taste but one thing . **readyGo** is not a template engine, it gives you a working project.*

 ### [know more about readyGo --> Wiki](https://github.com/JitenPalaparthi/readyGo/wiki)