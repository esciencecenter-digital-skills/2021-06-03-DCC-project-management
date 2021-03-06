# Project management

In this video we will introduce some good habits in organization and
documentation of a research project. Organizing and documenting your project
well is not technically difficult to do, especially if you do it from the
beginning. But organization and documentation can make an enormous difference in
making your project easier to work on: for yourself, reducing the chances that
you will make mistakes along the way, and for those who want to understand and
perhaps reuse your project.

## 1. Save your project in a single folder.

Start with your project in a single folder. Everything that relates to your
project will be inside this folder. This will make your project portable and
cohesive; it will make it easy for someone else to make sense of it. This is a
habit that applies with projects anywhere, but particularly in research projects
it contributes to their reproducibility, which is of course a vital component of
good science. The term 'research compendium' has been coined to refer to a
container for different elements that make up the research presentation: the
paper or report itself, but also the data and the code that is used to analyse
the data and generate the results.

## 2. Devise a logical system of sub-folders.

Make a logical system of sub folders, looking at what is standard in the
field. There is no one-size-fits-all, but this can be a good structure for a
research project. Having folders separate for data for documentation and for
figures. Make sure you structure your sub folders in a logical way. Don’t be
afraid to make sub sub and sub sub sub folders, so long as it is logical.
Especially when you were working with code or tools that generate content
automatically, it is important to separate the content that is generated
automatically from content that you yourself are writing. It is also important
to separate read-only content from the rest. Raw data should never be meddled
with!

The base of your folder system, the main folder at the highest level of your
project, is called the “root”. This is an important reference point of your
project: it contains the main files that are required to understand the project,
as well as the main sub folders.

## 3. Introduce the project (or sub-folder) in a README.

Especially on higher levels, it’s recommended that each folder contains a
description, or a README file, that describes the content of that folder. There
are certain things you can put in that README file. A good thing to start with
is always to ask yourself: what if, in one year time, you see this folder again,
what information do you need to understand it fully? With almost everything we
are going to show you, you yourself are the most likely the one to benefit from
a good project structure, and good documentation. Keep this in mind.

Other content you can put in a README, aside from a general overview of the
project, is: an explanation of any abbreviations used, the expected files and
folders in your project and their purpose, names of contributors and their
roles, and any links or references to important sources.

## 4. Use interoperable file types.

Using Excel may be great for you now, with all its bells and whistles, but what
if you leave your position and are no longer able to pay for the software. Can
you still access your own data? What if someone who wants to reuse your project
does not have access to Excel? And what happens to the file in 10 years? Would you
feel confident that you can access and successfully read an Excel file from 10
years ago?

Instead, we recommend that you save data in a format that will work with Excel,
but is not dependent on the software to be read. This format, .csv, takes the
form of a table where items in different columns are separated by commas (or
other characters). The data is stored in plain text, which allows it to be read
by many different types of software, including a plain text editor. And,
importantly, a .csv file will likely outlive you.

For almost any proprietary file type there is an interoperable alternative.
Instead of a word document, save your text as a txt file, or perhaps formatted
using Markdown. Information is ideally stored as plain text, but an
interoperable file format can be different. The important thing is that it can
be used by diverse platforms and applications, and does not require paid
software to be accessible.

## 5. Use descriptive and logical file names.

File names themselves can be important documentation. We are long past the time
that file names need to be short, although there is obviously a limit. A file
name first of all is a description of the file that is tightly connected to that
file. Filenames can be used to find the right data quickly amidst a jumble of
files, or they can be used to identify the content of a stray file.

Naming a file right is therefore important. There are three main considerations
to make. File names should first of all be machine readable. This means using a
latin alphabet, with consistent capitalization, and no spaces or strange
characters. When a filename contains important information about the content of
that file, it can be used to quickly retrieve that file inside your system. A
filename does not need to be short, but words should never be separated by
spaces. Instead use underscores (snake case), hyphens (kebab case), or
consistent capitalization (camel case) to separate elements. Using hyphens or
underscores has the added advantage that it is easy to separate elements
automatically based on the patterns found in a name.

Most importantly though, file names should be intelligible for humans. That
means that they should contain information that identifies the content of that
file for you, or ideally another person. Jenny Bryan, who gave an excellent
lecture about this, gave this example to drive that point home: what filenames
would you rather see at 3AM before a deadline?

Finally, file names will be important when you want to sort your files.
Therefore, make sure that file names start with the most general descriptor of
the file content. For example, when you are including a date in your file (and
you probably should) start with the year, then the month, and then the day. This
will make sure that when you are sorting your files, you will sort them
chronologically, and not all the October files with other October files, for
example. It also prevents any confusion with date notation in different parts of
the world.

## 6. Make your data tidy.

An important starting point for data analysis is to have clean data. But, data
can not only be clean, it can also be tidy. Tidy data is defined as follows:

* Each variable is a column and contains values
* Each observation is a row
* Each cell contains a single measurement

It may be logical to collect observations like this: on each individual plant,
you perform several measurements, and collect them in a single row. In this
example, however, you will see that data, namely the kind of features you were
measuring, are hiding as column names, and in every row, multiple observations
are recorded. That same data can be put in a tidy format. No data is lost,
though it looks different. The tidy format standardizes the structure of the
data, making it more straightforward to interpret and to run analyses on.

## To summarize our tips:

1. please save your project in a single folder
1. devise a logical system of sub-folders
1. introduce the project in a README
1. use interoperable file types
1. use descriptive and logical file names, and
1. make your data tidy.
