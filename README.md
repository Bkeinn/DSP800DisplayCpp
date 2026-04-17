# DSP800
This library implements some of the features mentioned in the Manual often delivered with the Display\
Not all features are implemented and there is overall a very low level of abstraction.
If you find this repository by accident and happen to have one of those, I would advice to just look at the code how it might be done and then desing it yourself, because I have personally no idea
how something like this "should" be done.

# How to use
```c++
void setup() {
  Serial.begin(9600, SERIAL_8N1, 14,12);
  DSP.clear();
  DSP.print("Hello World");
  DSP.setLanguage(DSP800::GERMANY);

  delay(5000);
}
```

