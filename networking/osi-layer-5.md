# Layer 5: Session

The Session Layer manages communication sessions between applications on different systems. It controls how conversations are started, maintained, and ended.

It does not transport data `Layer 4` or format data `Layer 6`; it manages the conversation structure between application

## Role and Purpose of Layer 5

The primary purpose of Layer 5 is to ensure that communication between two applications remains organized and coordinated.

**It provides:**

  - Session lifecycle control

  - Communication structure management

  - Recovery support during interruptions

> Layer 5 ensures communication happens in a controlled and orderly manner.

## Session Establishment

Session establishment is the process of initiating communication between two applications.

**This includes:**

  - Verifying both parties are ready

  - Negotiating session parameters

  - Allocating necessary resources

> A session must be successfully established before data exchange begins.

## Session Maintenance

Session maintenance keeps the session active and stable during communication.

**It involves:**

  - Monitoring session state

  - Keeping track of ongoing exchanges

  - Managing timeouts or inactivity

  - Ensuring session continuity

> If issues occur, the session layer helps manage recovery or re-synchronization.

Session Termination
Session termination is the process of properly closing a communication session after data exchange is complete.
It involves:
Notifying both parties that communication is ending
Releasing allocated session resources
Ensuring no data is left in transit
Proper termination prevents resource leaks and incomplete communication states.