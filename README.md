# drone
function future_time = calculate_future_time(current_time, hours)
current_datetime = datetime(current_time, 'InputFormat', 'yyyy-MM-dd HH시'); % 현재시간 입력
    future_datetime = current_datetime + hours/24; % 미래시간 계산 (시간을 일 단위로 변환)
    future_time = datestr(future_datetime, 'yyyy년 mm월 dd일 HH시'); % 포맷 지정하여 문자열로 변환
end
