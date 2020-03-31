# TS-Collections
### Installation
Add this library using npm or yarn from your terminal.
###### NPM
```bash
npm i ts-collection-set
```
###### YARN
```bash
yarn add ts-collection-set
```
### Usage
Import the collections library to your typescript file.
```typescript
import * as Collections from "ts-collection-set"
```
#### Dictionary (HashMap) 
Initialize a dictionary instance as follows.
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
#### Set (ArrayList)
Initialize a set instance as follows.
```typescript
const numArray: Collections.Set<string> = new Collections.Set();
```
Add elements to your set instance as follows.
```typescript
numArray.add("1");
numArray.add("2");
numArray.add("3");
numArray.add("4");
```
Remove an element from your set instance as follows.
```typescript
numArray.remove("2");
```

Check to see if is your set instance contains a particular element using the following method.
```typescript
numArray.contains("1");
```

### License
MIT License

Copyright (c) 2020 Ian Mugambi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

