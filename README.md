# trein

I set up this project because I wanted to check my train home and figure out
if I had to leave now, or wait for 10 minutes for the next one. Without 
going to the NS website, filling in details, clicking on a button and seeing it(Yes an extremely
non-essential 'first world' problem). Let's cut out the middle man and call
the NS API directly! 
With the `trein` RStudio addin you set up your trip and the addin will call
the API

## Installation

You can install the released version of trein from [CRAN](https://CRAN.R-project.org) with:

``` r
# install.packages("devtools")
devtools::install_github("rmhogervorst/trein")
```

## Example

![A gif screen recording of people running](https://media.giphy.com/media/xTiTnIQYQN4NUUBFIs/giphy.gif) 
and 
[rstudio plugin gif].


![Buster Keaton silent movie the general (1926)](https://media.giphy.com/media/NGSbD5vI6lUvC/giphy.gif)


## Explanation and definitions

*I sometimes use terms that you might not have heard. That never means you are stupid, but you just need an explanation, I hope this helps, otherwise shoot me an issue on github or contact me via twitter*

- API: an Application Programming Interface, which is a very general term but what 
I really mean is: there is a webservice where you can send request and get an answer back.[API wikipage]
- RStudio addin: In the RStudio IDE there is room for addins. Small screens or functions that help you with tasks. [rstudio addins page]
- IDE integrated development environment. The editor. [rstudio, you're probably already using it]
