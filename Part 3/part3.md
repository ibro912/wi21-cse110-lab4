Part 1:
The bug was that the input data of num1 and num2 are being read as strings, therefore, when they are added together, the result is a concatenation of the two strings, rather than the sum of the values. This would be fixed through changing the values of the two inputs into integers when adding them together, ensuring that they would be numbers, rather than strings

Part 2:
1) The name of the .json file that was downloaded is citylots.json
2) The file that initiated the download was part2.js
3) The file size is 11.7 MB
4) It took 77.74 ms total for the file to download
5) Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36
6) The server that the file came from was Apache
7) The file was last modified on Tuesday, 26 January 2021, at 22:14:13 GMT
8) The content-type of the file is application/json
9) The method within the initiating file was fetchData