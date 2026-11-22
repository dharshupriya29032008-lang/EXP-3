## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** |Priyadharshini S | **Reg. No.:** |26018313 |
|---|---|---|---|
| **Date:** |22-11-2026 | 
---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1600" height="932" alt="WhatsApp Image 2026-11-22 at 3 41 17 PM" src="https://github.com/user-attachments/assets/52048a47-f3f8-40ae-934e-12689f8db713" />


### Tabulation 1: Truth table – direct connection

<img width="1600" height="1133" alt="WhatsApp Image 2026-11-22 at 3 41 31 PM" src="https://github.com/user-attachments/assets/3387048d-1915-486a-ba6c-4010b3d30497" />

## B. CROSS CONNECTION

### Circuit diagram

<img width="1600" height="944" alt="WhatsApp Image 2026-11-22 at 3 41 46 PM" src="https://github.com/user-attachments/assets/6925ecc5-b472-479c-aa6b-cab4ac3c392f" />

### Tabulation 2: Truth table – cross connection

<img width="1600" height="1202" alt="WhatsApp Image 2026-11-22 at 3 41 56 PM" src="https://github.com/user-attachments/assets/990b7b0e-8d9c-4ba3-878e-51cfb5875406" />


## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="821" height="592" alt="Screenshot 2026-11-22 150348" src="https://github.com/user-attachments/assets/179dd444-690d-47c7-8b0a-b11c583b0c59" />
<img width="801" height="402" alt="Screenshot 2026-11-22 150417" src="https://github.com/user-attachments/assets/c984febb-cc34-4e67-8ff1-cc58d137c1ee" />

### B. Cross connection – simulation

<img width="772" height="408" alt="Screenshot 2026-11-22 150427" src="https://github.com/user-attachments/assets/9227b50b-05aa-459f-adaf-ed76f94dd20e" />
<img width="736" height="433" alt="Screenshot 2026-11-22 150445" src="https://github.com/user-attachments/assets/871b1180-ec16-41a8-b66d-505661f6d1e8" />



## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
