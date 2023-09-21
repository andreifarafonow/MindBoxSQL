### SQL-запрос:
```sql
SELECT Products.Name AS "Product",
       Categories.Name AS "Category"
FROM Products
LEFT JOIN ProductsCategories ON Products.Id = ProductsCategories.ProductID
LEFT JOIN Categories ON ProductsCategories.CategoryId = Categories.Id;
```

### Результат:
