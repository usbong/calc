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

5) 20260430 (CURRENT); http://store.usbong.ph/server/calc/index.html

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
