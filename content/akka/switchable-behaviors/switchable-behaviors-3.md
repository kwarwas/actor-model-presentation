## Akka.NET - Switchable behaviors

- API
    - **Become** - Replaces the message handler with the specified delegate
    - **BecomeStacked** - Adds the specified message handler to the top of the behavior stack, while maintaining the previous ones
    - **UnbecomeStacked** - Reverts to the previous message handler from the stack (only works with BecomeStacked)
