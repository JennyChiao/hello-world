```python
x=5
class
```

See so this way I can take notes for programming a lot easier. Always use \ for escaping.

# The Largest Heading is just one \#
## A little smaller heading without a line
### A little smaller than the previous
###### 6 #'s produces the smallest heading



# Emphasis and Highlight Things
**Double star is BOLD** or __double underscores bold__ ctrl b didn't seem to work here

*single star is italic* or use _single underscore_

~~double swigly tilda line for strikethrough~~

**can also combine *text* styles**

***or be kind of obnoxious and bold and italicize everything with triple stars***


When I want to quote someone I can use right carrot > like so:
> "I **never** said *that*." - Jenny Chiao


Can quote code with single backticks \` \` (not to be confused with single quotes) instead of a whole block `like so` or `class` 


But to quote a whole block of code use three backticks \`\`\` on their own lines. 

It will do syntax highlighting if you put the language after the backticks. ie \`\`\`python

But it doesn't seem to follow the color theme settings of the ide. oh well

```python
#Codeblock With Highlighting
x=5 #just trying this out


class Location:
    def __init__(self, name, lat, lon): #__init__ is constructor(variable declarations)
        self.name = name    # string for name of location #datascope called self that takes in variable name
        self.lat = lat      # latitude in degrees (-90 to 90)
        self.lon = lon      # longitude in degrees (-180 to 180)

```

```
#Codeblock Without Highlighting
x=5 #just trying this out


class Location:
    def __init__(self, name, lat, lon): #__init__ is constructor(variable declarations)
        self.name = name    # string for name of location #datascope called self that takes in variable name
        self.lat = lat      # latitude in degrees (-90 to 90)
        self.lon = lon      # longitude in degrees (-180 to 180)

```

Can also just tab but then can't specifify language.


# Links
Use the following format:

\[some text]\(and then the actual link)

Other ways to make links also available. Not 
sure they're particularly relevant to me.

# Lists
Use - or * for bulletpoint lists

* something like this
- ~~yeah~~

Or make a numbered list with...numbers
1. blah
2. blah blah
4. blah blah blah
1. blah blah blah blah
1000. blah blah blah blah blah
89. clearly doesn't matter if whats typed is actually in order b/c it does it for you. Just has to be a number and a dot

### Can also do nested lists like so:
1. blah
    - some
    - thing
        - right
            - and
                - again
                1. see
                2. how it works?
                    - yeah

### Task or To Do Lists!
 - [x] Finish my changes
 - [ ] Push my commits to GitHub
 - [ ] Open a pull request

I guess this didn't work exactly in the preview
Maybe not supported in VSCode  


# Spacing
To put things on new line add spaces at the end of where you want the new line to be.

Jenny Chiao
and
Python


versus

Jenny Chiao  
and  
Python
