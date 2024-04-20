# drone

from datetime import datetime,timedelta
def calculate_future_time(current_time,hours): 
  current_datetime=datetime.strptime(current_time,"%Y-%m-%d %H시")#현재시간 입력
  future_datetime = current_datetime + timedelta(hours = hours)#미래시간 계산
  
  return future_datrtime.strftime("%Y년 %m월 %d일 %H시")

  current_time=input("현재 날짜와 시간을 입력하시오(예시 2024-04-20 11시)")

  hours=int((input("시간 단위 숫자를 입력하시오 ")))

  future_time=calculate_future_time(current_time,hours)#계산 및 출력
  print(future_time)

