# CounterV1
This counter app includes all React lifecycle phases implemented using useEffect hook.
Created timer increments the value of the count variable by 1 every second when the start button is clicked. Pressing the Stop button will stop the countdown (the Stop button would appear instead of the Start button when the timer is running). When reset button is pressed, the timer stops counting and resets the counter to zero. 
If the counter value changes, that value is written to localStorage.
When the application is unmounted, the counter should also stop if it was running.
