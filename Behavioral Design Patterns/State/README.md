C:\Users\pc\Desktop\DesignPatterns\Behavioral Design Patterns\State

# State Design Pattern

### Definition

State Design Pattern allows an object to alter its behavior when its internal state changes.
The object will appear to change its class. 
The State pattern is closely related to the concept of a Finite-State Machine.
The main idea is that, at any given moment, there’s a finite number of states which a program can be in. Within any unique state, the program behaves differently, and the program can be switched from one state to another instantaneously.

### Use

- When An object's behavior depends on its state, and it must change its behavior at run-time depending on that state.
- When Operations have large, multipart conditional statements that depend on the object's state.

### Participants

- Context
  - defines the interface of interest to clients
  - maintains an instance of a ConcreteState subclass that defines the current state
- State
  - defines an interface for encapsulating the behavior associated with particular state of the Context
- Concrete State 
  - each subclass implements a behavior associated with a state of the Context

### UML