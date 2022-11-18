###  [Task 8 kyu](https://www.codewars.com/kata/5a023c426975981341000014/train/java)

You are given two interior angles (in degrees) of a triangle.

Write a function to return the 3rd.


### My solution
```Java
public class ThirdAngle {
    public static int otherAngle(int angle1, int angle2) {
        return (180 - angle1 - angle2);
    }
}
```

### Fav solution
```Java
public class ThirdAngle {
    public static int otherAngle(int angle1, int angle2) {
        if(angle1 <= 0 || angle2 <= 0){
            return 0;
        }
        int angle3 = 180 - angle1 - angle2;
        return angle3;
    }
}
```
I like this solution because I like it
