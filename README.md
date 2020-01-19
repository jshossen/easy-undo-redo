# What is Easy Undo Redo? #
Get the most easiest undo redo feature for your npm project

## Installation
`npm install easyUndoRedo --save`

##### Initial `easyUndoRedo()` with some options paramiter. #####
```
var UndoRedo = new easyUndoRedo({
   stackLength : 20,
   initialValue : "Your initial data"
});

UndoRedo.save("Your updated data");
UndoRedo.undo(); //returns undo result
UndoRedo.redo(); //returns redo result
```
