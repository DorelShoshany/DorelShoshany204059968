
---Befor you run this program, please change the path in file: "readFromFile.h" 
---the path now is:""C:/Users/cudauser/desktop/data1.txt"
---change it to your path, where is the txt is in. 

---please change the path in file: "work.h"
---the path now is:""C:/Users/cudauser/desktop/outPut.txt"
---change it to your path, where you want. 

---In "perceptron.cpp" there is a line: if you change between them the "perceptron" algo will be different:
---train(k, pointsArray[i], o.w, alphasForP[0], sign(error));
---//train(k, pointsArray[i], o.w, alphasForP[0], fAterSign);
---The algorithm checks if the guess is too high (above the line) or too low (below the line) 
---and doubles accordingly.
---If it is too high it will double by 1 and if it is too low it will double by 1.
---Now multiplication is what was obtained in F.
