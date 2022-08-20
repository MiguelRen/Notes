<!-- Tis is as the header-->
# Markdown NOTES

## Explanation
In this case Im going to create a note file that could help me and everybody to remember some important things, tips, cases and commands in this travel that I call "learning how to save class notes with Markdown". 

## Some commands
 
 ### Comments
 In here you can use the HTML coment sintax as well. so:
 ```html
 <!-- coment-->
```

### Code Formating
To format little piece of code (withing your paragraph, maybe), you can use backticks ( `` ) and enclose the code snipt in they, 
like this:
```html
`your code here`
```
and then your´re going to see this: 
`your code here`


But, if you wnat to do it with  a whole block code, you must use 3 backticks

follow by line break

follow by your code

follow by another line beak

follow by 3 backticks more:

*```*[language]

your block code here.
as you want it.


*```*

A completed block code can be highlighted adding the extention language for every case
*```js* 

or 
*```html* 

### Heading
You can create headings like in HTML but using hashes `#` and the mayor  quantity of hashes the more down in the hierarchy
     *`# > ####`*.  write the sign follow by a space and then write the title.

```html
# -------------> title h1
## ------------> title h2
### -----------> title h3
#### ----------> title h4
```

### Italic

To transform normal format word into italic you just have to enclose the word (or phrase) with asterics:
this `*words*` ends up like this *word*

### Bold

For bolding you can use the same trick using 2 asterisks, I mean, 1 pair of asterisks in every word edge 
```
**words or phrase**
```
it will looks like **words or phrase**.

Note: it´s important there not be spaces between  asterisks and words. if so, it won´t work.

### Crossed out words
For this one is the same thing...jus only  using double tilde. Like this:
 ```html
 ~~example word~~
 ```
 It will looks like:
~~example word~~

### Line Break
This is easy. You just make a line Breake pressing the Enter key and... that´s all.


### Unordered List
Just put asterisks  followed by espace, follow by list Item. Like this :

``` 
* A List Item here
 
* Another List Item here

 ```
And that will looks like this 

* A List Item here
 
* Another List Item here

If you want a subtitle just press enter(to get a line break), press tab key ,write  an asterisk, followed by your subtitle.Like this:


* A List Item here
     * A SUBtitle
 
* Another List Item here
     * A SUBtitle


### Links
Write the link between curve brackets but... before, you must write the link name between square brackets. Like this:
```
[link title here](www.theLinkHere.com "Custom tile when you make hover on it")

``` 
. The result: 

[link title here](www.theLinkHere.com "Custom tile when you make hover on it")


### Quotations
use >, spaces, followed by the quote:

> this is a quote

###  Horizontal lines or Divisory lines
 
 use 3 dashes ---

 ---
 ---
 ---



  ### Tables
  ```html
  
|column1 |column2  |column3  |
|--------|---------|---------|
|value1   |value2   |value3   |
|value4   |value5  |value6   |
|value6   |value8   |value9   |
  ```

|column1 |column2  |column3  |
|--------|---------|---------|
|value1   |value2   |value3   |
|value4   |value5  |value6   |
|value6   |value8   |value9   |

Note : the separaton between vertical slach and word, in the right side, is a tab.
The signs in the second line are dashes.

### Images
The images they all are going to be callled as a link. You mast apply this structure:
```
![image description(in case something goes wrong and it can`t charge it)](https//:www.WebPlaceWhereYourImageIs.com)
```
The result:

![image description(in case something goes wrong and it can`t charge it)](https//:www.WebPlaceWhereYourImageIs.com)

The result with no problems:

![Vue Image](https://w7.pngwing.com/pngs/854/555/png-transparent-vue-js-hd-logo-thumbnail.png "custom title when you make hover on it")


If you hace the image in you´r local Pc, or  even in the same folder than the markdown file, use a path to get the image.






## Last Part

Github uses the same standart than markdown but it adds functionalities to aggregate  other thinks like emojis... doodles...

