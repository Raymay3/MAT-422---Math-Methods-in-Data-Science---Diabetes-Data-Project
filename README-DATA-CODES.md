## Diabetes Dataset Description

Diabetes patient records were obtained from two sources:
- An automatic electronic recording device
- Paper records

The automatic device includes timestamps from an internal clock, while paper records only provide "logical time" slots:
- Breakfast (08:00)
- Lunch (12:00)
- Dinner (18:00)
- Bedtime (22:00)

As a result:
- Paper records use **fixed, uniform times**
- Electronic records contain **realistic timestamps**

---

## File Structure

Each diabetes record contains **four fields**:
- Fields are separated by a **tab**
- Records are separated by a **newline**

### File Format

1. Date (MM-DD-YYYY)
2. Time (HH:MM)
3. Code
4. Value

---

## Code Definitions

| Code | Description |
|------|------------|
| 33 | Regular insulin dose |
| 34 | NPH insulin dose |
| 35 | UltraLente insulin dose |
| 48 | Unspecified blood glucose measurement |
| 57 | Unspecified blood glucose measurement |
| 58 | Pre-breakfast blood glucose measurement |
| 59 | Post-breakfast blood glucose measurement |
| 60 | Pre-lunch blood glucose measurement |
| 61 | Post-lunch blood glucose measurement |
| 62 | Pre-supper blood glucose measurement |
| 63 | Post-supper blood glucose measurement |
| 64 | Pre-snack blood glucose measurement |
| 65 | Hypoglycemic symptoms |
| 66 | Typical meal ingestion |
| 67 | More-than-usual meal ingestion |
| 68 | Less-than-usual meal ingestion |
| 69 | Typical exercise activity |
| 70 | More-than-usual exercise activity |
| 71 | Less-than-usual exercise activity |
| 72 | Unspecified special event |

---

## Contact

Questions regarding the format of the diabetes data files can be sent to:

- Email: kahn@informatics.WUSTL.EDU  
- CompuServe: 70333,34  

*Note: Response via CompuServe may be delayed.*
