# TS-Collections
#### Installation
Add this library using npm or yarn.
###### NPM
```bash
npm i ts-collection-set
```
###### YARN
```bash
yarn add ts-collection-set
```
#### Usage
Import the collections library to your typescript file.
```typescript
import * as Collections from "ts-collection-set"
```
### Dictionary 
Initialize a dictionary instance as follow.
```typescript
const englishDictionary: Collections.Dictionary<string, string> = new Collections.Dictionary();
```
Add new elements to your dictionary instance as follows. The first parameter being the elements key and the second being its value.
```typescript
englishDictionary.setValue("A", "First english alphabet character.");
englishDictionary.setValue("Grey", "A metallic shade of black");
englishDictionary.setValue("Doctor", "An expert in a particular field of training");
```
Check if the dictionary contains a particular key using this method.
```typescript
englishDictionary.containsKey("key");
```
Remove an element from the dictionary instance using its key as follows.
```typescript
englishDictionary.remove("Key");
```
Get an array of key elements as follows.
```typescript
englishDictionary.keys();
```
