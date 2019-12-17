# simple-pid
Simple PID controller for Arduino IDE

To use, import the _PID folder inside your Arduino/libraries folder and include _PID.h in your sketch

### Public functions
```C
   PID(float, float, float, int16_t, int16_t);
   void reset();
   void setP(float);
   void setI(float);
   void setD(float);
   void setPID(float, float, float);
   void setLimits(int16_t, int16_t);
   float getP();
   float getI();
   float getD();
   float compute(float);
  ```
