# Projetos-de-SQL
SELECT year,
       month,
       month_name,
       west,
       midwest,
       south,
       northeast
  FROM tutorial.us_housing_units
  
  SELECT 
      year,
      month,
      west,
      month_name,
      south,
      midwest,
      northeast
  FROM tutorial.us_housing_units
      
  SELECT *
  FROM tutorial.billboard_top_100_year_end
 WHERE song_name LIKE '%California%'
   AND (year BETWEEN 1970 AND 1979 OR year BETWEEN 1990 AND 1999)
   
  
