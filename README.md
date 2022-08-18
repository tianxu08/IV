

Removed the total_iv_time < 24
Removed the last iv, put back. Otherwise, the dataset is imbalanced. 

Data collection window 6 hours. 
Finish the incompation 
I should also treat the gap smaller than 1 hour as continuous ventilation. 


Positive sample: the patient is on an invasive ventilation and will have a failed extubation
Negative sample: the patient is on an invasive ventilation and will have a successful extubation. (no re-intubation within 72 hours)

Without last iv:
Train: 
Extubation Failed(positive): 15556
Extubation Succeed(negative): 3807

Test: 
Extubation Failed(positive): 3786
Extubation Succeed(negative): 455

Total: 
Extubation Failed(positive): 19342
Extubation Succeed(negative): 4262

With last iv: 
Train: 
Extubation Failed(positive): 15556
Extubation Succeed(negative): 18578

Test: 
Extubation Failed(positive): 3786
Extubation Succeed(negative): 3929

Total: 
Extubation Failed(positive): 19342
Extubation Succeed(negative): 22507






