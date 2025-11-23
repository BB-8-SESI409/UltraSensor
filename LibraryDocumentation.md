# 📖 Introducing the library
This file will show you everthing you need know about UltraSensor library

---

# 📚 Documentation
| # | Function | What it does? | 
| :---: | :--- | :--- |
| **1**|**UltraSensor**() |Main function(contructor) - It's you used to create an ultrassonic sensor.|
| **2**| **void begin**( int **trigger**, int echo)|set ultrassonic pins.|
| **3**| **float update**()| this function calc the value of ultrassonic, an ultrassonic needs a delay to do a second read, and this is the resolution of sensor in this library the resolution is 20reads/second, during this delay the function return the last read value|

