# drone
function future_time = calculate_future_time(current_time, hours)
current_datetime = datetime(current_time, 'InputFormat', 'yyyy-MM-dd HH시'); % 현재시간 입력
    future_datetime = current_datetime + hours/24; % 미래시간 계산 (시간을 일 단위로 변환)
    future_time = datestr(future_datetime, 'yyyy년 mm월 dd일 HH시'); % 포맷 지정하여 문자열로 변환
end

current_time=input('현재 날짜와 시간을 입력하시오(예시 2024-04-20 11시) : ','s');
hours=input('시간 단위 숫자를 입력하시오 : ');

future_time=calculate_future_time(current_time,hours); %계산 및 출력
disp(future_time);