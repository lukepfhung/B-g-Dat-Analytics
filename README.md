# Big Data Analytics_Homework1
#### (1) 哪些屬性對於惡意程式分類有效？

算出來的重要值越高即是對於惡意程式分類越有效,故列出前二十
1. feature 306 (0.013411)
2. feature 117 (0.011097)
3. feature 265 (0.008002)
4. feature 228 (0.007035)
5. feature 1638 (0.006078)
6. feature 95 (0.006050)
7. feature 1497 (0.005857)
8. feature 740 (0.005746)
9. feature 877 (0.005639)
10. feature 314 (0.005220)
11. feature 1667 (0.005106)
12. feature 1641 (0.004970)
13. feature 224 (0.004953)
14. feature 132 (0.004919)
15. feature 226 (0.004915)
16. feature 1677 (0.004862)
17. feature 735 (0.004632)
18. feature 275 (0.004620)
19. feature 1503 (0.004597)
20. feature 800 (0.004587)

#### (2) 哪些屬性對於惡意程式分類無效？

算出來的重要值越低即是對於惡意程式分類越無效,故列出最後二十
1. feature 345 (0.000000)
2. feature 458 (0.000000)
3. feature 78 (0.000000)
4. feature 70 (0.000000)
5. feature 449 (0.000000)
6. feature 412 (0.000000)
7. feature 1049 (0.000000)
8. feature 1475 (0.000000)
9. feature 335 (0.000000)
10. feature 981 (0.000000)
11. feature 1001 (0.000000)
12. feature 1066 (0.000000)
13. feature 868 (0.000000)
14. feature 1093 (0.000000)
15. feature 382 (0.000000)
16. feature 350 (0.000000)
17. feature 1110 (0.000000)
18. feature 349 (0.000000)
19. feature 1112 (0.000000)
20. feature 1020 (0.000000)

#### (3) 用什麼方法可以幫助你決定上述的結論？

利用Forests Trees去算出重要值來做判斷

#### (4) 透過Python哪些套件以及方法可以幫助你完成上面的工作？
一開始利用Pandas對資料做前處理
及利用nampy來處理資料
再來用到Sklearn的套件來運算