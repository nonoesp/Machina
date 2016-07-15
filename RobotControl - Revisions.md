```text
██████╗  ██████╗ ██████╗  ██████╗ ████████╗ ██████╗ ██████╗ ███╗   ██╗████████╗██████╗  ██████╗ ██╗     
██╔══██╗██╔═══██╗██╔══██╗██╔═══██╗╚══██╔══╝██╔════╝██╔═══██╗████╗  ██║╚══██╔══╝██╔══██╗██╔═══██╗██║     
██████╔╝██║   ██║██████╔╝██║   ██║   ██║   ██║     ██║   ██║██╔██╗ ██║   ██║   ██████╔╝██║   ██║██║     
██╔══██╗██║   ██║██╔══██╗██║   ██║   ██║   ██║     ██║   ██║██║╚██╗██║   ██║   ██╔══██╗██║   ██║██║     
██║  ██║╚██████╔╝██████╔╝╚██████╔╝   ██║   ╚██████╗╚██████╔╝██║ ╚████║   ██║   ██║  ██║╚██████╔╝███████╗
╚═╝  ╚═╝ ╚═════╝ ╚═════╝  ╚═════╝    ╚═╝    ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝ ╚═════╝ ╚══════╝
                                                                                                        
██████╗ ███████╗██╗   ██╗██╗      ██████╗  ██████╗ 
██╔══██╗██╔════╝██║   ██║██║     ██╔═══██╗██╔════╝ 
██║  ██║█████╗  ██║   ██║██║     ██║   ██║██║  ███╗
██║  ██║██╔══╝  ╚██╗ ██╔╝██║     ██║   ██║██║   ██║
██████╔╝███████╗ ╚████╔╝ ███████╗╚██████╔╝╚██████╔╝
╚═════╝ ╚══════╝  ╚═══╝  ╚══════╝ ╚═════╝  ╚═════╝ 
```


## BUILD 1101
- [ ] New class structure: 
    - [x] Split all the public Robot API from all the internal actual operations
    - [x] Centralize private methods into a Control class
    - [x] Add placeholder classes for future developments (Tool, Library, Solvers, etc.)
    - [ ] Create a dedicated Communication class to handle connections to real/virtual controllers
- [x] Port all current functionality into the new structure
- [x] Make sure everything works as before with the new structure
- [x] Add Build number 
- [x] Merged ConnectionMode & OnlineMode into ControlMode 
- [ ] Split off the Comm object
- [ ] Big comments review
- [ ] Deep port of all functionality (make the Robot class basically a very shallow middleware for API purposes)
- [ ] Dead code cleanup

## BUILD 1100
- [x] Recheck all examples are working correctly and nothing is broken before branching

## BUILDS 10xx
- Previous test and prototyping builds
- Transitioning to a split class architecture and more programmatic implementation


