# JABAR-DIGITAL-SERVICE-2
JAWABAN UNTUK DE_SQL Score #2 *


SELECT name FROM employees
WHERE id NOT IN (SELECT managerId FROM employees WHERE managerId IS NOT NULL);
