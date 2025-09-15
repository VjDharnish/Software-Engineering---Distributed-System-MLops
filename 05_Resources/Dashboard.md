# 📊 Learning Dashboard

```dataview
TABLE file.link AS Note, status
FROM "01_Distributed_Systems" OR "02_MLOps" OR "03_Engineering_Foundations"
WHERE contains(file.name, "Progress_Tracking")
SORT file.name ASC
```

---

## ✅ Completed Tasks
```dataview
TASK WHERE completed
```

## 📌 Pending Tasks
```dataview
TASK WHERE !completed
```
