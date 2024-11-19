SELECT n,
    CASE WHEN n>=0 THEN n/2
    END AS res
    FROM oddcount