# What's in an Avocado Toast: A Supply Chain Analysis

This project investigates the supply chains behind three key ingredients in avocado toast using the [Open Food Facts database](https://world.openfoodfacts.org/). The goal is to identify countries of origin for each ingredient and understand the global logistics required to make this trendy breakfast dish possible.

## Project Objectives

- Clean and filter product data for **avocados**, **olive oil**, and **lemons** using their respective category tags.
- Extract and analyze **country of origin** information for each ingredient.

## Dataset

The dataset includes 3 ingredient-specific CSV files and their matching TXT files for filtering:

| File Name | Description |
|-----------|-------------|
| `avocado.csv` | Raw Open Food Facts data for avocado-related products |
| `relevant_avocado_categories.txt` | Valid category tags for avocado filtering |
| `olive_oil.csv` | Product data for olive oils |
| `relevant_olive_oil_categories.txt` | Category tags for filtering olive oil products |
| `lemon.csv` | Data for lemon products |
| `relevant_lemon_categories.txt` | Category tags for lemon filtering |

Each file includes `categories_tags` and `origins_tags` columns used for filtering and analysis.


## Tools Used

- Python 3  
- pandas  
- string filtering & text processing  

---

> This project highlights the complexity of sourcing even simple ingredients, showing how global supply chains affect everyday meals.
