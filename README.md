# Master-Thesis-2015
This is the programs created for the Master Thesis "Content Categorization for Contextual Advertising Using Wikipedia", by Ingrid Guren. 

##Files needed from Wikipedia to run program: 
* enwiki-latest-categorylinks.sql.gz
* enwiki-latest-page.sql.gz
* enwiki-latest-page_props.sql.gz
* enwiki-latest-redirect.sql.gz
* enwiki-latest-category.sql.gz
* enwiki-latest-langlinks.sql.gz

##Run order for the programs: 
- Find_all_hidden_categories.py
- Find_all_redirecting_titles.py
- Split_categorylinks.py
- Remove_hidden_categories.py
- Articlegraph_builder.py
- Categorygraph_builder.py
- Find_high_inlink_outlink_number.py

### If using ids. 
- Article_path_builder-id.py
- Create_category_grades-id.py 
- Grader-id.py

### To create the Norwegian classifier: 
- Create-entry-pageid.py
- Create-pageid-entry.py
- Find_norwegian.py
- Translate.py
- Create-dictionary.py



Ingrid Guren
August, 2015
