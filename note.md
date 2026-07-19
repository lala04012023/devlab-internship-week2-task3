# note.md

## Azərbaycan dili

- Dataset **541,909 sətir** və **8 sütun**dan ibarətdir.
- **InvoiceNo** sütununa əsasən ləğv edilmiş sifarişlər ayrıca analiz edildi.
- Müştəri analizi üçün **CustomerID** olmayan sətirlər silindi.
- Mənfi **Quantity** dəyərləri satış analizindən çıxarıldı və yalnız qaytarılma analizində istifadə olundu.
- Hər sifariş üçün **Revenue = Quantity × UnitPrice** hesablandı.
- Müştərilər ümumi gəlir, sifariş sayı və orta sifariş dəyərinə görə analiz edildi.
- Ölkələr üzrə ümumi gəlir, sifariş sayı və gəlir payı hesablandı.
- Aylıq gəlir trendi analiz edilərək ən yüksək satış dövrləri müəyyən edildi.
- Ən çox satılan **20 məhsul** ümumi satış miqdarına görə sıralandı.
- Ölkələr üzrə sifarişlərin qaytarılma faizi hesablandı.

---

## English

- The dataset contains **541,909 rows** and **8 columns**.
- Cancelled orders were identified using the **InvoiceNo** column.
- Rows with missing **CustomerID** values were removed for customer-level analysis.
- Negative **Quantity** values were excluded from sales analysis and kept only for return-rate analysis.
- A **Revenue** column was created using **Quantity × UnitPrice**.
- Customers were analyzed by total revenue, total orders, and average order value.
- Total revenue, order count, and revenue share were calculated for each country.
- Monthly revenue trends were analyzed to identify peak sales periods.
- The **top 20 products** were identified based on total quantity sold.
- Return rates were calculated for each country using cancelled orders.
