SELECT
  CASE
    WHEN Age BETWEEN 20 AND 29 THEN '20-29'
    WHEN Age BETWEEN 30
  AND 39 THEN '30-39'
    WHEN Age BETWEEN 40 AND 49 THEN '40-49'
    WHEN Age BETWEEN 50
  AND 59 THEN '50-59'
    ELSE '60+'
END
  AS Age_Group,
  ROUND(AVG(Yrs_Since_Last_Promo), 2) AS Avg_Years_Since_Promotion
FROM
  `mainproject-448508.main.hr_employee_attration`
GROUP BY
  Age_Group
ORDER BY
  Age_Group;
