[![](./CV_conorisco/front.PNG)](https://github.com/Conorisco/CV/raw/main/CV_conorisco/CV_conorisco.pdf)

# CV generated in R

My academic CV made with the `Vitae R` package, with code from a variety of github pages which I am indebted to including Brian Jenks https://github.com/tallguyjenks

long form pdf CV available [here](https://github.com/Conorisco/CV/raw/main/CV_conorisco/CV_conorisco.pdf)

Short form pdf CV - TBC

## Rationale

Before discovering `Vitae` I had a CV written in Word. The word-based CV was created while I was still a teenager, probably when I applied to be a lifeguard. The .doc condtained horrible formatting and Word 'anchors' that made editing incredibly frustrating.  

I always wanted to learn LaTeX. I fell in love with `Rmarkdown` and was delighted when I found out it had LaTeX converter using LaTeX templates.

Written in `rmarkdown` and exported using `tintex` to create LaTeX pdf 

Built using a bunch of excel files which hold raw data. I found this to be the most user friendly method to add new information. Other code examples added data within R, which I feel is not realistic way to read in new data. 

Built using a publication list exported from Mendeley desktop and using custom tables in excel.

## To do

- [x] Complete draft 1
- [x] Scrub student names or identifiable information 
- [x] Make public
- [X] Go into more detail on current roles and emphasize project management experience 
- [X] streamline text size by editing letex variables in .cls file
- [ ] build tables for skills using `kable()` to create a more impactful and shorter list of skills
- [ ] Automatically update publications from orcid/Google scholar rather than manually from citatioin manager
- [ ] programmatically create short and long form CV
- [x] goggle scholar integration - create some graphs, might be a bit too goofy.
- [ ] add a table of number of corresponding, first author and senior author papers
- [ ] Create data-science focused non-acedemic CV
- [ ] Create industry focused CV
