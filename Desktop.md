```python
#題目1
event="車禍肇事判賠"
sum_money=25688
a_rate=0.3
b_rate=0.7
a_money=sum_money*a_rate
b_money=sum_money*b_rate
print("事件：",event)
print("原告需賠償金額:",int(a_money),"元")
print("被告需賠償金額:",int(b_money),"元")
```

    事件： 車禍肇事判賠
    原告需賠償金額: 7706 元
    被告需賠償金額: 17981 元



```python
#題目2
money=11805
day_rate=0.0005
month1=150
month2=300
sum_money=money*(1+day_rate)**59+month1+month2
print("總共償還金額：",int(sum_money),"元")
```

    總共償還金額： 12608 元



```python
#題目3
event=input("請輸入案件:")

if event =="被告闖紅燈":
    print("被告賠100%")
elif event =="原告闖紅燈":
    print("原告多被告少")
elif event=="被告原告皆闖紅燈":
    print("原告50%被告50%")
else:
    print("請填入有效訊息")
```

    請輸入案件:被告闖紅燈
    被告賠100%



```python

```
