# PRACTICE EXERCISE
### SISTEM BILANGAN (Desimal, Biner, Oktal, dan Heksadesimal)  

**Nama**: Havid Rosihandanu  
**NRP**: 3124500048  
**Dosen Pengajar**: Dr. Ferry Astika Saputra ST, M.Sc  
**Program Studi**: D3 Teknik Informatika  
**Institusi**: Politeknik Elektronika Negeri Surabaya (PENS)  
**Tahun**: 2024  

a) **Resource Management**: Efficiently managing hardware resources.  
b) **Providing a User Interface**: Enabling user interaction with the system.  
c) **Facilitating Program Execution and Services**: Supporting applications with essential services and an execution environment.

---

## 1.2 When is it appropriate for the operating system to forsake efficiency and "waste" resources? Why is such a system not really wasteful?

a) **Improving User Experience**:  
   - A better user experience can lead to increased productivity and user satisfaction.  
   - The resource usage is typically minimal compared to the overall system capacity, and the trade-off is justified by the benefits to the end user.  

b) **Enhancing Security**:  
   - The resources used for security measures are essential for protecting the system and user data from threats.  
   - The cost of a security breach far outweighs the resources spent on prevention.

---

## 1.3 What is the main difficulty that a programmer must overcome in writing an operating system for a real-time environment?

The main difficulty is **ensuring deterministic timing and predictability**.

---

## 1.4 Should the operating system include applications such as web browsers and mail programs?

The decision depends on the target audience and the goals of the OS vendor:  
- **For General-Purpose OSs**: Including essential applications can improve usability and accessibility for the average user, making the OS more appealing to a broader audience.  
- **For Specialized or Minimalist OSs**: Excluding bundled applications allows for greater flexibility, customization, and resource efficiency, which may be preferable for advanced users or specific use cases.  

A middle-ground approach could involve:  
- **Optional Bundling**: Allowing users to choose whether to install bundled applications during the OS setup process.  
- **Modular Design**: Designing the OS so that bundled applications can be easily removed or replaced without affecting system stability.

---

## 1.5 How does the distinction between kernel mode and user mode function as a rudimentary form of protection (security)?

1. **Restricted Access**: User mode restricts applications from directly accessing hardware or executing privileged instructions, preventing unauthorized actions.  
2. **Controlled System Calls**: Applications must request kernel mode via system calls for privileged operations, which the OS validates and executes securely.  
3. **Memory Protection**: User mode limits applications to their own memory space, preventing interference with the OS or other applications.  
4. **Stability and Security**: If an application crashes or is compromised, it cannot harm the OS or hardware, as it runs in isolated user mode.

---

## 1.6 Which of the following instructions should be privileged?

a) **Set value of timer**:  
   - Reason: Timers are critical for scheduling and system operations. Allowing user programs to modify timers could disrupt system stability or cause denial-of-service attacks.  

b) **Clear memory**:  
   - Reason: Clearing memory could erase critical system data or other processes' data, leading to system crashes or data loss.  

c) **Turn off interrupts**:  
   - Reason: Disabling interrupts could prevent the OS from responding to critical events (e.g., hardware signals), causing system freezes or crashes.  

d) **Modify entries in device-status table**:  
   - Reason: Device-status tables control hardware operations. Unauthorized modifications could lead to hardware malfunctions or security breaches.  

e) **Switch from user to kernel mode**:  
   - Reason: Switching to kernel mode grants unrestricted access to system resources. Allowing user programs to do this would bypass all security mechanisms.  

f) **Access I/O device**:  
   - Reason: Direct access to I/O devices could compromise data integrity, security, and system stability. The OS must mediate all I/O operations.

---

## 1.7 What are two difficulties that could arise from placing the OS in a memory partition that cannot be modified?

a) **Limited Flexibility**:  
   - The OS cannot modify its own memory partition, making it difficult to perform essential tasks like dynamic memory allocation, updating system data structures, or applying patches.  

b) **Performance Overhead**:  
   - Enforcing strict memory protection requires additional hardware or software mechanisms, which can introduce complexity and slow down system performance.

---

## 1.8 What are two possible uses of multiple modes of operation in CPUs?

a) **Enhanced Security and Isolation**:  
   - Multiple modes can provide finer-grained access control, allowing the OS to isolate sensitive subsystems (e.g., hypervisors, device drivers) from both user applications and the core kernel.  

b) **Specialized Functionality**:  
   - Additional modes can support specialized operations, such as real-time mode for time-critical tasks or debug mode for diagnostics.

---

## 1.9 How can timers be used to compute the current time?

To compute the current time using a timer, the system follows these steps:  
a) **Initialize a Timer**: Set up a hardware timer to generate periodic interrupts (e.g., every millisecond).  
b) **Maintain a Counter**: Use a counter variable in memory to keep track of the number of timer interrupts since a known start time.  
c) **Calculate Current Time**: Multiply the counter value by the timer interval to get the elapsed time since the start time, then add the elapsed time to the start time to compute the current time.

---

## 1.10 Why are caches useful? What problems do they solve and cause?

**Why Caches Are Useful (Problems They Solve)**:  
a) **Speed Up Data Access**: Caches store frequently accessed data closer to the CPU, reducing the time needed to fetch data from slower main memory or storage.  
b) **Reduce System Bottlenecks**: By reducing the number of accesses to main memory or disk, caches decrease bandwidth usage and contention.  

**Problems Caches Cause**:  
a) **Cache Coherency**: Ensuring that all caches have consistent data in multi-core or multi-processor systems can be complex.  
b) **Increased Complexity**: Caches add complexity to system design, including cache management policies and hardware overhead.  
c) **Cache Miss Penalty**: When data is not found in the cache, the system incurs additional latency to fetch the data from main memory or storage.

---

## 1.11 Distinguish between the client-server and peer-to-peer models of distributed systems.

| **Aspect**         | **Client-Server**                          | **Peer-to-Peer**                          |
|---------------------|--------------------------------------------|-------------------------------------------|
| **Architecture**    | Centralized                                | Decentralized                             |
| **Roles**           | Client and server are distinct             | All peers are equal (clients/servers)     |
| **Scalability**     | Limited by server capacity                 | Highly scalable                           |
| **Control**         | Centralized control                        | Distributed control                       |
| **Use Cases**       | Web services, databases                    | File sharing, distributed computing       |
