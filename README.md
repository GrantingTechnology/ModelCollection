# GT ModelCollection(ModelCollection)

One of the simplest classes in the framework, but also as important as a column.

The feature that is native since framework 1.1, as it is a highly cohesive component, its responsibility is only to transport typed objects between layers.

These objects can be generic lists, classes, enumerators, or another object contained within an application that, when added to the ModelCollection type collector, will be instantly available throughout the GT architecture, referenced by the namespace: gt.business.container.

By default, the UI, Logic, and Data layers are already referenced to the namespace: gt.business.container, which stores the memory addresses of their referenced objects (ref), thus eliminating the risk of redundancy. The same object that was added along its path will remain the same, the same reference point in memory.


donwload 
https://dev.azure.com/GrantingTechnology-Community/_git/Download-Trial-Version?path=%2FArchitecture%2FFramework%2FLogic%2FBusiness%2F_General%2Fgt.business.container&version=GBmaster
