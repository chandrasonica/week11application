{\rtf1\ansi\ansicpg1252\cocoartf2513
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab560
\pard\pardeftab560\slleading20\partightenfactor0

\f0\fs24 \cf0 Business Understanding:\
We have given 426K data points for the price of used cars. Goal is to identify what features define the value of car. This will help dealer to predict price of used cars.\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 Data Understanding:\
There are few questions I kept in mind while looking the data. \
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls1\ilvl0\cf0 {\listtext	0.	}Which columns/features had correlation with price, so we can keep those columns and the one which don\'92t we can drop those columns\
{\listtext	0.	}Then we need to see, if there are columns which had lots of missing values, and if they did should we drop those columns or fill default values.\
{\listtext	0.	}Which of the columns are categorical and which ones have multiple string values, this will help us in featuriztion during modeling\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
Data Cleanup\
Based on above analysis, I cleaned up, unwanted columns, missing values and converted string values into numeric.\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 Modeling:\
I could see that there was high correlation between price and odometer, year, manufacture,.\
I used multiple models to and featurization techniques to come up best model possible.\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 Conclusion:\
I can see that odometer,  year, manufacturer, model has highest value to the prices, It would be good to have more data. \
\
\
}