# Smartphones Dataset Analysis
Data Mining Project

--------------------------------------
Прибирање на податоци <br>
  Библиотека: Scrapy<br>
  Извори: <br>
  https://gadgets.ndtv.com <br>
  https://www.firstpost.com/ <br>

Предпроцесирање на податоци <br>
  Интеграција на податоци <br>
  Агрегација на податоци <br>
  Чистење на податоци <br>
    Пополнување на missing values со mode() <br>
    Пополнување на missing values според други атрибути <br>
  Енкодирање и трансформација на податоци <br>
    Логаритамска трансформација на атрибутот цена <br>
    Label encoding <br>
    One hot encoding <br>

Визуелизација <br>
  Box plots <br>
  Histograms  <br>
  нумерички и категорични атрибути <br>
  Pie charts <br>
  boolean атрибути <br>
  Матрица на корелација <br>

Класификација <br>
  Цел: Предвидување на производителот во зависност од атрибутите на некој телефон <br>
  Крос-валидација <br>
  Подесување на хипер-параметри <br>
  Искористени модели <br>
    GaussianNB (0.571) <br>
    LinearDiscriminantAnalysis (0.885) <br>
    QuadraticDiscriminantAnalysis (0.9) <br>
    SVC (0.9428) <br>
    KNeighborsClassifier (0.957) <br>
    DecisionTreeClassifier (0.914) <br>
    RandomForestClassifier (0.857) <br>
    AdaBoostClassifier (0.842) <br>

Регресија <br>
  Цел: предвидување на цената на мобилниот телефон во зависност од производителот и останатите атрибути <br>
  Крос-валидација <br>
  Подесување на хипер-параметри <br>
  Намалување на димензионалност (Factor Analysis) <br>
  Искористени модели (R^2 и MSE како метрики): <br>
    LinearRegression (0.92, 0.042) <br>
    Ridge (0.9265, 0.039) <br>
    RandomForestRegressor (0.9041, 0.051) <br>
    KNeighborsRegressor (0.9155, 0.045) <br> 

Кластерирање <br>
  Кластерирање во 7 кластери и споредба со класификација во однос на атрибутот производители  <br>
    ARI = 0.1216 <br>
  Кластерирање во 3 кластери и споредба со дискретизација на атрибутот цена во 3 подмножества <br>
    ARI = 0.0697 <br>

