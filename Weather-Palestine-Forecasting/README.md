{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 Times-Roman;\f2\froman\fcharset0 Times-Bold;
\f3\fmodern\fcharset0 Courier;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Palestine Weather Forecasting\
\
This repository contains the code and notebooks for multi-variable weather forecasting using meteorological data from Palestine.\
\
## Project Overview\
\
This study compares statistical, classical machine learning, and deep learning models for multi-station weather forecasting. The dataset contains daily observations from five weather stations in Palestine between 2015 and 2025.\
\
## Forecasting Models\
\
The evaluated models include:\
\
- Persistence baseline\
- ARIMA\
- SARIMA\
- Random Forest\
- XGBoost\
- CNN\
- LSTM\
- GRU\
- ConvLSTM\
- CNN-GRU\
- CNN-LSTM with station embedding\
\
## Dataset\
\
The main dataset used for the experiments is:\
\
\
data/final_filled_climate_cleaned.xlsx\
\
\pard\pardeftab720\sa240\partightenfactor0

\f1 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The dataset includes the following variables:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Temperature\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Relative Humidity\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Wind Speed\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Rainfall\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Atmospheric Pressure\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Sunshine Duration\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Station ID\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Date\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Feature Engineering\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The models use:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 30-day historical sequences\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Temporal features: Month, Week, DayOfWeek\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Station encoding / station embedding\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Chronological train-validation-test split\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Evaluation Metrics\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The models are evaluated using:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Mean Absolute Error (MAE)\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Mean Squared Error (MSE)\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Root Mean Squared Error (RMSE)\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Coefficient of Determination (R\'b2)\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Installation\
\pard\pardeftab720\sa280\partightenfactor0

\fs28 \cf0 Option 1: Using pip\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 \
pip install -r requirements.txt\
\
\pard\pardeftab720\sa280\partightenfactor0

\f2\b\fs28 \cf0 Option 2: Using Conda\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 \
conda env create -f environment.yml\
conda activate palestine_weather_forecasting\
\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 How to Run\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Run the notebooks in the following order:\
\pard\pardeftab720\partightenfactor0

\f3\fs26 \cf0 \
notebooks/01_preprocessing.ipynb\
notebooks/02_statistical_models.ipynb\
notebooks/03_machine_learning_models.ipynb\
notebooks/04_deep_learning_models.ipynb\
notebooks/05_evaluation.ipynb\
\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Reproducibility Notice\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Deep learning models may show small run-to-run variations due to random weight initialization, optimization dynamics, hardware differences, and software versions. The overall trends and conclusions remain consistent.\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Data Availability\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The meteorological dataset was obtained from the Palestinian Meteorological Authority. If redistribution is restricted, only the cleaned dataset or sample data should be included, and access to the full dataset should be requested from the data provider.\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Repository Structure\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 \
Weather-Palestine-Forecasting/\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  data/\
\uc0\u9500 \u9472 \u9472  notebooks/\
\uc0\u9500 \u9472 \u9472  src/\
\uc0\u9500 \u9472 \u9472  figures/\
\uc0\u9500 \u9472 \u9472  results/\
\uc0\u9500 \u9472 \u9472  docs/\
\uc0\u9500 \u9472 \u9472  README.md\
\uc0\u9500 \u9472 \u9472  requirements.txt\
\uc0\u9500 \u9472 \u9472  environment.yml\
\uc0\u9492 \u9472 \u9472  LICENSE\
\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Citation\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 If you use this repository, please cite the associated research article.\
\pard\pardeftab720\partightenfactor0

\f3\fs26 \cf0 \
\
Also create a second file inside `data/` named `README.md`:\
\
```md\
# Dataset Information\
\
This folder contains the dataset used for the weather forecasting experiments.\
\
## File\
\
```text\
final_filled_climate_cleaned.xlsx\
\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Description\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The dataset contains daily meteorological observations collected from five weather stations in Palestine between 2015 and 2025.\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Variables\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Station\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Date\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Temperature\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Relative Humidity\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Wind Speed\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Rainfall\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Atmospheric Pressure\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Sunshine Duration\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 Preprocessing\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The dataset was cleaned before model training. The preprocessing steps included:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls5\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Date standardization\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Missing-value handling\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Pressure zero correction\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Sunshine correction for unavailable station records\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Temporal feature extraction\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Station encoding\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Chronological train-validation-test split\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf0 \
}