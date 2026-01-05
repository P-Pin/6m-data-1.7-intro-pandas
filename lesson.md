# **Lesson Plan**

## **Overview**

* **Total Duration:** 3 hours  
* **Context:** Blended Learning 
* **Target Audience:** Adult learners with Python basics.  
* **Learning Objectives:**  
  * LO1: Create and modify Pandas' data structures.  
  * LO2: Apply Pandas' indexing and selection.  
  * LO3: Apply function and mapping in Pandas.  
  * LO4: Sort and rank data in Pandas.

## **Top 3 Critical Topics**

1. **DataFrame Anatomy & Modification:** (LO1) The fundamental vessel of data.  
2. **Indexing (Loc vs Iloc):** (LO2) The most common stumbling block for beginners.  
3. **Applying Functions & Sorting:** (LO3, LO4) Essential for analysis.

## **Optional Topics (Post-Class)**

* Reindexing (Cognitively heavy, less frequently used).  
* Dropping Entries (Can be taught as a quick command, but deep logic is optional).  
* Multi-indexing (Advanced).

## **Section Breakdown**

### **Section 1: Structures & Modification (60 min)**

**Focus:** LO1 \- Create and modify Data structures.

* **0-10:** Zoom logistics, Introductions, Review Pre-class (Series/DataFrame).  
* **10-25 (Demo):** Creating DataFrames from dictionaries vs lists. Attributes (.shape, .dtypes, .columns). Accessing columns. Adding a new column (scalar vs array assignment).  
* **25-50 (Activity):** "The Inventory System". Learners create a DataFrame representing a store inventory, add columns for 'Price' and 'Stock', and calculate 'Total Value'.  
* **50-60 (Debrief):** Discuss how vectorization (column operations) replaces loops.

### **Section 2: The Art of Selection (60 min)**

**Focus:** LO2 \- Indexing and Selection (loc, iloc, \[\]).

* **0-10:** Concept check: "Address vs GPS Coordinates" analogy for Label (loc) vs Position (iloc).  
* **10-25 (Demo):** Slicing rows, selecting specific columns, Boolean filtering (df\[df\['Value'\] \> 100\]). Common pitfall: \[\] slicing behavior.  
* **25-50 (Activity \- Breakout Rooms):** "Data Detective". Give a dataset with errors or specific targets. Learners must extract:  
  1. Rows 5-10.  
  2. The 'Email' column for users in 'Texas'.  
  3. Update values for specific rows using loc.  
* **50-60 (Debrief):** Show solution. Poll: "Which method would you use to select the last row?"

### **Section 3: Analysis & Operations (60 min)**

**Focus:** LO3 (Functions) & LO4 (Sort/Rank).

* **0-10:** Intro to .apply() vs loops.  
* **10-25 (Demo):** Sorting by index vs values. Ranking data (handling ties). Using .apply() for custom text formatting.  
* **25-50 (Activity):** "Leaderboard Logic". Given a dataset of game scores:  
  1. Create a function to categorize scores (High/Low).  
  2. Apply it to create a 'Category' column.  
  3. Sort the data to find the winner.  
  4. Rank the players.  
* **50-60 (Wrap):** Q\&A, optional topics overview.
