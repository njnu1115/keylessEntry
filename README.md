# keylessEntry
design documents for vehicle keylessEntry
including:

- KeylessEntryState.uml

assume there are two entry device (aka. ED) registed for vehicle passive entry, we might need to carefully design the function state to cover all corner case, for either entry or exit scenario.

- why using Chinese charset? 

to reduce string length. If you need an full-English version, feel free to raise an issue.

- how to compile it?

java.exe -jar plantuml.jar -charset UTF-8 KeylessEntryState.uml

- note:

green dashed line: passive lock
blue dotted line: passive unlock
normal line: position change without lock status change
pinked statue: means LOCKED status
