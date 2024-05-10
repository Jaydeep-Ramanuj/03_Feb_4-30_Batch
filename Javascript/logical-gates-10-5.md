ON | T | True | 1=> presence of power
oFF| F | False| 0 => absence of power

1 switch =>
T | F

2 switch =>
T | T
T | F
F | T
F | F

3 switch =>

T | T | T
T | T | F
T | F | T
F | T | T
F | F | F
F | T | F
F | F | T
T | F | F

4 switch=> 2**4=> 16
5 switch=> 2**5=> 32

TTTTTTTFTT => 1 task
TTTTTTTFFT => 2 task

AND Gate (&&) gives true if all are true, otherwise false

T | T => T
T | F => F
F | T => F
F | F => F

OR Gate (||) gives true if any is true, otherwise false

T | T => T
T | F => T
F | T => T
F | F => F

NOT Gate (!) gives true if false and gives false if true

T => F
F => T
