# DSmidterm

### First Milestone Questions
* **Problem**: I plan to look at a snapshot of adoptable dogs across the United States (as posted on [Petfinder.com](https://www.petfinder.com)) to determine the predominant reported breeds of dogs within the shelter and rescue systems. In particular, I want to look at this distribution state-by-state.
* **Questions**:
    - For each state, what is the most populous reported breed found in shelters?
    - What is the current average length of stay (LOS) for each reported breed?
    - For each US geographical region, what are the top 10 reported breeds?
* **Justification**: Examining which reported dog breeds are most often ending up homeless and offered for adoption in local shelters/rescues may help to answer questions about breed popularity and dog ownership culture in the United States (and whether there are any region-specific trends). It may also help to answer questions about how meaningful a breed identity actually is in the context of animal rescue. [This professional study](https://pubmed.ncbi.nlm.nih.gov/27008213/) determined that breed labels in dogs can influence their percieved adoptability and LOS. Hopefully, this analysis will provide some insight into how dog breed identity in shelter/rescue systems differs by region. The results could perhaps lead to further study or reinforce preexisting conclusions.
* **Datasets**: I am considering this dataset from 2019: https://github.com/the-pudding/data/tree/master/dog-shelters. Or I might consider how the COVID-19 pandemic has influenced the data, and may take it from the PetFinder API myself.
* **Concerns/Considerations**:
    - The results should not cause people to draw false conclusions about why certain breeds often end up in shelters and rescues. Often, the overall popularity of the breed is the main reason.
    - With PetFinder, fradulent or misleading posts could potentially influence the data. 
    - Shelter-reported breed counts may not be accurate. This is not the fault of the rescues/shelters, since they usually must guess the breed of the dog (or what it is mixed with) and don't have access to DNA tests. However, I believe that my questions are more concerned with the social perception or physical appearance of a dog, not the actual genetic makeup.
    - Dogs are often transferred to another rescue in another state -- sometimes even across the country -- so the state they are found in is not necessarily the state where they become available for adoption. This could confound the results.
    - Some states will have more available data than others.
    - There is also the possibility that the results from this dataset will be completely unsurprising. This is why I am more interested in the top 5-10 breeds, which might reveal more subtle regional differences.
