# drone

from datetime import datetime,timedelta
def calculate_future_time(current_time,hours): 
  current_datetime=datetime.strptime(current_time,"%Y-%m-%d %H시")
  future_datetime = current_datetime + timedelta(hours = hours)
  
  return
future_datrtime.strftime("%Y년 %m월 %d일 %H시")

