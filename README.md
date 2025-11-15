# Software Evolution – Series 1 Java Projects

This repository contains the **Java systems used as input** for the *Software Evolution - Series 1* assignment on software metrics.

It exists **solely to ensure reproducibility**.  
The main Rascal project (submitted separately) includes a script that automatically downloads this repository and uses the included Java projects as input for a software metrics analysis based on the **SIG Maintainability Model**, which is derived from the **ISO/IEC 25010** software quality standard.

The analysis computes metrics such as **Volume, Unit Size, Unit Complexity, Duplication**, and **Unit Testing**, and derives maintainability scores following the model described in:

Heitlager, I., Kuipers, T., & Visser, J. (2007, September). *A practical model for measuring maintainability.* In *6th International Conference on the Quality of Information and Communications Technology (QUATIC 2007)* (pp. 30–39). IEEE.

Each folder is an independent Java project that serves as a case study for the analysis.

---

## 📜 Notes

- The included code originates from open-source projects and is used **only for educational and analytical purposes**.  
- Original licenses are preserved in the respective folders.  
- This repository is not part of the Rascal implementation itself but is referenced by it for automated, reproducible analysis.
- This repository includes code from Joda-Time (https://github.com/JodaOrg/joda-time) licensed under the Apache License 2.0.
- This repository includes code from Gson (https://github.com/google/gson) licensed under the Apache License 2.0.
