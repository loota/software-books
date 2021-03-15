# Effective Java

_Joshua Bloch_

- Favor composition. Inheritance is hard. Design for inheritance and test it by actually inheriting from the class. Otherwise ban inheritance from the class.

- Package private classes do not necessarily need accessors for data fields.

- If a class cannot be made immutable, limit its mutability as much as possible.

- Make every field final unless there is a compelling reason to make it nonfinal.

- Constructors must not invoke overridable methods.
