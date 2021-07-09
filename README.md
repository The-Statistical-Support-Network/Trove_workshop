# Trove_workshop

R SHiny interface to Trove API with csv data download option to work with tidy data. An extension of the original 
Trove_workshop repository on github here [r-lange/Trove_workshop].

## App available online 

This could be hosted by a potential community group, university or company. 
Contact me for support in this here @ `anthony.davidson@canberra.edu.au`.

## The Shiny webapp 

> ... would allow the interface with the Trove API and access a version of the data that is archived and managed by the identity

- An API key needs to be supplied for this to work 
  -   Update needed to align this with version 2.
  -   
- the user will only be able to access newspaper information for now.

## Work To Do:

- implement iteration of the search until all results are collated (i.e. there might be 200 records but the API only allows retrieval of 100 at a time)
- implement input selection for years
- inlcude proper error message when API key is not given
- remove leading and trailing spaces in inputs

### Original app

Coming here hopefully soon (anyone wana help?):

- selection of brief or full records possible
- The app displays the search results in a table
- search results can be viewed by clicking on links in the troveUrl column
- Download Data will open a dialog box to download the displayd table as a csv file

