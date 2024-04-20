# drone

current_time=input('현재 날짜와 시간을 입력하시오(예시 2024-04-20 11시) : ','s');
hours=input('시간 단위 숫자를 입력하시오 : ');

future_time=calculate_future_time(current_time,hours); %계산 및 출력
disp(future_time);
