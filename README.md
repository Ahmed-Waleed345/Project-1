# Data-Analysis-P1

### 📑 Data Transformation Change Log (Artifact)

| Change ID | Description | Impact | Status |
| :--- | :--- | :--- | :--- |
| **CR001** | Identified 300+ records with missing `CouponCode` and imputed with `'NO_COUPON'` | Preserved statistical power and retained crucial customer transactions (e.g., C26817, C39416, etc.) | **Resolved** |
| **CR002** | Validated `Date` column datatype as `datetime64[ns]` | Verified strict adherence to chronologically consistent tracking | **Resolved** |
| **CR003** | Applied `.str.strip()` & `.str.upper()` to `OrderID` | Ensured zero hidden duplicate IDs across all transactions | **Resolved** |
| **CR004** | Executed automated trimming loop across all `object` columns | Eliminated extra spaces, standardizing textual categories | **Resolved** |
| **CR005** | Performed comprehensive Cross-Column Integrity Audit | Confirmed a **0% Duplicate Error Rate** for full rows and specific identifiers | **Resolved** |
