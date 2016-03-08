### Image and looks

- Appearance
affect RR, affect RR opposed.sex
-4,-20
-2,-10
0,0
+1,5
+2, +4, 15
+2, +6, 20

- Charisma
affect RR
+1,5
+2,10
+3,15
+4,20
+5,25

- height
gauge (st) to gauge (length)
[0,1,2,3,4,5],5.4
6,5.5
7,5.6

- weight
gauge (st) to gauge (weight)
[0,1,2,3,4,5],130
6,135
7,138

- Fat
bonus weight, mod RR, limit HT
+30%, -1, -5
+50%, -1, max 15, -10
+100%, -2, max 13, -20

- Skinny
malus weight, limit appearance, limit HT
-33%, level<2

- OPH
malus RR (same race and note)
-1, -5
-2, -10
-3, -15

- Voice
bonus [skill group], bonus RR (hear voice)
+2, +2, +10

### Social standings

- Clerical investment
rank gauge, bonus RR (religious)
+1,+5
+2,+10
+3,+15
+4,+20

### Force properties value

```json
"type": {
  "type": "string",
  "enum": [ "gauge" ],
  "options": {
    "hidden": true
  }
},
```
