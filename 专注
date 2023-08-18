import time

def focus_timer(duration, break_duration):
    print("专注时间开始！")
    while duration > 0:
        mins, secs = divmod(duration, 60)
        timer_format = f"{mins:02d}:{secs:02d}"
        print(timer_format, end="\r")
        time.sleep(1)
        duration -= 1
    print("\n专注时间结束！现在是休息时间。")

    time.sleep(break_duration)

    print("休息时间结束！")
    
if __name__ == "__main__":
    focus_duration = 25 * 60  # 25 minutes in seconds
    break_duration = 5 * 60   # 5 minutes in seconds

    focus_timer(focus_duration, break_duration)
