# Data visualization from LINE chat. :speech_balloon:

Requriment.
- pandas
- scipy
- datetime
- matplotlib
- seaborn

## How to export chat history.
![export chat history](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/export_chat_history.jpg)

## Getting start.

run this file `Line-Visualization.ipynb`
put your chat history name instead of 'LINE_Chat_with_someone.txt'
```python
chatName = 'LINE_Chat_with_someone.txt'
chat_data = bf.OpenFile(chatName)
```

`bf.summaryInformation(chat_data)` Show summary visualizes from the chat history.
![summary plot](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/summary_plot.PNG)

`bf.availableDay(chat_data)` Show all of date in chat history.

`bf.dateFilter(data=chat_data, month=11, year=2019)` Select a specific date in chat history.

`bf.respondHist((filtered_data), brange=60)` Show histogram of chat respond(minute) and average respond time from each user.
![chat respond](https://github.com/wsirigate/Line_chat_visualize/blob/master/img/respond_hist.PNG)

`bf.TrendPlot(filtered_data, method='Daily')` In this function you can change method in this list ['Daily', 'Weekday', 'Month']
