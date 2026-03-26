# pz11
<img width="1055" height="371" alt="image" src="https://github.com/user-attachments/assets/bfd37e5e-a50d-442e-b363-b775a70a9da8" />

Ex1
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int i = 1;
while (i <= n) {
    cout << i << " ";
    i++;
}

    // Ваш код:


    return 0;
}
```
Ex2
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int sum = 0;      
    int i = 1;      
    while (i <= n) {   
        sum += i;     
        ++i;        
    }

    cout << sum << endl;

    return 0;
}

```
Ex3
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int num, sum = 0;
cin >> num;
while (num != 0) {
    sum += num;
    cin >> num;
    
}
cout << sum;


    return 0;
}
```
Ex4
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    int n;
    cin >> n;

    // Ваш код:
    int i = 2;
    while (i <= n) {
        cout << i << " ";
        i += 2;
    }
 

    return 0;
}

```
Ex5
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    int f = 1;  
    int i = 1;        

    while (i <= n) {
        f = f * i;  
        i = i + 1;               
    }

    cout << f;

    return 0;
}

```
Ex6
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    int i = 0;
    if (n < 0) {
        n = -n;
    }
    while (n != 0) {
        i++;   
        n /= 10;  
    }
    cout << i;

    return 0;
}

```
Ex7
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    
    int n;
    cin >> n;

    // Ваш код:
    if (n <= 1) {
        cout << "Не простое";
        return 0;
    }
    if (n == 2) {
        cout << "Простое";
        return 0;
    } 
    if (n % 2 == 0) {
        cout << "Не простое";
        return 0;
    }
    int i = 3;
    int x = 0; 
    while (i * i <= n && x == 0) {
        if (n % i == 0) {
            x = 1;  
        }
        i += 2;  
    }
    if (x == 1) {
        cout << "Не простое" ;
    } else {
        cout << "Простое";
    }
    return 0;
}

```
Ex8
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    
    int n;
    cin >> n;
    
    int i = 1; 
   while (i <= n) {
        int x = 1;  
        while (x <= n) {
            cout << (i * x) << " ";  
            x++;
        }
       cout << endl;
        i++;
    }
    
    return 0;
}

```
