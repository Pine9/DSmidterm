# DSmidterm

### First Milestone Questions
* **Problem**: I plan to look at a snapshot of adoptable dogs across the United States (as posted on [Petfinder.com](https://www.petfinder.com)) to determine the predominant breed makeups and characteristics of dogs within the shelter and rescue systems. In particular, I want to look at this distribution state-by-state. Hopefully, this will provide some insight into how the nature of the shelter/rescue systems differs by region. The results could perhaps open the door for further study.
* **Questions**:
    - For each state, what is the most populous breed found in shelters?
    - What is the current average length of stay (LOS) for each breed?
    - For each US geographical region, what are the top 10 breeds?
* **Justification**:
* **Datasets**: I am considering this dataset from 2019: https://github.com/the-pudding/data/tree/master/dog-shelters. Or I might consider how the COVID-19 pandemic has influenced the data, and may take it from the PetFinder API myself.
* **Concerns/Considerations**:
    - With PetFinder, fradulent or misleading posts could potentially influence the data. 
    - With my problem in particular, I worry that shelter-reported breed counts may not be accurate in my findings. This is not the fault of the rescues/shelters, since they usually must guess the breed of the dog (or what it is mixed with) and don't have access to DNA tests. However, I believe that my questions are more concerned with the social perception or physical appearance of a dog, not the actual genetic makeup.
    - There is also the possibility that the results from this dataset will be completely unsurprising. For example, I expect the American Pit Bull Terrier to be the most populous breed in shelters/rescues throughout many states (though this may be influenced by any Breed-Specific Legislation within the state). This is why I am more interested in the top 5-10 breeds (there may be a lack of data in some states), which might reveal more subtle regional differences. Another issue is the the fact that dogs are often transferred to another rescue in another state -- sometimes even across the country -- so the state they are found in is not necessarily the state where they become available for adoption.
