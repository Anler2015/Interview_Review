求最大共除数
```
public int GCD(int a, int b) {
   if (b==0) return a;
   return GCD(b,a%b);
}
```
