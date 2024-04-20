# drone

currentYear=input('현재 연도를 입력하시오 '); %현재 날짜 및 시간
currentMonth=input('현재 달을 입력하시오 ');
currentDay=input('현재 날짜를 입력하시오 ');
currentHour=input('현재 시각을 입력하시오 ');

hoursToAdd=input('더하고 싶은 시간을 입력하시오 '); %더할 시간 입력

dateTime=datetime(currentYear,currentMonth,currentDay,currentHour,0,0);
newDateTime=dateTime(hoursToAdd);

disp(datestr[(newDateTime)]);
