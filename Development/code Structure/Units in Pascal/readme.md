This line in Lazarus' [Simba.lpi](https://github.com/Villavu/Simba/blob/simba1500/Source/Simba.lpi) defines all unit files in Subdirectories!
```
<OtherUnitFiles Value="$(ProjPath);script;forms;codetools;targets;matchtemplate;algorithms;editor;finders;script/imports/lcl;script/imports/simba;script/imports/simbaclasses;package;../Third-Party;../Third-Party/lape;../Third-Party/lape/extensions/ffi;imagebox;colormath;components"/>
```

book: Object Pascal
>All the units you refer to must be present in the project directory or **in a directory of the search path**.
>
>tip You can set the **Search Path for a project in the Project Options**. The system also considers units in
the Library path, which is a global setting of the IDE.
