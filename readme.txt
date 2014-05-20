In order to get this to compile with newer Arduino IDEs this change must be made.

In SoftwareServo.h, This:
Code:
#include <WProgram.h>

Needs replacing with:
Code:
#include "Arduino.h"
