# Academia Course Registration Portal

A client-server based course registration system developed in C, designed to simulate real-world academic enrollment workflows with concurrent user access.

## Features
- Role-based access control (Admin, Faculty, Student)
- Secure authentication system
- Concurrent multi-client handling
- File-based database with locking mechanisms
- Course creation, enrollment, and seat management
- Socket-based client-server communication

## Tech Stack
- Language: C
- Concepts: Operating Systems, Socket Programming, File Locking
- Architecture: Client–Server
- Build Tool: Make
- Platform: Linux / macOS

## System Architecture
- **Server**: Handles authentication, business logic, and data storage
- **Client**: Terminal-based UI for user interaction
- **Database**: File-based storage with read/write locks

## Installation & Execution

### Compile Server
```bash
cd server
mkdir -p obj data
make clean
make
./server
