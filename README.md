# Browser-based Calculator App

Can you make use of your knowledge of HTML5 and Javascript to create a simple calculator app that runs on web browers?

# Development Logs

1) Create the appearance first. Without yet interactivity.

<img src="https://github.com/usbong/calc/blob/main/screenshots/calcScreenshotV20260427T1507.png" width="60%">

2) 20260428; http://store.usbong.ph/server/calc/index20260428.html

Add basic arithmetic: Addition, Subtraction, Multiplication, Division


3) 20260429; http://store.usbong.ph/server/calc/index20260429.html

+added: backspace

+fixed: equals button not correctly displayed in newer browsers

+fixed: error when operator is added before adding any operand

4) 20260430; http://store.usbong.ph/server/calc/index20260430.html

<img src="https://github.com/usbong/calc/blob/main/screenshots/calcScreenshotV20260430T1447.png" width="60%">

+fixed: backspace error when there's only a digit left after doing an operation; "sCurrOperand" incorrectly set to Float, instead of String

+fixed: backspace error when the operator is backspaced, then a new operator cannot anymore be added

+added: decimal point

+added: max 11 digits for the resulting answer if it has a decimal point

+added: max 13 operands and operators including the decimal point

+added: "Clear" button which replaces the "Backspace" button after using the equals operator; then, again bring back the "Backspace" button upon entering an operand or an operator 

+updated: multiply symbol to "×"

+updated: multiply symbol to "÷"

+updated: equals button position to "136px;" from "136.5px;"

5) 20260501; http://store.usbong.ph/server/calc/index20260501.html

+added: current operator can be changed at its position

+set: temporarily input box to read-only to prevent intentional or inadvertent entering of text via keyboard 

7) 20260502 (CURRENT); http://store.usbong.ph/server/calc/index20260502.html

+fixed: pressing equals button multiple times causes next arithmetic operation to result to zero

+removed: reset function via pressing equals button; instead, use "Clear" button

+fixed: certain sequences that lead to incorrect output; 

**Examples:** `3*/B*` error, `5*60=*B==/2` error

+added: changeable number signs

+fixed: `3/=5`; previously resulted to `05`; now results to `5`

TODO: -fix: `3*-B` becomes `3`, instead of `3*`

TODO: -fix: `-*B` now removes both `-*`

8) 20260504 (CURRENT); http://store.usbong.ph/server/calc/index.html

fixed: `3*-B` becomes `3`, instead of `3*`

fixed: `-*B` now removes both `-*`; `-*` already results to `<blank>`

fixed: `-*` should result to `<blank>`

fixed: backspace in `3x-` incorrectly results to `3` instead of `3x`

TODO: -add: PEMDAS

<img src="https://github.com/usbong/calc/blob/main/plan/pemdasPlan20260504.jpg" width="60%">


# Get PhilNITS Certified!

https://philnits.org/

# Open Source Software License

Copyright 2026 SYSON, MICHAEL B.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
  
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

@company: USBONG<br/>
@author: SYSON, MICHAEL B.<br/>
@website address: http://www.usbong.ph<br/>
