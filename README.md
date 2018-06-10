# PID controll Project

## PID controller
PID(proportional–integral–derivative) controller는 아래 공식으로 표현할 수 있으며, 
![](https://wikimedia.org/api/rest_v1/media/math/render/svg/708c8516a7531aca1fa256551f73752fae023e9c)
아래와 같은 3가지 term으로 이루어진다. 
* Proportional term(K_p): The proportional term produces an output value that is proportional to the current error value.
* Integral term(K_i): The integral term eliminates the residual steady-state error that occurs with a pure proportional controller.
* Derivative term(K_d): 출력값의 급격한 변화에 제동을 걸어 오버슛(overshoot)을 줄이고 안정성(stability)을 향상시킨다.

## Tuning control parameters
```
pid.Init(0.2, 0.0001, 3.0);
```

