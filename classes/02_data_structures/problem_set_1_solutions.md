# Data Structures - Solutions

### Lists

    # 1. Initialize a list called "boys" with the elements: "Fred", "George", "Percy", "Ron".
    boys = ["Fred", "George", "Percy", "Ron"]
    
    # 2. Initialize a list called "girls" with elements: "Giney".
    girls = ["Giney"]
    
    # 3. Print both lists.
    print(boys)
    print(girls)
    
    # 4. Print the first element in "girls".
    girls[0]
    
    # 5. Find two or three ways to print the last element in "boys".
    boys[3]
    boys[len(boys) - 1]
    boys[-1]
    
    # 6. Add the element "Charles" to the "boys" list.
    boys.append("Charles")
    
    # 7. Add the "boys" and "girls" together, and save the results as a list called "weasleys".
    weasleys = boys + girls
    
    # 8. Use the `.sort()` method to sort the "weasleys" list into alphabetical order.
    weasleys.sort()
    print(weasleys)

### Dictionaries

    # 1. Create an empty dictionary named "tardis".
    tardis = {}
    
    # 2. Add a key/value pair to tardis of "Doctor"/"Who".
    tardis['Doctor'] = 'Who'
    
    # 3. Add a key/value pair to the tardis dictionary of "Dalek"/"Evil".
    tardis['Dalek'] = 'Evil'
    
    # 4. Print the tardis dictionary. Print the keys. Print the values.
    tardis
    tardis.keys()
    tardis.values()
    
    # 5. Change the value of "Dalek" to "Exterminate"
    tardis["Dalek"] = "Exterminate"
    
    # 6. Print tardis (in two different ways).
    tardis
    print(tardis)
    
    # 7. Save the Doctor! Remove the "Dalek" key from the dictonary.
    del tardis["Dalek"]
    
    # 8. Print tardis.
    tardis

### Tuples

    # 1. Create a tuple called "months" containing the words "January" and "February".
    months = ("January", "February")
    
    # 2. Add "March" to the "months" tuple.
    # TRICK QUESTION: You can't modify a tuple.
    
    # 3. Change "January" to "June".
    # TRICK QUESTION: You can't modify a tuple.
    
    # 4. Return the first element in "months"
    months[0]
    
    # 5. Return the last element in "months" in two or three different ways.
    months[-1]
    months[1]
    months[len(months) - 1]

### Sets

#### Solutions

    # 1. Create a empty sets called "insects".
    insects = set()
    
    # 2. One-at-a-time, add these elements to insects: "6 legs", "exoskeleton",
    #    "3-part bodies", "small", "lay eggs"
    insects.add("6 legs")
    insects.add("exoskeleton")
    insects.add("3-part bodies")
    insects.add("small")
    insects.add("lay eggs")
    
    # 3. Create a new set called "spiders" that starts off including the elements:
    #    "8 legs", "spin webs", "2-part bodies", "small", "lay eggs"
    spiders = set(["8 legs", "spin webs", "2-part bodies", "small", "lay eggs"])
    
    # 4. Print both sets.
    >>> insects
    >>> spiders
    
    # 5. Find the intersection of both sets.
    >>> insects.intersection(spiders)
    set(["small", "lay eggs"])
    
    # 6. Determine if either set is a subset of the other.
    >>> insects.issubset(spiders)
    False
    >>> spiders.issubset(insects)
    False
    >>> insects.issuperset(spiders)
    False
    >>> spiders.issuperset(insects)
    False
    
    # 7. Add "not cuddly" to the spider set, and print.
    >>> spider.add("not cuddly")
    >>> spider
    set(["8 legs", "spin webs", "2-part bodies", "small", "lay eggs", "not cuddly"])
    
    8. Remove the "not cuddly" from the spider set, and print.
    >>> spider.remove("not cuddly")
    >>> spider
    set(["8 legs", "spin webs", "2-part bodies", "small", "lay eggs"])

[Back to Problem Set](problem_set_1_data_structures.md)