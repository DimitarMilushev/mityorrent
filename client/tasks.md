- [ ] Database
  - Pull any library to manage the CSV
  - Structure:
    - usersTable
      - rewrite()
      - getBy()
- [ ] Command Interpreter
  - [x] unsupported command exception
  - [ ] base main.java.commands
    - [ ] download
    - [x] register
    - [x] list-files
    - [x] unregister
    - [x] get-users
- [ ] Application
  - [ ] Client channels handler
    - [ ] File Receiver
    - [ ] File Sender
    - [ ] File Transfer Job
  - [ ] Origin channel handler
  - [x] User Base Refresh Job
  - [x] implement safe thread utility
  - [ ] Logger
  - [ ] REST-like Protocol
  - [ ] TCP exception interceptor
    - [ ] MessageParser