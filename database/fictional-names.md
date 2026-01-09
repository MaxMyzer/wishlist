A big database (likely built with wikibase) that indexes names (places, people, species, work name, etc.) found in popular fictional works. Most likely to be built with WikiBase. 

The database only includes very basic information about each item. Instead of going into detail, templated external links guide the user to other sites, such as:
  - Official/fan wiki pages for the item
  - WikiMedia project (WikiData, Wikipedia, etc.) pages for the item
  - Searches for the name on sites with fan works

Database structure brainstorming: 
- Common name parts with attributes
  - Import common firstnames and surnames in various languages to reference.
  - Character names link back to this so users can find "related" entries or track down what something is refering to.
  - Common names should have attributes such as how often it is a given name vs surname, and how often it is with different genders, if applicable.
  - For languages with multiple writing systems, names that are the same as still seperate entries that link to eachother with appropriate properties.
    - Eg, Japanese may have a name written in Kana with multiple Kanji names linked to it.
- Character (`name_(work)`), work (`work_(franchise)`), and franchise (`franchise`) pages:
  - This naming scheme prevents characters from differnet franchises with the same name from being confused
  - Should point to entries for:
    - given name
    - surname
    - origin work
    - nicknames
  - Additional attributes for _basic_ information that may help users identify them can be added
    - Species (wikidata item)
    - Gender(s)
    - Hair color(s) and length(s)
    - Skin/scale/fur color(s)
    - Basic Physique
    - VERY Common clothing/accessories (appears almost always

