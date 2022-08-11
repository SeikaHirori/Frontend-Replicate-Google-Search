
# Sample inputs:
- test
- this
- out
- man

# Search page
- Simplified link: 
> https://www.google.com/search?q=test

How it works:
- NECESSARY:
    - 'search?'
        - I think this is like a folder/parent to all of the other searches.
    - 'q=test'
        - 'q'
            - This the name of the function, where it searches all parts of the word
        - 'test'
            - The input from the user.


# Image page
- Simplified link: 
> https://www.google.com/search?q=test&tbm=isch

How it works:
> This extends from #search page
- 'tbm=isch'
    - 'tbm'
        - This is results in outputting in only a type of information.
            - i.e. images or news
    - 'isch'
        - This is the name for the "image"

Alternative link:
> http://images.google.com/images
- This works as well, but the control for it seems lackluster in comparison to the one above.


# Advance page
- Simplified link:
> https://www.google.com/search?as_q=test&as_epq=this&as_oq=out&as_eq=man

How it works:
> This extends from #search page
- 'as_'
    - I think this is a template that indictates that different criteras are being used for the search.
- 'q'
    - Function: 'All these words'
- 'epq'
    - Function: 'This exact word or phrase'
- 'oq'
    - Function: 'Any of these words'
- 'eq'
    - Function: 'None of these words'