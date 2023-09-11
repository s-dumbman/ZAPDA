import time as tm
from datetime import datetime
import math as s
# value set
val = 1 #0 / 0이 아닌 실수
a = 60
if a < 1:
    print("올바른 값을 입력해주십시오")
    tm.sleep(s.pow(10,5))
def ch():
    if val == 0:
        ab()
    else:
        ad()
def ab():
    print("타이머 시작됨 (",a,"초 )")
    try:
        num = a + 1
        for i in range(1,a+1):
            num = num - 1
            print(num)
            tm.sleep(1)
        print("타이머 종료됨 (",a,"초 )")
    except KeyboardInterrupt:
        print("타이머 강제종료됨 (",a,"초, 현황",str(num),"초 )")
def ad():
    try:
        print("스톱워치 시작됨 ( 시각",datetime.now()
              ,")")
        num = 0
        for i in range(1,600000):
            tm.sleep(1)
            num = num + 1
            print(str(num))
    except KeyboardInterrupt:
        print("스톱워치 종료됨 ( 시각",datetime.now()
              ,"/ 현황"
              ,num
              ,")")
if __name__=='__main__':
    ch()
