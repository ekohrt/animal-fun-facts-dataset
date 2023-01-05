# Animal Fun Facts Dataset
A dataset of 7734 animal "fun facts" from various sources on the web.

| animal_name | source | text | media_link | wikipedia_link |
|---|---|---|---|---|
| aardvark  | https://www.animalfactsencyclopedia.com/Aardvark-facts.html  | Aardvarks are sometimes called "ant bears", "earth pigs", and "cape anteaters" |   |  /wiki/Aardvark |
  
Columns:  
- *animal_name*: Name of the animal as presented on the source page. (Note: most animals have many common names, so there may be duplicates).
- *source*: Link to the page where this fact was found.  
- *text*: Text of the animal fact.
- *media_link*: r/Awwducational posts often have a photo or video included for context.  
- *wikipedia_link*: Shortened wikipedia url for this animal (ex. https://en.wikipedia.org/wiki/Aardvark shortened to /wiki/Aardvark). These were hand-labeled by me, a non-expert, so treat it as a best guess. Some valeus mising. Many pages refer to broad taxonomical groups instead of individual species. Possibly useful for finding scientific classification and merging duplicate animal names.

Sources:
- FactAnimal [3361]: https://factanimal.com/animals/
- A-Z Animals [2138]: https://a-z-animals.com/animals/
- Seaworld [1101]: https://seaworld.org/animals/facts/  
- Animal Facts Encyclopedia [614]: https://www.animalfactsencyclopedia.com/Animals-A-to-Z.html
- r/AskReddit (various threads) [273]: ex. https://www.reddit.com/r/AskReddit/comments/gbh7zz/what_are_some_really_amazing_animal_facts/
- r/Awwducational ("verified" flair only) [247]: https://www.reddit.com/r/Awwducational/top/?t=all&f=flair_name%3A%22Verified%22


