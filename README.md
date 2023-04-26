# DSC_Exp-4
## Pointers

### Code:-
```
  #include <stdio.h>
  int main()
  {
    int x=4;
    int *p;
    p=&x; 
    printf("Value at address pointed by p: %d \n",*p);
    printf("Value of x: %d \n",x);
    printf("Address of x: %d \n",&x);
    printf("Value of p: %d \n",p);
    printf("Address of p: %d \n",&p);
  return 0;
  }
```
### Output:-

![image](https://user-images.githubusercontent.com/124967782/230788496-0774c4a8-bd14-4f4b-ab70-3ffe8daea56d.png)
