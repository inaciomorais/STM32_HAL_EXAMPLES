Counter Settings:

25000000 (Clock Hz) / 250 (PSC) = 100000

1s / 10000Hz = 0.00001 = 10us


50000 (Period) * 0.00001 = 0.5s



PSC value 0 = prescaler of 1

PSC value 1 = prescaler of 2



PSC value 79 = prescaler of 80

We put a value of 80 - 1 just to remember what the prescaler value really is.


Counter period 65356 - 1

Because it starts counting the 0 (zero) tick.

HAL_TIM_Base_Start_IT
HAL_TIM_PeriodElapsedCallback
HAL_GPIO_TogglePin
