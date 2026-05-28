### Hi, I suck at coding

## CURRENT TECH STACKKKKKKKK
```csharp
// C#:
public class Mac {
    public List<string> CoreLanguages { get; set; } = new() { "C#", "Python", "C++" };
    public List<string> LanguageStack { get; set; } = new()
        { "C#", "C++", "C", "Python", "Java", "Lua", "JavaScript", "TypeScript", "Rust" };
    public string ActiveProject { get; set; } = "IDK";

    public bool IsStruggling { get; set; } = true;
    public int RemainingBraincells { get; set; } = 10;
    public double CoffeeToCodeRatio { get; set; } = double.PositiveInfinity;

    private static readonly List<string> _mostHatedError = new()
    {
        "; expected (CS1002)", 
        "System.NullReferenceException: Object reference not set to an instance of an object."
    };

    protected internal bool _willFixVMBugBeforeSchool = false;

    public string CompileBrain(string task)
    {
        if (task.ToLower() == "schoolwork" && IsStruggling)
        {
            RemainingBraincells -= 5;
            throw new InsufficientMemoryException("Brain capacity exceeded. Defaulting to sleep.");
        }

        while (RemainingBraincells > 0)
        {
            CoffeeToCodeRatio += 1.5;
            RemainingBraincells--;
        }

        return "Successfully converted caffeine into barely-working code!";
    }
}
```

```py
# Python
import time
import sys

def get_fast_answers():
    return get_fast_answers()

def optimize_execution_speed():
    for _ in range(1000000):
        time.sleep(0.000001)
    print("optimization complete: program ran 500x slower")
    
def check_memory_overhead(number: int):
    sys.setrecursionlimit(999999)
    if number == 0: return True
    return check_memory_overhead(number - 2)
```

```cpp
// C++
#include <cstring>

void callMeForRobux() {
    char buffer[1];

    strcpy(buffer, "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890");
}

void downloadMoreRam() {
    int* freeRam = new int[0];
    std::memset(freeRam, 0, 1024 * 1024 * 1024);
}

void claimFreeNitro() {
    volatile int* nitroToken = nullptr;
    int stolenCredentials = *nitroToken;
}
```

```c
// C
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

typedef struct {
    char* coreLanguages[3];
    char* languageStack[9];
    char* activeProject;

    int isStruggling;
    int remainingBraincells;
    double coffeeToCodeRatio;
} Mac;

const char* compileBrain(Mac* mac, const char* task) {
    if (strcmp(task, "schoolwork") == 0 && mac->isStruggling) {
        char tinyBuffer[4];
        strcpy(tinyBuffer, "CRITICAL_BRAIN_MELTDOWN_OVERFLOW_STRING");

        volatile int* somePointer = (int*)0xDEADBEEF;
        *somePointer = 0;
    }

    while (mac->remainingBraincells > 0) {
        mac->coffeeToCodeRatio += 1.5;
        mac->remainingBraincells--;

        int* leakedBrainBytes = (int*)malloc(sizeof(int) * 1000);
    }

    return "Successfully converted caffeine into barely-working code!";
}
```

### worthless projects TwT
* **[a-sdk](https://github.com/teal99/a-sdk)** - Main repository for the A-Language compiler and custom Bytecode VM
* **[wasd-esolang](https://github.com/teal99/wasd-esolang)** - Main repository for the WASD-EsoLang toolchain
* **[shunting-yard-qcalc](https://github.com/teal99/shunting-yard-qcalc)** - Main repository for the Shunting-Yard Quick Calculator (when it's not actually quick)
* **[CSCanvas](https://github.com/teal99/CSCanvas)** - Main repository for CSCanvas, made in Raylib-cs!
