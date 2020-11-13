# Question 1 (4 points): Perceptron
Đầu tiên ta tìm nhãn có điểm cao nhất trong tập dữ liệu train. Nếu nhãn này và nhãn thực tế không giống nhau , ta cập nhất lại trọng số của nhãn vừa tìm và nhãn thực tế
```
python dataClassifier.py -c perceptron 
```    
# Question 2 (1 point): Perceptron Analysis
Ta duyệt 100 lần để tìm 100 features có trọng số lớn nhất. Với mỗi lần duyệt, ta lấy ra trọng số max và thêm vào list , đồng thời xoá trọng số đó ở list ban đầu.
```
python dataClassifier.py -c perceptron -w
```
# Question 3 (6 points): MIRA
Tính toán dựa theo công thức
```
python dataClassifier.py -c mira --autotune 
```
# Question 4 (6 points): Digit Feature Design
```
python dataClassifier.py -d digits -c naiveBayes -f -a -t 1000  
```
# Question 5 (4 points): Behavioral Cloning
```
python dataClassifier.py -c perceptron -d pacman
```
