# 1. **Sass**

- [1. **Sass**](#1-sass)
  - [1.1. What You Should Already Know](#11-what-you-should-already-know)
  - [1.2. So what's Sass?](#12-so-whats-sass)
  - [1.3. Why Use Sass?](#13-why-use-sass)
  - [1.4. How Does Sass Work?](#14-how-does-sass-work)
  - [1.5. Sass File Type](#15-sass-file-type)
  - [1.6. Sass Comments](#16-sass-comments)
  - [1.7. Sass Example](#17-sass-example)
  - [1.8. Sass Installation](#18-sass-installation)
    - [1.8.1. System Requirements for Sass](#181-system-requirements-for-sass)
    - [1.8.2. Install Sass](#182-install-sass)
  - [1.9. Official Sass Web Site](#19-official-sass-web-site)

<h2>Css With Superpowers.</h2>

## 1.1. What You Should Already Know

Before you continue you should have a basic understanding of the following:

.HTML

.CSS

Am try on my best to elaborate important concept concerning about sass with real examples through code.

## 1.2. So what's Sass?

>Sass stands for Syntactically Awesome Stylesheet
>Sass is an extension to CSS
>Sass is a CSS pre-processor
>Sass is completely compatible with all versions of CSS
>Sass reduces repetition of CSS and therefore saves time
>Sass was designed by Hampton Catlin and developed by >Natalie Weizenbaum in 2006
>Sass is free to download and use

<p> Sass reduces repetition of CSS and therefore saves time.
</p>

## 1.3. Why Use Sass?

Stylesheets are getting larger, more complex, and harder to maintain. This is where a CSS pre-processor can help.

Sass lets you use *features* that do not exist in CSS, like variables, nested rules, mixins, imports, inheritance, built-in functions, and other stuff.

## 1.4. How Does Sass Work?

A browser does not understand Sass code. Therefore, you will need a Sass pre-processor to convert Sass code into standard CSS.

This process is called transpiling. So, you need to give a transpiler (some kind of program) some Sass code and then get some CSS code back.

>***Tips***: Transpiling is a term for taking a source code written in one language and transform/translate it into another language.

## 1.5. Sass File Type

Sass files has the "```.scss```" file extension.

## 1.6. Sass Comments

Sass supports standard CSS comments ``` /*comment*/ ```, and in addition it supports inline comments ```// comment```:

## 1.7. Sass Example

```sass
/* define primary colors */
$your-color_1: #a2b9bc;
$your-color_2: #b2ad7f;

/* use the variables */
.main-header {
  background-color: your-color_1; // here you can put an inline comment
  color: your-color_2;
}
 ```

## 1.8. Sass Installation

### 1.8.1. System Requirements for Sass

.Operating system - Sass is platform independent

.Browser support - Sass works in Edge/IE (from IE 8), Firefox, Chrome, Safari, Opera

. Programming language - Sass is based on Ruby

### 1.8.2. Install Sass

There are several ways to install Sass in your system. There are many applications that will get you up and running with Sass in a few minutes for Mac, Windows, and Linux. Some of these are free, but some are paid apps.

> You can read more about them here: sass-lang.com/install

## 1.9. Official Sass Web Site

Read more about Sass at the official Sass web site: <https://sass-lang.com/>
