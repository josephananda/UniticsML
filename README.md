# UniticsML

- Part of: Build on Asean 2021 Competition Project
- Task: College Major Recommendation System

# Unitics Data Preprocessing, Modeling, and College Major Recommendation
Unitics (University Analytics) is designed to help high school students who would like to pursue higher education in Indonesian state university. Identified problems, such as lack of self-understanding (only following others, not their personal interest or talents and only see trends), lack of relevant information (various majors but no idea which one is suitable), and lack of ability to make decisions become the reasons why this solution is needed.

SNMPTN 2016 and 2017 data from HaloKampus formed a dataset of accepted students' scores at 9 Indonesian state universities. Six subjects trained a Science Multi-Layer Perceptron (MLP) model and seven for a Social MLP model. The models achieved 94.57% accuracy for science (174 majors) and 89.79% accuracy for social (70 majors).

## What is in my project...
This project consists of 4 parts:
1) Data Preprocessing
2) Exploratory Data Analysis
3) Machine Learning Modeling - Multi-Layer Perceptron / Dense Neural Network
4) College Major Prediction and Recommendation

and Machine Learning part is divided into two different model:
1) Multi-Layer Perceptron (MLP) for Science Major
2) Multi-Layer Perceptron (MLP) for Social Major

## What is in the dataset...
Selected Attributes:
1) Jurusan Sekolah (School Major): The high school major of the students, "IPA" for Science major and "IPS" for Social major
2) Jurusan Diterima (Accepted Major)
4) PTN Diterima (Accepted University)
5) Mat Sem 1, Mat Sem 2, Mat Sem 3, Mat Sem 4, Mat Sem 5 (1st up to 5th semester Mathematics subject score)
6) Ing Sem 1, Ing Sem 2, Ing Sem 3, Ing Sem 4, Ing Sem 5 (1st up to 5th semester English subject score)
7) Ind Sem 1, Ind Sem 2, Ind Sem 3, Ind Sem 4, Ind Sem 5 (1st up to 5th semester Indonesian subject score)
8) Fis Sem 1, Fis Sem 2, Fis Sem 3, Fis Sem 4, Fis Sem 5 (1st up to 5th semester Physics subject score)
9) Kim Sem 1, Kim Sem 2, Kim Sem 3, Kim Sem 4, Kim Sem 5 (1st up to 5th semester Chemistry subject score)
10) Bio Sem 1, Bio Sem 2, Bio Sem 3, Bio Sem 4, Bio Sem 5 (1st up to 5th semester Biology subject score)
11) Eko Sem 1, Eko Sem 2, Eko Sem 3, Eko Sem 4, Eko Sem 5 (1st up to 5th semester Economy subject score)
12) Geo Sem 1, Geo Sem 2, Geo Sem 3, Geo Sem 4, Geo Sem 5 (1st up to 5th semester Geography subject score)
13) Sos Sem 1, Sos Sem 2, Sos Sem 3, Sos Sem 4, Sos Sem 5 (1st up to 5th semester Sociology subject score)
14) Sej Sem 1, Sej Sem 2, Sej Sem 3, Sej Sem 4, Sej Sem 5 (1st up to 5th semester History subject score)

Non-Selected Attributes:
1) Nama Panggilan (Nickname)
2) Asal Sekolah (School Origin)
3) Jenis Sekolah (School Type)
4) Jenis Kelas (Class Type, acceleration / regular class)
5) Akreditasi Sekolah (School Accreditation)
6) Prestasi Sekolah (School Achievement)
7) Alumni Sekolah (School Alumni)
8) PTN Pilihan I (1st university choice)
9) Jurusan Pilihan I di PTN Pilihan I (1st chosen major on 1st university choice)
10) Jurusan Pilihan II di PTN Pilihan I (2nd chosen major on 1st university choice)
11) PTN Pilihan II (2nd university choice)
12) Jurusan Pilihan I di PTN Pilihan II (1st chosen major on 2nd university choice)
13) Jurusan Pilihan II di PTN Pilihan II (2nd chosen major on 2nd university choice)
14) Kom Sem 1, Kom Sem 2, Kom Sem 3, Kom Sem 4, Kom Sem 5 (1st up to 5th semester Computer subject score)
15) Peringkat Kelas Sem 1 (1st semester class rank)
16) Peringkat Kelas Sem 2 (2nd semester class rank)
17) Peringkat Kelas Sem 3 (3rd semester class rank)
18) Peringkat Kelas Sem 4 (4th semester class rank)
19) Peringkat Kelas Sem 5 (5th semester class rank)
20) Nilai UN (National Exam Scores)
21) Saran buat adik kelas (Tips for younger students / classmate)
22) Prestasi lain yang dilampirkan (Other achievements)

## Result of this project...

## What should I improve next...
1) Try to collect more data from various sources
2) More in-depth observation on the dataset, since there's a lot of outlier.

## My resources...
1) A lot of google searches (geeksforgeeks, kaggle, github, medium articles)
2) Stack Overflow for debugging the problems
3) ChatGPT: I use chatGPT to help me check if my code syntax is correct or not. (In the newer version of the UniticsML improvement. It haven't existed back then in 2021)
