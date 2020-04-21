# Data visualization from LINE chat. :speech_balloon:

Requriment.
- pandas
- scipy
- datetime
- matplotlib
- seaborn

## How to export chat history.
![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture0.jpg)

## Getting start.

run this file `Line-Visualization.ipynb`
put your chat history name instead of 'LINE_Chat_with_someone.txt'
```python
chatName = 'LINE_Chat_with_someone.txt'
chat_data = bf.OpenFile(chatName)
```
This function `Open File()` will convert chat history into a data frame.

Function `available Day(chat_data)` show available chat history date.

<!-- **ข้อมูลแสดงเวลาที่ใช้ในการตอบแชท**<br>
ข้อมูลแสดงระยะเวลาในการตอบเฉลี่ย ระยะเวลาในการตอบที่สั้นที่สุด และระยะเวลาในการตอบที่นานสุดของผู้สนทนาและคู่สนทนา
```python
# Choose the month and year.
df_filter = line_function.filter_my(df, '11/2019')
# Create dataframe of reply to chat.
responsetime_df = line_function.urt(df_filter)
# Show output.
line_function.rpt_summary(df, responsetime_df)
```
![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture7.PNG)

**กราฟแสดงจำนวนข้อความของเราและคู่สนทนา**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture1.png)

**กราฟแสดงจำนวนข้อความที่ส่งหากันในแต่ละวัน**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture2.PNG)

**กราฟแสดงจำนวนข้อความที่ส่งหากันโดยแบ่งตามคนส่ง**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture3.png)

**กราฟแสดงจำนวนข้อความที่ส่งหากันโดยแบ่งตามคนส่ง(แสดงตามเดือนที่เลือก)**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture4.png)

**กราฟแสดงจำนวนข้อความที่ส่งหากันทั้งหมดโดยแยกตามช่วงเวลา**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture5.PNG)

**กราฟแสดงวันและเวลาไหนที่มีการคส่งข้อความหากันมากที่สุด(ยิ่งสีเข้มแสดงว่ามีการส่งข้อความหากันมาก)**

![alt text](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/Capture6.PNG) -->
