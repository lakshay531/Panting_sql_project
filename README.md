
# Famous Paintings & Museum Dataset: SQL Challenges

This repository provides a series of SQL challenges based on the "Famous Paintings & Museum" dataset. The goal is to analyze the dataset and solve complex queries to gain insights about paintings, museums, artists, and related data.

---

## Dataset Description

### Key Tables:
1. **Paintings**:
   - Contains information about various paintings, including their names, prices, and styles.

2. **Museums**:
   - Includes details about museums, such as their name, location, and operational hours.

3. **Artists**:
   - Contains artist-specific data, such as their name, nationality, and number of works.

4. **Museum_Hours**:
   - Tracks the opening and closing hours of museums by day.

5. **Canvas_Sizes**:
   - Provides details about the canvas sizes and associated costs.

6. **Product_Size**:
   - Links paintings to their specific canvas sizes.

---

## Challenges

### Queries to Solve:
1. **Unlinked Paintings**: Fetch all the paintings that are not displayed in any museum.
2. **Empty Museums**: Are there museums without any paintings?
3. **High Asking Price**: Count paintings with an asking price higher than their regular price.
4. **Discounted Paintings**: Identify paintings priced at less than 50% of their regular price.
5. **Most Expensive Canvas**: Determine the canvas size that costs the most.
6. **Remove Duplicates**: Delete duplicate records from `work`, `product_size`, `subject`, and `image_link` tables.
7. **Invalid City Names**: Identify museums with invalid city information.
8. **Invalid Museum Hours**: Detect and remove invalid entries from the `Museum_Hours` table.
9. **Popular Subjects**: Fetch the top 10 most famous painting subjects.
10. **Museums Open on Sunday and Monday**: List museums open on both days, including their name and city.
11. **Always Open Museums**: Count museums open every single day.
12. **Popular Museums**: Identify the top 5 museums with the highest number of paintings.
13. **Popular Artists**: List the top 5 artists with the highest number of paintings.
14. **Least Popular Canvas Sizes**: Display the 3 least popular canvas sizes.
15. **Longest Open Hours**: Which museum is open for the longest duration in a day? Include museum name, state, hours open, and the specific day.
16. **Popular Painting Style**: Which museum hosts the most paintings of the most popular style?
17. **Artists in Multiple Countries**: Identify artists whose paintings are displayed in multiple countries.
18. **Museum Locations**: Find the country and city with the most museums. Output two separate columns (city and country), separating multiple values with commas.
19. **Most/Least Expensive Paintings**: Identify the artist, museum, and details for the most and least expensive paintings.
20. **5th Highest Paintings**: Find the country with the 5th highest number of paintings.
21. **Popular and Unpopular Styles**: List the 3 most popular and 3 least popular painting styles.
22. **Portraits Outside USA**: Identify the artist with the most portrait paintings displayed outside the USA. Include artist name, number of paintings, and nationality.

---

## Usage

### Running the Queries:
- Ensure the dataset is loaded into your SQL-compatible database (e.g., MySQL, PostgreSQL).
- Run the SQL queries provided in the solutions folder to solve the challenges.

---

## License
This dataset and challenge repository is open for educational purposes. Attribution is appreciated!

--- 

Let me know if you'd like solutions or assistance with specific queries!
