# 0624090 劉佳晟

## 0624090 劉佳晟

### 0624090 劉佳晟

#### 0624090 劉佳晟

##### 0624090 劉佳晟

###### 0624090 劉佳晟

>台中市
>>東勢區

>>*豐原區*

---
[cs.money](https://cs.money/zh/)

:horse: :cat2:

```csharp
private void index(){
  MessageBox.Show("hello world");
}
```
| Table        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| 第三欄        | 靠右對齊      | $1600 |
| 第二欄        | 置中對齊      |   $12 |
| 斑馬條紋      | 是整齊的      |    $1 |
| csgo         |Talon knife    | USD300|

![una](20170418190908_6ef5fba813fad74feed9e35c35267e72_2.jpeg)

###
```js
import java.util.*;
import java.lang.*;
import java.io.*;

abstract class CShape
{
    protected String color;
    public void setColor(String str)
    {
        color = str;
    }
    public abstract void show();
}
class CTriangle extends CShape
{
    protected int side_a,side_b,side_c;
    public CTriangle(int a,int b,int c)
    {
        side_a=a;
        side_b=b;
        side_c=c;
    }
    public void show()
    {
        System.out.print("color="+color+",");
        System.out.print("area="+0.5*side_a*side_b);
    }

}
public class app11_1
{
    public static void main(String args[])
    {
        CTriangle trian = new CTriangle(3,4,5);
        trian.setColor("RED");
        trian.show();
    }
}
