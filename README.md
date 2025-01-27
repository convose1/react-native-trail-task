# Convose React native cofounder Trial task:

## Create interests search (input & autocomplete) for the Convose interests:

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/91b23058-90d3-4f0e-a929-6afb3a3820dc/2368ad22-9e45-477d-8d5a-fd4294b69194/image.png)

**Key terms:**
1. Primary Search term (the display term, E.g., see “Geology” & “German” in above image)
2. Secondary search term (”Rocks” in image above)

See [Convose.com](http://Convose.com) & the Convose app to see how it currently works, no need to replicate that exactly just get the basic functionality working as described below:

Here is the documentation for the api: [https://shadowed-camelotia-c37.notion.site/Interests-Autocomplete-API-184fff04b6f180a9a7add4a5524a7a9d](https://www.notion.so/184fff04b6f180a9a7add4a5524a7a9d?pvs=21)

As a user I want to be able to search for interests. Backend will provide list like this:
1. Alphabetical order and then
2. Order of popularity. 
E.g., if I type “G” it will show many interests that have a display term (or secondary search term) beginning with the letter “G”. It should list these “G” interests in order of popularity (i.e., the amount of users who’ve added that interest).

Interests should be listed from bottom to top for the app (not top to bottom like Convose.com). So I, as a user, can easily tap them with my thumb (without needing to reach to top of phone).

As a user I dont want the list to continually reload every time a character is typed. E.g., in the case of the above design I’ve typed “G”, if I now type “e” it wont reload these interests it will just remove/replace the ones that don’t begin with “Ge”. This is a nicer UX for me as a user because the list isn’t then continuously disappearing & reappearing as I type.

Make sure there’s no unecessary flashing of the list (e.g., as I delete or add characters (letters) the list should never jump around or disappear/reappear necessarily.

In addition to the way it currently works in the app do:
1. Show the secondary search terms like in the above design
2. Any other improvements you see are needed.

Can be built with CLI (prefered) but expo also fine. 
Generate apk for Josh to test.
