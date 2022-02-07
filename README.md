# CTS_miniproject

This miniproject includes a method to filter some data and to give top 10 values chosen by users. The client gave a file containing value list(values.txt) to be back referenced, 20 text documents containing top 10 values of 20 users, an excel sheet containing top 10 values of other 12 users.
All the 20 text files are combined into single one(comb.txt) using unix code(single line code is shown in unix code)
The resulted text file(comb.txt) and excel file(file 21.xlsx) is filtered and cleaned using regex function in python(google colab), along with that deleted all datas which got mistakes in it. Complete python program is shown in SarathSumith-miniproject.ipynb-Colaboratory.pdf. 
Matching datas with values.txt are appended into a text file(final_list.txt)
The resulted file is then imported into informatica powercenter, did aggregate funtion(count) and rank transformation(top 10) and the output file is saved as target.txt which contains top 10 values(most selected by users)
The screenshot of informatica designer is provided as informatica screenshot.png
