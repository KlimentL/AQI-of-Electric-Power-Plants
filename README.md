This project analyzes air quality across the United States by using data from electric power plants. The goal of the analysis is to detect anomalies in Air Quality Index (AQI) and predict missing values related to fossil fuel usage.

Project Overview
Air quality is a crucial aspect of environmental health. Accurate prediction and detection of anomalies in air quality can help in identifying potential environmental issues and forming effective responses. This project addresses two key challenges:

Missing Value Prediction: Some data records related to fossil fuel usage (like coal, natural gas, and oil) in power plants were missing. We trained a machine learning model to predict these missing values based on available data, thus providing a complete dataset for further analysis.

Anomaly Detection: Using a predictive model, we determined expected AQI values based on the data from power plants. We then compared these predictions with actual AQI values, with significant deviations identified as anomalies. These anomalies could signify unexpected changes in air quality that warrant further investigation.

Data
The data used in this project includes information about electric power plants, such as the number of generator units and the quantities of different fossil fuels used. It also includes the Air Quality Index (AQI) for different locations across the United States.

Links:

Tableau https://public.tableau.com/views/AQIfromelectricpowerplantsinUS/Sheet6?:language=en-US&:display_count=n&:origin=viz_share_link

Colab Notebook https://colab.research.google.com/drive/1ImUGi8sTJO65hUALWenO_aewTVI0SHwF?usp=sharing

