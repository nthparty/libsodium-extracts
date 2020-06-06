# static-checking-via-metaclasses
When managing a community project involving many contributors, setting standards can improve consistency across components and reduce the incidence of unexpected issues. Can existing Python features make it possible to encode such standards so that they are checked automatically with minimal effort from contributors?

Python metaclasses are how classes are created, and by defining your own metaclasses you can guide and constrain code contributors in a complex codebase. This article reviews how metaclasses can be employed to implement static checking of user-defined derived classes.
