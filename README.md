# pds
This is a sample project to show how to simulate an obligation in an NGAC environment. Obligations update a graph in response to certain events occuring.

- [PDS](src/main/java/pds/PDS.java) provides the main method that runs the steps in a PDS workflow, and simulates events using the `simulateAssignToEvent` method.
- [Obligations](src/main/java/pds/Obligations.java) provides the responses that will be applied to a graph when an event is triggered.
