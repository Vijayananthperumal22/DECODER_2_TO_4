# DECODER2TO4
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)

# Program
```
input a,b,c;
output [7:0]y;
and gl (y[0], (~a), (~b), (~c));
and g2 (y[1], (~a), (~b), (c));
and g3 (y[2], (~a), (b), (~c));
and g4 (y[3], (~a), (b), (c));
and g5(y[4], (a), (~b), (~c));
and g6(y[5], (a), (~b), (c));
and g7(y[6], (a), (b), (~c));
and g8 (y[7], (a), (b), (c));
endmodule
```
# Output
![316433302-f89cfa70-5732-4c06-8a4d-b1557f99a6c4](https://github.com/Vijayananthperumal22/DECODER_2_TO_4/assets/107705127/5422e324-749b-4902-8aeb-42d349c7d5cf)
