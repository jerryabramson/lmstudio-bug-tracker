---
name: Bug report
about: Create a report to help us fix issues
title: 'OOPS'
labels: ''
assignees: ''

---

**Which version of LM Studio?**
Example: LM Studio Version 0.4.16+2 (0.4.16+2)
**Which operating system? 
          Operating System 
                  Platform Mac17,7 (Darwin 25.5.0)
What is your operating system? macOS 26.5 (25F71) : macOS Tahoe 26.5

**What is the bug?**
OOPS - 
Details:

TypeError: Cannot read properties of undefined (reading 'paramType')
    at i.parseParamTypes (file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:155:45981)
    at file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:155:55813
    at Array.map (<anonymous>)
    at s.deserialize (file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:155:55794)
    at file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:57:89080
    at Object.Fo [as useMemo] (file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:2:5344044)
    at e.useMemo (file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:2:24998847)
    at e.useLoadTimeConfigSchema (file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:57:89020)
    at e.useChatConfigRef (file:/tions/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:57:45998)
    at file:///Applications/LM%20Studio.app/Contents/Resources/app/.webpack/renderer/main_window.js:35:5919


**Screenshots**
If applicable, add screenshots to help explain your problem.

**Logs**
Add any relevant logs.

**To Reproduce**
Steps to reproduce the behavior:
3 LM Studio Instances via LM Link 
  A. Dell GB10 (128 GB unified)
  B. PC with AMD 9070 GPU (16 GB GPU, 128 GB CPU)
  C. Macbook Pro M5 MAX (128 GB unified)



