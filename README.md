VSNSPersistentContainer+Extension
============


`VSNSPersistentContainer+Extension` is an extension on `NSPersistentContainer` that adds a method to get all entity names and a method that drops (deletes) all objects for all entities in the Core Data model

Installation
============


Add `VSNSPersistentContainer+Extension.swift` to your project.


Usage
=====

```
let appDelegate = UIApplication.shared.delegate as! AppDelegate

appDelegate.persistentContainer.dropAllCoreDataEntities {
    print("YAY :)")
}
```