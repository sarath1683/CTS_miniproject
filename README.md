# CTS_miniproject
This miniproject includes a method to filter some data and to give top 10 values chosen by users. The client gave a file containing value list(values.txt) to be back referenced, 20 text documents containing top 10 values of 20 users, an exccel sheet containing top 10 values of other 12 users.
All the 20 text files are combined into single one(combin.txt) using unix code
The resulted text file(combin.txt) and excel file(file 21.xlsx) is filtered and cleaned using regex function in python(google colab), along with that deleted all datas which got mistakes in it.
Matching datas with values.txt are appended into a text file(final_list.txt)
The resulted file is then imported into informatica powercenter, did aggregate funtion(count) and rank transformation(top 10) and the output file is saved as target.txt which contains top 10 values(most selected by users)
