Audible Dataset Cleaning & Preparation 📚🎧
Overview

This repository contains a cleaned and structured version of the Audible Audiobooks Dataset (1998–2025).
The dataset includes valuable information on audiobook titles, authors, narrators, release dates, languages, ratings, prices, and durations.
With the growing popularity of audiobooks, this project aims to provide a reliable dataset for Exploratory Data Analysis (EDA), visualization, and predictive modeling.

Dataset Features

Name: Title of the audiobook

Author(s): One or multiple authors (separated and standardized)

Narrator(s): One or multiple narrators (separated and standardized)

Release Date: Cleaned and converted into proper date format

Language: Standardized language values

Ratings Count: Converted into numeric values

Star Rating: Extracted and cleaned (0 for “Not rated yet”)

Price: Converted to numeric (float), with “Free” replaced by 0 and commas removed

Duration: Converted from text format (e.g., 2 hrs 30 mins) into total minutes

Data Cleaning Steps

✔ Removed duplicates while keeping unique author–narrator pairs
✔ Handled missing values across time, releasedate, language, ratings, and price
✔ Standardized string formats (author, narrator, name)
✔ Converted numeric columns (price, ratings_count, star_rating, duration) into float/int
✔ Cleaned unwanted characters in titles (e.g., #, [], Book)

Goal 🎯

To create a comprehensive and structured audiobook dataset that helps researchers, data analysts, and ML practitioners analyze audiobook trends, author/narrator contributions, pricing patterns, and audience engagement over time.
