- a modern general-purpose computer system consists of one or more CPU's and a number of device controllers connected through a common bus that provides access to shared memory

- memory -> CPU -> Disk Controller (disks) -> USB Controllers (mouse, keyboard, printer) -> video adapter (monitors)

- a number of device controllers are connected through a common bus that provides access to shared memory
- each device controller is in charge of a specific type of device
- the CPU and the device controllers can execute concurrently, competing for memory cycles.
- to ensure orderly access to shared memory, a memory controller is provided, whose function is to synchronize access to the memory

- Bootstrap Program: 
 > - initial program that runs when a computer is powered up / rebooted\
 > - stored in ROM\
 > - must know how to load OS and start executing the system\
 > - must locate and load OS kernel into memory

- Interrupt:
  > - signals occurence of event from hardware or software
  >  - hardware can trigger an interrupt at any time by sending a signal to the CPU, by system bus
 
- System Call:
  > - interrupt triggered by software by execution of a special call
  
- When CPU is interrupted, it stops what it is doing immediately and transfers execution to a fixed location(contains starting address of where the service routine of the interrupt was located)
- interrupt service routine executes
- on completion, CPU resumes interrupted computation


