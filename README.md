 # Analysis-of-open-loop-and-closed-loop-control-system
## Aim :
  To analyse the open loop and closed loop system having G(S)=1/(S^2+10S+20)  when an unit step input is applied using MATLAB.
## Apparatus Required:
  Computer with MATLAB software
## Theory
  ### Open loop control system
  In this system, the output doesn’t change the action of the control system. It doesn’t have any feedback. It is very simple, needs low maintenance, quick operation, and cost-effective. The accuracy of this system is low and less dependable.
  <img width="652" height="175" alt="image" src="https://github.com/user-attachments/assets/0a9d8129-eb64-40bb-8efd-434edcb2bd5a" />
 ### Closed loop control System
The closed-loop control system can be defined as the output of the system that depends on the input of the system. This control system has one or more feedback loops among its input & output. This system provides the required output by evaluating its input. This kind of system produces the error signal and it is the main disparity between the output and input of the system.
                     <img width="508" height="220" alt="image" src="https://github.com/user-attachments/assets/ad4b9b9e-bf06-4108-a4c0-5320be064b1f" />

Consider a system having plant G(S)=  1/(S^2+10S+20), H(S) = 1(negative unity feedback system) and Controller C(S) = 300.
C(S) and G(S) are in series, 300/(S^2+10S+20)
300/(S^2+10S+20) and H(S) are in negative feedback.
Therefore, Closed loop transfer function, (C(S))/(R(S))=300/(S^2+10S+320)
## Program: 
### Open loop System
<img width="1559" height="712" alt="Screenshot 2026-10-24 091616" src="https://github.com/user-attachments/assets/1d0cbdf2-e8f5-4eb8-9a36-cd58028fc6c0" />

### Closed loop System
<img width="637" height="600" alt="Screenshot 2026-10-24 084448" src="https://github.com/user-attachments/assets/c7c8d88b-b017-44b0-8e19-885fe10add20" />

## Simulink:

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Analyse the result.
## Output:
### Open Loop System:
<img width="1919" height="1079" alt="Screenshot 2026-10-24 085838" src="https://github.com/user-attachments/assets/ab6a18a2-d16c-47f0-85c7-c94451db2406" />

### Closed Loop System:
<img width="1915" height="1079" alt="Screenshot 2026-10-24 085726" src="https://github.com/user-attachments/assets/a6ec03cd-467f-4246-99f2-9498b539a2d5" />

## Result:
Thus the open loop and closed loop system are analysed and the following conclusions are arrived.
### Open loop system
Steady State Error = 0.95

Settling Time = 2.5
### Closed loop System
Steady State Error = 0.05

Settling Time = 1





