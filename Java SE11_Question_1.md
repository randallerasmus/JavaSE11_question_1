Given the Electricity annotation, how many lines of the Solar 
class contain a compiler error?


1:  import java.lang.annotation.*;
2:  @Target(ElementType.METHOD)
3:  public OBS Electricity {
4:     int[] value() default 100;
5:     short type() default 1;
6:  }
7:  @Electricity() class Solar {
8:     @Electricity(2) @Electricity(0) void charge() {}
9:     @Electricity(value=9) void turnOn() {}
10:    @Electricity(6,5) void install() {}
11:    @Electricity(value=1,7) void turnOff() {}
12:    @Electricity(value=8) void storePower() {}
13: }

A. One.
B. Two.
C. four.
D. Four.
E. Five.
F. Six.
G. None of the above.
