# Analyse-et-Prévision-de-Séries-Chronologiques-de-la-Production-électrique-avec-Python.
Ce projet a pour objectif d'analyser et de prévoir la production électrique en utilisant des techniques de séries chronologiques avec Python. L'objectif principal est d'identifier les tendances, les saisonnalités et les irrégularités dans les données afin de produire des prévisions précises. Après une exploration initiale des données et la vérification de la stationnarité (via le test de Dickey-Fuller), la méthodologie de Box-Jenkins a été appliquée pour guider la sélection du modèle. Cette approche repose sur une analyse itérative des graphiques ACF (Autocorrelation Function) et PACF (Partial Autocorrelation Function) pour identifier les composantes autorégressives (AR), de différenciation (I), et de moyennes mobiles (MA), ainsi que leurs équivalents saisonniers. En suivant cette méthode, plusieurs configurations ont été testées et évaluées à l’aide du critère AIC, permettant d'identifier le modèle optimal SARIMAX(1,1,1)(2,1,2)[12]. Ce modèle capture à la fois les dynamiques temporelles et les effets saisonniers sur une base annuelle. Les résidus ont ensuite été examinés à l'aide du test de Ljung-Box pour s'assurer de l'absence d'autocorrélation et du test de Jarque-Bera pour vérifier leur normalité. Les performances du modèle ont été évaluées à l'aide des métriques telles que le MAE et le RMSE, et les prévisions générées ont été visualisées pour en valider la qualité. Ce projet met en lumière l'efficacité de la méthodologie de Box-Jenkins combinée au modèle SARIMAX pour la modélisation et la prévision de séries temporelles complexes.
