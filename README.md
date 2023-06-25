# זרוע רובוטית בשישה דרגות חופש
פרויקט זה אנו מתעסקים עם זרוע רובוטית סטנדרתית במרחב שלושה ממדים עם שישה פרקים או מעלות-חופש.

עם זרוע כזו ניתן למדוד עמדות באמצעות קינמטיקה קדימה או לבצע פעולות תעשייתיות באמצעות קינמטיקה קדימה והפוכה.
# קינמטיקה ישירה
נציג את תוצאות הקינמטיקה הישירה עבור חמשת הנקודות שבחרנו:

    point1=[0, 0, 0, 0, 0,0]
    point2=[90 90 60 0 0 0]
    point3=[0 90 60 90 60 0]
    point4=[270 0 270 90 270 180]
    point5=[270 180 270 90 90 90]


![image](https://github.com/menach/6DOF-robot/assets/67026699/b65951ba-c082-41dd-9cfe-dfc5531c68f9)




![image](https://github.com/menach/6DOF-robot/assets/67026699/89daa566-7995-4326-8fd4-fda36c080081)




![image](https://github.com/menach/6DOF-robot/assets/67026699/269f71b1-c928-4674-98b8-a81028f843a3)




![image](https://github.com/menach/6DOF-robot/assets/67026699/9b17ee3f-1fa7-4a17-8f89-3ca9a3f13e15)




![image](https://github.com/menach/6DOF-robot/assets/67026699/e0e353f8-2105-4c82-80f3-185ec31abd22)


# מרחב העבודה של הרובוט
מרחב העבודה של הרובוט הוא הנקודות אליהן הרובוט יכול להגיע
נציג תמונה איזומטרית המתארת את המרחב העבודה:
![image](https://github.com/menach/6DOF-robot/assets/67026699/636bf272-5b67-4c49-a8f9-5d7025bb951c)

# יעקוביאן
בעזרת נוסחא זו נוכל לחשב את היעקוביאן:

![image](https://github.com/menach/6DOF-robot/assets/67026699/9bdaac76-6ca3-447c-ad6f-1ffcba5ff231)

# סטטיקה
עבור F וקטור הכוחות ו T וקטור המומנטים הפועלים בקצה התפסנית. מתקבל τ וקטור המומנטים במפרקים:

![image](https://github.com/menach/6DOF-robot/assets/67026699/ad488028-6c1a-443a-9466-f946d009f76b)


# תכנון התנועה
כדי לחשב את תכנון התנועה נגדיר נקודת התחלה וסיום. מעבר בין הנקודות בהתחשבות בהאצה וההאטה נעשה על ידי פרופיל מהירויות טרפזי. נציג את פרופילי המהירויות עבור כיוון X,Y,Z
![image](https://github.com/menach/6DOF-robot/assets/67026699/ea663dbe-c315-400f-a692-55d8d795eb5d)

# סימולציה 
סרטון של הסימולציה המבוססת מודל מקלות:

https://github.com/menach/6DOF-robot/assets/67026699/ebb5d58e-795a-46e9-af7c-3a3614ad240f


