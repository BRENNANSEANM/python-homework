# python-homework
UW FinTech Python Homework

1. Why is a list better for this homework then a dictionary?
    * I struggled with this item to get past the know logic as it seemed to be more linear for sum and average.  I did a lot of google searching and still found it difficult to do the sum function on the value based on Keys
    * On the plus side I was able to learn how to import a csv into a dictionary - is there any good references for best practices?  I didn't include this code in the final main code submitted.  Here is sample of what I tried to leverage.

    with open(csvpath) as monthly_returns:
        reader = csv.reader(monthly_returns)
        header = next(reader)
        dict_from_csv = {rows[0]:rows[1] for rows in reader}

    * Then from there I spent a lot of time trying to get the sum command to work, but kept getting syntax or undefined errors - but I could confirm I created a dictionary with Date as the Key and Profit/Losses as the Value.

2. Guidance on best practices for Python/Pandas going forward:
    * Should we always create a bucket for intializing objects, int, str, float, lists, dictionaries, etc.  I had originally placed them itermittantly, as some of the in class work had it that was, again never got far enought to truly test this theory out and more intereted in best practice.

3. I had to lean on a lot of help to understand the logic - I did focus more on code documentation and descriptors to establish an understanding of descriptive statements within the code.

4. Practice, practice and more practice - do you have any more good recs for Python tutorials, I have gone through some of the data camp set's, but was just wondering of any other good practice on Loops and use of lists, that seems to be my foggy point for sure.  I plan to get into a tutoring session and walk through PyRamon, still diving into to that one, but since it is optional wanted to get this submitted tonight before it is to late.
