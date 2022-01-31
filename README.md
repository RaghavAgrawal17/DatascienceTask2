# DatascienceTask2
This is a recruitment Task/Challenge by Paperdrop.

## Video Explaination :- https://drive.google.com/file/d/18cpg_t4gZJ1pbJIRAMdsRfJeq3KX0Vd5/view?usp=sharing

# About the Dataset :-
The dataset(text) is collected from the website : https://algorithammer.herokuapp.com/ where images are excluded.
The data is then stored into a text file and is uploaded to github (cloud). [ task.txt ]

## Code :-
The main steps in the keyword density finding are:-
1. Text preprocessing - Includes removal of all the unwanted words (like special symbols and numbers).
2. I have mentioned the code for stop word removal but commented as it was not explicitly asked.
3. We have to perform for single words, 2 word phrase, 3 word phrase so we have used zip() to find out those values.
# 4. Output :
It is the displaying of the output. So we have displayed the output with the help of numpy and pandas in python library.
# Output is stored in keyword_density_output as nested lists :
[
  0:[[density], [count], [word]], 
  1:[[density], [count], [2 Word Phrase]],
  2:[[density], [count], [3 Word Phrase]]
]


![image](https://user-images.githubusercontent.com/81867011/151742191-6a142b93-36f4-4309-9ef0-74af026b1c15.png)
![image](https://user-images.githubusercontent.com/81867011/151742235-650f385f-50aa-43c6-bb89-57596103ae7d.png)
![image](https://user-images.githubusercontent.com/81867011/151742268-180aef44-b918-43a9-bc27-9031ff4349b3.png)

Hence the task is performed.
