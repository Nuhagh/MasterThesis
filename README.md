
* Folder (fastTextComparisonPaper)
    
    Contains .ipynb files used to build models of paper: [A Comparison of fastText Implementations Using Arabic Text Classification](https://link.springer.com/chapter/10.1007/978-3-030-29513-4_21).

* Folder (ThesisClassificationModels)
    
    Contains vectors files and .ipynb file that trained multiple classification models using fastText. The results are used in paper:[Solving the Cold-Start Problem in Recommender Systems Using Contextual Information in Arabic from Calendars](https://link.springer.com/article/10.1007/s13369-020-04890-z) 

* Files (dataset_16Feb.csv and dataset_16Feb.json)
  
    An Arabic dataset which was collected via WikipediaAPI in Python.

    * The dataset contains 1909 labeled articles in five classes:
        1. Tech: 400 articles about techonlogy, electronics, home automation and mobile phones.
        2. Work: 400 articles about office, office wear, formal clothes, uniforms, work interviews, shared work space, working as a team, careers, and education.
        3. Sport: 309 articles about sports, sport wear, gym, sport shoes, exercises, football and universal games, sport equipment, leagues and sport clubs.
        4. Beauty: 400 articles about shopping, fashion, makeup, social events, occasions, parties, gifts, perfumes and accessories.
        5. Health: 400 articles about medicine, women's health, men's health, child health, vaccination (medicine), pharmacy, global health, medical speciality, prevntion, cleaning, and dentistry.

    * The dataset is cleaned by removing:
        1. digits.
        2. Underscores.
        3. Any word written by the letters from a-z or A-Z.
        4. Punctuation.
        5. Special characters including (Tashkeel).
        6. Unrelated common words: "بالإنجليزية","باللاتينية","باليونانية","انظر أيضا","أنظر أيضا","اقرأ أيضا","وصلات خارجية","مصادر","مراجع","المراجع","مقالات ذات صلة"
        7. Empty lines.
        8. The articles were checked manually and some articles which were tagged inaccurately by Wikipedia were removed. 
