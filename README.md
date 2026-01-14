# KMNIST-Classification-Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Yyq9K_ioBFGMQ1Pco1r9xuc8_-vWVCI1)


## 📝 Overview
פרויקט זה מבצע סיווג של תווים יפניים מתוך מאגר *KMNIST* באמצעות רשת נוירונים מסוג MLP. 
הפרויקט כולל חיפוש היפר-פרמטרים (Hyperparameter Search) כדי למצוא את השילוב האופטימלי בין מספר נוירונים, Dropout וקצב למידה.

## 📊 תוצאות הניסויים
ריכזתי את כל 12 ההרצות שבוצעו בתוך קובץ ה-kmnist_results.csv.
התוצאה הטובה ביותר שהושגה: *89.65% Accuracy* (ניסוי מספר 10).

### Top 3 Experiments:
| Experiment | Neurons | Dropout | Learning Rate | Test Accuracy |
|:---:|:---:|:---:|:---:|:---:|
| 10 | 512 | 0.2 | 0.001 | *89.65%* |
| 7 | 512 | 0.1 | 0.001 | 89.26% |
| 4 | 256 | 0.2 | 0.001 | 88.45% |

## 📉 ויזואליזציה
כאן תוכלו לראות את גרפי הלמידה ואת מטריצת הבלבול של המודל הטוב ביותר:


| <img width="1189" height="390" alt="loss_accuracy_plot" src="https://github.com/user-attachments/assets/366dbe28-e4ee-470f-94fb-dafc43446957" />
 | <img width="788" height="701" alt="confusion_matrix" src="https://github.com/user-attachments/assets/cbf681ef-9954-4213-bf4c-e71b344524c6" />
 |


